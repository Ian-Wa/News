# Reliable News

## Built By [Ian Wanjira](https://github.com/ian-wa/)

## Description
News is an application that displays a list of various news sources. Users can select a news source and preview the top news article of the day. On clicking a news article users will be redirected to read the full article from the source. This is achieved by using the [News API](https://newsapi.org/).

## User Stories
Users would like to:
* See various news sources 
* Select the ones they prefer
* See the top news articles from that news source
* See the image, description and time the news article was created
* Click on an article and read it fully from the news source

## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Display news sources | **On page load** | List of various news sources is displayed per category |
| Display articles from a news source | **Click a news source** | Redirected to a page with a list of articles from the source |
| Display the preview of an article | **On page load** | Each article displays an image, title, description and publication date |
| Read an entire article | **Click an article** | Redirected to the news source's site to read the entire article |

## SetUp / Installation Requirements
### Prerequisites
* python3.8
* pip
* virtualenv

### Cloning
* In your terminal:
        
        $ git clone https://github.com/ian-wa/News/
        $ cd News