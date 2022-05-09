# 💹 Fintech | Crypto Arbitrage

As **Bitcoin** trades on markets across the globe, can you capitalize on simultaneous price dislocations in those markets by using the powers of *Pandas*? In this repository we will analyze the historical trade data for Bitcoin on two exchanges: Bitstamp and Coinbase and determine if any arbitrage opportunities exist for Bitcoin.

---

## Technologies

This analysis is implemented on the web-based interactive computer platform [Jupyter Notebook](https://jupyter.org/) using *Python* and **Pandas**. 

---

## Usage

Clone the app from this repository to start using it.

📂 In the folder called resources, you will find two files, with historical trade data for Bitcoin on two exchanges: Bitstamp (**bitstamp.csv**) and Coinbase (**coinbase.csv**)

📅 The data is in the date range: **2018-01-01** to **2018-03-31**

📚 This project uses the following libraries to analyze and plot the data:
* Pandas
* Pathlib
* matplotlib

For analysis purposes the data will be analized in 3 dates:
* An early date
* A middle date
* A late date

To make a decision, the data is plotted, the **arbitrage spread** is calculated and the profitable trades are obtained. The total *profit* for each date and the cumulative profit (*cumsum*). The notebook is fully commented to guide you step by step in the analysis
