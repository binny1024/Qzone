# Py3Utils
py3 scripting tools, including crawling tiger-teeth live stream, QQ space bulk message, increase the number of visits, etc.

# Qzone

Get all QQ friends, batch comments, check access permissions, etc., expandable

# Environment
2, install selenium
```
pip3 install selenium
```
3,isntall chromedriver

I use chrome ,you can download a driver depending your browser.

Chromedriver`s version must be same with your chrome browser version in you computer.

You can get the chromedriver from [Firefox](https://github.com/mozilla/geckodriver/releases/),[chromedriver](https://sites.google.com/a/chromium.org/chromedriver/)
or [chromedriver](http://chromedriver.storage.googleapis.com/index.html),[IE](http://selenium-release.storage.googleapis.com/index.html)

After you download  the driver ,you can put it in to the dictionary :
copy it into the path where python installed,
or if you sue mac ,you can put it into `/usr/local/bin`.

Form now on ,you can use it like this:
```python
from selenium import webdriver

browser = webdriver.Chrome()
browser.get('http://www.baidu.com/')
```


# Note: make sure the page is visible
# Note: make sure the page is visible
# Note: make sure the page is visible

# FQA

## 'ascii' codec can't decode byte 0xe5
```python
import sys
# ...
reload(sys)
sys.setdefaultencoding('utf8')
```
## add sleep time