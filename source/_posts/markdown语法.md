---
title: markdown语法
date: 2018-08-28 10:46：23
tags: 
- markdown
- 教程
categories:
- 语法
cover_picture: images/1.jpg  #文章封面图
---
# 标题
--------------------
标题分为一到六级，分别为1~6个#号，#号后面需要带上一个空格

# 引用
写法一：
>书是人类进步的阶梯
别看了，其实只有上面这一句

写法二：
>书是人类进步的阶梯
别看了，其实只有上面这一句

嵌套引用：
> 天王盖地虎
>> 宝塔镇河妖
>>> 小鸡炖蘑菇

# 代码块
下面是一段js代码：
```javascript
for(var i = 0;i < 10;i++){
    console.log(i)
}
```
下面是一段css代码：
```css
body{
    color:red;
    font-size:12px;
}
```

# 超链接
[点我](http://www.baidu.com)跳转到百度

# 图片
```
引入图片方法：   ![图片名字](图片链接)
```
![表情包](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1535436673004&di=ad9b8faec76063d3276e3692e556eac6&imgtype=0&src=http%3A%2F%2Fimg.bqatj.com%2Fimg%2Fcbb818e8bea24f53.jpg)
## 图片超链接
```
[![图片名字](图片地址)](超链接地址)
```
[![表情包](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1535436673004&di=ad9b8faec76063d3276e3692e556eac6&imgtype=0&src=http%3A%2F%2Fimg.bqatj.com%2Fimg%2Fcbb818e8bea24f53.jpg)](http://www.baidu.com)跳转到百度
# 列表
## 有序列表
1. 手机
2. 电脑
3. pad

## 无序列表
* 小米
* 华为
* 三星

# 表格

姓名|排行|特长|数字
-|-|-|-
刘备|老大|哭|1
关羽|老二|打|2
张飞|老三|骂|3


