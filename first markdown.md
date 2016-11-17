
# Markdown标记语言笔记
***

## 标题
# 一级标题
### 三级标题
###### 这是六级


## 无序列表
* 1
* 2
* 3


## 有序列表
1. 1
	1. 我意犹未尽的想起你
	2. 以及有关你的所有
2. 2
3. 3


## 引用
> 例如
> 
> 楼上
> 说的不错


## 链接 && 图片
[baidu](http://baidu.com)
![图片](http://img2.3lian.com/2014/f5/158/d/86.jpg)


## 粗体 && 斜体
**粗体**

*斜体*


## 表格 
| Tables        | Are           | Cool  |
| :------------ |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

>**:** 表示对齐方式


## 代码框
`
	这是不会换行的代码  
	我换 我换 换不了。。。
`

``` 这一行不会显示,貌似是说明代码语言的
	这个也不会。。。(曾经)
咦?
换了
	(改成github风格的markdown处理器就好了)
```

		这样就好了
		要缩进八个空格(两个tab)

***相比来说还是这样好点:***
``` python
def fib(n):
	if n==0:
		yield (1,1)
	else:
		for a in fib(n-1):
			b = a[-1]+a[-2]
			yield (a+(b,))

			
for s in fib(5):
	print(s)
```

***
