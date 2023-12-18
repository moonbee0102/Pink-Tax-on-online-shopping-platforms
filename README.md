# Pink-Tax-on-online-shopping-platforms
Pink tax refers to the different pricing for consumers of different genders in products that are functionally identical or similar, usually women need to pay higher prices. In order to reveal the existence of pink tax more intuitively, we used Python to write a web crawler to collect a large amount of product price data of similar products for women and men, as well as pink and all colours on Jingdong(京东). We also collect price data of certain products that can be substituted for each other, then cleaned and analysed these data. At the same time, we also carried out word frequency analysis of the discussion about pink tax on Douban(豆瓣).
Here are some python codes.
1. The data source of “Jingdong” code is the search results page on the Jingdong official website: www.jd.com. Using the codes, you can search for certain keywords and collect the names and prices of the first 500 products on the result page and then store them into a csv file.
2. The data source of “Douban” code is a discussion page from Douban. The code aims to crawling replies in the discussion and do a word frequency analysis with it.

Here are also some data we already collected from Jingdong and Douban. You can refer to the file “First 10 rows” to see the first 10 rows of these data.
