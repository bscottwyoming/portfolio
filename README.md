## Brian Scott Work Examples
Below are explainers for some of the examples contained in repo list. In addition to the below links the reader is invited to peruse this content as the below highlights are not exhaustive. At each GitHub link there is a download button in the ellipse in the upper right (which can be helpful for viewing multi-page documents).  

### Research, Analysis, Coding
#### Some work examples from Schwab Asset Management (current employer)
* Current quantitative research group owns multiple models that rate active funds. At the end of 2022 one of our model’s expected performance repeatedly appeared in our division’s annual business plan. [Since the performance report's](https://github.com/bscottwyoming/portfolio/blob/main/tableauFursPerfReport.pdf) distribution far exceeded our immediate team I took it upon myself to improve the quality of monthly analysis/telemetry and publishing efficiency. This document had the furthest reach, was thus our primary speaking piece, and should be our most airtight presentation. This version is redacted to be above board in all matters IP. 
* Here is [a sensitivity analysis writeup](https://github.com/bscottwyoming/portfolio/blob/main/Sensitivity%20analysis%20and%20outlier%20detec-TOR.pdf) conducted on one of our models. For the same model, [here is the monthly input validation report](https://github.com/bscottwyoming/portfolio/blob/main/inputValidationExample.pdf) as determined by Detec-TOR (total outlier removal) the outlier/anomaly module I was tasked to build. As determined by sensitivity testing, outlier scores that crossed certain thresholds are counted and collected and if enough scores cross a breadth threshold the process is paused for investigation. This version is redacted to be above board in all matters IP.
* Risk/audit requested additional research for another one of our models. [Here I explain their ask then do some tests](https://github.com/bscottwyoming/portfolio/blob/main/marscleanversion.pdf). This version is redacted to be above board in all matters IP. 

### Asset Allocation
#### Some highlights as senior investment analyst at state sovereign wealth fund
* As a semi-state agency, received annual Governor of Utah award for leading reinvention of annual AA work. While still being required to show our technical process, [here is the investment committee presentation](https://github.com/bscottwyoming/portfolio/blob/main/AssetAllocation--2019Presentation.pdf). We show the range of portfolios produced by our CMA computations (valuation) and sampling (industry publication) processes as the inputs into four different optimization approaches. We qualitatively select four desired portfolios and compare to current target and various benchmark portfolios. [Here is a tear sheet of a single optimization run](https://github.com/bscottwyoming/portfolio/blob/main/Asset%20Allocation%20--%20optimization%20tear%20sheet.PDF). We also simulate portfolio performance across various holding periods and conduct historical stress tests. We then generalize the results of preferred portfolios and, at a later date, presented the specific allocations we believed would imbue the portfolio with the desired modifications teased out in the AA process.

### "betaRank"
#### An example of a model used at both asset manager and wealth fund jobs
* Oft-quoted PageRank algo is of course simply the stationary distribution of a Markov chain. In application its utility is the handy dampening factor equation that allows the code to arrive at an ergodic matrix and thus the stationary distribution will converge. At the asset manager I built betaRank as a trend following model for our inhouse software environment  called Strategy Tester. The goal was to build the systematic overaly for for multi-strat portfolio products. The Strategy Tester C# code is long gone but  [here is an attempt to replicate the approach in Python]( https://github.com/bscottwyoming/portfolio/blob/main/trend_relative_MarkovChain.ipynb). Additionally, in my role at the wealth fund, I used the same approach to build a relative trend following overlay on our liquid book. [Here is a monthly tear sheet for our public equities book](https://github.com/bscottwyoming/portfolio/blob/main/Strategy%20Analysis%20--%20public%20equity%20relative%20trend.pdf). The tear sheet shows monthly weights and hypothetical trend portfolio performance alongside current and target performance. Trend signal weights are translated to min/max constraints as defined by asset allocation. 

### Portfolio Construction 
#### Took experience from asset manager and built related wealth fund portfolio
* A key reason the wealth fund hired me was my experience with our trend following funds at the asset manager. The wealth fund’s CIO believed in “tail risk” or “risk mitigation” or “crisis alpha” portfolios (10-20% of total portfolio). Here we deployed two things. First was long UST Strips (3-15%) with a gearing overlay such that when risk-off telemetry crossed various thresholds we went long UST futures, increasing duration from ~25 years to ~45 years. [Here is my full investment memo](https://github.com/bscottwyoming/portfolio/blob/main/Investmnet%20Memo%20--%20Long%20UST%20Systematic%20Overlay.pdf). Second, the Alpha Protect fund we created with Man FRM (3-15%). Alpha Protect existed before me, but this version of the portfolio reflects my efforts to evolve its approach. [Here is a report I built to monitor its performance and sensitivities](https://github.com/bscottwyoming/portfolio/blob/main/Strategy%20Analysis%20--%20crisis%20risk%20offset.pdf). Here we create four silos: multiple trend following approaches, short term and vol-breakout trading, global macro plus some risk-off factors, and straight up long vol strategies. The portfolio performed well enough and was liquid enough to fund purchasing of crashing liquid assets in March 2020. This bore the intended fruit when liquid assets subsequently inflated for ~20 straight months.  
 
### Risk Reporting 
#### Created for state sovereign wealth fund 
* I was tasked to build the entire risk reporting suite and for all intents and purposes designed the risk management framework. The CIO, board, and I first authored a risk manifesto. For reporting we emphasized returns- and holdings-based risk reporting. For returns reporting, we wanted to understand exposures. Since asset allocation was defined by past returns we wanted to always know if we were actually getting those exposures. We ran portfolio and AA returns across various risk factor schema (eventually deciding on Two Sigma’s Venn approach for factor taxonomy) and compared/monitored these loadings while paying particular attention to tracking error. [Here is the returns-based report](https://github.com/bscottwyoming/portfolio/blob/main/Quarterly%20Risk%20--%20returns%20based.pdf). For holdings, we paid a reporting service for a quarterly flat file detailing liquid and private holdings across various dimensions like geography, sector, security type, etc. We used this file to build our own report. Here our primary focus was understanding concentration risk. [Here is the holdings-based report](https://github.com/bscottwyoming/portfolio/blob/main/Quarterly%20Risk%20--%20holdings%20based.pdf). 

### Journalism and Media 
#### Some examples from a professional media career working for companies like Teton Gravity Research, POWDER Magazine, and Rainbow Media
* I worked in media for 10 years before finance. I was reluctant in the beginning of my finance journey to detail these accomplishments because I didn’t want to convey the impression it’s what I’d rather be doing. It has become at least semi-relevant to show my media career required training and developed some skills transferrable to my current quantitative analyst/researcher roles. And that I might bring a unique multidisciplinary background to the table.
* TGR gave me the responsibility for pubishing its annual magazine and the masthead title “Editor” immediately after getting my undergrad in journalism ([year one](https://www.icloud.com/iclouddrive/0443KJHEbSmawEpABnrTLVeoA#exposedMagYearOne) and [year two](https://www.icloud.com/iclouddrive/0b3h29torFuWrYqvG9mJgvwEQ#exposedMagYearTwo)). Here is one of a few [quick pieces]( https://www.icloud.com/iclouddrive/05cekuwYmTONLDuSUloim7n1Q#powderMagCordova) I wrote for POWDER, an international publication but the North American skier’s bible for sure (when print still had a pulse, that is). Here is [a feature I wrote for a national magazine]( https://www.icloud.com/iclouddrive/086ZwOwCAIpIC6C0iIrS16Lmg#norwayMagEnglish) based in Australia, [here it is again translated to German]( https://www.icloud.com/iclouddrive/049Za6dntmUm7cQvp7vUk5ZnQ#norwayMagTranslated) for an Austrian publucation. Here is a [film and television reel]( https://www.icloud.com/iclouddrive/021O-CnGGmAIYS00K7X913fVw#projectsReel) showing my producer, director, cinematographer, and editor work. Here is a [commercial I made for The North Face]( https://www.icloud.com/iclouddrive/0850-txPyuZGo9pQw5VuBtyIQ#tnfCommercial). Here are some one-hour on-location shows I did for international broadcast on Rainbow Media channels (these were on Dish Network in the States): ski shows in [South America]( https://www.icloud.com/iclouddrive/01a18v9iA-b-pzpcJNlTDOjHQ#skiArgentinaChile), [Alaska]( https://www.icloud.com/iclouddrive/0a2F1VQ79VmX2l01b_G_XhLVw#skiAlaska), and [Montana]( https://www.icloud.com/iclouddrive/007qyug4VxYZ1W8ocK7reAzgw#skiMontana); [mountain bike show in Mexico]( https://www.icloud.com/iclouddrive/03cwmFTlgS6ZDb-5WzAqD6ZEA#mtbMexico); [BASE-jumping show in Idaho and California]( https://www.icloud.com/iclouddrive/092epkWtI8xBHahdvJPByFvBA#baseIdahoSkydiveCali). 



