# **Dart Documentation By " Ahmed Amer "**

****

**<u>[Online Code Editor](https://dartpad.dev/?null_safety=true)</u> =>** https://dartpad.dev/?null_safety=true

[Online Code Editor 2](https://replit.com/) => https://replit.com/

**<u>[Reference](https://www.tutorialspoint.com/dart_programming/index.htm)</u> =>** https://www.tutorialspoint.com/dart_programming/index.htm

********

1-) What is Dart ? Who is create it ?

###### Answer :

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
      String name = 'Steve'; 
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
   
   /* we can use nested conditions */
   if(condition){
       if(condition){
       	 if(condition){
             // statement
         }else{
             // statement
         }
       }else{
           // statement
       }
   }else{
       // statement
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
  default:
    // do something if not all before cases
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
   
   num_list.add(4); // add to list function
   print(num_list);
   
   num_list.remove(1); // remove from list function
   print(num_list);
   
   var lst= [1,2,3,4,5];
    lst.forEach((i) {
    print('i = ${i}');
   });
    /*
     list_or_map.forEach((element) {
     	// Statment
     });
    */
   print("-" * 30);
   var mylist = ['A', 'B', 3.14, true, 55];
   print(mylist);
   print("-" * 30);
   
   mylist.insert(4, 44); // insert in specefic index
   mylist.insert(6, 555);
   mylist.insert(7, 777);
   print(mylist);
   print("-" * 30);
   
   mylist.add(88); // after last index
   mylist.add(99);
   print(mylist);
   print("-" * 30);
   
   mylist.remove('A'); // remove the element
   mylist.remove(55);
   mylist.removeAt(0); // remove by index
   for (var i = 0; i <= mylist.length - 1; i++) {
     print("Value : ${mylist[i]}");
   }
}
```

```
[1,2,3]
[1, 2, 3, 4]
[2, 3, 4]
i = 1
i = 2
i = 3
i = 4
i = 5
------------------------------
[A, B, 3.14, true, 55]
------------------------------
[A, B, 3.14, true, 44, 55, 555, 777, 88, 99]
------------------------------
Value : 3.14
Value : true
Value : 44
Value : 555
Value : 777
Value : 88
Value : 99
```

****

10-) Map :

```dart
void main() { 
   var details = {'Username':'tom','Password':'pass@123'}; 
   print(details); 
   
   details.remove('Username'); // remove from Map
   print(details);
    
   details['test'] = '55'; // add to Map
   print(details);
    
   details.addAll({'Email': 'a@a.a'}); // add to Map using function build in
   print(details);
   
   details.forEach((key, value) { // print Map content using forEach
    print('Key = ${key}\nValue = ${value}');
   });
}
```

```
{Username: tom, Password: pass@123}
{Password: pass@123}
{Password: pass@123, test: 55}
{Password: pass@123, test: 55, Email: a@a.a}
Key = Username
Value = tom
Key = Password
Value = pass@123
```

```dart
void main() { 
   var details = new Map(); 
   details['Username'] = 'admin'; 
   details['Password'] = 'admin@123'; 
   print(details); 
} 
```

```
{Username: admin, Password: admin@123}
```

****

11-) Functions :

```dart
void main() {
  msg();
  print(age());
  print(name());
  print(cond());
  print(lst());
  print(myMap());
}

msg(){ // void function without return
  print('message');
}

int age(){ // integer function should return integer number
  return 20;
}

String name(){ // string function should return string
  return 'Ahmed';
}

bool cond(){ // boolean function should return true or false
  return true;
}

List lst(){ // list function should return list
  return [1,2,3,4,5];
}
Map myMap(){ // map function should return map
  return {'one':'1', 'two':'2'};
}

```

```
message
20
Ahmed
true
[1, 2, 3, 4, 5]
{one: 1, two: 2}
```

***

12-) Arrow Function

```dart
void main() {
  msg();
  print(age());
  print(name());
  print(cond());
  print(lst());
  print(myMap());
}
/*
	Note: This type of function work with single line statment
*/
msg() => print('message'); // arrow function with void type

int age() => 20; // arrow function with integer type

String name() => 'Ahmed'; // arrow function with string type

bool cond() => true; // arrow function with boolean type

List lst() => [1, 2, 3, 4, 5]; // arrow function with list type

Map myMap() => {'one': '1', 'two': '2'}; // arrow function with map type

```

```
message
20
Ahmed
true
[1, 2, 3, 4, 5]
{one: 1, two: 2}
```

```dart
void main() {
  print("main function");
  print('-' * 30);
  msg('error', '104');
  print('-' * 30);
//   var n = number();
//   print(n);
  print(number(10, 20));
  print('-' * 30);
  print(name('Ahmed'));
  print('-' * 30);
  print(result(true));
  print('-' * 30);
  print(lst([1, 2, 3]));
  print('-' * 30);
  print(mp({'username': 'GDSC'}));
}

void msg(error, n) => print(' - msg function ${n} -> ${error}');

int number(x, y) => x + y;

String name(username) => 'Hello ${username}';

bool result(bool r) => r;

List lst(List l) => l;

Map mp(var m) => m;
```

```
 main function
------------------------------
 - msg function 104 -> error
------------------------------
30
------------------------------
Hello Ahmed
------------------------------
true
------------------------------
[1, 2, 3]
------------------------------
{username: GDSC}
```

***

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

***

```dart
class google {
  var username;
  var password;
  var dept;
  var lst;

  google(a, b, c, d) {
    //constractor
    this.username = a;
    this.password = b;
    this.dept = c;
    this.lst = d;
    print('Welcome ${a} => ${b} => ${c} => ${d}');
    employees();
  }

  employees() {
    if (username == 'Ali' && password == '123') {
      if (dept == 'web') {
        dashboard_msg(dept);
      } else if (dept == 'apps') {
        dashboard_msg(dept);
      } else {
        error_msg();
      }
    } else {
      error_msg();
    }
  }

  dashboard_msg(dept) {
    print('Welcome in Dashboard ${username}');
    if (dept == 'web') {
      web();
    } else if (dept == 'apps') {
      apps();
    } else {
      error_msg();
    }
  }

  error_msg() {
    print('This is Error message !!!');
  }

  web() {
    print('- web department');
    myList();
  }

  apps() {
    print('- apps department');
    myList();
  }

  myList() {
    print('your list => ${lst}');
  }

} /* End Class */

void main() {
  var lst = [1, 2, 3, 4, 5];
  google ob1 = new google('Ali', '123', 'web', lst);
  print('-' * 30);
  google ob2 = new google('Sarah', '111', 'apps', lst);
}
```

Output:

```
Welcome Ali => 123 => web => [1, 2, 3, 4, 5]
Welcome in Dashboard Ali
- web department
your list => [1, 2, 3, 4, 5]
------------------------------
Welcome Sarah => 111 => apps => [1, 2, 3, 4, 5]
This is Error message !!!
```

