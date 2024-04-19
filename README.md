- 1. 

Given:


public class Course {

  public static void main(String[] args) {

    [x]double courseFee = 1000.0;

    float percentage = 5.0f;

    // line n1

    newFee = courseFee * percentage;

    System.out.println(newFee);

  }

}


Which statement, when inserted at line n1, enables the Course class to compile?

- int newFee;
- [x] double newFee;
- long newFee;
- float newFee;

______________________________________________________________________

- 2. 

Given:

 

public class TestFinal {

  final int 1 = 5;

  static void modify (TestFinal test) {

    test.1 = 99;

  }

  public static void main(String[] args) {

    final TestFinal tf = new TestFinal();

    modify(tf);

    System.out.println(tf.1);

  }

}

 

What is the result?

The are 3 correct answers

-[x] A compilation error occurs in the modify method
- 99
- 5
- [x]A compilation error occurs in the main method
- [x]First compilation error occurs in final int 1 = 5 declaration

__________________________________________________________________________

3. 

How many of the following lines compile?

 

bool b = null;

Bool bl = null;

int i = null;
Integer in = null;

String string = null;

The are 1 correct answers

- None
- One
-[x] Two
- Three
- Four
- Five

____________________________________________________________________________

- 4. 

Which of these assignments are valid?

The are 3 correct answers

[x]long g = 012;
int i = (int) false;
float d = 0 * 1.5;
[x]short s = 12;
[x]float f = -123;

_________________________________________________________________________________


- 5. 

Which of the following declarations are valid?

The are 3 correct answers

float f1 = 43e1;
[x]float f2 = -1;
float f3 = 1.0;
[x]float f4 = 4;
[x]float f5 = 0x0123;

__________________________________________________________________________________
- 6. 

Which statement is true about primitive variables?

The are 1 correct answers

[x]They can be compared with the == operator.
They can be compared with the equals method only.
They cannot be compared.
They can be compared with the compareTo method only.

____________________________________________________________________________________

- 7. 

Given:


public static void main(String[] args) {

 int a, b, c = 0;

 int a, b, c;

 int g, int h, int i = 0;

 int d, e, F;

 int k, l, m; = 0;

}


Which declarations will compile?

The are 2 correct answers

int g, int h, int i = 0;
[x]int a, b, c = 0;
int k, l, m; = 0;
int a, b, c;
[x]int d, e, F;

___________________________________________________________________________________________________________________

- 8. 

Which of the following is illegal?

The are 1 correct answers

double d = 320;
char c = 320;
float f = 320;
[x]byte b = 320;
float f = 22.0f/7.0f;

__________________________________________________________________________________________________-

- 9. 

Given:


public class Test {

 int var1; //line n1

 public static void main(String[] args) {

  int var2; // line n2

  Test obj = new Test();

  int var3 = var2 + obj.var1;

  System.out.println(var3);

 }

}


What is the result?

The are 1 correct answers

Compilation fails. To make it compile, replace line n1 with var1 = 0;
[x]Compilation fails. To make it compile, replace line n2 with var2 = 0
Nothing is printed

_______________________________________________________

- 10. 

Which statement is valid?

The are 1 correct answers

int 2 totalScore = 0;
int total&amp;score = 0;
[x]int totalScore2 = 0;
int total score = 0;

_______________________________________________-


- 11. 

Which is equivalent to var q = 5.0f;?

The are 1 correct answers

[x]float q = 5.0f;
Float q = 5.0f;
double q = 5.0f;
Double q = 5.0f;
Object q = 5.0f;
None of the above

________________________________________________--

 - 12. 

 Which of the given code fragments will not compile (select all that apply)

The are 3 correct answers

byte a = 128;
byte b = 1;
b = b + 1;
byte c = 100;
c *= 1;
int i = 128;

__________________________________________________________

- 13. 

1. Implicit type casting is storing smaller data type into large data type.
2. Explicit type casting is storing larger data type value into smaller data type.
Are both of these sentences True or False.

The are 1 correct answers

Only 1 is true
Only 2 is true
Both are true
none of them are true
1 is false, 2 cannot predict
1 cannot predict, 2 is false

- 14. 


Which can fill in the blank? (Choose two.)
public void math() { _____ pi = 3.14; }

The are 2 correct answers

byte
[x]double
float
short
[x]var
None of the above


- 15. 

What will the following code print?


public class TestClass {

 public static void main(String[] args) {

  int x = 13; //line 1

  long y = 13; //line 2

  float z = 3.234567f; //line 3

  System.out.println(x + “ “ +y+ “ “ +z);

 }

}

The are 1 correct answers

- Compilation error at line 3
- 10003 103 3.234567
- Compilation error at line 1
- Compilation error at line 1 and line 3
- Compilation error at line 2
- [x] 13 13 3.234567 

- 16. 
How many of the following lines contain a compiler error?


double num1= 2_.718;

double num2 = 2._718;

double num3 = 2.7_1_8;

double num4 = _2.718;

The are 1 correct answers

1
2
[x]3
4
None of the above

- 17. 

Given the file Magnet.java shown, which of the marked lines can you

independently insert the line

var color;

into and still have the code compile?


// line 1 public class Magnet {
// line 2 public void attach() {

// line 3 }
// line 4 }

The are 1 correct answers

2
3
2 and 3
1,2,3,4
[x]None
All of the above

- 18. 

Given the code fragment:

