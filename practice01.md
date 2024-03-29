## 关于python
Python 是一种解释型语言，开发中没有了编译这个环节；是一种交互式语言，可以在一个Python提示符之后```>>>```后直接执行代码；是面向对象的编程语言。

推荐安装 Anaconda,它是一个开源的 Python 发行版本，其中包含了 conda、Python 等 180 个科学包及其依赖项。虽然安装包比较大，但以后使用起来很方便的。

### 变量
* 变量必须先赋值，才能使用。
* 变量名可以是字母，下划线，数字，但不能以数字开头
* 变量名的命名尽量做到符合规范，可读性高

### 运算符
运算符主要分为算术运算符，逻辑运算符，比较运算符，还有一种比较简洁的三目运算符，这里主要讲一下三目（或者三元）运算符：
```python
# 一般的 if 语句是这样写的

if 9 > 3:
  print(9)
else:
  print(3)
  
# 而用三元运算符写就一行代码
print(9) if 9 > 3 else print(3)
```

#### 值得注意的一点是要牢记它们的优先级顺序
算术运算符优先级从低到高是：
* 对两个值进行操作的 +、- 的优先级最低；
* 而后是 *、/、//、%；
* 而后是对单个值进行操作的 +、-；
* 而后是 **。

逻辑运算符优先级从低到高是：
* 或（or）
* 且（and）
* 非（not）

各类运算符优先级从高到低：
* 算数运算符
* 比较运算符
* 逻辑运算符

（针对这个不用死记，你想啊，我们小学就开始算这个了。先进行数值之间的计算，再将结果进行大小于比较，最后进行‘或、且、非’的判断是 True or False）
有了这个规则，我们才能进行程序的控制，继续走下一步。

### Python 中的数据类型
主要分为三类：
* 布尔值（Boolean Value)
* 数字（Numbers）：整数（Int）、浮点数（Float）、复数（Complex Numbers）
* 字符串（Strings）
各数据类型之间有些可以相互转换，str() 换成了字符串型的，int()转成整型，float()转成浮点型。

第一次用 Markdown 写文章，第一次写关于编程的文章，第一次用 github 记录文字······希望对看到此处的你有帮助。谢谢你的关注，很开心你能提出我的不足之处，多多交流，共同进步。


