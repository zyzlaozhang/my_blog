# 我的博客

## 后台
语言我使用的是**python**

框架使用的是**flask**

```python
    from flask import Flask
    app=Flask(__name__)
    @app.route("/")
    def index():
        return 'hello_world'
    if __name__ =="__main__":
        app.run(debug=True)
        
```
(一个最基础的**flask**程序)

### 项目所需的库

| 库名 | 版本 | 
| :----- | ----: | 
| Flask  | 2.1.2 | 
| Flask-Share | 0.1.1 | 
| jieba | 0.42.1|
| Markdown | 3.4.1 |
| pymongo | 4.1.1 |
| requests | 2.28.2 |
| urllib | 1.26.12 |

## 数据库
数据库使用**Mongodb**

是**这**个样子的

>System  *自带的不用管*

>config  *自带的不用管*

>testdb  *所有数据存在这里*

>>collection *集合都在这里*

>>> userdb  *存放用户信息*

>>> bookdb  *存放作品信息*

>>> pricedb *存放商品信息*

***pricedb 往下看***
    
 ```json
 /* 1 */
{
    
    "name" : "井字棋",
    "price" : 250,
    "stitle" : "人机对战，任意三个标记形成一条直线，则为获胜",
    "png_url" : "../static/images/ttt.png"
}

/* 2 */
{
    
    "name" : "数字炸弹",
    "price" : 200,
    "stitle" : "在一个数字范围内，有一个数字作为炸弹，谁猜中这个炸弹就会爆炸",
    "png_url" : "../static/images/szzd.png"
}

/* 3 */
{
    
    "name" : "金坷垃",
    "price" : 450,
    "stitle" : "非洲农业不发达，我们都要金坷垃",
    "png_url" : "../static/images/jkl.png"
}

/* 4 */
{
    
    "name" : "诈骗神曲",
    "price" : 650,
    "stitle" : "你被骗了",
    "png_url" : "../static/images/rick.png"
}

/* 5 */
{
    
    "name" : "鸡你太美",
    "price" : 514,
    "stitle" : "我是个人练习生蔡徐坤",
    "png_url" : "../static/images/cxk.png"
}
```
    

## 前端

没什么好说的


# 给个星星吧