# PMU_sourceSpecificScraper_publicTemplate
Project Category: Partisianship_Messaging_Understanding <br>
Mission: develop news-source specific article scrapers. <br><br>

Overview:<br>
[Insert .py file]: This .py script is meant to executed in parallel with other source-specific scrapers as a batch throughout the day. This template is deigned to be run every 7 hours. <br><br>

The first execution create a temporary "day" file. With each subsequent execution the day file is amended to include new article information. <br>
The last execution of the .py file exports the day file to a master file for the specific news source. <br> <br>

The following information is stored from each article: <br>
article_link: The url for the article <br>
header: The article header <br>
pub_date: The publication date of the article <br>
article_text: The full scraped text from the article <br><br>

ExampleOutput: <br>




