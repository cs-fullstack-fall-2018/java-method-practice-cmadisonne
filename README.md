# Java_Method_Practice

For the exercises below only create the function call in the main, the function declaration, and any returns if necessary. If no return is necessary enter NONE
### Example 1
Create a function that’s passed three numbers and returns the sum

Main

* ```newFunction(number1, number2, number3);```

Function Declaration

* ```public static String newFunction(int num1, int num2, int num3){```

Function Return

* ```return (num1 + num2 + num3)```

### Example 2
Create a function that’s passed four names and returns an array of those names

Main

* ```newFunction (name1, name2, name3, name4);```

Function Header

* ```Public static ArrayList<String> newFunction (String name1, String name2, String name3, String name4){```

Function Return

* ```return newArray```

## Exercises
1. Create a function that’s passed two numbers and prints the sum.
Main: newFunc(num1, num2)
newFunc: public static void newFunc(int num1, int num2){
return NONE
}
2. Create a function that’s passed [NAME] and prints Hello [NAME].
Main: String name = "Kenn";
      greeting("Hello " + name)
newFunc: public static void newFunc("Hello " + "Kenn")
return: NONE
3. Create a function that’s passed a firstName and lastName. Return lastName comma firstName.
Main: String firstName = Lotus
      String lastName = Goddess
      System.out.println(newFunc(firstName, lastName))
newFunc: public static String newFunc(String name2," , ", String name1)
return: name1, name2
4. Create a function that’s passed a name and the number of times a user wants to print Hello [NAME]. Print Hello [NAME] that many times in the function.
Main: String name = "Lotus";
      Scanner keyboard = new Scanner(System.in);
      System.out.println("Enter a number.);
      int userInput = keyboard.newInt();
     newFunc(name, userInput)
newFunc: public static void newFunc(String name, int userInput)
return: NONE
5. Create a function that’s passed two numbers and if the user wants to add, subtract, multiply, or divide. Return the result.
Main: System.out.println(newFunc(num1, num2, userInput);
newFunc: public static Integer newFunc(int num1, int num2, String userInput){}
return: newNum
6. Create a function that’s passed an array of names and prints each item on a different line.
Main: newFunc(nameArray)
newFunc: public static void newFunc (ArrayList<String>nameArray)
return: NONE
7. Create a function that’s passed an array of names and a number that returns the item at the index of that number.
Main: System.out.println(newFunc(nameArray, returnItem)
newFunc: public static String newFunc(ArrayList<String>nameArray, int returnItem)
return: nameArray.get(returnItem)
8. Create a function that’s passed two numbers and returns the sum. Create another function that takes the sum of that function and prints “The sum is [SUM]“
Main:newFunc(sum)
     System.out.println(newFunc2("The sumn is ", sum))
newFunc:public static Integer newFunc(int sum)
return: sum
newFunc2:public static void numFunc2("The sum is ", int sum)
return:NONE
9. Create a function that’s passed two numbers and returns the sum. Create another function that takes the sum of that function and returns “The sum is [SUM]“
Main:newFunc(sum)
     newFunc2("The sum is ", sum)
newFunc:public static Integer newFunc(int sum)
return:sum
newfunc2:public static Integer newFunc2(int sum)
return:sum
10. Create a function that’s passed two names and returns an Array. Create another function that’s passed two integers and returns the difference. Create a third function that’s passed an integer array and prints it.
Main: newFunc(name1, name2)
      newfunc2(num1, num2)
      System.out.println(newFunc3(numArray))
newFunc:public static String newFunc(String firstName, String secondName)
return: nameArray
newFunc2:public static Integer newFunc2(int firstNum, int secondNum)
return: num1 - num2
newFunc3:public static void newFunc3(ArrayList<Integer>numArray)
return: NONE

**EXTRA CREDIT:**
Create the entire program. Create a function that’s passed two numbers and ask if the user wants to add, subtract, multiply, or divide. Return a string that prints the two numbers, which operation it did, and the result.
