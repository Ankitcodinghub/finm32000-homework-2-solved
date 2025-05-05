# finm32000-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [FINM32000 Homework 2 Solved](https://www.ankitcodinghub.com/product/finm32000-homework-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98414&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;FINM32000 Homework 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
The Gold Dragon Coin (GDC) is a unit of currency in Westeros. Let S denote the GDC/USD exchange rate (the USD value of 1 GDC). Assume S has dynamics

dSt = (r − q)Stdt + σ(St, t)StdWt,

where W is Brownian motion under the [USD] risk-neutral probability measure. The USD interest

rate is r = 0.06, the GDC interest rate is q = 0.01, today’s time-0 spot is S0 = 100, and σ(S, t) := min[0.2 + 5(log(S/100))2 + 0.1e−t, 0.6].

<ol>
<li>(a) &nbsp;Find the time-0 price of an American-style put on the GDC. The put is struck at 95 and expires at time 0.75.</li>
<li>(b) &nbsp;Find the time-0 price of a European-style call, with strike 10 and expiry 0.25, on an American put on the GDC, to be issued at time 0.25 if the European call is exercised (therefore the put will not already have been exercised prior to time 0.25). The American put has strike 95 and expiry 0.75.
This call is an example of a compound option. At time 0.25 it gives you the right to buy the underlying put for 10. The underlying put will have the usual exercise privilege on the time interval [0.25, 0.75], at strike 95.
</li>
</ol>
All prices are, as usual, in USD unless stated otherwise.

Complete the coding of the function pricer compound localvol trinom in the provided file

hw2.ipynb. Use a trinomial tree.

Your code may reject N for which the call expiry fails to be represented in the tree. In choosing

∆x, follow L2.10 and choose the “representative” volatility σavg to be σ(S0,0).

The amount of work done by your algorithm in this problem should grow like N2 as N grows (no proof required). If it grows like N3 in this problem, then your algorithm has some major

inefficiency.

Problem 2 on next page

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Problem 2

<ol>
<li>(a) &nbsp;In the Black-Scholes model with interest rate r, no dividends, and volatility σ, approximate the time-0 delta of an at-the-money (K = S0) vanilla call with expiry T, by applying a first-order Taylor expansion to the exact formula, and obtaining an explicit approximation formula in terms of the given parameters.
Then evaluate this approximation to two decimal places, assuming σ = 0.2 and T = 0.25 and r = 0.01.
</li>
<li>(b) &nbsp;Suppose that some option, or combination of options – let’s call it the “combination” – has a time-0 pricing function C(S) with respect to an underlying stock S.
price S0 dollars per share).

Define the combination’s time-0 dollar gamma to be its gamma multiplied by S02/100:

1 S 02 ∂ 2 C , 100 ∂S2

which equals the dollar value of stock shares that need to be purchased/sold in order to rebalance a delta hedge, per 1 percent movement in the stock price.

(because: the shares of stock to be purchased/sold is ∂2C per dollar movement in S. ∂S2

So the dollars of stock to be purchased/sold is S ∂2C per dollar movement in S. 0 ∂S2

So the dollars of stock to be purchased/sold is S ∂2C × S0 per 1 percent change in S.) 0 ∂S2 100

Suppose that at time 0, the underlying stock has price S0 = 4, and the option combination has price 5, dollar delta 3, and dollar gamma 0.02.

Use a second-order Taylor expansion (with zeroth, first, and second order terms) to approxi- mate the time-0 value of the contract, given an underlying stock price 3.6.

Hint: convert the dollar delta and dollar gamma into delta and gamma, and apply Taylor expansion to C.
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
Define the combination’s time-0 dollar delta to be its delta multiplied by S0: S ∂C,

</div>
</div>
<div class="layoutArea">
<div class="column">
0 ∂S

which equals the dollar value of the stock position in the delta hedge (quantity ∂C shares ×

</div>
</div>
<div class="layoutArea">
<div class="column">
∂S

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
