# stock-analysis
## Module2

### 1) Overview of Project: Explain the purpose of this analysis.

- This stock analysis is done to help Steve, for assisting his parents to invest in right green energy stock.

- As his parents without much research wants to invest in DAQO new energy corporation. So Steve has created an Excel with DAQO and also other green energy stocks so we can compare and analyse which stocks are good to invest.

- This is done by 1) Calculating total daily Volume for each stocks
                  2) Calculating yearly returns for each stocks.

##### Calculating total daily Volume 
To check if the stock is traded often and to find yearly volume - we sum all the daily Volume for each stock.

##### Calculating yearly returns
Yearly returns are calculated to know the percentage increase or decrease in price from the beginning of the year to the end of the year 


### 2) Results: 
Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.

- We first look into DQ stock - The company had 200% returns for the year 2017 with daily volume of 35 million stocks. The company had significant drops of returns in 2018 of 63% and daily volume of 108 million.

![2017 stock](https://user-images.githubusercontent.com/92698873/140686763-3b3ba26b-1d0f-44da-988a-0a5a855ced06.png)
![2018 stock](https://user-images.githubusercontent.com/92698873/140687963-0d338b75-da6c-4f1d-85eb-0345898c2d07.png)


- From the list of stocks provided in the Excel sheet - the overall market in 2017 and performnace of individual stocks looks postive with good returns to investers. Whearas 2018 the overall stocks and returns has dropped significantly. If the drop was due to the company performance (revenue) , then Steve parents had to hold there investments.If this was due to any market issue , then all these stock may go up again.

Orginal Script run time -

![oldcode_2017](https://user-images.githubusercontent.com/92698873/140689708-c1a66bce-e7b0-4b82-9edb-4805ec276f90.png)
![oldcode_2018](https://user-images.githubusercontent.com/92698873/140689735-9999128b-0b3d-4fd6-9e0c-d5d883227223.png)

Refactored Script run time -

![Ref_2017](https://user-images.githubusercontent.com/92698873/140689792-b041d8dc-1910-4302-a99e-7037ed9b4555.png)
![Ref_2018](https://user-images.githubusercontent.com/92698873/140689797-62475f47-0aa9-4e4a-8a99-cb2c373cf11c.png)

From the run time - it looks like refactored code is more efficeient than the original script.

### 3) Summary: 
In a summary statement, address the following questions.
#### 3a) What are the advantages or disadvantages of refactoring code?
##### Advantages of Refactoring the code
- Eaiser to maintain the code
- Increase the quality of code
- Updating the code is easier
- Adding new featurs is faster
- Less time for documentaion


##### Disadvantages of Refactoring the code
- Not recommended if its a big application
- Time consuming 
- Can introduce untraceble errors. 

#### 3b) How do these pros and cons apply to refactoring the original VBA script?
##### Advantages of Refactoring the code
- It was easier to start off with adding changes to code.
- Lots of documentation/comments in code made it easy to understand.
- It took less time to add the changes to the code than writing a new code from scratch.

##### Disadvantages of Refactoring the code
- Takes time to trace back the variable.
- As all the variables were declared as array - updating the code gave me new errors. 

