# JavaScript学习笔记

## JS变量

当声明一个变量后并未赋值，此时该变量的值为undefined。
变量在重新声明后并不会覆盖之前的值内容。

## JS数据类型

JS的数据类型包括：String, Number, Boolean, Array, Object, Null和Undefined。

Undefined和Null
变量值未赋值时为** undefined **，变量可以通过null设置为空值（empty）

## JS数字

通过数字的toString()方法可以将数字转化为16进制，8进制或2进制。
```
var myNumber = 128;
myNumber.toString(16);
myNumber.toString(8);
myNumber.toString(2);
```

数字中的Infinity表示数字溢出，除零时的结果也是Infinity。

## JS操作符

** delete操作符 **

delete操作符用于删除对象的属性，它对变量和方法不起作用。

```
var person = {
    firstName: "Kevin",
    lastName: "Lee",
    age: 35,
    eyeColor: "black"
};

delete person.age;
console.log("%o", person);
```

## JS类型转换

JavaScript中包含五种数据类型

1. string
2. number
3. boolean
4. object
5. function

三种对象类型

1. Object
2. Date
3. Array
