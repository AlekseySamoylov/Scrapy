scrapy startproject Scrapy    
scrapy genspider quotes quotes.toscrape.com
scrapy shell
fetch("http://quotes.toscrape.com")  
inspect elements in web browser  
response
response.css('h1::text')
response.xpath('//h1/a/text()').extract()
response.xpath('//h1/a/text()').extract_first()
response.xpath('//*[@class="tag-item"]')
response.xpath('//*[@class="tag-item"]/a/text()').extract()

scrapy list  

scrapy crawl quotes

