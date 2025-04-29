# cs2040s-problem-set-7--data-analysis-speed-demon-solved
**TO GET THIS SOLUTION VISIT:** [CS2040S Problem Set 7- Data Analysis Speed Demon Solved](https://www.ankitcodinghub.com/product/cs2040s-data-structures-and-algorithms-solved-7/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109418&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2040S Problem Set 7- Data Analysis Speed Demon Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Overview

We live in a world overwhelmed with information. Every two days, we create as much new information as was created in the entire history of human civilization up until 2003 (according to Eric Schmidt, the CEO of Google). We produce more than 3 exabytes of data per day! Much of this data is stored in large databases, and one of the challenges today is to rapidly process and analyze all the data. Since the databases are so large, it requires very fast algorithms and data structures that are highly optimized for maximum efficiency. In this competition, you will try to develop the fastest algorithm for analyzing a large dataset.

When analyzing a large dataset, there are many different goals. We will focus on a particular type of data mining in which we want to discover properties and patterns of the underlying data. Frequently, we want to know various statistics: the average, the median and the mode. Often, we also want to know about patterns: how often do users of a certain profile (e.g., males between the ages of 18 and 32) buy a certain item? Often, we want to know about correlations: how often does a user who buys item A click on link B?

For the purpose of this competition, we define an abstract data mining problem that involves finding correlations in our data set. The database consists of a large set of very large data entries. The goal is to find how many pairs of entries are identical, i.e., contain the same information. Your job is to implement a data mining program that reads in the database and performs this analysis as fast as possible.

Problem Details

We now describe the details of the competition more precisely.

Your program will implement a single public method: public int processData(String filename). This method will take a filename as an input. It should then parse the file and process the data in the file. Finally, it should return an integer as the answer. (We have given you an existing class file template to use.)

Example. The following is an example of an input database:

7

BCDEFGH

ABACD

BDCEF

BDCAA

DBACA

DABACA

DABAC

The appropriate output in this case is:

6

In particular, note the following six pairs of equivalent entries:

(ABACD, BDCAA)

(ABACD, DBACA)

(ABACD, DABAC)

(BDCAA, DBACA)

(BDCAA, DABAC)

(DBACA, DABAC)

Rules

The following are the rules of the competition:

• Your solution must be written in Java.

• You are allowed to submit only one final program.

Submission Details

Here are some instructions for submitting the code:

• You need to submit your solution on Coursemology as usual.

• If you want to qualify for the competition, you will need to separately submit your solution on a different platform. More details about this will be given later via an announcement.

• The top 10 winners of the competition will get bonus marks.

Hints

A few hints toward achieving good performance:

• First, develop and test a working solution that achieves good asymptotic performance. Then improve it.

• Think about the performance of the data structures you are using and the actual costs of the operations involved.

• Remember that for large databases, memory usage is important. Maintaining big data structures that use a lot of memory can be slow.

• Think about data locality in memory: accessing elements in memory that are near to each other is much cheaper than accessing elements that are far away from each other.

• Beware of the small costs that add up. For example, declaring a variable leads to a memory allocation which has a cost.

• Beware the costs of recursion.

• Profile your solution to determine what to optimize.

Java Help

How do I read in a file?

import java.io.BufferedReader; import java.io.FileReader;

try {

// Code for accessing the ile goes here

} catch (Exception e) {

System.out.println(e);

}

The first thing you need to do is to open the file using the FileReader:

FileReader dataFile = new FileReader(fileName);

You then access the file via a BufferedReader:

BufferedReader bufferedDataFile = new BufferedReader(dataFile);

You can then read the file:

String line = bufferedDataFile.readline();

For more information on the BufferedReader and FileReader (and other file access mechanisms), see the Oracle Java Reference:

https://docs.oracle.com/javase/8/docs/api/java/io/BufferedReader.html How do I measure how fast my program runs?

We have included several sample databases to test your program on. And remember the StopWatch class you used back in the Sorting Detectives Problem Set? That might be useful here too.
