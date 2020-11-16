### Context
(Data engineered from an existing kaggle dataset:

[check source]: https://www.kaggle.com/khalidnasereddin/retail-dataset-analysis)

Nowadays, retail stores save a tremendous amount of data each day.this dataset contains historical purchase data for 5 different brand of chocolate.

### Content

------

For the **Segmentation file** their is 8 columns
ID a unique identifier for the customer.

**Sex** Biological sex (gender) of a customer. In this data set there are only 2 different options.
male -->0
female -->1

**Marital status** Marital status of a customer.
single -->0
non-single (divorced / married) -->1

**Age** Integer The age of the customer

**Education** The level of education of the customer
other / unknown-->0
high school-->1
university-->2
graduate school-->3

**Income** annual income in US dollars of the customer.

**Occupation** Category of occupation of the customer.
unemployed / unskilled -->0
skilled employee / official-->1
management / self-employed / highly qualified employee-->2

**Settlement size** The size of the city that the customer lives in.
small -->0
mid-sized city-->1
big city-->2

------

The **purchase data** set contains 17 columns
ID: a unique identifier for the customer.

**Day**: Day when the customer has visited the store

**Incidence**: Purchase Incidence: *<u>**target variable **</u>*
customer has not purchased -->0
The customer has purchased -->1

**Brand**: Shows which brand the customer has purchased-->(1-5)
No brand was purchased-->0

**Quantity**: Number of items bought by the customer

**Last*Inc*Brand**: Shows which brand the customer has purchased on their previous store visit-->(1-5)
No brand was purchased-->0

**Last*Inc*Quantity**: Number of items bought by the customer from the product category of interest during their previous store visit

**Price_1**: Price of an item from Brand 1 on a particular day

**Price_2**: Price of an item from Brand 2 on a particular day

**Price_3**: Price of an item from Brand 3 on a particular day

**Price_4**: Price of an item from Brand 4 on a particular day

**Price_5**: Price of an item from Brand 5 on a particular day

**Promotion_1**: Indicator whether Brand 1 was on promotion or not on a particular day
There is no promotion-->0
There is promotion-->1

**Promotion_2**: Indicator of whether Brand 2 was on promotion or not on a particular day
There is no promotion-->0
There is promotion-->1

**Promotion_3**: Indicator of whether Brand 3 was on promotion or not on a particular day
There is no promotion-->0
There is promotion-->1

**Promotion_4**: Indicator of whether Brand 4 was on promotion or not on a particular day
There is no promotion-->0
There is promotion-->1

**Promotion_5**: categorical {0,1} Indicator of whether Brand 5 was on promotion or not on a particular day
There is no promotion-->0
There is promotion-->1