# learyC

简单学习下 C 语言

## 字符

### 结束字符

- window 系统下使用 `ctrl + z`
- Unix/Linux 系统中输入 `ctrl + d`

### 字符常量

单引号中的字符表示一个整型值，该值等于此字符在机器字符集中对应的数值，这样的字符
称为字符常量。

## 函数

### 传参

在 C 语言中，所有函数参数都是通过值传递的。传递给函数的参数值存放在临时变量中。
如果想在函数中改变参数初始数据的值，可以在调用函数时传入参数的指针。如果是数组参
数，传递给函数的值是数组起始元素的位置或地址（并不会复制数组元素本身）。在被调用
函数中，可以通过数组下标访问或修改数组元素的值。
