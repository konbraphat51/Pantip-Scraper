# Pantip-Scraper
Pantip is Thai Redit.  
These jupyter notebooks will get text from Pantip with following procedure:  
  
## Scraping part
  
* 01: Get Links of posts searched from keywords  
* 02: Get rid of duplicated links (Links will be unique)  
* 03: Scrape texts from each links  
  
The text data will be following format:  
DATE@@-(text content)  

New line characters will be converted to single space  
Each row show single post 
  
## Analyzing part
  This will use pythainlp  

  * 04:Tokenize all text data
  
  Data format:  
  (time)@@-(token1_text),@-(token1_tag),@-(token1_BIO)|@-(token2_text)..
