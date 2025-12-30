# EXPERIMENT-2:
## 2a) Title: Find Area and Perimetre of given Rectangle
## Source Code:
```java
class Rectangle {
  double length;
  double breadth;
  double area() {
    return length*breadth;
  }
  double perimeter() {
    return 2*(length + breadth);
  }
}
class main {
  public static void main(String[] args) {
    Rectangle rect = new Rectangle();
    rect.length = 10;
    rect.breadth = 5;
    double area = rect.area();
    double perimeter = rect.perimeter();
    System.out.println("Area of given rectangle: " + area);
    System.out.println("Perimeter of given rectangle: " + perimeter);
  }
}
```
## Output:
![output](r1.png)
