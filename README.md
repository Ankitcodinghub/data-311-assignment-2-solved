# data-311-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [DATA 311 ASSIGNMENT 2 Solved](https://www.ankitcodinghub.com/product/data-311-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115870&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DATA 311 ASSIGNMENT 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Yunfan Yang 30067857

Quick Sort

Description

Quicksort is a divide-and-conquer sorting algorithm, and it can be implemented by using recursion. A partition is a divided sub-array, and a pivot is a flag point chosen by the algorithm in a partition for conquest. Quicksort executes the following steps:

1. Pick an element from the given array as a pivot. This pivot element can be random or designated.

2. Partitioning the given array: starting from both side, conquer the two value on the left and the right side with the pivot value; if the left value is smaller than the pivot, or if the right value is greater than the pivot, keep moving to the next element on the side; until one element from the left side is greater than the pivot, meanwhile one element from the right side is smaller than the pivot, then exchange them and keep moving to the next element on both sides. The element equals to the pivot can go either side. Eventually, both left and right conquest index will meet each other at one element, and as a result, all the elements on the left of the pivot point will be smaller than the pivot and all the elements on the right of the pivot point will be greater than the pivot point.

3. Divide the given array into two sub-arrays, and the element which left and right searching point meet is the point of division. For each of the divided sub-arrays, recursively apply the above steps.

The base case of Quicksort is the left conquest index is greater than or equal to the right conquest index, which means all the elements in the given array are partitioned.

The best, average and worst case are: 𝑂(𝑛 log 𝑛), 𝑂(𝑛 log 𝑛) and 𝑂(𝑛2). The selection of the pivot element can affect the Big-O since it might be the smallest or greatest element which leads to one sub-array only has one element and increase the times of recursion.

Asymptotic Complexity

𝑛

𝑇(𝑛) = 2𝑇( ) + 𝜃(𝑛)

2

𝑎 = 2, 𝑏 = 2, 𝑓(𝑛) = 𝜃(𝑛)

𝑙𝑜𝑔𝑏𝑎 = 𝑙𝑜𝑔22 = 1 = 𝜃(𝑛)

𝜃(𝑛𝑙𝑜𝑔𝑏𝑎 log 𝑛) = 𝜃(𝑛 log 𝑛)

Merge Sort

Description

Merge sort is a divide-and-conquer sorting algorithm as well and it can be implemented by using recursion. This algorithm divides the given array into all sub-arrays, then sort by conquest and merge the sub-arrays. Merge sort executes the following steps:

1. Divide the given array into two sub-arrays by half, recursively apply this step until there is only one element to divide. The divided will apply the next step.

2. Sort and merge the two halves: starting from the first element of both halves, conquer both elements from both sides, the greater element will be copied to the new array first, and move to the element of the side, then continuing conquest; until there is no element left for conquest on one side, copy the rest of elements on the another side to the new array.

3. After merging the two sub-arrays, recursively continuing sort and merge with the upperlevel sub-arrays, until there is only one whole array.

The base case of Merge sort is the left conquest index is greater than the right conquest index, which means the given array cannot be divided anymore.

The best, average and worst for Merge sort are all 𝑂(𝑛 log 𝑛).

Asymptotic Complexity

𝑛

𝑇(𝑛) = 2𝑇( ) + 𝜃(𝑛)

2

𝑎 = 2, 𝑏 = 2, 𝑓(𝑛) = 𝜃(𝑛)

𝑙𝑜𝑔𝑏𝑎 = 𝑙𝑜𝑔22 = 1 = 𝜃(𝑛)

𝜃(𝑛𝑙𝑜𝑔𝑏𝑎 log 𝑛) = 𝜃(𝑛 log 𝑛)

Binary Search

Description

Binary search is a searching algorithm which finds the position of a target value in an array or detects whether the given array contains the target value. For using this searching algorithm, the given array must be sorted first. This algorithm can be implemented using recursion. Binary search executes the following steps:

1. Pick a middle point index from the given search range in the given array.

2. If the value to this middle point index is exactly the target value, return the middle point index since the position of the target value is found; otherwise, compare the target value with the value to the middle point index: if the target value is greater, the search range zoom in to the middle point element and the last element of the given range; else, if the target value is smaller, the search range zoom in to the first element of the given range to the middle point element.

3. Recursively apply the above steps until the value is found or the range cannot be zoomed any more.

The base case of Binary search is the left range index is greater than the right range index which means the range is not valid and the target value is not in the given array.

The best, average and worst case for Binary search are: 𝑂(1), 𝑂(log 𝑛) and 𝑂(log 𝑛). The best case means that the first middle point value exactly is the target value.

Asymptotic Complexity

𝑛

𝑇(𝑛) = 𝑇 ( ) + 𝜃(1)

2

𝑎 = 1, 𝑏 = 2, 𝑓(𝑛) = 𝜃(𝑛)

𝑙𝑜𝑔𝑏𝑎 = 𝑙𝑜𝑔21 = 0 &lt; 𝜃(1)

𝜃(𝑛𝑙𝑜𝑔𝑏𝑎 log 𝑛) = 𝜃(𝑛0𝑙𝑜𝑔𝑛) = 𝜃(log 𝑛)
