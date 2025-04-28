# cs61a-homework-3--recursion-tree-recursion-solved
**TO GET THIS SOLUTION VISIT:** [CS61A Homework 3- Recursion, Tree Recursion Solved](https://www.ankitcodinghub.com/product/cs61a-homework-3-recursion-tree-recursion-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119647&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS61A  Homework 3- Recursion, Tree Recursion Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Instructions

Download hw03.zip. Inside the archive, you will find a file called hw03.py, along with a copy of the ok autograder.

Using Ok: If you have any questions about using Ok, please refer to this guide.

Readings: You might find the following references useful: Section 1.7

Grading: Homework is graded based on correctness. Each incorrect problem will decrease the total score by one point. There is a homework recovery policy as stated in the syllabus. This homework is out of 2 points.

Required Questions

Getting Started Videos

YouTube link

Parsons Problems

To work on these problems, open the Parsons editor:

python3 parsons

Q1: Neighbor Digits

Implement the function neighbor_digits. neighbor_digits takes in a positive integer num and an optional argument prev_digit. neighbor_digits outputs the number of digits in num that have the same digit to its right or left.

py def neighbor_digits(num, prev_digit=-1): “”” Returns the number of digits in num that have the same digit to its right or left. &gt;&gt;&gt; neighbor_digits(111) 3 &gt;&gt;&gt; neighbor_digits(123) 0 &gt;&gt;&gt; neighbor_digits(112) 2 &gt;&gt;&gt; neighbor_digits(1122) 4 “”” “*** YOUR CODE HERE ***” Q2: Has Subsequence

Implement the function has_subseq, which takes in a number n and a “sequence” of digits seq. The function returns whether n contains seq as a subsequence, which does not have to be consecutive.

For example, 141 contains the sequence 11 because the first digit of the sequence, 1, is the first digit of 141, and the next digit of the sequence, 1, is found later in 141.

“`py def has_subseq(n, seq): “”” Complete has_subseq, a function which takes in a number n and a “sequence” of digits seq and returns whether n contains seq as a subsequence, which does not have to be consecutive.

&gt;&gt;&gt; has_subseq(123, 12)

True

&gt;&gt;&gt; has_subseq(141, 11)

True

&gt;&gt;&gt; has_subseq(144, 12)

False

&gt;&gt;&gt; has_subseq(144, 1441)

False

&gt;&gt;&gt; has_subseq(1343412, 134)

True

“””

“*** YOUR CODE HERE ***”

“`

Code Writing Questions

Q3: Num eights

Write a recursive function num_eights that takes a positive integer pos and returns the number of times the digit 8 appears in pos.

Important: Use recursion; the tests will fail if you use any assignment statements. (You can however use function definitions if you so wish.) “`py def num_eights(pos): “””Returns the number of times 8 appears as a digit of pos.

&gt;&gt;&gt; num_eights(3)

0

&gt;&gt;&gt; num_eights(8)

1

&gt;&gt;&gt; num_eights(88888888)

8

&gt;&gt;&gt; num_eights(2638)

1

&gt;&gt;&gt; num_eights(86380)

2

&gt;&gt;&gt; num_eights(12345)

0

&gt;&gt;&gt; from construct_check import check

&gt;&gt;&gt; # ban all assignment statements

&gt;&gt;&gt; check(HW_SOURCE_FILE, ‘num_eights’,

… [‘Assign’, ‘AnnAssign’, ‘AugAssign’, ‘NamedExpr’]) True

“””

“*** YOUR CODE HERE ***”

“`

Use Ok to test your code:

python3 ok -q num_eights

Q4: Ping-pong

The ping-pong sequence counts up starting from 1 and is always either counting up or counting down. At element k, the direction switches if k is a multiple of 8 or contains the digit 8. The first 30 elements of the ping-pong sequence are listed below, with direction swaps marked using brackets at the 8th, 16th, 18th, 24th, and 28th elements:

|Index|1|2|3|4|5|6|7|[8]|9|10|11|12|13|14|15|[16]|17|[18]|19|20|21|22|23| |:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:| |PingPong Value|1|2|3|4|5|6|7|[8]|7|6|5|4|3|2|1|[0]|1|[2]|1|0|-1|-2|-3|

|Index (cont.)|[24]|25|26|27|[28]|29|30| |:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:| |PingPong Value|[-4]|-3|-2|-1|[0]|-1|-2|

Implement a function pingpong that returns the nth element of the ping-pong sequence without using any assignment statements. (You are allowed to use function definitions.)

Important: Use recursion; the tests will fail if you use any assignment statements. (You can however use function definitions if you so wish.)

Hint: If you’re stuck, first try implementing pingpong using assignment statements and a while statement. Then, to convert this into a recursive solution, write a helper function that has a parameter for each variable that changes values in the body of the while loop.

Hint: There are a few pieces of information that we need to keep track of. One of these details is the direction that we’re going (either increasing or decreasing). Building off of the hint above, think about how we can keep track of the direction throughout the calls to the helper function.

“`py def pingpong(n): “””Return the nth element of the ping-pong sequence.

&gt;&gt;&gt; pingpong(8)

8

&gt;&gt;&gt; pingpong(10)

6

&gt;&gt;&gt; pingpong(15)

1

&gt;&gt;&gt; pingpong(21)

-1

&gt;&gt;&gt; pingpong(22)

-2

&gt;&gt;&gt; pingpong(30)

-2

&gt;&gt;&gt; pingpong(68)

0

&gt;&gt;&gt; pingpong(69)

-1

&gt;&gt;&gt; pingpong(80)

0

&gt;&gt;&gt; pingpong(81)

1

&gt;&gt;&gt; pingpong(82)

0

&gt;&gt;&gt; pingpong(100)

-6

&gt;&gt;&gt; from construct_check import check

&gt;&gt;&gt; # ban assignment statements

&gt;&gt;&gt; check(HW_SOURCE_FILE, ‘pingpong’,

… [‘Assign’, ‘AnnAssign’, ‘AugAssign’, ‘NamedExpr’]) True

“””

“*** YOUR CODE HERE ***”

“`

Use Ok to test your code:

python3 ok -q pingpong

Q5: Count coins

Given a positive integer change, a set of coins makes change for change if the sum of the values of the coins is change. Here we will use standard US Coin values: 1, 5, 10, 25. For example, the following sets make change for 15:

15 1-cent coins

10 1-cent, 1 5-cent coins

5 1-cent, 2 5-cent coins

5 1-cent, 1 10-cent coins

3 5-cent coins

1 5-cent, 1 10-cent coin

Thus, there are 6 ways to make change for 15. Write a recursive function count_coins that takes a positive integer change and returns the number of ways to make change for change using coins.

You can use either of the functions given to you:

get_larger_coin will return the next larger coin denomination from the input, i.e. get_larger_coin(5) is 10.

get_smaller_coin will return the next smaller coin denomination from the input, i.e. get_smaller_coin(5) is 1.

There are two main ways in which you can approach this problem. One way uses get_larger_coin, and another uses get_smaller_coin.

Important: Use recursion; the tests will fail if you use loops.

Hint: Refer the implementation of count_partitions for an example of how to count the ways to sum up to a final value with smaller parts. If you need to keep track of more than one value across recursive calls, consider writing a helper function.

“`py def get_larger_coin(coin): “””Returns the next larger coin in order. &gt;&gt;&gt; get_larger_coin(1) 5 &gt;&gt;&gt; get_larger_coin(5) 10 &gt;&gt;&gt; get_larger_coin(10) 25 &gt;&gt;&gt; get_larger_coin(2) # Other values return None “”” if coin == 1: return 5 elif coin == 5: return 10 elif coin == 10: return 25

def get_smaller_coin(coin): “””Returns the next smaller coin in order. &gt;&gt;&gt; get_smaller_coin(25) 10 &gt;&gt;&gt; get_smaller_coin(10) 5 &gt;&gt;&gt; get_smaller_coin(5) 1 &gt;&gt;&gt; get_smaller_coin(2) # Other values return None “”” if coin == 25: return 10 elif coin == 10: return 5 elif coin == 5: return 1

def count_coins(change): “””Return the number of ways to make change using coins of value of 1, 5, 10, 25. &gt;&gt;&gt; count_coins(15) 6 &gt;&gt;&gt; count_coins(10) 4 &gt;&gt;&gt; count_coins(20) 9 &gt;&gt;&gt; count_coins(100) # How many ways to make change for a dollar? 242 &gt;&gt;&gt; count_coins(200) 1463 &gt;&gt;&gt; from construct_check import check &gt;&gt;&gt; # ban iteration &gt;&gt;&gt; check(HW_SOURCE_FILE, ‘count_coins’, [‘While’, ‘For’]) True “”” ”

YOUR CODE HERE ” “`

Use Ok to test your code:

python3 ok -q count_coins

Optional Questions

Homework assignments will also contain prior exam-level questions for you to take a look at. These questions have no submission component; feel free to attempt them if you’d like a challenge!
