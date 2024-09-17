# "Что такое метод в javascript" ?

**Метод — это блок кода, который выполняется только при его вызове. В метод можно передавать данные, известные как параметры. Методы используются для выполнения определенных действий, и они также известны как функции.**
___

## _String МЕТОДЫ JAVASCRIPT_
 + charAt()
 + at()
 +  concat()
 +  concat()
+ includes()
+ indexOf()
+ replace(), replaceAll()
+ repeat()
+ slice()
+ substring()
+ split()
+ toString()
+ toLowerCase()
+ toUpperCase()
____
***Что делает метод charAt() ?***
+ Метод charAt() возвращает указанный символ из строки.
```java 
let text = "hello Billol how are you
console.log(text.charAt(1));
console.log(text.charAt(6));
```
___
# Что делает метод  at() ?
+ *Метод at () принимает значение в виде целого числа и возвращает элемент массива с данным индексом*
```java
let text = "hello Salmon how are you;
console.log(text.charAt(1));
console.log(text.at(-1));
```
___ 
# Что делает метод concat() ?
+ ***Метод concat сливает указанные массивы в один общий массив. Метод применяется к одному из массивов, а в параметрах метода передаются остальные массивы для слияния. При этом метод не изменяет исходный массив, а возвращает новый.***
```java
let text1 = "Hello";
let text2 = "JavaScript"
let jointext = text1.concat(" ", text2);
console.log(jointext)
```
___
# Что делает метод  trim() ?
+ ***Метод trim удаляет пробелы по краям строки. Чаще всего это нужно при вводе пользователем каких-либо значений: он может случайно налепить лишних пробелов - и наша задача очистить введенный текст от них.***
```java
let i  = "                    salom                            "
console.log(i.trim());"salom" //without whitespaces
```
___
# Что делает метод includes() ?
+ Метод include() **считывает свойство length у this, а затем обращается к каждому свойству, ключ которого представляет собой неотрицательное целое число, меньшее length.**
```java
let text = "hello world, i am glad to see you!"
let result = text.includes("world")
console.log(result); // true
console.log(text.includes("Javascript")); //false
```
___
# Что делает метод indexOf() ?
+ **Метод indexOf осуществляет поиск элемента в массиве. В первом параметре указываем номер позиции искомого символа. Метод возвращает номер первого найденного элемента, либо -1, если такого элемента нет. Второй необязательный параметр метода задает позицию, с которой следует начинать поиск.**
```java
let text = "hello world!"
console.log(text.indexOf("w")) //6
console.log(text.indexOf("lo")) //3
console.log(text.indexOf("f")) //-1

```
___
# Что делает метод replace(), replaceAll() ?
+ Метод **replaceAll()** возвращает новую строку со всеми совпадениями pattern, который меняется на replacement. pattern может быть строкой или регулярным выражением, и **replacement** может быть строкой или функция возвращающая каждое совпадение.
```java
let text = "hello Jane.Lets check your homework Jane"
let text1 = text.replace("Jane", "Bro")
console.log(text1)
```
___
#  Что делает метод repeat() ?
+ Метод repeat() возвращает новую строку с указанным количеством копий строки, на которой он был вызван.
```java
let text =  
```
___
# Что делает метод slice() ?
+ ***Метод slice () возвращает новый массив, содержащий копию части исходного массива.***
```
let a = "12345678"

console.log(a.slice(0,-1));

```
___
# Что делает метод substring() ?
+ Сводка Метод substring() возвращает подстроку строки между двумя индексами, или от одного индекса и до конца строки
___
# Что делает метод split() ?
  + Сводка Метод split() разбивает объект String на массив строк путём разделения строки указанной подстрокой.
___
# Что делает метод toString() ?
+ Метод toString () Java класса Object **возвращает символьную строку, описывающую объект**
___
# методы Nubers
+ Math.round(),ceil(),floor()
+  Math.max() and Math.min()
+  Math.pow() and Math.sqrt()
