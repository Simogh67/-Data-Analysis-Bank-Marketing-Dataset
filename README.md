# Data-Analysis-Bank-Marketing-Dataset

In this project, we consider Bank Marketing dataset, which is a public dataset available at https://archive.ics.uci.edu/ml/datasets/bank+marketing. <br>

The data is related with two different direct marketing campaigns of a Portuguese banking institution.<br> 
The marketing campaigns were based on phone calls. 
Often, more than one contact to the same client was required, <br> 
in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

# Business Questions and Data Understanding

Let's, take a look at the dataset via the following data dictionary:

1 - age (numeric)

2 - job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student",
"blue-collar","self-employed","retired","technician","services")

3 - marital : marital status (categorical: "married","divorced","single";)

4 - education (categorical: "unknown","secondary","primary","tertiary")

5 - default: has credit in default? (binary: "yes","no")

6 - balance: average yearly balance, in euros (numeric)

7 - housing: has housing loan? (binary: "yes","no")

8 - loan: has personal loan? (binary: "yes","no")

9 - contact: contact communication type (categorical: "unknown","telephone","cellular")

10 - day: last contact day of the month (numeric)

11 - month: last contact month of year (categorical: "jan", "feb", "mar", …, "nov", "dec")

12 - duration: last contact duration, in seconds (numeric)

13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

14 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)

15 - previous: number of contacts performed before this campaign and for this client (numeric)

16 - poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

**Output variable (desired target)**:
 y - has the client subscribed a term deposit? (binary: "yes","no")
 
### Based on the dataset, we propose the following business questions:

* **1. Did the new campaign perform significantly different (better or worse) than the old one?**

* **2. Is there any bias between the new and old campaigns (a bias is a variable that is not constant across the two groups of the population)?**

* **3. To increase the conversion rate of future campaigns, which variables are important ?**

* **4. Can we use the data for future customers' behavior prediction?**

### The answers to the above questions are available in the Jupiter Notebook included in this repository.

To answer the above questions, we leverage supervised machine learning algorithms and Statistical hypothesis testing.
