# cse412-assignment-4-fund-raising-event-simulation-solved
**TO GET THIS SOLUTION VISIT:** [CSE412 Assignment 4-Fund raising event simulation Solved](https://www.ankitcodinghub.com/product/cse-412-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112786&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE412 Assignment 4-Fund raising event simulation Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Assignment-4/Fund raising event simulation

A sports club is holding an event which is advertised as a cultural programme, but the real purpose is fund raising (or, money extraction) from the participants/attendants of the event by gambling. There is a fixed cost of 50,000 Taka for arrangement of the event (hiring the artistes) and a variable cost of 30 Taka/person (for serving tea/lemonade). There is an entry fee of 30 Taka/person.

The number of attendants (4500/2500/1500) depend on the weather (sunny/cloudy/rainy) respectively. There are three gambling instruments: [1] Two-Sided Game Table (TST), [2] wheel of fortune (WF), and [3] Roulette Wheels (RT). The playing odds are (0.4/0.4/0.5) for (TST/WF/RT) respectively. This means a player’s probability of winning a game of TST is 0.4 and the house’s probability of winning it is (1 – 0.4) = 0.6. To play a game, a player bets an amount of 50 Taka. The house also bets the same amount which means the pot of money has 2 * 50 Taka = 100 Taka. The winner takes all of 100 Taka at the end of the game.

To calculate profit, you need to determine the revenue and the costs. The revenue consists of the earnings of the games and the entry fee. The costs include the bets of the house for the games and the cost of arrangement (fixed + variable costs).

The three types of games have participation odds. If a particular type of game has a participation odd of 0.8, then 80% of the attendants play it. It is assumed that everybody participates in all the games in the first round. This means all three type have participation odds of 1.0 in the first round. The participation odds of a type of game in the second round depends on its playing odds in the first round. If the first round playing odd is x, then the second round participation odd is minimum (1, 2*x). This means the participation odd of TST in the second round is minimum (1, 2*0.4) = 0.8. The playing odds in the second round also depend on the first round playing odds. If the first round playing odd is x, then the second round playing odd is maximum (0.1, x – 0.1). This means the participation odd of TST in the second round is maximum (0.1, 0.4 – 0.1) = 0.3.

1.

a) Find out the profits, costs, and revenues of the first round only. Show how the profit varies for two variables bets and entry fee. This is a deterministic model with no randomness. Vary the values of the parameters to find a few break-even points (when the profit is zero).

b) Find out the profits, costs, and revenues of the first round and the second round. The total profit is the sum of the first and second round profits.

2. Consider that the weather conditions can be either sunny (5000 participants) or rainy (2500 participants), depending on standard uniform random probability distribution. Find out average profit for 10 runs for two cases: (i) 30 % sunny, 70% rainy (ii) 30 % rainy, 70% sunny.
