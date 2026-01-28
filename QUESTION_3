abstract class Shape {
    abstract double area();
}

interface Drawable {
    void draw();
}

class Circle extends Shape implements Drawable {
    double radius = 5;

    double area() {
        return Math.PI * radius * radius;
    }

    public void draw() {
        System.out.println("Drawing Circle");
    }
}

class Rectangle extends Shape implements Drawable {
    double length = 4, width = 6;

    double area() {
        return length * width;
    }

    public void draw() {
        System.out.println("Drawing Rectangle");
    }
}

public class Main {
    public static void main(String[] args) {
        Shape c = new Circle();
        System.out.println("Circle Area: " + c.area());

        Shape r = new Rectangle();
        System.out.println("Rectangle Area: " + r.area());
    }
}





