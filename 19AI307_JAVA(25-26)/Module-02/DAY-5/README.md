# Ex.No:2(E) ACCESS MODIFIERS

## AIM:

Show how access modifiers control the visibility and usability of class members.

## ALGORITHM :

1. Start the program.
2. Create a class with variables and methods using different access modifiers.
3. Create an object of the class in the main method.
4. Access only the members allowed by their modifiers.
5. Display the results.

## PROGRAM:

### to implement a Access Modifiers using Java

## SOURCE CODE:

```java
class Animal {
    public String name = "Elephant";
    private int age = 10;
    protected String habitat = "Forest";

    public void showName() {
        System.out.println("Name: " + name);
    }

    private void showAge() {
        System.out.println("Age: " + age);
    }

    protected void showHabitat() {
        System.out.println("Habitat: " + habitat);
    }
}

public class Main {
    public static void main(String[] args) {
        Animal obj = new Animal();
        obj.showName();
        obj.showHabitat();
    }
}
```

## OUTPUT:

```
Name: Elephant
Habitat: Forest
```

## RESULT:

Program executed successfully.

