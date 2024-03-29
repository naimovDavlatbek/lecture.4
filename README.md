# lecture.4
## JAVA SCRIPT METHODS.
### What is the Method in Java Script?
JavaScript methods are actions that can be performed on objects. 
A JavaScript method is a property containing a function definition.

###  JAVA SCRIPT STRING METHODS.
+ charAt();
+ at();
+ concat();
+ trim();
+ includes();
+ indexOf();
+ replase(), replaseAll();
+ repeat();
+ slice ();
+ substring();
+ split();
+ toString();
+ toLowerCase();
+ toUpperCase();


  ### CharAt()

  Метод charAt() возвращает указанный символ из строки.
   
````JavaScript
   let str = "Naimov";
   console.log(str.charAt(2))//"i";
````
____
### at();
  Усули at() арзиши бутунро мегирад ва элементи массивро дар индекси додашуда бармегардонад. Усул рақамҳои мусбат ва манфиро ҳамчун далел қабул мекунад. Агар арзиш манфӣ бошад, ҳисоб аз охири массив оғоз мешавад.

 ````JavaScript
   let str = "Naimov";
   console.log(str.charAt(-1))//"v";
````
___
### concat();
Усули concat()мисолҳо Arrayбарои якҷоя кардани ду ё зиёда массивҳо истифода мешавад.
 Ин усул массивҳои мавҷударо тағир намедиҳад, балки ба ҷои он массиви навро бармегардонад.

 ````JavaScript
   let str = "Naimov";
   let text= "Davlatbek";
   let join = str.concat(" ", text); 
   console.log(join); // Naimov Davlatbek
````
___
  ### replace()
  Усули иваз () сатри навро бо баъзе ё ҳама мувофиқати намунавӣ, ки бо ҷойнишин иваз карда шудаанд, бармегардонад. Намуна метавонад сатр ё ифодаи муқаррарӣ бошад ва ҷойнишин метавонад сатр ё функсияе бошад, ки дар ҳар як мувофиқат даъват карда мешавад.

 ````JavaScript
   let str = "Hello World";
   let chang = str.replace("World ", "text"); 
   console.log(chang); // Hello text
````

___
  ### replaceAll()
  Усули replaceAll()арзишҳо Stringсатри навро бо ҳама мувофиқати patterna иваз мекунад replacement. Он patternметавонад сатр ё a бошад RegExp, ва он replacementметавонад сатр ё функсия бошад, ки барои ҳар як мувофиқат даъват карда мешавад. Сатри аслӣ бетағйир боқӣ мемонад.


 ````JavaScript
   let str = "Hello Naim. go Naim";
   let replacetext = str.replaceAll("Naim ", "Ali"); 
   console.log(chang); // Hello Ali. go Ali
````

_____
### split();
Усули split()арзишҳо Stringнамуна мегирад ва ин сатрро бо ҷустуҷӯи намуна ба рӯйхати тартибёфтаи зерсатрҳо тақсим мекунад, ин зерсатрҳоро ба массив мегузорад ва массивро бармегардонад.


 ````JavaScript
   let str = "Hello Naim. go Naim";
   console.log(str.split()); // ['Hello Ali. go Ali']
````
____
### substring();
Усули substring()арзишҳо Stringқисми ин сатрро аз шохиси оғоз то ва ба истиснои шохиси ниҳоӣ ё то охири сатр бармегардонад, агар ягон индекси ниҳоӣ дода нашавад.

 ````JavaScript
   let str = "Hello";
   let sub=str.substring(0,2);
   console.log(sub)
````
___

### slice();
Метод slice() возвращает новый массив, содержащий копию части исходного массива.

 ````JavaScript
   let str = "Hello";
   let sliced=str.slice(1,2);
   console.log(sub)
````
___


### toLowerCase();

Тавассути ин метод мо метавонем ҳарфҳои калонро хурд кунем.


 ````JavaScript
   let str = "HELLO";
   console.log(str.toLowerCase())//hello;
````
___


### toUpperCase();
Ин функсия баръакси функсияи  toLowerCase(); кор мекунад яъне ҳарфҳои хурдро калон мекунад.

 ````JavaScript
   let str = "hello";
   console.log(str.toUpperCase())//HELLO;
````
___

### trim();
Усули trim() фосиларо аз аввал то охири сатр нест мекунад. Аломатҳои фосила дар ин замина аломатҳои холигии воқеӣ (фосила, ҷадвал, фазои шикаста ва ғайра) ва охири сатр (LF, CR ва ғайра) ҳисобида мешаванд.
  

 ````JavaScript
   let str = "   hello          ";
   console.log(str.trim())//'hello';
````
___

### includes();
Метод includes() определяет, содержит ли массив определённый элемент, возвращая в зависимости от этого true или false.



 ````JavaScript
   let str = "hello world, i am glad to see you!";
   let res=str.includes("see")
   console.log(res)   ///true

````
____

### toString();
Метод toString() возвращает строку, представляющую объект.
   
 ````Javascript
  let  number = 25;
    console.log (typeof number.tostring()); // 'string'
````

### Java Script methods indexOf()
Дар ин метод мо элементро дохил мекунем индекси элементро бармегардонад.
   

   ````Javascript
    
    let str = "Salom Ali";
    console.log(str.indexOf(a)); //1
    ````
    