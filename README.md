# day1-of-flutter-10-days-bootcamp

=> Day 1: Intro to Flutter, Basics of Dart
//your program always starts with main fun
void main(List<String> args){
  //print('hello world');

  //dart syntax:
  //reserve keywords (almost 52)
  int numberOne; //declare variable
  numberOne = 50; //initialize a variable
  
  int numberTwo = 60; //declare and initialize at the same time

  int sum = numberOne + numberTwo;
  print(sum);

  int subtract = numberOne - numberTwo;
  print(subtract);

  //error: int divide = numberOne / numberTwo;
  double divide = numberOne / numberTwo;
  String name = "Zeeshan Ahmed";
  print(name);
  print(name[0]);

  //loops
  String name1 = "zeeshan";
  for(int i=0; i<name1.length; i++){
    print(name1[i]);
  }
  
  int sum1 = 0;
  for(int i=0; i<10; i++){
    sum = sum + i;
  }
  print(sum);

  //conditions: to catch certain conditions
  int number1 = 10;
  int number2 = 20;


  //bool: data type having value of true or false only
  //bool value = number2 > number1; //result comes in boolean from true or falsue
  if(number1 > number2){
    print('number1 is greater than number2');
  } else{
    print("number2 is greater than number1");
  }

  //nested if-else-if
   if(number1 > number2){
    print('number1 is greater than number2');
  } else if(number1 == number2){
    print("number1 is == to number2");
  } else{
    print("number2 is greater than number1");
  }

  //Car car = Car();
  //Car car =  Car('Honda22');
  //print(car.engine.toString());

  Student std = Student();
  std.student_name = "Zeeshan";
  print(std.student_name);

}

 //OOP concepts: create classes and objects
  //classes: 
//create class
class Student{   
   String? name;
   int? age;
   String get student_name{
    return name!;
   }
   void set student_name(String name){
    this.name = name;
   }
    /*
    String engine = 'Honda23';
    void name(){
      print(engine);
    }
    void myName(String name){
      print(name);
    }
    Car(String myEngine){
      print(myEngine.toString());
    }
    */
}

