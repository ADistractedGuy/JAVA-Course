# JDK.java
<style>
button {
    background-color: #000000; /* Green */
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 20px;
    margin: 4px 2px;
    cursor: pointer;
}
</style>
<a href="C:\Users\Wolve\Desktop\Java aplications\java fundmentals\JDK.java">
    <button>JDK.JAVA</button>
</a>

This is a simple Java program that prints "functioning!" to the console. It serves as a basic example of how to create and run a Java application using the Java Development Kit (JDK) and test if the environment is set up correctly.
it's current using Eclipse Adoptium
, but you can use any JDK distribution you prefer, such as Oracle JDK, OpenJDK, or Amazon Corretto. Just make sure to set up your environment variables correctly to point to the JDK installation directory.
```java
public class JDK {
    public static void main(String[] args) {
        System.out.println("functioning!");
    }
}
```
To run this program, follow these steps:
1. Save the code in a file named `JDK.java`.
2. Open a terminal or command prompt and navigate to the directory where the file is located.
3. Compile the program using the command:
    ```
    javac JDK.java
    ```
4. Run the compiled program using the command:
    ```
    java JDK
    ``` 
You should see the output:
```
functioning!
```
This indicates that your Java environment is set up correctly and the program is running as expected.

---