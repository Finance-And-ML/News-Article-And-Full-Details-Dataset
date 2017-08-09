# News Full Details Dataset (JSON)

### Please visit https://figshare.com/projects/Financial-News-Full-Details-JSON-Dataset/23893 for all latest data sets.

### Data set contents: 
Reuters and WSJ news in full details from June 6th.    

### Original Scrapped JSON Attributes:
- news_time
- news_title
- keywords
- content
- url
- **sector** - this sector attribute is collected from news html tag, which is provided by the news publisher.

### Cleaned News JSON Attributes:
- news_time
- news_title
- keywords
- content
- url

#### Notes:
* The **sector** attribute is removed from original data set because the **sector** named by the news publisher does not necessarily refer to the industrial category of the companies mentioned in the news content.  

* Dataset that only contains News publish time from 10:00AM to 4:00PM is for a training model that eliminates a frequent price fluctuation in the begining of a trade day.   

