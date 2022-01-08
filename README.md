# **Dart Documentation By " Ahmed Amer "**

****

**<u>[Online Code Editor](https://dartpad.dev/?null_safety=true)</u> =>** https://dartpad.dev/?null_safety=true

[Online Code Editor 2](https://replit.com/) => https://replit.com/

**<u>[Reference](https://www.tutorialspoint.com/dart_programming/index.htm)</u> =>** https://www.tutorialspoint.com/dart_programming/index.htm

********

1-) What is Dart ? Who is create it ?

Answer :

**<u>Dart :</u>** is a programming language designed for client development, such as for the web and mobile apps. It is developed by Google and can also be used to build server and desktop applications. Dart is an object-oriented, class-based, garbage-collected language with C-style syntax.

**[Developer](https://www.google.com/search?rlz=1C1GCEA_enIQ911IQ911&sxsrf=AOaemvJRRgecrjBH0KYo1chTa4qtbGzf8A:1641667033386&q=dart+programming+language+developer&sa=X&ved=2ahUKEwj4v_Si5qL1AhUFgv0HHcaKAtQQ6BMoAHoECDMQAg):** [Google](https://www.google.com/search?rlz=1C1GCEA_enIQ911IQ911&sxsrf=AOaemvJRRgecrjBH0KYo1chTa4qtbGzf8A:1641667033386&q=Google&stick=H4sIAAAAAAAAAONgVuLUz9U3MDFNNk9axMrmnp-fnpMKAMKapuoWAAAA&sa=X&ved=2ahUKEwj4v_Si5qL1AhUFgv0HHcaKAtQQmxMoAXoECDMQAw).

**[Stable release](https://www.google.com/search?rlz=1C1GCEA_enIQ911IQ911&sxsrf=AOaemvJRRgecrjBH0KYo1chTa4qtbGzf8A:1641667033386&q=dart+programming+language+stable+release&sa=X&ved=2ahUKEwj4v_Si5qL1AhUFgv0HHcaKAtQQ6BMoAHoECEYQAg):** 2.15.1 / 14 December 2021; 23 days ago.

**[Filename extensions](https://www.google.com/search?rlz=1C1GCEA_enIQ911IQ911&sxsrf=AOaemvJRRgecrjBH0KYo1chTa4qtbGzf8A:1641667033386&q=dart+programming+language+filename+extensions&sa=X&ved=2ahUKEwj4v_Si5qL1AhUFgv0HHcaKAtQQ6BMoAHoECDoQAg):** dart.

**[Designed by](https://www.google.com/search?rlz=1C1GCEA_enIQ911IQ911&sxsrf=AOaemvJRRgecrjBH0KYo1chTa4qtbGzf8A:1641667033386&q=dart+programming+language+designed+by&sa=X&ved=2ahUKEwj4v_Si5qL1AhUFgv0HHcaKAtQQ6BMoAHoECEIQAg):** [Lars Bak](https://www.google.com/search?rlz=1C1GCEA_enIQ911IQ911&sxsrf=AOaemvJRRgecrjBH0KYo1chTa4qtbGzf8A:1641667033386&q=Lars+Bak&stick=H4sIAAAAAAAAAONgVuLSz9U3MC00qSyJX8TK4ZNYVKzglJgNAFu6_xEZAAAA&sa=X&ved=2ahUKEwj4v_Si5qL1AhUFgv0HHcaKAtQQmxMoAXoECEIQAw&biw=1536&bih=714&dpr=1.25) and [Kasper Lund.](https://www.google.com/search?rlz=1C1GCEA_enIQ911IQ911&sxsrf=AOaemvJRRgecrjBH0KYo1chTa4qtbGzf8A:1641667033386&q=Kasper+Lund&stick=H4sIAAAAAAAAAONgVuLVT9c3NEzPKMuuMjWzWMTK7Z1YXJBapOBTmpcCAF2km-gfAAAA&sa=X&ved=2ahUKEwj4v_Si5qL1AhUFgv0HHcaKAtQQmxMoAnoECEIQBA&biw=1536&bih=714&dpr=1.25)

**[First appeared](https://www.google.com/search?rlz=1C1GCEA_enIQ911IQ911&sxsrf=AOaemvJRRgecrjBH0KYo1chTa4qtbGzf8A:1641667033386&q=dart+programming+language+first+appeared&sa=X&ved=2ahUKEwj4v_Si5qL1AhUFgv0HHcaKAtQQ6BMoAHoECCUQAg):** October 10, 2011; 10 years ago.

****

2-) Camp output ? What can I do if I learn Dart ?

Answer :

Well, You gonna deal with the Dart programming language with write the codes and read the codes with Dart. You can use it with **Flutter SDK** to build native cross-platform applications.  

****

3-) Dart Syntax :

- Main Syntax & Print :

  ```dart
  void main() { 
     print("Hello World!"); 
  }
  ```

  ```dart
  main() {
     print('Hello World');
  }
  ```

  ```
  Hello World
  ```

- Comments :

  ```dart
  /* multiline comment */
  // single line comment
  ```

- Data Types :

  ```
  The Dart language supports the following types−
  - integer
  - string
  - double
  - bool
  - const
  - var 
  - list
  - map
  ```

- Variables :

  ```dart
  main(){
      string name = 'Steve'; 
      int n = 10;
      double x = 15.2; /* OR */ x = 15;
      const pi = 13.4;
      var k = all types; /* It's gonna declare and got what data type of it */
      bool var_name = true;  /* OR */   bool var_name = false;
  }
  ```

- Operators :

  ```
  [ + , / , * , - , % , ++ , -- , < , <= , > , >= , == , != , && , || ]
  ```

****

4-) For Loop:

```dart
void main() {    
    for (var i = 1; i <= 5; i++) { 
    	print("Item : ${i}"); 
    }
}
```

```
Item : 1
Item : 2
Item : 3
Item : 4
Item : 5
```

****

5-) While Loop :

```dart
void main() { 
   var i = 1;    
   while(i <= 5) { 
      print("Item : ${i}"); 
      i++; 
   } 
}
```

```
Item : 1
Item : 2
Item : 3
Item : 4
Item : 5
```

****

6-) Do While Loop :

```dart
do {  
   Statement(s) to be executed;  
} while (expression); 
```

```dart
void main() { 
   var n = 10; 
   do { 
      print(n); 
      n--; 
   }
   while(n>=0); 
} 
```

```
10 
9 
8 
7 
6 
5 
4 
3 
2 
1 
0
```

****

7-) Conditions :

```dart
void main() { 
   var str = 'abc'; 
   if(str) { /* true */
      print('String is not empty'); 
   } else { /* false */
      print('Empty String'); 
   } 
}
```

```
String is not empty
```

****

8-) Switch Case :

