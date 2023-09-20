# DESKTOP APP - CLAIM

## About

This project is an application software that I was for an insurance brokerage.  The company needed an easy to use app that processed the information of their reciepts  and check if the payments made by the insurance companies to the brokerage were correct. The insurance policyholders would pay the insurance cost to the insurance company and the insurance company would pay a percentaje of said insurance cost to the brokers. This percentage would depend on the product and the insurance seniority.

I encountered a few issues:
	- The information stored in the database of the insurance brokerage was incomplete and the data of the percentage from the insurance cost that the brokers should get was missing in manu products.
	- Some of the policies had a reducted commission as the brokers and the policyholders had agreed so many years ago but that information was also incomplete in the database.
	- For a few years an insurance company had been paying the insurance brokerage a lowerer commission that the agreed but this fact was spotted by the brokers, the debth was claimed and it had already paid the difference to the insurance brokerage.

So was this application does first is procces the information in the reciepts and elaborate a list of the products that appear in the list of recepits with some statistic information, from this information establish if there is a discrepancy and markes them so the insurance brokerage knows that either the commision in the database is missing or there are some policies with an agreed reduced commission and the company must complete this information in the database.
Then, it crosses the information from the receipts that were already claimed and regularized with the information of the receipts in the insurance brokarage database and elaborate two excel files, one of the with the reciepts in which the percentage commision is lower than the agreed, so they are to be claimed and regularized and another excel file with reciepts that are correct.

## Requirements 

This project is written in Python language and thus needs the Python3 interpreter. It also uses the following modules: Pandas, Pillow, requests, XlsxWriter and openpylx

## Instructions

### 1.Cloning the repositories  
```shell
$ git clone https://github.com/castrogr/aplicativo.git
```
### 2.Executing  
click the executable claim
### 3. Tester. 
The app will ask you to open the files to process. There are two excel files to test the program, the one that contains the data of the reciepts, testfile.xlsx ("abra el archivo excel a evaluar") and the one that contains the reciepts that were already regularized ("Cargue el archivo de los recibos reclamados de Cosesa")
### Saving the results
Once processed, you can save the results files, one contains the statistic data with the marked discrepancies, another contains the recietps in wich the commission paid is lower that the agreed and the amount to claim. And the last one contains the reciepts that were paid according to agreed commission
