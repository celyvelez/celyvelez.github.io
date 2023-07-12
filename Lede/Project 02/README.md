# Project 02
## What does the Colombian Senate work towards?

This is my submission for Project 02 of Lede 2023. 

I was interested in looking at the bills presented by the Colombian Senators during the 2018-2022 period because I wanted to see the percentage of sanctioned bills compared to those that got archived and the categories that congresspeople work most towards. 

### Findings
Most bills get archived, and the reasons vary from the author's withdrawal to the transit of legislation and expiration of terms; even one bill was ruled unconstitutional by the Supreme Court.

The top five categories are also quite interesting.
1. Social Security and health
2. Education, culture, science and technology
3. Justice 
4. Commerce, industry and tourism
5. Celebrations, honours and monuments

Out of those, number five had the highest percentage of bills sanctioned, three times greater than the percentage of the first category. In general, 88% of bills are archived, and only 11% are sanctioned as law.

The story webpage is here: https://celyvelez.github.io/Lede/Project%2002/colombian-bills-2018-2022.html

### Data collection
I scraped [Congreso Visible](https://congresovisible.uniandes.edu.co/proyectos-de-ley/)'s website to build the dataset and compared it to the official [Senate](https://senado.gov.co/) site. Given the number of individual pages I had to request through Python, the dataset was built with the help of Google Sheets.

### Data analysis
The analysis of categories and statuses was done with pandas and Google Sheets. For the topics, I applied Natural Language Processing to the title and abstract of each proposed bill to determine 25 macro-categories and their matrix, which was later used to see the change over time of two topics.

### Charts
The charts were done with Plot and d3 in Observable, with RAWGraphs and Datawrapper. All of them were modified using Illustrator to match the style of my website. 

### Skills learned: 
I learned a little about machine learning and NLP. I also polished my skills in Observable and Illustrator.

### Further questions:
If I were to continue with this project, I would like to find the answer to the following questions:
- When are the most bills proposed?
- Are the bills sanctioned being proposed by the Senators or the Government?
- What is the average life expectancy of each process?
- Which bills take the longest to debate?
- Which commission gets the most work done?
- What parties pass the most bills?
- Which senators appear the most as authors or speakers?