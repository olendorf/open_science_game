---
title       : A Game Theoretical Exploration of Open Science
subtitle    : An Objectivist's Guide
author      : Robert Olendorf
event       : Penn State Libraries Research Colloquium
event_date  : March 16, 2017
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap, shiny, interactive}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
output      :
  ioslides_presentation: 
    transition: slower
---







<img src="assets/fig/A researcher's dilemma-1.png" title="plot of chunk A researcher's dilemma" alt="plot of chunk A researcher's dilemma" style="display: block; margin: auto;" />

*** {name: pnotes}
a test

---&vcenter

<h1 class='jumbo'>We Need Solutions That Survive the <span class='warning'>WWJD</span> Test<h1>

---


<img src="assets/img/ayn_rand.png" title="plot of chunk Ayn Rand saying What would John Galt do" alt="plot of chunk Ayn Rand saying What would John Galt do" width="800px" style="display: block; margin: auto;" />

---&twocol

## A Game Theoretic Approach


*** {name: left}
<br/>
 - Developed in 1928 by John von Neumann
 - Used to determine 
   - Optimal Behavior
   - Expected Behavior
 <br/>
 - Basic Approach
   - Determine Payoffs
   - Determine Strategies
   - Find Equilibria

*** {name: right}
<br/>
<br/>
<img src="assets/img/john_von_neuman.png" title="plot of chunk Introduce Game Theory" alt="plot of chunk Introduce Game Theory" width="300px" style="display: block; margin: auto;" />


*** {name: footer}

<br/>
<hr/>
<blockquote>Truth...is much too complicated to allow anything but approximations. <br/><span class="author">-John Von Neumann</span></blockquote>

---
## Prisoners' Dilemma
<br/>
<br/>

<img src="assets/img/prisoners_dilemma_first.png" title="plot of chunk Introduce the Prisoners Dilemma" alt="plot of chunk Introduce the Prisoners Dilemma" width="700px" style="display: block; margin: auto;" />

<br/>
<hr/>

*** {name: footer}
<blockquote>Beware of altruism. It is based on self-deception, the root of all evil. <br/><span class="author">-Robert Heinlein in "Time Enough for Love"</span></blockquote>

---

<img src="assets/img/cost_benefits.png" title="plot of chunk Determining the Payoffs" alt="plot of chunk Determining the Payoffs" width="600px" style="display: block; margin: auto;" />

<hr/>
<br/>
<h4 class="text-centered">
  <span class="info">Payoff</span> = 
  <span class="success">Benefits</span> - 
  <span class="warning">Cost</span> => Chance of Promotion
</h4>

<br/>
<hr/>

*** {name: footer}
<blockquote>Nature is an expert in cost-benefit analysis. Although she does her accounting a little differently, she always collects in the long run. <br/><span class="author">-Margaret Atwood</span></blockquote>

---

## Play a Game With Your Neighbor

<br/>
<br/>

<img src="assets/img/audience_play1.png" title="plot of chunk Audience Plays 1" alt="plot of chunk Audience Plays 1" width="600px" style="display: block; margin: auto;" />

<br/>
<br/>
<hr/>

*** {name: footer}
<blockquote>Every time you play your hand the way you would if you could see your opponent's cards, you gain, and every time your oppenents play their cards differently from the way they would play them if they could see your cards, you gain.<span class="author">-David Sklansky (3x World Series of Poker Champion, poker theoretician and author)</span></blockquote>

---

## Play a Game With Your Neighbor

<br/>
<br/>

<img src="assets/img/audience_play2.png" title="plot of chunk Audience Plays 2" alt="plot of chunk Audience Plays 2" width="600px" style="display: block; margin: auto;" />

<br/>
<br/>
<hr/>

*** {name: footer}
<blockquote>The only redeeming thing about mankind is coopration.<span class="author">-Bertrand Russell (Philosopher, Author, Nobel Laureate)</span></blockquote>

---

## Play a Game With Your Neighbor

<br/>
<br/>

<img src="assets/img/audience_play3.png" title="plot of chunk Audience Plays 3" alt="plot of chunk Audience Plays 3" width="600px" style="display: block; margin: auto;" />

<br/>
<br/>
<hr/>

*** {name: footer}
<blockquote>A single raised eyebrow. "You've defected, sweetheart. No use worrying about the big, bad wolf now.<span class="author">-Nalini Singh in "Kiss of Snow"</span></blockquote>

