
# Making an advanced Word Cloud

For normal word clouds, colors are randomly assigned. Advanced word clouds that map meaningful attributes (like coefficient values or token frequencies) to visual characteristics can provide a lot more insight. 


## Visualization 
Figure: Word Cloud for Amazon reviews 
![]()



## Conclusion
- From analyzing Figure 1, it is evident that applying a Japanese tokenizer to BERTopic significantly impacts the topic representation. When BERTopic is not coupled with a Japanese tokenizer, the topic representations resemble complete sentences rather than individual words, resulting in a cluttered and disorganized topic word score figure. However, when we utilize a Japanese tokenizer, the results are more appropriate for our objective of detecting and visualizing topics. Figure 2 and Figure 3 exhibit the outcomes of each scenario, respectively. Therefore, incorporating a Japanese tokenizer in BERTopic enhances the topic representation and makes it more useful for topic identification and visualization.
## Scrapping Tweets

#### snscrape - Scrape contents from social networking services (SNS)

```http
https://github.com/JustAnotherArchivist/snscrape
```

#### Check my tutorial on how to use snscrape to scrape twitter data: 
```http
https://medium.com/@cd_24/using-bertopic-to-analyze-qatar-world-cup-twitter-data-a5956c4949f1
```
## Japanese Stop Words
I adopted the list of Japanese stop words from the following:   
```http
https://github.com/stopwords-iso/stopwords-ja
```
## Code
The codes programmed in this project are displayed in this repository. Feel free to check and use them. 
## Relevant Materials
If you are interested in learning more about how to develop a Japanese tokenizer and the necessity of using a tokenizer when utilizing BERTopic for analyzing Japanese texts, I recommend reading my post on Medium. In the article, I delve into the importance of tokenization in natural language processing and explain how Japanese language's unique characteristics require a specific tokenizer to ensure accurate analysis. Furthermore, I outline the steps involved in building a Japanese tokenizer and provide detailed code snippets for your reference. 

- [Using BERTopic on Japanese Texts](https://medium.com/@cd_24/using-bertopic-on-japanese-texts-99d3ac1f05a2)
