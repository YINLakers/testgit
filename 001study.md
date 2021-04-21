```python
`hello word`
python

import os
print("hello world!")

```

graph TD

```
`graph TD`
```





# Markdown快速入门（typora）

## 1,代码块

```````
//代码块语法：aaa
三个```java
   ```shell
   
```



**1.java代码**

```java
 public static void method2(){
        InputStream in = null;
        try{
            in = new BufferedInputStream(new FileInputStream("src/nomal_io.txt"));
            byte [] buf = new byte[1024];
            int bytesRead = in.read(buf);
            while(bytesRead != -1)
            {
                for(int i=0;i<bytesRead;i++)
                    System.out.print((char)buf[i]);
                bytesRead = in.read(buf);
            }
        }catch (IOException e)
        {
            e.printStackTrace();
        }finally{
            try{
                if(in != null){
                    in.close();
                }
            }catch (IOException e){
                e.printStackTrace();
            }
        }
 }
```

**2.shell脚本**

```shell
//linux 下spring项目的启动
my_array=(A B "C" D)

echo "第一个元素为: ${my_array[0]}"
echo "第二个元素为: ${my_array[1]}"
echo "第三个元素为: ${my_array[2]}"
echo "第四个元素为: ${my_array[3]}"
```



## 2,标题:

```java
//标题语法
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

```

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题



##  3，字体

```java
// 加粗
**等不到天黑 **
//代码高亮显示
== 我不是孙红雷 ==
//删除线
 ~~被删除的文章~~
//斜体
*斜体内容*    
    
```



// 加粗
**等不到天黑 **

//代码高亮显示

== 我不是孙红雷 ==

//删除线
 ~~被删除的文章~~

//斜体
*斜体内容*    



## 4,引用

```java
//引用语法
>作者：叶问
>>作者:叶问
>>>作者:叶问
    
```

//引用语法
>作者：叶问
>>作者:叶问
>>
>>>作者:叶问

## 5，分割线

```java
//分割线
---
//分割线2
***
    
```

//分割线
---
//分割线2

***

## 6，图片插入

```java
//在线图片 /本地图片
![我的图片](image/me.png)
    
```

![我的图片](//www.baidu.com/img/flexible/logo/pc/result.png)



## 7,超链接

```java
//超链接语法
[我的github](https://github.com/YINLakers/testgit)
```

[我的github](https://github.com/YINLakers/testgit)



## 8,列表语法

```java
//无序列表
- 目录1
- 目录2
- 目录3    

//有序
 1+. +名称  
    
```

//无序列表
- 目录1
- 目录2
- 目录3    



1. 首页
2. 分类
3. 标签

## 9，表格

|      |      |      |      |
| ---- | ---- | ---- | ---- |
|      |      |      |      |

