# 一、变量和数据类型
~~~
message = "Hello world!"
print(message)
~~~
可以按如图所示命名变量
## 1、变量的命名和使用
* 变量名只能包含字母、数字和下划线，变量名可以以字母或下划线开头。
* 变量名不能有空格
* 不能用python关键字和函数名作为变量名
* 简短且有描述性
* 慎用小写l和大写O
## 2、字符串
字符串是一系列字符，用括号引起的都是字符串，包括''和""。可以用方法修改字符串的大小写
~~~
name = "ada joey"
print(name.title()) #按标题格式输出，即首字母大写
print(name.upper()) #输出全大写的
print(name.lower()) #输出全小写的
~~~
<b>可以对字符串进行拼接</b>,方法就是简单的加一个'+'
~~~
first_name = "monica" #字符串要加引号，大小引号都可以
second_name = 'geller'
full_name = first_name + " " + second_name
message2 = "hello, " + full_name
print(full_name.title())
print(message2)
~~~
也可以用<b>制表符</b>添加空格

\t相当于空格 \n换行
~~~
print('\tpython') #用print直接输出文本时需要加引号
print("\nc language")
~~~
删除空白

用rstrip和lstrip分别删除字符串左端和右端的空白，用strip删除字符串中的空白
~~~
language = "  python "
print(language.rstrip())
print(language.lstrip())

language = language.rstrip()
print(language)
~~~
## 3、数字
除法类似现实中的数学，不像c语言要转换类型。**代表乘方，//代表地板除法（求余数），%代表取模。
~~~
c = 2**3 #**表示乘方
print(c)
d = 3/2  # /表示除法，不同于整除
print(d)
e = 7//3 # //表示求余数
print(e)
print(c,d,e,c%e)
~~~
对于<b>浮点数，要加到小数点后，否则不准确</b>

<b>不同类型的不能直接相加</b>
~~~
age = 23
message = "Happy " + str(age) + "rd Birthday"
print(message)
~~~
## 4、注释
#单行注释;'''整段注释

## 5、python之禅
在终端输入import this
# 二、列表简介



