# comp9021-coding-quiz-6-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/comp9021-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;131253&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP9021 Coding Quiz 6 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
COMP9021 Principles of Programming

Coding Quiz 6

Description

You are provided with a stub in which you need to insert your code where indicated without doing any changes to the existing code to complete the task.

Given the value of seed and density, the provided code randomly fills an array (or grid) of size 10 x 10 with 0s and 1s.

Your task is to determine the maximum number of “spikes” in a shape.

A shape is made up of 1s connected horizontally or vertically (it can contain holes).

A “spike” in a shape is a 1 that is part of this shape and “sticks out” (has exactly one neighbour in the shape).

Neighbours are only considered vertically or horizontally (not diagonally).

Note that a shape with a single 1 is also a spike.

See test cases below for more examples.

Make sure not to change the filename quiz_6.py while submitting by clicking on [Mark] button in Ed. It is your responsibility to check that your submission did go through properly using Submissions link in Ed otherwise your mark will be zero for Quiz 6.

Test Cases

$ python3 quiz_6.py

Enter two integers, the second one being strictly positive: 0 8

Here is the grid that has been generated:

1 1 0 1 1 1 1 1 1 1

1 1 1 1 1 1 1 1 1 1

1 1 1 1 1 1 1 1 1 0

0 1 1 0 1 1 1 1 1 1

1 1 1 1 1 1 1 1 1 1

1 1 1 1 1 1 1 1 1 1

1 1 1 1 0 1 1 1 1 1

1 0 1 1 1 1 1 1 1 1

1 1 1 1 1 1 1 1 1 0

1 1 1 1 1 1 1 0 1 1

The maximum number of spikes of some shape is: 1

Enter two integers, the second one being strictly positive: 0 7

Here is the grid that has been generated:

1 1 1 1 0 1 1 1 1 1

1 1 1 1 1 1 1 1 1 1

1 0 1 1 1 1 1 1 1 1

1 0 1 0 1 1 1 1 1 0

1 1 1 1 1 1 1 1 1 1

1 1 0 1 1 0 0 1 1 1

1 1 1 1 1 0 1 1 1 1

1 1 1 1 1 1 0 1 1 1

1 1 1 1 1 1 0 0 1 1

1 0 1 1 1 1 0 1 1 1

The maximum number of spikes of some shape is: 3

$ python3 quiz_6.py

Enter two integers, the second one being strictly positive: 0 2 Here is the grid that has been generated:

1 1 0 1 1 1 1 1 1 0

0 1 0 0 1 0 1 0 0 1

1 0 1 1 1 0 1 1 1 0

0 0 1 0 1 1 0 1 0 0

0 0 0 1 0 0 1 1 0 1

1 0 1 0 1 1 0 1 1 0

1 0 0 0 0 1 1 0 0 0

0 0 0 1 1 0 0 1 1 1

1 1 0 1 0 1 1 0 0 0

1 0 0 1 0 1 1 0 0 0

The maximum number of spikes of some shape is: 7

$ python3 quiz_6.py

Enter two integers, the second one being strictly positive: 0 4 Here is the grid that has been generated:

1 1 0 1 1 1 1 1 1 1

1 1 1 0 1 1 1 0 0 1

1 0 1 1 1 1 1 1 1 0

0 0 1 0 1 1 1 1 0 1

1 1 1 1 0 0 1 1 0 1

1 0 1 1 1 1 0 1 1 1

1 1 1 1 0 1 1 0 0 1

1 0 0 1 1 1 1 1 1 1

1 1 0 1 0 1 1 1 1 0

1 0 1 1 1 1 1 0 0 1

The maximum number of spikes of some shape is: 8

$ python3 quiz_6.py

Enter two integers, the second one being strictly positive: 1 2 Here is the grid that has been generated:

1 0 1 1 0 1 1 0 0 1

0 0 0 0 1 0 1 0 0 1

0 1 0 1 1 0 1 1 1 1

0 1 0 1 1 0 1 1 0 1

0 0 1 1 1 0 1 0 1 1

0 0 0 0 0 0 1 1 1 1

1 0 1 0 0 1 0 1 1 0

1 1 1 1 1 0 1 1 0 0 The maximum number of spikes of some shape is: 5

0 0 1 0 1 1 1 1 0 0

