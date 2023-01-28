# How to use the webscrapper

This readme will explain you how to use the scrapper from zero to hero. 

## 1. Prerequisite

- install dependencies
```python
> pip3 install -r requirements.txt
```

- install your own web driver from this [link](https://chromedriver.chromium.org/downloads) and put it on the `/webdriver` folder. Note that it has to match with your chrome browser version.

## 2. Usage

- make your own `data.csv`, using this format : 
```
title,url
{title},{url}
```

- After everything is set, run this command line to execute the code: 
```python 
> python3 main.py data.csv {NUM_IMAGES_PER_STYLE}
```

### Additional

To check the meta-data of the image, you can run the `metadata.py` file, change the `imagename` variable accordingly.

```python 
> python3 metadata.py 
```

Images will be saved in the `/photos` folder. Happy scrapping :) 