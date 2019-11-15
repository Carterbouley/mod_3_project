# mod3_project

This repo contains:
* Description of the project in a PDF
- Our project will analyse the effect of Trumpism. His tweets have stated that this is the best economy ever. However labeling a single economic era as the greatest in history is subjective because there’s no agreed-upon metric. 

So, given his likelyhood of election in 2020 (betfair implied odds suggest he has a 40.9% chance of winnig). We have decided to test his statement using a variety of economic indicators, including s&p 500 growth, unemployment rate, total public debt, US trade balance, GDP growth, (house prices?).

Through comparing to other presidents, if the results are significantly different (as opposed to being attributed to market cycles) we could have a better idea on whether to expect these trends to continue.
- The S&P 500 data is collected from yale economics department, using the Quandle API to access it.

Hypthesis_1: Carter

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">The S&amp;P just hit an ALL TIME HIGH. This is a big win for jobs, 401-K’s, and, frankly, EVERYONE! Our Country is doing great. Even killed long sought ISIS murderer, Al-Baghdadi. We are stronger than ever before, with GREAT upward potential. Enjoy!</p>&mdash; Donald J. Trump (@realDonaldTrump) <a href="https://twitter.com/realDonaldTrump/status/1188813055108374533?ref_src=twsrc%5Etfw">October 28, 2019</a></blockquote>


 
    h0 = Trump has no effect on the rate of growth of the s&p 500
    h1 = Trump is increasing the rate of growth of the s&p 500
    
Hypothesis_2: Josh

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Breaking News: Unemployment Rate, at 3.5%, drops to a 50 YEAR LOW. Wow America, lets impeach your President (even though he did nothing wrong!).</p>&mdash; Donald J. Trump (@realDonaldTrump) <a href="https://twitter.com/realDonaldTrump/status/1180102056411095042?ref_src=twsrc%5Etfw">October 4, 2019</a></blockquote>



    h0 = Trump has no effect on the rate of unemployment in the usa
    h1 = Trump has reduced the rate of unemployment in the USA

Hypothesis_3: Aroa

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">The media has not reported that the National Debt in my first month went down by $12 billion vs a $200 billion increase in Obama first mo.</p>&mdash; Donald J. Trump (@realDonaldTrump) <a href="https://twitter.com/realDonaldTrump/status/835479283699224576?ref_src=twsrc%5Etfw">February 25, 2017</a></blockquote>



    h0 = Trump has no effect on the level of debt in the USA
    h1 = Trump had reduced the level of national debt in the USA
    
   

Hypothesis_4: All

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">The trade deficit rose to a 7yr high thanks to horrible trade policies Clinton supports. I will fix it fast- JOBS! <a href="https://t.co/jaGeN4u50U">https://t.co/jaGeN4u50U</a></p>&mdash; Donald J. Trump (@realDonaldTrump) <a href="https://twitter.com/realDonaldTrump/status/743486962670141440?ref_src=twsrc%5Etfw">June 16, 2016</a></blockquote>


    h0 = Trump has no effect on the trade balance of the USA
    h1 = Trump is reducing the trade balance of the USA



* Three python starter files
* Three test files
* A starter jupyter notebook