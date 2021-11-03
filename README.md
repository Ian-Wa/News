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

## Running the Application
* Creating the virtual environment

        $ python3.8 -m venv --without-pip virtual
        $ source virtual/bin/env
        $ curl https://bootstrap.pypa.io/get-pip.py | python 

* Setting up the API Key
        
        To be able to gather article info from the News API you will need an API Key.
        
        * Visit https://newsapi.org/ and register for an API key.
        * In the root directory of the project folder create a file: start.sh
        * Insert the following info into it: 
        
                export NEWS_API_KEY='<Your-Api-Key>'
                python3.8 manage.py server
                
        * Insert the API Key you received from News Api where <Your-Api-Key> is.