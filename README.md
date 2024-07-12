# 📱 Android-Mini-Projects 🚀

A collection of bite-sized Android projects for learning and experimentation. From UI designs to API integrations, explore the world of Android development one small app at a time! Perfect for beginners and intermediate developers looking to sharpen their skills. 💡👨‍💻👩‍💻

<p align="center">
  <a href="#"><img alt="Android OS" src="https://img.shields.io/badge/OS-Android-3DDC84?style=flat-square&logo=android"></a>
  <a href="#"><img alt="Languages-Kotlin" src="https://flat.badgen.net/badge/Language/Kotlin?icon=https://raw.githubusercontent.com/binaryshrey/Awesome-Android-Open-Source-Projects/master/assets/Kotlin_Logo_icon_white.svg&color=f18e33"/></a>
  <a href="#"><img alt="Languages-Java" src="https://img.shields.io/badge/Language-Java-1DA1F2?style=flat-square&logo=java"></a>
  <a href="#"><img alt="PRs" src="https://img.shields.io/badge/PRs-Welcome-3DDC84?style=flat-square"></a>
</p>
<p align="center">
  <a href="https://github.com/kunalbandale"><img alt="Github - kunalbandale" src="https://img.shields.io/badge/GitHub-kunalbandale-181717?style=flat-square&logo=github"></a>
</p>

---

## 🗺️ Journey Map

- 🌟 **Java Refresher** Get geared up with a Java refresher.
- 🌟 **Android Installation and Setup** Learn how to install and set up Android Studio and the necessary SDKs to start developing Android applications.

  ---

## Java Refresher for Android Development

Android development primarily uses Java (or Kotlin), so having a solid understanding of Java is crucial before diving into Android development. This refresher will cover essential Java concepts, including basic syntax, object-oriented programming, and common libraries and tools used in Java development.

## Table of Contents

