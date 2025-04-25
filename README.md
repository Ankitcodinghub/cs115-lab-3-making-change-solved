# cs115-lab-3-making-change-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs-115-lab-3-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;127965&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS115 Lab 3-Making Change Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
            5/5 - (4 votes)    </div>
    </div>
Making Change

In this problem, you will solve a different problem using the powerful use-it-or-lose-it strategy.

Imagine that you just got a job working for Cash Register Advanced Products. (The public relations division has suggested that the company avoid using an acronym for the company name.) The company builds electronic cash registers and the software that controls them. The cash registers are used all around the world in countries with different coin systems.

Next, imagine that we are given a list of the coin types in a given country. For example, in the U.S. the coin types are:

[1, 5, 10, 25, 50]

But, in the Kingdom of Shmorbodia, the coin types are:

[1, 7, 24, 42]

In general, the coin system could be anything, except that there is always a 1 unit coin (penny). In these examples, the denominations were given smallest to largest, but that’s not necessary. There’s nothing about use-it-or-lose-it that depends on the order of the coins.

Here’s the problem. Given an amount of money and a list of coin types, we would like to find the least number of coins that makes up that amount of money. For example, in the U.S. system, if we want to make 48 cents, we give out 1 quarter, 2 dimes, and 3 pennies. That solution uses 6 coins and that’s the best we can do in this case. Making 48 cents in the Shmorbodian system, however, is different. Giving out a 42 cent coin – albeit tempting – will force us to give the remaining balance with 6 pennies, using a total of 7 coins. We could do better by simply giving two 24 cent coins.

Your first task is to write a function called change(amount, coins) where amount is a non-negative integer indicating the amount of money to be made and coins is a list of coin values with 1 always being in the list when we first call the function. (This ensures that it is always possible to make change for any positive amount.) The function should return a non-negative integer indicating the minimum number of coins required to make up the given amount.

Here is an example of this function in action:

&gt;&gt;&gt; change(48, [1, 5, 10, 25, 50])

6

&gt;&gt;&gt; change(48, [1, 7, 24, 42])

2

CS 115 – Lab 3

&gt;&gt;&gt; change(35, [1, 3, 16, 30, 50]) 3

A few notes and tips…

Not surprisingly, the secret-to-all-happiness is to use the use-it-or-lose-it recursion strategy.

&gt;&gt;&gt; float(“inf”) &gt; 42 True

&gt;&gt;&gt; 42 + float(“inf”) inf &lt;– It’s still infinity!

&gt;&gt;&gt; min(42, float(“inf”))

42
