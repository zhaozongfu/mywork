## 1. Javascript 的 typeof 返回哪些数据类型

     Object
     number
     function
     boolean
     undefind

## 2 说说写 JavaScript 的基本规范？

    1) 不要在同一行声明多个变量
    2) 使用 ===或!==来比较true/false或者数值
    3) switch必须带有default分支
    4) 函数应该有返回值
    5) for if else 必须使用大括号
    6) 语句结束加分号
    7) 命名要有意义，使用驼峰命名法

## 3 介绍 JavaScript 的基本数据类型

    Number、String 、Boolean 、Null、Undefined
    Object 是 JavaScript 中所有对象的父对象

    数据封装类对象：Object、Array、Boolean、Number 和 String
    其他对象：Function、Arguments、Math、Date、RegExp、Error
    新类型：Symbol

## 4 列举几种强制类型转换和隐式转换

    强制（parseInt ,parseFloat ,number）
    隐式（==， = = =，-）

## 5 split() join()的区别

    前者是切割成数组的形式，后者是将数组转换为字符串

## 6 分别阐述 split(),slice(),splice(),join()？

    join()用于把数组中的所有元素拼接起来放入一个字符串。所带的参数为分割字 符串的分隔符，默认是以逗号分开。归属于 Array

    split()即把字符串分离开，以数组方式存储。归属于 Stringstring

    slice() 方法可从已有的数组中返回选定的元素。该方法并不会修改数组，而是 返回一个子数组。如果想删除数组中的一段元素，应该使用方法 Array.splice()

    splice() 方法向/从数组中添加/删除项目，然后返回被删除的项目。返回的是含 有被删除的元素的数组。

## 7 数组方法 pop() push() unshift() shift()

    push()尾部添加 pop()尾部删除
    unshift()头部添加 shift()头部删除

## 8 事件绑定和普通事件的区别

    事件绑定是指事件注册到具体的元素之上，普通事件可以用来注册的事件

## 9 谈谈 this 的理解

    1.  this 总是指向函数的直接调用者（而非间接调用者）
    2.  如果有 new 关键字，this 指向 new 出来的那个对象
    3.  在事件中，this 指向目标元素，特殊的是 IE 的 attachEvent 中的 this 总是指向全局对象 window。

## 10 什么是 window 对象? 什么是 document 对象?

    window 对象代表浏览器中打开的一个窗口。document 对象代表整个 html 文档。 实际上，document 对象是 window 对象的一个属性。