1.  [Introduction to Java](#introduction-to-java)
2.  [Basic Syntax](#basic-syntax)
3.  [Object-Oriented Programming (OOP)](#object-oriented-programming-oop)
4.  [Common Libraries and Tools](#common-libraries-and-tools)
5.  [Conclusion](#conclusion)


## Introduction to Java

Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a general-purpose programming language intended to let application developers write once, run anywhere (WORA), meaning that compiled Java code can run on all platforms that support Java without the need for recompilation.

## Basic Syntax

### Hello World

The simplest Java program looks like this:
```
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

### Variables and Data Types

Java supports various data types, including:

-   `int`: integer
-   `double`: double-precision floating-point number
-   `char`: single character
-   `String`: a sequence of characters
-   `boolean`: true or false

Example:
```
int number = 10;
double price = 19.99;
char letter = 'A';
String message = "Hello, Java!";
boolean isJavaFun = true;
```

### Control Flow

Java supports standard control flow statements such as `if`, `else`, `for`, `while`, and `switch`.

Example:
```
int number = 5;

if (number > 0) {
    System.out.println("Positive number");
} else if (number < 0) {
    System.out.println("Negative number");
} else {
    System.out.println("Zero");
}

for (int i = 0; i < 5; i++) {
    System.out.println(i);
}

int j = 0;
while (j < 5) {
    System.out.println(j);
    j++;
}`
```
## Object-Oriented Programming (OOP)

Java is an object-oriented language, which means it uses objects to model real-world things.

### Classes and Objects

A class is a blueprint for creating objects. An object is an instance of a class.

Example:

```
public class Dog {
    String name;
    int age;

    public Dog(String name, int age) {
        this.name = name;
        this.age = age;
    }

    public void bark() {
        System.out.println("Woof!");
    }
}

public class Main {
    public static void main(String[] args) {
        Dog myDog = new Dog("Buddy", 3);
        System.out.println(myDog.name);
        myDog.bark();
    }
}
```
### Inheritance

Inheritance allows one class to inherit the fields and methods of another class.

Example:
```
public class Animal {
    public void eat() {
        System.out.println("This animal eats food.");
    }
}

public class Dog extends Animal {
    public void bark() {
        System.out.println("Woof!");
    }
}

public class Main {
    public static void main(String[] args) {
        Dog myDog = new Dog();
        myDog.eat();  // Inherited method
        myDog.bark();
    }
}
```
### Polymorphism

Polymorphism allows objects to be treated as instances of their parent class rather than their actual class.

Example:
```
public class Animal {
    public void makeSound() {
        System.out.println("This animal makes a sound.");
    }
}

public class Dog extends Animal {
    public void makeSound() {
        System.out.println("Woof!");
    }
}

public class Main {
    public static void main(String[] args) {
        Animal myDog = new Dog();
        myDog.makeSound();  // Outputs "Woof!"
    }
}
```
### Encapsulation

Encapsulation is the concept of wrapping data and methods into a single unit, usually a class.

Example:
```
public class Person {
    private String name;
    private int age;

    public Person(String name, int age) {
        this.name = name;
        this.age = age;
    }

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public int getAge() {
        return age;
    }

    public void setAge(int age) {
        this.age = age;
    }
}
```
## Common Libraries and Tools

### Java Development Kit (JDK)

The JDK is a software development kit required to develop Java applications. It includes the Java Runtime Environment (JRE), an interpreter/loader (Java), a compiler (javac), an archiver (jar), a documentation generator (Javadoc), and other tools needed in Java development.

### Integrated Development Environments (IDEs)

Popular IDEs for Java development include:

-   **IntelliJ IDEA**: Known for its powerful features and ease of use.
-   **Eclipse**: An open-source IDE with a large community and many plugins.
-   **NetBeans**: Another open-source IDE that is simple and easy to use.

### Maven and Gradle

Maven and Gradle are build automation tools used primarily for Java projects. They manage project dependencies, build processes, and can generate documentation.

### Libraries

-   **Apache Commons**: A collection of reusable Java components.
-   **Google Guava**: A set of core libraries that include new collection types, immutable collections, a graph library, and more.
-   **JUnit**: A simple framework to write repeatable tests. It is an instance of the xUnit architecture for unit testing frameworks.

## Conclusion

This refresher covered the basics of Java that are essential for Android development. Understanding Java's syntax, object-oriented principles, and common tools will provide a strong foundation as you start learning Android development. Happy coding!

---

# Android Development Setup

This guide provides step-by-step instructions to install and set up Android Studio for developing Android applications.

## Step 1: Download Android Studio

1. Visit the [Android Studio download page](https://developer.android.com/studio/install).
2. Click on the "Download Android Studio" button.
3. Review and accept the terms and conditions to proceed with the download.

## Step 2: Install Android Studio

### Windows

1. Locate the downloaded .exe file and double-click to launch the installer.
2. Follow the setup wizard to install Android Studio:
   - Choose the installation location.
   - Select the components you want to install (Android Studio, Android SDK, Android Virtual Device).
3. Once the installation is complete, click "Next" and then "Finish" to launch Android Studio.

### macOS

1. Locate the downloaded .dmg file and double-click to open it.
2. Drag and drop the Android Studio icon into the Applications folder.
3. Open the Applications folder and launch Android Studio.
4. Follow the setup wizard to complete the installation.

### Linux

1. Locate the downloaded .zip file and extract it to a suitable location.
2. Open a terminal and navigate to the extracted directory.
3. Run the following command to launch the setup wizard:
   ```bash
   ./studio.sh

4.  Follow the setup wizard to complete the installation.

## Step 3: Configure Android Studio

1.  When you first launch Android Studio, you will be greeted by the "Welcome to Android Studio" setup wizard.
2.  Choose whether you want to import previous settings or not (if you are a new user, select "Do not import settings").
3.  Click "Next" to continue with the standard setup.
4.  Select the type of installation (Standard or Custom) and click "Next."
5.  Verify the installation settings and click "Finish" to download and install any necessary components.

## Step 4: Set Up an Android Virtual Device (AVD)

1.  Open Android Studio and go to `Tools` > `AVD Manager`.
2.  Click on "Create Virtual Device."
3.  Choose a device definition and click "Next."
4.  Select a system image for the virtual device and click "Next."
5.  Configure the AVD settings as desired and click "Finish."

## Step 5: Install Additional SDK Tools

1.  Open Android Studio and go to `Tools` > `SDK Manager`.
2.  In the SDK Platforms tab, select the Android versions you want to support and click "Apply."
3.  In the SDK Tools tab, select any additional tools you need (e.g., Android Emulator, Android SDK Build-Tools) and click "Apply."

## Conclusion

You have now successfully installed and set up Android Studio. You are ready to start developing Android applications! For more detailed guidance, refer to the [official documentation](https://developer.android.com/studio/install).

---

