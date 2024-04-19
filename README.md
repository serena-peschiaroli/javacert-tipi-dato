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
- Two
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

[x]float f1 = 43e1;
[x]float f2 = -1;
float f3 = 1.0;
[x]float f4 = 4;
float f5 = 0x0123;

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
The code will compile correctly and will display 9 when run


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

double d = 0b10_000D;
[x]long x = 0b10000L;
float x = 0b20_000;
float x = 0b10_000f;
[x]double x = 0xb10_000;
[x]float x = 0b10_000;







