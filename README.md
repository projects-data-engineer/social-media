# social-media
1. [Create env and install pyspark and jupyter lab](#schema1)
2. [Dataset](#schema2)



8. [Resources](#schemaref)

<hr>
<a name='schema1'></a>

## 1. Create env and install pyspark and jupyter lab

1. Create env
```python
python3 -m venv pyspark-env
```
2. Activate
```python
source pyspark-env/bin/activate
```
3. Install Pyspark and jupyterlab
```python
pip install pyspark

pip install findspark

pip install jupyterlab
```
4. Install matplotlib and searborn
```
pip install matplotlib seaborn
```


<hr>
<a name='schema2'></a>

## 2. Dataset

| **Feature**   | **Description**                                        |
|---------------|--------------------------------------------------------|
| Text          | User-generated content showcasing sentiments           |
| Sentiment     | Categorized emotions                                   |
| Timestamp     | Date and time information                              |
| User          | Unique identifiers of users contributing               |
| Platform      | Social media platform where the content originated     |
| Hashtags      | Identifies trending topics and themes                  |
| Likes         | Quantifies user engagement (likes)                     |
| Retweets      | Reflects content popularity (retweets)                 |
| Country       | Geographical origin of each post                       |
| Year          | Year of the post                                       |
| Month         | Month of the post                                      |
| Day           | Day of the post                                        |
| Hour          | Hour of the post                                       |

**Sentiment Analysis:**

Explore the emotional landscape by conducting sentiment analysis on the "Text" column.
Classify user-generated content into categories such as surprise, excitement, admiration, thrill, contentment, and more.

**Temporal Analysis:**

Investigate trends over time using the "Timestamp" column.
Identify patterns, fluctuations, or recurring themes in social media content.




<hr>
<a name='schemaref'></a>

## Resource

[Dataset](https://www.kaggle.com/datasets/kashishparmar02/social-media-sentiments-analysis-dataset)