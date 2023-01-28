# How to use the webscrapper

This readme will explain you how to use the scrapper from zero to hero. 

## 1. Prerequisite

- install dependencies
```python
> pip3 install -r requirements.txt
```

- install your own web driver from this [link](https://chromedriver.chromium.org/downloads). Note that it has to match with your chrome browser version.

## 2. Usage

- make your own `data.csv`, using this format : 
```
title,url
{title},{url}
```

- After everything is set, run this command line : 
```python 
> python3 main.py data.csv {NUM_IMAGES_PER_STYLE}
```

Happy scrapping :) 