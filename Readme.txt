Data Analysis:
It is quite clear from the beginning that id is not going to contribute anything in our analysis

Funded and Paided range from 01/01/2005 to 31/12/2013
Philippines took maximum numbers of loan out of a total 75 countries.
Most of the loans are made in USD(rest are empty)
Maximum loans were taken for 'General Store' to purchase additional products to sell.

After looking at the data it is clear there are some missing data.
Difference between count and sum: .isnull() gives a list of Boolean. .sum() is the sum of total True in the Boolean whereas .count() counts the total number of Booleans.

Visualisation:
Sector-wise analysis: showed that maximum loans were made to Food, Retail and Agriculture sectors.
pd.DataFrame[Column].value_counts() counts the value of distinct entities in the column. It has index(name) and values(value) of the column.
enumerate() gives two output. first rowcount and value.
plt.text() is used for displaying values on the graph. in the plt.text() x and y arguments decides the position of the output.

Status of the Loan: showed that most of the loan are already paid and only small number of numbers were refunded.

Count of activity: Maximum number of loans were asked for were (Top 3) General Store, Farming and Retail.

Distribution of Funded Amount clearly shows that most of the loans were below $1000.
However, there are some instances where loans above $10000 were also made.
So, we can infer that a small investment can make huge difference.

I didnt plot Paid Amount as there were missing values

Use of the Loans: Most people used the loan to purchase additional prodects to sell, which confirms that most loans were indeed asked for General Stores.


 