# csci544-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CSCI544 Assignment 2 Solved](https://www.ankitcodinghub.com/product/csci544-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93678&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI544 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
This assignment is an extension to HW assignment 1 on sentiment analysis. Please follow the instructions and submit a zipped folder containing:

1. A PDF containing a Jupyter Notebook response to the assign- ment. Your Jupyter Notebook should contain both code and text cells with sufficient comments such that the reader can understand your solution as well as your responses for some of the questions. On the Jupyter notebook, please print the requested values, too. If it is more convenient, you can also submit a PDF similar to assignment 1, i.e., initially explaining your solution and then merge a Jupyter notebook.

2. You also need to submit your Jupyter Notebook separately in .ipynb format such that it can be easily executed. Please include the version of required dependencies. You can consider that data.tsv is a raw dataset in the current directory that your notebook should read and perform all the required steps and generate the desired outputs.

The preferred library to implement neural models is PyTorch but TensorFlow (or Keras) is also acceptable. Please name your zipped file “HW2-YourFirstName-YourLastName-AAA.zip”, where “AAA” is either “Py” or “TF” depending on the library you have used. You can also use publicly available implementations in portions of your solution but you need to include proper reference to your resources, e.g., url to the page that you used as a reference, books, etc.

1. Dataset Generation

We will use the Amazon reviews dataset used in HW1. Load the dataset and build a balanced dataset of 250K reviews along with their ratings (50K instances per each rating score) through random selection. Create ternary labels using the ratings. We assume that ratings more than 3 denote positive

1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
sentiment (class 1) and rating less than 3 denote negative sentiment (class 2). Reviews with rating 3 are considered to have neutral sentiment (class 3). You can store your dataset after generation and reuse it to reduce the com- putational load. For your experiments consider a 80%/20% training/testing split.

2. Word Embedding

In this part the of the assignment, you will learn how to generate two sets of Word2Vec features for the dataset you generated. You can use Gensim library for this purpose. A helpful tutorial is available in the following link:

<pre>   https://radimrehurek.com/gensim/auto_examples/tutorials/run_word2vec.
html
</pre>
(a) Load the pretrained “word2vec-google-news-300” Word2Vec model and learn how to extract word embeddings for your dataset. Try to check semantic similarities of the generated vectors using two examples of your own, e.g., King − Man + Woman = Queen or excellent ∼ outstanding.

(b)

Train a Word2Vec model using your own dataset. Set the embedding size to be 300 and the window size to be 11. You can also consider a minimum word count of 10. Check the semantic similarities for the same two examples in part (a). What do you conclude from comparing vectors generated by yourself and the pretrained model? Which of the Word2Vec models seems to encode semantic similarities between words better?

3. Simple model

Using the Word2Vec features that you can generate using the two models you prepared in the Word Embedding section, train a perceptron and an SVM model similar to HW1 for class 1 and class 2 (binary models). For this purpose, you can just use the average Word2Vec vectors for each review as the input feature (x = N1 􏰀Ni=1 Wi for a review with N words). To improve

2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
your performance, use the data cleaning and preprocessing steps of HW1 to include only important words from each review when you compute the average x = N1 􏰀Ni=1 Wi. Report your accuracy values on the testing split for these models for each feature type along with values you reported in your HW1 submission, i.e., for each of perceptron and SVM, you need to report three accuracy values for “word2vec-google-news-300”, your own Word2Vec, and TF-IDF features.

What do you conclude from comparing performances for the models trained using the three different feature types (TF-IDF, pretrained Word2Vec, your trained Word2Vec)?

4. Feedforward Neural Networks (25 points)

Using the features that you can generate using the models you prepared in the Word “Embedding section”, train a feedforward multilayer perceptron network for sentiment analysis classification. Consider a network with two hidden layers, each with 50 and 10 nodes, respectively. You can use cross entropy loss and your own choice for other hyperparamters, e.g., nonlinearity, number of epochs, etc. Part of getting good results is to select good values for these hyperparamters.

You can also refer to the following tutorial to familiarize yourself:

Although the above tutorial is for image data but the concept of training an MLP is very similar to what we want to do.

(a) (10 points)

To generate the input features, use the average Word2Vec vectors similar to the “Simple models” section and train the neural network. Train a network for binary classification using class 1 and class 2 and also a ternary model for the three classes. Report accuracy values on the testing split for your MLP model for each of the binary and ternary classification cases.

(b) (15 points)

To generate the input features, concatenate the first 10 Word2Vec vectors for each review as the input feature (x = [W T , …, W T ]) and train the neural

3

</div>
</div>
<div class="layoutArea">
<div class="column">
1 10

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
network. Report the accuracy value on the testing split for your MLP model for each of the binary and ternary classification cases.

What do you conclude by comparing accuracy values you obtain with those obtained in the “’Simple Models” section (note you can compare the accuracy values for binary classification).

5. Recurrent Neural Networks (20 points)

Using the features that you can generate using the models you prepared in the “Word Embedding” section, train a recurrent neural network (RNN) for sentiment analysis classification. You can refer to the following tutorial to familiarize yourself:

<pre>   https://pytorch.org/tutorials/intermediate/char_rnn_classification_
tutorial.html
</pre>
(a) (10 points)

Train a simple RNN for sentiment analysis. You can consider an RNN cell with the hidden state size of 50. To feed your data into our RNN, limit the maximum review length to 50 by truncating longer reviews and padding shorter reviews with a null value (0). Train the RNN network for binary classification using class 1 and class 2 and also a ternary model for the three classes. Report accuracy values on the testing split for your RNN model.

(b) (10 points)

Repeat part (a) by considering a gated recurrent unit cell.

Note that in total, you need to report accuracy values for:

2 (number of Word2Vec models) * (2 (Perceptron + SVM) + 2 (bi- nary/ternary settings) ( 2 (FNN) + 2 (RNN))) = 2 (2+ 2 (2 + 2)) = 20 cases.

4

</div>
</div>
</div>
