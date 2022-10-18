# Hello, World!

In any programming language, it is tradition to execute a 'Hello World' program on initial setup of an environment. We can verify our setup is correct and see our output in the console if all is well.

Here's how to do that in Java:

```java
class Main {
    public static void main(String[] args) {
        System.out.println("Hello world!");
    }
}
```
Lets quickly explain what this means.

First things first, we need a **class** to store our program's information/functionality. We can name our class anything we want, as long as it matches the filename it's stored in (the file for this class is `Main.java`). The curly brackets `{` `}` outline the contents of the class.

```java
class Main {

}
```

Once we have a class for our program, we need to make a **main** method inside to tell the program what it should do when we press the run button. Every Java project needs a main method in at least one of its classes.

```java
public static void main(String[] args) {

}
```

Finally, we run this line which prints some line of text to the system console.

```java
System.out.println("Hello world!");
```

> You might be confused at the syntax used here. `public`? `static`? `void`? Don't worry, we'll cover this later in the curriculum. For now, just focus on the inside of the `main` method.

------

Try replicating the above example yourself now.

------