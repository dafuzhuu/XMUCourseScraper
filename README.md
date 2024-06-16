# XMUCourseScraper
Selenium爬厦大选课网站

爬虫入门作品，十分粗糙，有很大改进空间

**必要的库**

- `selenium`
- `PIL`
- `pandas`

此外，还需安装[Chrome WebDriver](https://chromedriver.chromium.org/)

**记得填入账号密码**
在`login`函数里：

```
username.send_keys('username') # 填入用户名
# ...
password.send_keys('password') # 填入密码
```

建议使用`.ipynb`文件，卡退或被管理员踢出去后方便继续