```dart
switch (value) {
  case 0:
    // do something
    break;
  case 1: 
    // do something else
    break;
}
```

```dart
void main() { 
   var grade = "A"; 
   switch(grade) { 
      case "A": {  print("Excellent"); } 
      break; 
     
      case "B": {  print("Good"); } 
      break; 
     
      case "C": {  print("Fair"); } 
      break; 
     
      case "D": {  print("Poor"); } 
      break; 
     
      default: { print("Invalid choice"); } 
      break; 
   } 
} 
```

```
Excellent
```

****

9-) List :

```dart
void main() { 
   var num_list = [1,2,3]; 
   print(num_list); 
}
```

```
[1,2,3]
```

****

10-) Map :

```dart
void main() { 
   var details = {'Usrname':'tom','Password':'pass@123'}; 
   print(details); 
}
```

```
{Usrname: tom, Password: pass@123}
```

```dart
void main() { 
   var details = new Map(); 
   details['Usrname'] = 'admin'; 
   details['Password'] = 'admin@123'; 
   print(details); 
} 
```

```
{Usrname: admin, Password: admin@123}
```

****

11-) Functions :

```dart
void main() { 
   print(msg());
}  
msg() { 
	print("this is function msg"); 
}
```

```
this is function msg
```

****

12-) Arrow Function

```dart
void main() { 
   printMsg(); 
   print(test()); 
}  
printMsg()=> print("hello"); 
int test()=>123;                       
// returning function 
```

```
hello 123
```

****

13-) OOP :

```dart
class Car {  
   // field 
   String engine = "E1001";  
   
   // function 
   void disp() { 
      print(engine); 
   } 
}
main(){
	var ob = new Car(); /* OR */ Car ob = new Car();
	ob.disp();
}
```

```
E1001
```

****

14-) Classes :

```dart
class Student { 
   void test_method() { 
      print("This is a  test method"); 
   } 
   
   void test_method1() { 
      print("This is a  test method1"); 
   } 
}  
void main()    { 
   Student s1 = new Student(); 
   s1.test_method(); 
   s1.test_method1(); 
}
```

```
This is a  test method
This is a  test method1
```

****

## 

