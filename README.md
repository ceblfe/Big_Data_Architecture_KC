# Big Data Architecture KC

This repository contains a Word file that explain the steps: to design and to deploy a Hadoop cluster in Google Cloud Platform. Also, we are processing the structured data that we have got from a public web with scraping  techniques. We have done a word count with the aid of the Hadoop cluster.
We use HIVE to do queries of the results.

We use the programming language Python to scrapping the web.
We use HIVE to do queries to the results.

Python library that we are using:
* Scrapy

This repository has the following files:
  1. data/
  2. wordcount_europe/
  3. Big_Data_Architecture_KC.docx
  4. README.md
 

## 1. data/

This file contain the raw of data to do the scrapping. The name of this file is: europe.txt

## 2. wordcount_europe/

This file contains the data that we have processed with the Hadoop cluster. The result of this data processing is the word count of the file europe.txt:

wordcountout_europe_2Fpart-r-00000
wordcountout_europe_2Fpart-r-00001
wordcountout_europe_2Fpart-r-00002
wordcountout_europe_2Fpart-r-00003
wordcountout_europe_2Fpart-r-00004
wordcountout_europe_2Fpart-r-00005
wordcountout_europe_2Fpart-r-00006
wordcountout_europe_2Fpart-r-00007


## 3. Big_Data_Architecture_KC.docx

This Python file is divided into 5 sprints:

  1. Design, drawing the data flow and specifying the tools used
  2. Create a scraper in Google Collaboratory from an API or crawler with scrapy.
  3. Using the docker repository to deploy a cluster with 2 configured containters.
  4. Providing the results of a processing task (in this case the wordcount) along with the steps its execution, the copy of results (including hadoop commands) and the execution log.
  5. Using HIVE to categorize the data and making a couple of queries with the command line to extract data to a file.
