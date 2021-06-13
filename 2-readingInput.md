# Reading input

### Input

- Input is always read as a string
- Scanner class is used to read input in Java
- Scanner class can be imported by `import` statement i.e `import java.util.Scanner`

Reading Input

```java
public class Program {

    public static void(String[] args) {
        Scanner scanner = new Scanner();

        String message = scanner.nextLine();

        System.out.println(message);
    }

}
```

In the above program `nextLine()` function in `scanner` object is used to read the user input.
