# FINAL PROJECT 

# Analysis of the business situation of the company DATAMART


<img src="fotos/portada.jpeg?raw=true" width="400" height="200" />

**TARGET**

The objective of this project is the analysis of the situation of a shopping center (unreal name) during a specific period of time.

**STRUCTURE**

<img src = "fotos/foto1.png?raw=true" width="400" height="200">

The information is distributed in the following folders:

* *- Code:* The different Jupyter notebooks with all the information obtained and captured in the presentation.
* *- Presentation:* The Power Bi presentation with the different conclusions obtained after carrying out the analysis. 

Regarding the different Jupyter notebooks;

### DataCo
The initial notebook, contains the [database](https://www.kaggle.com/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis?select=DescriptionDataCoSupplyChain.csv) with all the information related to sales, customers, stores and markets, products...among others.  It has been cleaned in order to unify the information with the rest of the data obtained from other sources. 

### IP_scraping
 Based on the csv provided with all information related to the clickstream of the clients, we have scraped the different [IPs](https://tools.keycdn.com/geo?host=) to obtain the country of each one of them and thus to be able to calculate the conversion ratio. The target was to compare the % of customers who end up buying in our shopping center in relation to those who visit our website. 

### GDP_scraping
 We have scraped [Wikipedia](https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)), to obtain the GDP data of the different customers to analyze if the purchasing power really influences in sales.

### Km_scraping
In order to study whether the distance between stores and customers affects the ability to meet delivery times, we have scraped a [web page](http://es.distancias.himmera.com/) containing this information. 


**CONCLUSIONS**

<img src = "fotos/foto2.png?raw=true" width="400" height="200">

After studying and analyzing the data, we can state the following:

## Products

- There are three star products, Field & Stream Sportsman 16 Gun Fire Safe', 'Perfect Fitness Perfect Rip Deck' and Diamondback which account for 42% of sales.

## Customers

- The most important customers are located in the cities of New York, Santo Domingo, Los Angeles and Tegucigalpa, but they account for only 4%. Sales are widely distributed among all countries. 
- They need to work on customer loyalty to increase the clickstream conversion rate, especially in important markets such as France, Australia and Germany.
- The most important segment is the consumer, with 51% of sales.

## Store locations
- The most important store is located in Caguas, Puerto Rico, with 37% of sales, where they must work to improve delivery times, as 20% of orders are delivered late.
- Analyzing the routes between Caguas and the cities where the company's main customers are located, it can be seen that there should not be so many delays. Resources will be invested to improve productivity in packaging and subsequent delivery. 

## Types of delivery
- ‘Standard' type is the most used by the customers with 60% of sales. There is much room for improvement as 23% of these orders are delivered late. 
- ‘First class’ type delivers all orders in two days when the stipulated time is one day, company should study if it is really necessary to offer it.
- In general terms 55% of orders are 'Late delivery', they must focus on improving these ratios. 



**LINKS & RESOURCES**
* https://www.kaggle.com/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis?select=DescriptionDataCoSupplyChain.csv
* https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)
* https://tools.keycdn.com/geo?host=
*http://es.distancias.himmera.com/
* https://numpy.org/doc/1.18/
* https://pandas.pydata.org/
* https://docs.python.org/3/library/functions.html
* https://docs.python.org/3/library/time.html
* https://scikit-learn.org/stable/
* https://selenium-python.readthedocs.io/
* https://www.crummy.com/software/BeautifulSoup/bs4/doc/
* https://powerbi.microsoft.com/es-es/

