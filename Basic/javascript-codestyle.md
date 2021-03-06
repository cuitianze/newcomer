# JavaScript 编程规范

## 代码换行

 - 我们要求左右花括号后都要换行，例如
```js
  if (...) {
      [code]  
  }
  else {
      [code]
  }
  // 单行除外：
  // if (...) { [code] }
```
  
 - 请在每个代码内适当插入空行，这样有助于他人阅读代码。
```js
 function fun1 () {
     [code]
 }
 
 function fun2 () {
     [code]
 }
```

 - 文件结尾必须有单独的空行。

## 空格使用

 - 在使用运算符的时候要注意空格的使用例如：`var foo = 1;`和`for (var foo = 0; foo <= 10; for++) {[code]}`，我们注意到第一个例子中"="两边都添加了空格。再看复杂些的第二个例子，在赋值、比较运算符两边都添加了一个空格
 - 在分号";"之后也有一个空格例如`for (var foo = 0; foo <= 10; for++)`但常规赋值语句的句末不需要。
 - 在关键字和括号之后也要加一个空格例如：
```js
    function fun1 () {
        [code]
    }
    
    while (...) {
        [code]
        // while/do/for/if...ect类似代码体的都是这种空格的格式
    }
```
  - 逗号","和冒号":"则只需要在使用之后添加一个空格，例如：`function fun1 (key, value)`和`{key: value}`
  - 注释“// xxx”，此处双斜杆后建议添加一个空格。
  - 行尾空格建议删除。
 
##变量命名规则
- 使用小驼峰命名法，即若变量名由多个单词组成，则首字母小写，变量名中每个单词的首字母大写`var _serializeField = xxx;`
- 变量以下划线"_"开头，意为不推荐使用，这些方法一般不会出现在API文档中。

##缩进
- 请不要使用Tab作为缩进符，而是四个空格