1 0 1 0 0 1 1 0 1 0

2 2

0 0 0 1 0 1 1 0 0 0

1 1 1 1 1 0 0 1 1 1

1 1 0 0 0 0 0 0 1 0

0 1 0 1 1 1 1 1 1 0

1 1 0 1 1 1 1 1 1 1

1 1 0 1 0 1 1 1 1 1

1 0 1 1 0 1 0 0 0 0

0 1 0 0 0 1 0 0 0 1

0 0 1 1 0 0 0 0 0 0

0 0 0 1 1 0 0 0 0 1

The maximum number of spikes of some shape is: 4

Test Cases Explained

$ python3 quiz_6.py

Enter two integers, the second one being strictly positive: 0 8

Here is the grid that has been generated:

1 1 0 1 1 1 1 1 1 1

1 1 1 1 1 1 1 1 1 1

1 1 1 1 1 1 1 1 1 0

0 1 1 0 1 1 1 1 1 1

1 1 1 1 1 1 1 1 1 1

1 1 1 1 1 1 1 1 1 1

1 1 1 1 0 1 1 1 1 1

1 0 1 1 1 1 1 1 1 1

1 1 1 1 1 1 1 1 1 0

1 1 1 1 1 1 1 0 1 1

The maximum number of spikes of some shape is: 1

$ python3 quiz_6.py

Enter two integers, the second one being strictly positive: 0 7

Here is the grid that has been generated:

1 1 1 1 0 1 1 1 1 1

1 1 1 1 1 1 1 1 1 1

1 0 1 1 1 1 1 1 1 1

1 0 1 0 1 1 1 1 1 0

1 1 1 1 1 1 1 1 1 1

1 1 0 1 1 0 0 1 1 1

1 1 1 1 1 0 1 1 1 1

1 1 1 1 1 1 0 1 1 1

1 1 1 1 1 1 0 0 1 1

1 0 1 1 1 1 0 1 1 1

The maximum number of spikes of some shape is: 3

0 2

1 1 0 1 1 1 1 1 1 0

0 1 0 0 1 0 1 0 0 1

1 0 1 1 1 0 1 1 1 0

0 0 1 0 1 1 0 1 0 0

0 0 0 1 0 0 1 1 0 1

1 0 1 0 1 1 0 1 1 0

1 0 0 0 0 1 1 0 0 0

0 0 0 1 1 0 0 1 1 1

1 1 0 1 0 1 1 0 0 0

1 0 0 1 0 1 1 0 0 0

The maximum number of spikes of some shape is: 7

0 4

1 1 0 1 1 1 1 1 1 1

1 1 1 0 1 1 1 0 0 1

1 0 1 1 1 1 1 1 1 0

0 0 1 0 1 1 1 1 0 1

1 1 1 1 0 0 1 1 0 1

1 0 1 1 1 1 0 1 1 1

1 1 1 1 0 1 1 0 0 1

1 0 0 1 1 1 1 1 1 1

1 1 0 1 0 1 1 1 1 0

1 0 1 1 1 1 1 0 0 1

The maximum number of spikes of some shape is: 8

$ python3 quiz_6.py

Enter two integers, the second one being strictly positive: 1 2 Here is the grid that has been generated:

0 0 1 0 1 1 1 1 0 0

1 0 1 1 0 1 1 0 0 1

0 0 0 0 1 0 1 0 0 1

1 0 1 0 0 1 1 0 1 0

0 1 0 1 1 0 1 1 1 1

0 1 0 1 1 0 1 1 0 1

0 0 1 1 1 0 1 0 1 1

0 0 0 0 0 0 1 1 1 1

1 0 1 0 0 1 0 1 1 0

1 1 1 1 1 0 1 1 0 0

The maximum number of spikes of some shape is: 5

2 2

0 0 0 1 0 1 1 0 0 0

1 1 1 1 1 0 0 1 1 1

1 1 0 0 0 0 0 0 1 0

0 1 0 1 1 1 1 1 1 0

1 1 0 1 1 1 1 1 1 1

1 1 0 1 0 1 1 1 1 1

1 0 1 1 0 1 0 0 0 0

0 1 0 0 0 1 0 0 0 1

0 0 1 1 0 0 0 0 0 0

0 0 0 1 1 0 0 0 0 1

The maximum number of spikes of some shape is: 4
