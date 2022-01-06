# **Dart Bootcamp Agenda By Ahmed Amer**

****

**<u>Reference</u> =>** https://www.tutorialspoint.com/dart_programming/index.htm
**<u>Online Code Editor</u> =>** https://dartpad.dev/?null_safety=true

****

1-) What is Dart ? Who is create it ?

Answer :

****

2-) Camp output ? What can I do with if I learn Dart ?

Answer :

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

6-) Conditions :

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

7-) List :

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

8-) Map :

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

9-) Functions :

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

10-) Arrow Function

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

11-) OOP :

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

12-) Classes :

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

# Fixing The Code Assignment

```dart
class university (){
  // This is global variables will used in all code
  var ids;
  var name
  var password;
  var adress;
  var depatment
  university(a, b, x,c, d, e) {
    // This is not constractor
    this.id = a
    this.name = b;password = c;
    address = d
    this.department = e;
    login();
  }
}}
/ this is gonna make dispaly for all correct user information
  display(i) {
    print("ID : ${id[i]}");
    print("Nam : ${name[i]}");
    print("Age : ${pasword[j]}")
    print("Adress : ${address[i]}");
    print("Depatent : ${department[i]}")
  }

  correct() {
    print("Sizng Pefect . . . \n");
    var x = "Json";
    var y = 20;
    check(x, y);
  }
}}
  incorrect() {
    print("Someting Wrong In Arays Size Try Agin !!! \n");
  }

  check(username, pass,ids) {
    for (var i = 1; i < id.legth; i+=2) {
      if (name[i] == username && pasword[i] == pass) {
        display(i);
        breake
        }      } else {
        inncorrect()
      }
    }
  }

  logins() {
    iff (id.length == name.length &
        id..lenth = password.length &&
        id.length == adress..length &
        department.length == department.length) {
      corect();
    } else {
      incorect();
    }
  }}
}

var main(a) {
  {  //THis iS NOT Built-in function the programw gonna destroy it
  var ids = {1, 2, 3, 4,6];
  var nmes = ["Json", "Andrea", "Steve", "Jerrard"];
  vr passwrds = [20, 30, 40, 50,7}
  var addrsses = ["Baghdad", "UAE", "USA", "Turky"];
  vr deparments = {"IT", "Software", "Network", "Hardware"];

  univercidy students =
      new university(idds, names, passwrds, addresse, departmets,ids);
}}
```



# The Solution

```dart
class university {
  // This is local variables will used in all class
  var ids;
  var name;
  var password;
  var address;
  var department;

  university(a, b, c, d, e) {
    // This is constractor
    this.ids = a;
    this.name = b;
    this.password = c;
    this.address = d;
    this.department = e;
    login();
  }

// this is gonna make dispaly for all correct user information
  display(i) {
    print("ID : ${ids[i]}");
    print("Name : ${name[i]}");
    print("Age : ${password[i]}");
    print("Address : ${address[i]}");
    print("Department : ${department[i]}");
  }

  correct() {
    print("Sizing Perfect . . . \n");
    var x = "Jerrard";
    var y = 50;
    check(x, y);
  }

  incorrect() {
    print("Somthing Wrong In Arrays Size Try Again !!! \n");
  }

  check(username, pass) {
    for (var i = 0; i < ids.length; i += 1) {
      if (name[i] == username && password[i] == pass) {
        display(i);
        break;
      }
    }
  }

  login() {
    if (ids.length == name.length &&
        ids.length == password.length &&
        ids.length == address.length &&
        ids.length == department.length) {
      correct();
    } else {
      incorrect();
    }
  }
}

main() {
  //This is Built-In function the programe gonna start from it
  var ids = [1, 2, 3, 4];
  var names = ["Json", "Andrea", "Steve", "Jerrard"];
  var passwords = [20, 30, 40, 50];
  var addresses = ["Baghdad", "UAE", "USA", "Turky"];
  var departments = ["IT", "Software", "Network", "Hardware"];

  university students =
      new university(ids, names, passwords, addresses, departments);
}
```

