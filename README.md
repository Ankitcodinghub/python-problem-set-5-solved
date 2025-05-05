# python-problem-set-5-solved
**TO GET THIS SOLUTION VISIT:** [Python Problem Set 5 Solved](https://www.ankitcodinghub.com/product/python-problem-set-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99651&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Python Problem Set 5 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
# Problem Set 5

## Overview

This problem set explores randomized algorithms and graphs. The programming portion of this problem set focuses on QuickSelect, a Las Vegas randomized algorithm.

*Make sure to pull from the course source often or check Ed for updates. We hope to release a perfect problem set but sometimes we add to the problem set to make things easier or fix obscure bugs.*

## Instructions

**Problem 1a**: For this part of the problem, you must fill in the implementation for QuickSelect. We have provided some local tests to help you check that your implementation returns the right answer. You can run the included tests with `python3 -m ps5_tests` (as explained below). **If you pass the local tests you should be in good shape to move on. The focus of this problem is to implement a specific randomized algorithm.** It also sets up for the next parts of the problem.

**Problem 1b**: For this part, we have provided most of the code for plotting. You do not need to do much for this part of the problem except complete `MergeSortSelect`, experiment with different values for `k`, and possibly play around with the number of runs. `MergeSortSelect` should be an extension of `MergeSort` (provided) that runs `MergeSort` and resolves a number of queries, returning the results in one list/array. Once you have finished `MergeSortSelect`, you can test your implementation with the local tests (safe as for part 1a). After the local tests, you can start plotting. All the plotting logic and code is provided for you but feel free to adjust the plotting parameters. However, do not change `N` or the datasets for your final figure. Feel free to explore different number of `RUNS`. The more runs, the better we are able to approximate and plot the distribution; but more runs means it will take longer to complete, so set aside time to run these. It is set to 20, but if you have the time, experiment with different numbers of runs. To generate the chart run `python3 -m ps5` (as explained below). If you are having trouble fitting your generated chart on your screen, try changing the width and height parameters. **Make sure to save your generated chart and add it to your writeup.**

**Problem 1b (Continued)**: By this point in the class and in the problem set, you have implemented deterministic and randomized algorithms. We have also discussed runtime analysis but often times this hides constants that can make a difference in application; this is why we sometimes benchmark. Here you will analyze the benchmark to get a better understanding of the runtimes of randomized algorithms versus deterministic algorithms on a conceptual and practical level. Note that the conclusions we draw here are not for all randomized and deterministic algorithms, only our specific implementation of these two algorithms. In class, we went over a brief runtime analysis for QuickSelect. In reality, it might be wise to use MergeSort in some scenarios and QuickSelect in others. This is often true between two algorithms whether one be randomized and one deterministic or both are deterministic/randomized. This problem should make this idea concrete. **In this part of the problem, we want you to form your rationale on the data/figure from benchmarking and show how your intuition is developing in regard to using benchmarking to understand algorithm implementations.**

**Conclusion**: If your work passes the local tests, includes the figure for your generated chart, and answers 1b, you should be in good shape to get full marks for this problem.

## Running the Code

The problem set includes some starter code in `ps5.py`. To run the code, type in your terminal:

“`bash

python3 -m ps5

“`

## Running the Included Tests

The problem set also includes some tests for you to test your code.

To run the tests, type in your terminal:

“`bash

python3 -m ps5_tests

“`
