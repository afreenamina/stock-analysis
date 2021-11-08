# stock-analysis
## Module2

## 1) Overview of Project: 

- This stock analysis is done to help Steve, for assisting his parents to invest in the right green energy stock.

- As his parents without much research want to invest in DAQO new energy corporation. So Steve has created an Excel with DAQO and also other green energy stocks so we can compare and analyze which stocks are good to buy.

- This is done by 1) Calculating the total daily Volume for each stock
                  2) Calculating yearly returns for each stock.

#### Calculating the total daily Volume 
- To check how often the stock is traded often - we sum all the daily Volume for each stock.
- Below is the VB script to find the total volume of each stock

![total stock](https://user-images.githubusercontent.com/92698873/140691967-5f6b352f-2b36-497e-98f8-29e15ad8c101.png)


#### Calculating yearly returns
- Yearly returns are calculated to know the percentage increase or decrease in closing price from the beginning of the year to the end of the year.
- This is calculated by percentage increase or decrease in price from the beginning of the year to the end of the year
- Below is the code for getting the closing price for the beginning of the year and closing price for the end of the year for each stock

![starting Ending](https://user-images.githubusercontent.com/92698873/140692019-91679e36-dacb-4b9d-b568-a31bdca82a79.png)

### 2) Results: 
- Below is the code written to display Ticker , its total volume and returns 
-
![output](https://user-images.githubusercontent.com/92698873/140694927-93427083-efea-4294-8421-b419f5cee58f.png)

- We first look into DQ stock - The company had 200% returns for the year 2017 with the total daily volume of 35 million stocks. The company had significant drops of returns in 2018 of 63% and the total daily volume of 108 million.

![2017 stock](https://user-images.githubusercontent.com/92698873/140686763-3b3ba26b-1d0f-44da-988a-0a5a855ced06.png)
![2018 stock](https://user-images.githubusercontent.com/92698873/140687963-0d338b75-da6c-4f1d-85eb-0345898c2d07.png)


- From the list of stocks provided in the Excel sheet - the overall market in 2017 and performance of individual stocks looks positive with good returns to investors. Whereas 2018 the overall stocks and returns have dropped significantly. If the drop was due to the company's performance (revenue) , then Steve parents had to hold there investments.If this was due to any market issue , then all these stocks may go up again.

Original Script run time -

![oldcode_2017](https://user-images.githubusercontent.com/92698873/140689708-c1a66bce-e7b0-4b82-9edb-4805ec276f90.png)
![oldcode_2018](https://user-images.githubusercontent.com/92698873/140689735-9999128b-0b3d-4fd6-9e0c-d5d883227223.png)

Refactored Script run time -

![Ref_2017](https://user-images.githubusercontent.com/92698873/140689792-b041d8dc-1910-4302-a99e-7037ed9b4555.png)
![Ref_2018](https://user-images.githubusercontent.com/92698873/140689797-62475f47-0aa9-4e4a-8a99-cb2c373cf11c.png)

From the run time - it looks like refactored code is more efficient than the original script.

### 3) Summary: 
In a summary statement, address the following questions.
#### 3a) What are the advantages or disadvantages of refactoring code?
##### Advantages of Refactoring the code
- Easier to maintain the code
- Increase the quality of code
- Updating the code is easier
- Adding new features is faster
- Less time for documentaion


##### Disadvantages of Refactoring the code
- Not recommended if its a big application
- Time consuming 
- Can introduce untraceable errors. 

#### 3b) How do these pros and cons apply to refactoring the original VBA script?
##### Advantages of Refactoring the code
- It was easier to start off by adding changes to code.
- Lots of documentation/comments in code made it easy to understand.
- It took less time to add the changes to the code than writing a new code from scratch.

##### Disadvantages of Refactoring the code
- Takes time to trace back the variable.
- As all the variables were declared as arrays - updating the code gave new errors. 