---

## Two Player Single Play Equilibrium

<br/>
<br/>

<img src="assets/img/pd_simple_equilibrium.png" title="plot of chunk Two Player Single Play Equilibrium" alt="plot of chunk Two Player Single Play Equilibrium" width="600px" style="display: block; margin: auto;" />

<br/>
<br/>
<hr/>

*** {name: footer}
<blockquote>Neither pleasure nor pain should enter as motives when one must do what must be done.<span class="author">-Julius Evola in "Ride the Tiger: A Survival Manual for the Aristocrats of the Soul"</span></blockquote>

---&vcenter

<h3 class='jumbo'>Expanding to the Population Level</h3>
<h1 class= 'jumbo info'>The Person Over There Seems More Trustworthy</h1>

---

## Playing Against a Population

<img src="assets/fig/Simple PD with population-1.png" title="plot of chunk Simple PD with population" alt="plot of chunk Simple PD with population" width="500px" height="500px" style="display: block; margin: auto;" />


*** {name: footer}
<hr/>
<blockquote>Expectation is the mother of all frustration. <br/><span class="author">-Antonio Banderas</span></blockquote>

--- .big-picture
<div class='image ape-pic'>
<img src="assets/img/ape.png" title="plot of chunk I want to play again" alt="plot of chunk I want to play again" width="1200px" />
  <div class="text">
    <h2> I Want To Play Again! </h2>
  </div>
</div>

---

## Playing More Than Once

<img src="assets/fig/C vs D repeated interactions, -1.png" title="plot of chunk C vs D repeated interactions, " alt="plot of chunk C vs D repeated interactions, " style="display: block; margin: auto;" />


*** {name: footer}
<hr/>
<blockquote>Game over man!! GAME OVER! <br/><span class="author">-Bill Paxton in "Aliens"</span></blockquote>

---&twocol

## Tit For Tat

<br>
<br>

*** {name: left}
<img src="assets/img/tft_flow.png" title="plot of chunk Tit For Tat flow" alt="plot of chunk Tit For Tat flow" width="500px" style="display: block; margin: auto;" />

*** {name: right}
<img src="assets/img/tft_attributes.png" title="plot of chunk Tit for Tat Attributes" alt="plot of chunk Tit for Tat Attributes" width="500px" style="display: block; margin: auto;" />


*** {name: footer}
<br>
<br>

<hr/>
<blockquote>There is one word which may serve as a rule of practice for all one&apos;s life - reciprocity.<br/><span class="author">-Confucius</span></blockquote>

---

## Tit For Tat In A Population

<img src="assets/fig/TFT vs D repeated interactions, -1.png" title="plot of chunk TFT vs D repeated interactions, " alt="plot of chunk TFT vs D repeated interactions, " style="display: block; margin: auto;" />


*** {name: footer}


<hr/>
<blockquote>It&apos;s good to have the opportunity to help others who have helped you. It&apos;s not about &ldquo;tit for tat&rdquo; it&apos;s  about &ldquo;I love you, too.&rdquo;<br/><span class="author">-Karen E. Quinones Miller (Author, Community Activist)</span></blockquote>

---

## Optimal Strategies in a Free For All

<img src="assets/fig/Ternary Plot with 3 interactions, -1.png" title="plot of chunk Ternary Plot with 3 interactions, " alt="plot of chunk Ternary Plot with 3 interactions, " style="display: block; margin: auto;" />



*** {name: footer}


<hr/>
<blockquote>The devil can cite Scripture for his purpose.<br/><span class="author">-William Shakespear in &ldquo;The Merchant of Venice&rdquo;</span></blockquote>

---

<img src="assets/img/choose_your_sith.png" title="plot of chunk Choose Your Favorite Sith" alt="plot of chunk Choose Your Favorite Sith" width="800px" style="display: block; margin: auto;" />

---

## Open Science Works If...
<br>
<br>
<img src="assets/img/open_science_works_if.png" title="plot of chunk Open Science Works If" alt="plot of chunk Open Science Works If" width="800px" style="display: block; margin: auto;" />

---

## Questions?

<br>
<br>

<h5> Code is available at <a href="https://github.com/olendorf/open_science_game">https://github.com/olendorf/open_science_game</a>

<br>
<br>

<h5> Slides can be views at <a href="https://olendorf.github.io/open_science_game">https://olendorf.github.io/open_science_game</a>
