# big-data-processing-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [Big Data Processing: Assignment 3 Solved](https://www.ankitcodinghub.com/product/big-data-processing-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117660&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Big Data Processing: Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
You will be given a file with text documents, where each line corresponds to one document. For a given word (say W), the goal is to find:

1) Find top k positively associated word to W.

2) Find top k negatively associated word to W.

The association is computed based on word co-occurrence in documents using pointwise mutual information (PMI) scores. A word must not contain anything other than English letters. While computing co-occurrence, you must lowercase all the words and you must also remove the stopwords available here: https://github.com/terrier-org/terrier-desktop/blob/master/share/stopword-list.txt

PMI(w1, w2) =

where P(w1,w2) = co/N, P(w) = m/N co -&gt; # documents where two words appear m -&gt; # documents where w present

N -&gt; # documents

You goal is to write spark program for the above problem. You can use either scala or pyspark. Your code must have the main function.

Output format: Output needs to be printed on screen. First the list of positively associated words along with the PMI score. Then the list of negatively associated words along with the PMI scores.

We will evaluate your program on a linux system from command line with the arguments as follows:

spark-submit &lt;your-code&gt; &lt;path to file&gt; &lt;query-word&gt; &lt;k&gt; &lt;stopword-file&gt;

Where “query-word” is the given word, k is the top positively associated and negatively associated words to “query-word”. This format is very important for evaluation. Thus, your program arguments must follow the sequence. Your program must have a main function. The &lt;stopword-file&gt; contains the list of stopwords (one word in one line).

Submission guidelines:

Important notes:

1. No credit will be given if your program does not run and produces wrong output.

3. It is your responsibility to check that the file has been submitted successfully.
