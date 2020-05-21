# installing pip
sudo apt-get install python-pip
sudo apt-get install python3-pip
. ~/.profile

# installing scripy
https://docs.scrapy.org/en/latest/intro/install.html
pip install scrapy

# create project
scrapy startproject tutorial

# run spider
scrapy crawl quotes

# extracting data
scrapy shell <url>
eg: scrapy shell "http://www.scrapted.com"


