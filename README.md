# PMU_sourceSpecificScraper_publicTemplate
<b>Project Category:</b> Partisianship_Messaging_Understanding <br>
<b>Mission:</b> develop news-source specific article scrapers. <br>
<b>Developers:</b> Roberto Vargas, PhD <br>
<b>Note:</b> This is a generic template. Source specific templates are currently private. Please email robertj.vargas@gmail.com for further inquiries. <br><br>

<b>Overview:</b><br>
[Insert .py file]: This .py script is meant to executed in parallel with other source-specific scrapers as a batch throughout the day. This template is deigned to be run every 7 hours. <br><br>

The first execution create a temporary "day" file. With each subsequent execution the day file is amended to include new article information. <br>
The last execution of the .py file exports the day file to a master file for the specific news source. <br> <br>

<b>The following information is stored from each article:</b><br>
<i>article_link:</i> The url for the article <br>
<i>header:</i> The article header <br>
<i>pub_date:</i> The publication date of the article <br>
<i>article_text:</i> The full scraped text from the article <br><br>

ExampleOutput: <br>




