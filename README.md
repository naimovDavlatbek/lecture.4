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


