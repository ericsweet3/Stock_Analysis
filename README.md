# Refactoring the Code

---

## Overview of Project

For this challenge we looked at code written to examine a certain amount of stocks, and refactored to it to be able to examine several thousands of stocks

## Results, Analysis, and Challenges

### Results of the Re-factoring and Analysis
- The re-factoring was a success, the code was not only streamlined, but it now works for a larger grouping of data than before. So lets take a look at the charts and what they show. Lets start with the obvious, 2017 was a great year for portfolios, and 2018 was a bit of a fall (in my personal opinion, 2018 would be the time to buy)(also see pictures 1a and 1b). 
- Now lets examine the code and the changes that I made to it to accommodate the request from the client. Instead of 
just going through the various tickers and having it go through several loops, I created a single (but a bit more complex) loop and had the data stored into various output arrays. Then the code was taken and output to the correct column in order to be displayed. Compare that to these times from the less refined code 2017 and 2018 respectively. Even though the times aren't consistent themselves when I run it, it is consistently faster, which was the ultimate goal! Lets talk about the possible downfalls of refactoring code starting with the obvious, you could have something that works and then immediately make it into something that doesnt work. Possibly messing with a "working product" just to make it a bit more streamlined and faster doesn't necessarily always end in a working code, which could also lead to not remembering where you started (if you didn't save it before refactoring). But the obvious pros to all of this is that I now have code that can work with much larger data sets and do it more quickly!

Refactored Code:

![refactored_code](https://user-images.githubusercontent.com/75768098/103468457-b2429e00-4d1e-11eb-9850-89c8d299a3aa.png)



Original Code for 2017 and 2018:

![unfactored_2017](https://user-images.githubusercontent.com/75768098/103468277-0ba9cd80-4d1d-11eb-89a5-86df0ac8bcd3.png)![unfactored_2018](https://user-images.githubusercontent.com/75768098/103468281-15333580-4d1d-11eb-8199-91267a6877a8.png)



## Pictures
1a)

![stocks_2017](https://user-images.githubusercontent.com/75768098/103468211-5a0a9c80-4d1c-11eb-9187-b8e1f41d60d0.png)

1b)

![stocks_2018](https://user-images.githubusercontent.com/75768098/103468225-78709800-4d1c-11eb-9477-49c214a91cdc.png)
