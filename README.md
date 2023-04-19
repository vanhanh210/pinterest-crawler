
## How to Run


```python
from src import PinterestScraper, PinterestConfig

configs = PinterestConfig(search_keywords="random pic", # Search word
                          file_lengths=200,     # total number of images to download (default = "100")
                          image_quality="orig", # image quality (default = "orig")
                          bookmarks="")         # next page data (default= "")

PinterestScraper(configs).download_images() # download images directly (photos/atatürk, photos/web-scraping)

print(PinterestScraper(configs).get_urls()) # get image links
```
