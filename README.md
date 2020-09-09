# South Park Image Scraper

*Scrapes all the images of South Park characters and downloads them to a local folder*

I was looking for a database of South Park images for a GAN project I was working on, but couldn't find anything that really fit my needs. I found [this web-site](https://southpark.fandom.com/wiki/Portal:Characters) that had all the images I needed, but it has thousands of them, so I wasn't about to right click on every single one of them to save. 

These images were not placed in the web-site like normal images, but were instead links for other wiki pages, so I ran into some issues using traditional web scrapers. After inspecting the source code of the page, I discovered all images had a corresponding URL where they were stored that started with the same pattern: 

>https://vignette.wikia.nocookie.net/southpark/images/ 

So I used that information to get all the URLs beginning with that phrase and download the images to a local folder. 
