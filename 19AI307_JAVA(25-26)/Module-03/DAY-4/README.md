# Ex.No:3(D) INTERFACE

## AIM:

Demonstrate how an interface defines behaviors that a class must implement.

## ALGORITHM :

1. Start the program.
2. Create an interface with one or more abstract methods.
3. Create a class that implements the interface.
4. Create an object of that class inside the main method.
5. Call the implemented method and display the output.

## PROGRAM:

### to implement a Interface using Java

## SOURCE CODE:

```java
interface Animal {
    void sound();
}

class Dog implements Animal {
    public void sound() {
        System.out.println("Dog barks");
    }
}

public class Main {
    public static void main(String[] args) {
        Animal d = new Dog();
        d.sound();
    }
}
```

## OUTPUT:

```
Dog barks
```

## RESULT:

Program executed successfully.

