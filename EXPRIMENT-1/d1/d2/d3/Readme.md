# EXPERIMENT-1
## 1a) Title: Displaying Default Primitive Types
## Source Code:
```# EXPERIMENT-1
## 1a) Title: Displaying Default Primitive Types
## Source Code:
```java
class DisplayDefaultPrimitiveType {
  int printInt;
  double printDouble;
  float printFloat;
  char printChar;
  long printLong;
  boolean printBoolean;
  public static void main(String[] args) {
    DisplayDefaultPrimitiveType dpt = new DisplayDefaultPrimitiveType();
    System.out.println("Default value of int: " + dpt.printInt);
    System.out.println("Default value of double: " + dpt.printDouble);
    System.out.println("Default value of float: " + dpt.printFloat);
    System.out.println("Default value of char: " + dpt.printChar);
    System.out.println("Default value of long: " + dpt.printLong);
    System.out.println("Default value of boolean: " + dpt.printBoolean);
  }
}
```
## Output:
![output](primitive.png)

## 1b) Title: To Find The Roots of Quadratic Equations
## Source Code:
```java
import java.util.Scanner;
class QuadraticEquationSolution {
  public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);
    System.out.print("Enter value of a: ");
    double a = sc.nextDouble();
    System.out.print("Enter value of b: ");
    double b = sc.nextDouble();
    System.out.print("Enter value of c: ");
    double c = sc.nextDouble();
    double D = (b*b)-(4*a*c);
    if(D>0) {
      double x1 = (-b+Math.sqrt(D))/(2*a);
      double x2 = (-b-Math.sqrt(D))/(2*a);
      System.out.println("the real roots are: ");
      System.out.println("x1 = " + x1);
      System.out.println("x2 = " + x2);
    }
    else if(D==0) {
      double Y = -b/(2*a);
      System.out.println("the roots are equal: ");
      System.out.println("Y = " + Y);
    }
    else if(D<0) {
      double Z1 = -b/(2*a);
      double img1 = Math.sqrt(-D)/(2*a);
      System.out.println("the complex roots are: ");
      System.out.println("the complex roots are of root1: " + Z1 + "+" + img1 + "i" );
      System.out.println("the complex roots are of root2: " + Z1 + "-" + img1 + "i" );
    }
    else {
      System.out.println("invalid choice.");
    }

  }
}
```
## Output:
![case1](d1)

![case2](d2)

![case3](d3)

