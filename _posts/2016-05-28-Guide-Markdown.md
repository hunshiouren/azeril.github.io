---
layout: post
title: Markdown 语法
categories: [blog ]
tags: [guide, ]
description: markdown 语法指南
---


# Markdown 语法规则指南
## 1. 多级标题
### 语法
```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
```
### 效果
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题

###注意点：
* 井号与标题之间注意空格
* GitHub 网站支持 Markdown 书写，最多六级标题
* 日常使用，三级标题运用足以，过多干扰阅读

## 2. 斜体
### 语法
```
*斜体*
_斜体_
```
### 效果
*斜体*  
_斜体_
### 注意点

## 3. 加粗
### 语法
```
**加粗**
__加粗__
```
### 效果
**加粗**  
__加粗__
### 注意点

## 4. 分隔符
### 语法
```
***
* * *  
*****  
_ _ _  
___
```
### 效果
***
* * *  
*****  
_ _ _  
___
### 注意点

## 5. 列表
### 语法
```
无序列表    

* English  
* Japanese
* Chinese  

有序列表  

1. Orange
2. Apple
3. Banana

```
### 效果
无序列表    

* English  
* Japanese
* Chinese  

有序列表  

1. Orange
2. Apple
3. Banana

### 注意点  
有序列表英文输入，点后空格

## 6. 多层列表
### 语法
```
- 南京 
  + 玄武湖
  + 中山陵
  + 鸡鸣寺
- 杭州 
  + 西湖
     * 苏堤
     * 湖心亭
     * 太子湾
  + 九溪
  + 灵隐 
```
### 效果  

- 南京 
  + 玄武湖
  + 中山陵
  + 鸡鸣寺
- 杭州 
  + 西湖
     * 苏堤
     * 湖心亭
     * 太子湾
  + 九溪
  + 灵隐 

### 注意点

## 7. 引用内容
### 语法
```
杜拉斯：

> 爱之于我，不是肌肤之亲，不是一饭一蔬。它是一种不死的欲望；是疲惫生活的英雄梦想。


```
### 效果
杜拉斯：

> 爱之于我，不是肌肤之亲，不是一饭一蔬。它是一种不死的欲望；是疲惫生活的英雄梦想。

### 注意点
* 有些编辑器要求「>」引用的上一行为空行，语法才能生效
* 「>」与引用字间需添加一个空格

## 8. 标记代码
### 语法

    ```
    <style>
    {
        font-size: 22px;
    }
    </style>
    ```

### 效果  
```
<style>
  {
      font-size: 22px;
  }
</style>
```
### 注意点
* 输入：英文输入模式下，键盘右上角「～」键
* 另一种方式：每行前空四格

## 9. 换行
### 语法
```
  



```
### 效果
  


 
### 注意点
* 方式一：行末两次回车，隔开一个空行继续书写
* 方式二：行末两个空格，一次回车，适用于引用、代码区等场景

## 10. 添加链接
### 语法

    [Google](http://google.com)  
    [Google][a]

    [a]: http://www.google.com  

### 效果
[Google](http://google.com)  
[Google][a]

[a]: http://www.google.com
### 注意点

## 11. 生成自动链接
### 语法
```
<http://www.google.com>
```
### 效果  
<http://www.google.com>
### 注意点

## 12. 添加图片
### 语法
```
![Pic](http://7xp5vc.com1.z0.glb.clouddn.com/%E7%8B%97%E7%8B%97.jpg)
```
### 效果
![Pic](http://7xp5vc.com1.z0.glb.clouddn.com/%E7%8B%97%E7%8B%97.jpg)
### 注意点
* 日常使用，需先上传至某图床，再获取图片的外链进行调用

## 13. 插入本地图片
### 语法
```
![image](Downloads/dog.jpg)
```
### 效果
![image](Downloads/dog.jpg)
### 注意点

## 14. 图片居中显示
### 语法
```
<center>
   ![](http://7xp5vc.com1.z0.glb.clouddn.com/%E7%8B%97%E7%8B%97.jpg)
</center>

<center>
   <img src="http://7xp5vc.com1.z0.glb.clouddn.com/%E7%8B%97%E7%8B%97.jpg">
</center>
  
 <figure>
       <img src="http://7xp5vc.com1.z0.glb.clouddn.com/%E7%8B%97%E7%8B%97.jpg">
 </figure>
```
### 效果
<center>
   ![](http://7xp5vc.com1.z0.glb.clouddn.com/%E7%8B%97%E7%8B%97.jpg)
</center>

<center>
   <img src="http://7xp5vc.com1.z0.glb.clouddn.com/%E7%8B%97%E7%8B%97.jpg">
</center>
  
 <figure>
       <img src="http://7xp5vc.com1.z0.glb.clouddn.com/%E7%8B%97%E7%8B%97.jpg">
 </figure>
### 注意点
* 套用HTML语法，进行优化

## 15. 制作表格
### 语法
```
|Title|Title 1|Title 2|Title 3|
|---|---|---|---|
|A|B|C|D|
```
### 效果
|Title|Title 1|Title 2|Title 3|
|---|---|---|---|
|A|B|C|D|
### 注意点
* 第二行中间隔断数量至少3个，更多不限

## 16. 表格中的文字对齐
### 语法
```
|Title|Title 1|Title 2|Title 3|
|---| :---|---:|:---:|
|A|B|C|D|
```
### 效果
|Title|Title 1|Title 2|Title 3|
|---| :---|---:|:---:|
|A|B|C|D|
### 注意点
* :--- 冒号在左，左对齐
* ---: 冒号在右，右对齐
* :---: 冒号在左右两侧，居中对齐

## 17. 转义符
### 语法
```
\*斜体*
```
### 效果
\*斜体*
### 注意点