At which line does a compilation error occur?

The are 1 correct answers

float fValue = 120;
int iValue = fValue;
double dValue = fValue;
long LValue = fValue;


lines 5 and 7
line 7
[x]lines 6 and 8
line 5



- 19. 
What will be the result of attempting to compile and run the following class?

 

public class TestClass {

  public static void main(String[] args) {

    int i, j, k;
    i = j = k = 9;

    System.out.println(i);

  }
}

 

Please select 2 options:

The are 2 correct answers

[x]All the variables will get a value of 9
The code will not compile as j  is being used before getting initialized
The code will not compile as j and i are being used before getting initialized
The code will not compile because unlike in c++, operator = cannot be chained i.e. a =  b = c = d is invalid
[x]The code will compile correctly and will display 9 when run


- 20. 

Given the following code:


public class TestClass {

 public static void main(String[] args) {

  //INSERT CODE HERE

  System.out.println(x);

 }

}


What can be inserted in the above code so that it will compile and run without any problem?

The are 3 correct answers

- double d = 0b10_000D;
- [x]long x = 0b10000L;
- float x = 0b20_000;
- float x = 0b10_000f;
- [x]double x = 0xb10_000;
- [x]float x = 0b10_000;




_______________________________________________________

- 21. 

What will be the output of the following code?


package com.company;
public class Main {
  public static void main(String[] args){
    System.out.print((char) 65);
  }
}

The are 1 correct answers

compile-time error
runtime error
- 1
- [x]A
- B

________________________________________________-


- 22. 

The default value assigned to a double data type in Java?
The are 1 correct answers

- null
- undefined
- none of these
- Zero
- - 0.0f
[x]0.0d

__________________

- 23. 

After the execution of the below program what will be the value present inside the “sum” variable? package com.example;
The are 1 correct answers

package com.example;
import java.lang.*;

public class Main {
    public static void main(String[] args) {
        float arr[] = {4.2f, 5.1f, 1.6f};
        int sum = 0;
        Boolean bool = Boolean.FALSE;

        for (int i = 0; i < arr.length; i++) {
            sum += (int) arr[i];  
        }
        sum = sum / 10; 
    }
}


- [x]1
- TRUE
- 4
- 5
- Zero


- 24. 

Which of the following are primitive data types in JAVA?
The are 1 correct answers

- [x]All of these
- None of these
- boolean
- char
- short
- long

- 25. 

The default value assigned to an object data type in Java?
The are 1 correct answers



- [x]null
- none
- undefined
- NaN
- Zero


- 26. 

What will be the output of the following code?


package com.company;
public class Main {
  public static void main(String[] args){
    System.out.print((char) 65);
  }
}

The are 1 correct answers

compile-time error
runtime error
- 1
- [x]A
- B

- 27. 

What of the following statements are incorrect?
1. A value of a final variable cannot be changed after initialization.

2. A final method can be overridden

3. A final class is a class that cannot be sub classed

The are 1 correct answers

- 1 and 3
- Only 1
- 1 and 2
- [x]Only 2
- 2 and 3
- Only 3

- 28. 

Which of the following is an invalid code snippet?
The are 1 correct answers

- [x]long a, short b;
- int s=10; double m = 50;
- All are invalid
- short c, d;
- All are valid
- float u = 5, v = 7.5F;

- 29. 

Is there a chance of data loss when performing implicit type casting?
The are 1 correct answers

[x]No
Yes

- 30. 

What are the different types of typecasting available in Java?
The are 2 correct answers

- linear
- unordered
- binary
- [x]implicit
- ordered
- [x]explicit

- 31. 
What is the output of the following program?


package com.example;
public class Main {
  public static void main(String[] args) {
    float s = 20.5f;
    int a = (int)s;
    System.out.println(a+30.5);
  }
}

The are 1 correct answers

- [x]50.5
- 20
- 20.5
- Compile time error
- 50
- 51

- 32. 

What is the output of the following program?
The are 1 correct answers

public class Main {

    public static void main(String[] args) {

    int a = 72;
    int b = 105;
    char x = (char) a;
    char y = (char) b;

    System.out.println(x+""+y);

    }   

}

- 72
- hi
- 72105
- hI
- [x]Hi


- 33. 

Which statements are true, false, or cannot predict?
1. Implicit type casting is storing smaller data type into large data type.

2. Explicit type casting is storing larger data type value into smaller data type.

The are 1 correct answers

- none of them are true
- Only 1 is true
- [x]Both are true
- Only 2 is true
- 1 cannot predict, 2 is false
- 1 is false, 2 cannot predict

- 34. 

Which of the is not a primitive data type in Java? Choose all that apply
The are 4 correct answers

- [x] Strings
- [x] Arrays
- [x] Integer
float
- [x] Character
int


- 35. 

The final keyword in Java can be used with which of the following in Java?
The are 1 correct answers

All of these
- [x] class
- [x] variable
Objects
- [x] method
None of these

- 36. 

Suggest the anticipated result of the provided  code?
The are 1 correct answers

package com.company;

public class Main {
    public static void main(String[] args) {
        int b = 5;
        final int a = --b + b--;  
        b--;  // Decrement b one more time
        System.out.print(a); 
    }
}

- [x] 8
- 6
- 2
- 5
- Zero
- 7

- 37. 

Is there a chance of data loss when performing explicit type casting?
The are 1 correct answers

No
- [x] Yes








