# 📱 Android-Mini-Projects 🚀

A collection of bite-sized Android projects for learning and experimentation. From UI designs to API integrations, explore the world of Android development one small app at a time! Perfect for beginners and intermediate developers looking to sharpen their skills. 💡

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
- 🌟 **Creating App** Creating your first "Hello World!" app in Android Studio
- 🌟 **Activities** and **Layouts** in Android Development Using Java
- 🌟 **Multiple Activities** in Android Development Using Java
- 🌟 **ListView and RecyclerView** in Android Development Using Java
- 🌟 **Working with Databases** in Android Using Java

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


# Creating Your First Android App: Hello World!


## Step 1: Create a New Project
1. Open Android Studio.
2. Click on **"Start a new Android Studio project"**.
3. Select **"Empty Activity"** and click **Next**.
4. Configure your project:
   - **Name**: `HelloWorld`
   - **Package name**: `com.example.helloworld`
   - **Save location**: Choose a directory to save your project.
   - **Language**: Choose either **Java** or **Kotlin**.
   - **Minimum SDK**: Choose the minimum SDK level you want to support (e.g., API 21: Android 5.0 Lollipop).
5. Click **Finish** and wait for Android Studio to create your project.

## Step 2: Understand the Project Structure
- **app/src/main/java/com/example/helloworld/MainActivity.java (or MainActivity.kt)**: The main activity file.
- **app/src/main/res/layout/activity_main.xml**: The XML layout file for the main activity.
- **AndroidManifest.xml**: The manifest file that contains essential information about your app.

## Step 3: Modify the Layout
1. Open `app/src/main/res/layout/activity_main.xml`.
2. Modify the `TextView` element to display "Hello, World!" using `ConstraintLayout`.

```xml
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello, World!"
        android:textSize="24sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>
```

## Step 4: Run Your App

1.  Connect an Android device via USB or set up an emulator.
2.  Click on the **Run** button (green arrow) in Android Studio.
3.  Select your device or emulator and click **OK**.
4.  Wait for the app to build and install on the device.

## Step 5: View Your App

-   Once the app is installed, it should launch automatically, displaying "Hello, World!" on the screen.

Congratulations! You've successfully created and run your first Android app.

## Additional Resources

-   [Official Android Developer Guide](https://developer.android.com/guide)
-   [Android Studio User Guide](https://developer.android.com/studio/intro)

Feel free to explore and modify your app further. Happy coding!

---


# Activities and Layouts in Android Development Using Java

## Introduction

In Android development, activities and layouts are fundamental components. Activities represent a single screen with a user interface, while layouts define the structure of the user interface within an activity. This guide will cover the essentials of activities and layouts in Android development using Java.

## Activities

### What is an Activity?

An activity in Android is a single, focused thing that the user can do. It usually represents a single screen in an application. Activities are subclasses of the `Activity` class.

### Creating an Activity

To create a new activity, follow these steps:

1.  **Define the Activity in the Manifest:** Every activity must be declared in the `AndroidManifest.xml` file.
    
    
    ```
    <activity android:name=".MyActivity">
    <intent-filter>
        <action android:name="android.intent.action.MAIN" />
        <category android:name="android.intent.category.LAUNCHER" />
    </intent-filter>
</activity>

**Create the Activity Class:** Create a new Java class that extends `Activity` or `AppCompatActivity`.

```
package com.example.myapp;

import android.os.Bundle;
import androidx.appcompat.app.AppCompatActivity;

public class MyActivity extends AppCompatActivity {
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_my);
    }
}
```

### Activity Lifecycle

An activity goes through various states during its lifecycle. Understanding these states is crucial for managing resources and ensuring a smooth user experience.

1.  **onCreate():** Called when the activity is first created.
2.  **onStart():** Called when the activity becomes visible to the user.
3.  **onResume():** Called when the activity starts interacting with the user.
4.  **onPause():** Called when the activity is partially obscured.
5.  **onStop():** Called when the activity is no longer visible.
6.  **onDestroy():** Called before the activity is destroyed.

```
@Override
protected void onCreate(Bundle savedInstanceState) {
    super.onCreate(savedInstanceState);
    setContentView(R.layout.activity_main);
    // Initialization code here
}

@Override
protected void onStart() {
    super.onStart();
    // Code to handle the activity becoming visible
}

@Override
protected void onResume() {
    super.onResume();
    // Code to handle the activity resuming
}

@Override
protected void onPause() {
    super.onPause();
    // Code to handle the activity being partially obscured
}

@Override
protected void onStop() {
    super.onStop();
    // Code to handle the activity being no longer visible
}

@Override
protected void onDestroy() {
    super.onDestroy();
    // Code to clean up resources
}
```

## Layouts

### What is a Layout?

A layout defines the structure for a user interface in an activity. All user interface elements are built using View and ViewGroup objects. Layouts can be declared in XML or programmatically in Java.

### Declaring Layouts in XML

Layouts are typically defined in XML files located in the `res/layout` directory. Here is an example of a simple LinearLayout with a TextView and a Button:

``
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp">

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello, World!"
        android:textSize="18sp" />

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Click Me" />

</LinearLayout>
```

### Common Layout Types

1.  **LinearLayout:** Aligns its child elements in a single direction, either vertically or horizontally.

```
<LinearLayout
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical">
    <!-- Child views here -->
</LinearLayout>
```

2. **RelativeLayout:** Enables you to position child elements relative to each other or the parent.
```
<RelativeLayout
    android:layout_width="match_parent"
    android:layout_height="match_parent">
    <!-- Child views here -->
</RelativeLayout>
```
3.  **ConstraintLayout:** A more flexible and efficient layout for creating complex user interfaces.

```
<androidx.constraintlayout.widget.ConstraintLayout
    android:layout_width="match_parent"
    android:layout_height="match_parent">
    <!-- Child views here -->
</androidx.constraintlayout.widget.ConstraintLayout>
```

### Accessing Views in Java

To interact with views defined in XML, use the `findViewById()` method in your activity.

```
@Override
protected void onCreate(Bundle savedInstanceState) {
    super.onCreate(savedInstanceState);
    setContentView(R.layout.activity_main);

    TextView textView = findViewById(R.id.textView);
    Button button = findViewById(R.id.button);

    button.setOnClickListener(new View.OnClickListener() {
        @Override
        public void onClick(View v) {
            textView.setText("Button Clicked!");
        }
    });
}
```
## Conclusion

Understanding activities and layouts is essential for developing Android applications. Activities represent individual screens, while layouts define the user interface for those screens. By mastering these concepts, you can create dynamic and user-friendly Android applications using Java.

---

# Multiple Activities in Android Development Using Java

Creating and managing multiple activities is essential for building complex Android applications. Each activity provides a screen with which users can interact to perform specific tasks. This guide will cover how to create, manage, and navigate between multiple activities using Java.

## Table of Contents

1.  [Introduction to Multiple Activities](#introduction-to-multiple-activities)
2.  [Creating a New Activity](#creating-a-new-activity)
3.  [Declaring Activities in AndroidManifest.xml](#declaring-activities-in-androidmanifestxml)
4.  [Starting an Activity](#starting-an-activity)
5.  [Passing Data Between Activities](#passing-data-between-activities)
6.  [Returning Data from an Activity](#returning-data-from-an-activity)
7.  [Managing Activity Lifecycle](#managing-activity-lifecycle)
8.  [Best Practices](#best-practices)
9.  [Conclusion](#conclusion)

## Introduction to Multiple Activities
In Android, an activity represents a single screen with a user interface. Applications often have multiple activities that users navigate between. Each activity has its own lifecycle and user interface components.

## Creating a New Activity

To create a new activity in Android Studio:
1.  **Right-click on the package name in the `java` directory**.
2.  **Select New > Activity > Empty Activity**.
3.  **Name your activity** (e.g., `SecondActivity`).
4.  **Click Finish**.

This process generates a new Java file for the activity and a corresponding layout file.

Example: `SecondActivity.java`
```
package com.example.myapp;

import android.os.Bundle;
import androidx.appcompat.app.AppCompatActivity;

public class SecondActivity extends AppCompatActivity {
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_second);
    }
}
```
Example: `activity_second.xml`

```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Welcome to the Second Activity"
        android:textSize="18sp" />
</LinearLayout>


```

## Declaring Activities in AndroidManifest.xml

All activities must be declared in the `AndroidManifest.xml` file. When you create a new activity in Android Studio, it automatically updates the manifest file.

Example:

```
<application
    ...>
    <activity android:name=".MainActivity">
        <intent-filter>
            <action android:name="android.intent.action.MAIN" />
            <category android:name="android.intent.category.LAUNCHER" />
        </intent-filter>
    </activity>
    <activity android:name=".SecondActivity"></activity>
</application>
```

## Starting an Activity

To start a new activity, use an explicit `Intent`. An `Intent` is a messaging object that you can use to request an action from another app component.

Example: Starting `SecondActivity` from `MainActivity`.

In `MainActivity.java`:

```
package com.example.myapp;

import android.content.Intent;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        Button button = findViewById(R.id.button);
        button.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                Intent intent = new Intent(MainActivity.this, SecondActivity.class);
                startActivity(intent);
            }
        });
    }
}
```
In `activity_main.xml`:

```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp">

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Go to Second Activity" />
</LinearLayout>

```

## Passing Data Between Activities

You can pass data between activities using `Intent` extras.

Example: Passing data from `MainActivity` to `SecondActivity`.

In `MainActivity.java`:
```
Intent intent = new Intent(MainActivity.this, SecondActivity.class);
intent.putExtra("KEY_NAME", "Hello, Second Activity!");
startActivity(intent);
```

In `SecondActivity.java`:

```
@Override
protected void onCreate(Bundle savedInstanceState) {
    super.onCreate(savedInstanceState);
    setContentView(R.layout.activity_second);

    String message = getIntent().getStringExtra("KEY_NAME");

    TextView textView = findViewById(R.id.textView);
    textView.setText(message);
}
```

In `activity_second.xml`:

```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp">

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Welcome to the Second Activity"
        android:textSize="18sp" />
</LinearLayout>
```

## Returning Data from an Activity

Sometimes you need to return data from a child activity to the parent activity. To achieve this, use `startActivityForResult()` and `setResult()` methods.

Example: Returning data from `SecondActivity` to `MainActivity`.

In `MainActivity.java`:

```
public class MainActivity extends AppCompatActivity {
    private static final int REQUEST_CODE = 1;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        Button button = findViewById(R.id.button);
        button.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                Intent intent = new Intent(MainActivity.this, SecondActivity.class);
                startActivityForResult(intent, REQUEST_CODE);
            }
        });
    }

    @Override
    protected void onActivityResult(int requestCode, int resultCode, Intent data) {
        super.onActivityResult(requestCode, resultCode, data);
        if (requestCode == REQUEST_CODE && resultCode == RESULT_OK) {
            String result = data.getStringExtra("result");
            TextView textView = findViewById(R.id.textViewResult);
            textView.setText(result);
        }
    }
}
```

In `SecondActivity.java`:

```
public class SecondActivity extends AppCompatActivity {
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_second);

        Button button = findViewById(R.id.buttonReturn);
        button.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                Intent resultIntent = new Intent();
                resultIntent.putExtra("result", "Data from Second Activity");
                setResult(RESULT_OK, resultIntent);
                finish();
            }
        });
    }
}
```

In `activity_second.xml`:
```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp">

    <Button
        android:id="@+id/buttonReturn"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Return Data" />
</LinearLayout>
```
In `activity_main.xml`:

```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp">

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Go to Second Activity" />

    <TextView
        android:id="@+id/textViewResult"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Result will be displayed here"
        android:textSize="18sp"
        android:paddingTop="20dp" />
</LinearLayout>

```

## Managing Activity Lifecycle

Understanding the activity lifecycle is crucial for managing resources and ensuring a smooth user experience. The main lifecycle methods are:

1.  **onCreate()**: Called when the activity is first created.
2.  **onStart()**: Called when the activity becomes visible to the user.
3.  **onResume()**: Called when the activity starts interacting with the user.
4.  **onPause()**: Called when the activity is partially obscured by another activity.
5.  **onStop()**: Called when the activity is no longer visible to the user.
6.  **onDestroy()**: Called before the activity is destroyed.
7.  **onRestart()**: Called after the activity has been stopped, just before it is started again.

Example:
```
public class MainActivity extends AppCompatActivity {
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        // Initialization code
    }

    @Override
    protected void onStart() {
        super.onStart();
        // Code to execute when the activity becomes visible
    }

    @Override
    protected void onResume() {
        super.onResume();
        // Code to execute when the activity starts interacting with the user
    }

    @Override
    protected void onPause() {
        super.onPause();
        // Code to execute when the activity is partially obscured
    }

    @Override
    protected void onStop() {
        super.onStop();
        // Code to execute when the activity is no longer visible
    }

    @Override
    protected void onDestroy() {
        super.onDestroy();
        // Code to execute before the activity is destroyed
    }

    @Override
    protected void onRestart() {
        super.onRestart();
        // Code to execute after the activity has been stopped, just before it is started again
    }
}
```
## Best Practices

1.  **Minimize activity transitions**: Avoid unnecessary activity transitions to improve performance and user experience.
2.  **Use fragments for reusable UI components**: If you have reusable UI components, consider using fragments instead of multiple activities.
3.  **Manage the back stack**: Understand how activities are managed in the back stack and use appropriate flags to control navigation.
4.  **Optimize resource usage**: Release resources in lifecycle methods to avoid memory leaks.
5.  **Handle configuration changes**: Use `onSaveInstanceState()` and `onRestoreInstanceState()` to save and restore state during configuration changes.

## Conclusion

Understanding how to create, manage, and navigate between multiple activities is fundamental for Android development. By following best practices and effectively managing the activity lifecycle, you can build robust and user-friendly applications. This guide provides a comprehensive overview, but always refer to the official [Android developer documentation](https://developer.android.com/guide/components/activities/intro-activities) for more detailed information and updates.

---


# ListView and RecyclerView in Android Development Using Java

This guide covers how to use `ListView` and `RecyclerView` in Android development. Both are essential for displaying lists of data in a structured and efficient manner.

## Table of Contents

1.  [Introduction](#introduction)
2.  [ListView](#listview)
    -   [Creating a ListView](#creating-a-listview)
    -   [Setting up the Adapter](#setting-up-the-adapter)
    -   [Handling Item Clicks](#handling-item-clicks)
3.  [RecyclerView](#recyclerview)
    -   [Creating a RecyclerView](#creating-a-recyclerview)
    -   [Setting up the Adapter and ViewHolder](#setting-up-the-adapter-and-viewholder)
    -   [Handling Item Clicks](#handling-item-clicks-1)
4.  [Comparison and Best Practices](#comparison-and-best-practices)
5.  [Conclusion](#conclusion)

## Introduction

Both `ListView` and `RecyclerView` are used for displaying collections of data in a vertically scrolling list. `RecyclerView` is a more advanced and flexible version of `ListView`.

## ListView

### Creating a ListView

1.  **Create a new Activity** if you haven't already.
2.  **Add a ListView** to your activity's layout file.

Example: `activity_main.xml`

```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp">

    <ListView
        android:id="@+id/listView"
        android:layout_width="match_parent"
        android:layout_height="match_parent" />
</LinearLayout>
```
### Setting up the Adapter

1.  **Create a data source** (e.g., an array of strings).
2.  **Create an ArrayAdapter** to bind the data to the ListView.

In `MainActivity.java`:

```
package com.example.myapp;

import android.os.Bundle;
import android.view.View;
import android.widget.AdapterView;
import android.widget.ArrayAdapter;
import android.widget.ListView;
import android.widget.Toast;
import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        ListView listView = findViewById(R.id.listView);
        String[] values = new String[] { "Android", "iOS", "Windows", "Linux", "macOS" };

        ArrayAdapter<String> adapter = new ArrayAdapter<>(this,
                android.R.layout.simple_list_item_1, android.R.id.text1, values);

        listView.setAdapter(adapter);
    }
}



```
### Handling Item Clicks

You can handle item clicks by setting an `OnItemClickListener` on the `ListView`.

In `MainActivity.java`:
```
listView.setOnItemClickListener(new AdapterView.OnItemClickListener() {
    @Override
    public void onItemClick(AdapterView<?> parent, View view, int position, long id) {
        String item = (String) parent.getItemAtPosition(position);
        Toast.makeText(MainActivity.this, "Clicked: " + item, Toast.LENGTH_SHORT).show();
    }
});

```

## RecyclerView

### Creating a RecyclerView

1.  **Add RecyclerView dependency** to your `build.gradle` file:

```
dependencies {
    implementation 'androidx.recyclerview:recyclerview:1.2.1'
}
```
2.  **Add a RecyclerView** to your activity's layout file.

Example: `activity_main.xml`

```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp">

    <androidx.recyclerview.widget.RecyclerView
        android:id="@+id/recyclerView"
        android:layout_width="match_parent"
        android:layout_height="match_parent" />
</LinearLayout>
```
### Setting up the Adapter and ViewHolder

1.  **Create a layout file** for individual items in the RecyclerView.

Example: `item_view.xml`

```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:orientation="vertical"
    android:padding="16dp">

    <TextView
        android:id="@+id/textView"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:textSize="18sp" />
</LinearLayout>
```
2.  **Create a ViewHolder class**.
```
package com.example.myapp;

import android.view.LayoutInflater;
import android.view.View;
import android.view.ViewGroup;
import android.widget.TextView;
import androidx.annotation.NonNull;
import androidx.recyclerview.widget.RecyclerView;
import java.util.List;

public class MyAdapter extends RecyclerView.Adapter<MyAdapter.ViewHolder> {
    private List<String> values;

    public static class ViewHolder extends RecyclerView.ViewHolder {
        public TextView textView;
        public ViewHolder(View view) {
            super(view);
            textView = view.findViewById(R.id.textView);
        }
    }

    public MyAdapter(List<String> values) {
        this.values = values;
    }

    @NonNull
    @Override
    public MyAdapter.ViewHolder onCreateViewHolder(@NonNull ViewGroup parent, int viewType) {
        View view = LayoutInflater.from(parent.getContext())
                .inflate(R.layout.item_view, parent, false);
        return new ViewHolder(view);
    }

    @Override
    public void onBindViewHolder(@NonNull ViewHolder holder, int position) {
        String value = values.get(position);
        holder.textView.setText(value);
    }

    @Override
    public int getItemCount() {
        return values.size();
    }
}
```

3.  **Set up the RecyclerView** in your activity.

In `MainActivity.java`:

```
package com.example.myapp;

import android.os.Bundle;
import androidx.appcompat.app.AppCompatActivity;
import androidx.recyclerview.widget.LinearLayoutManager;
import androidx.recyclerview.widget.RecyclerView;
import java.util.Arrays;
import java.util.List;

public class MainActivity extends AppCompatActivity {
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        RecyclerView recyclerView = findViewById(R.id.recyclerView);
        recyclerView.setLayoutManager(new LinearLayoutManager(this));

        List<String> values = Arrays.asList("Android", "iOS", "Windows", "Linux", "macOS");
        MyAdapter adapter = new MyAdapter(values);
        recyclerView.setAdapter(adapter);
    }
}

```
### Handling Item Clicks

To handle item clicks in a `RecyclerView`, you can modify the `ViewHolder` to include a click listener.

In `MyAdapter.java`:
```
public class MyAdapter extends RecyclerView.Adapter<MyAdapter.ViewHolder> {
    private List<String> values;

    public static class ViewHolder extends RecyclerView.ViewHolder implements View.OnClickListener {
        public TextView textView;
        private ItemClickListener itemClickListener;

        public ViewHolder(View view, ItemClickListener itemClickListener) {
            super(view);
            textView = view.findViewById(R.id.textView);
            this.itemClickListener = itemClickListener;
            view.setOnClickListener(this);
        }

        @Override
        public void onClick(View v) {
            itemClickListener.onItemClick(getAdapterPosition());
        }
    }

    public interface ItemClickListener {
        void onItemClick(int position);
    }

    private ItemClickListener itemClickListener;

    public MyAdapter(List<String> values, ItemClickListener itemClickListener) {
        this.values = values;
        this.itemClickListener = itemClickListener;
    }

    @NonNull
    @Override
    public MyAdapter.ViewHolder onCreateViewHolder(@NonNull ViewGroup parent, int viewType) {
        View view = LayoutInflater.from(parent.getContext())
                .inflate(R.layout.item_view, parent, false);
        return new ViewHolder(view, itemClickListener);
    }

    @Override
    public void onBindViewHolder(@NonNull ViewHolder holder, int position) {
        String value = values.get(position);
        holder.textView.setText(value);
    }

    @Override
    public int getItemCount() {
        return values.size();
    }
}

```
In `MainActivity.java`:
```
MyAdapter adapter = new MyAdapter(values, new MyAdapter.ItemClickListener() {
    @Override
    public void onItemClick(int position) {
        String item = values.get(position);
        Toast.makeText(MainActivity.this, "Clicked: " + item, Toast.LENGTH_SHORT).show();
    }
});
recyclerView.setAdapter(adapter);
```

## Comparison and Best Practices

-   **ListView**:
    
    -   Simpler to implement for basic lists.
    -   Less flexible and performant for large or complex data sets.
-   **RecyclerView**:
    
    -   More efficient and flexible.
    -   Supports different view types and more complex layouts.
    -   Preferred for modern Android development.

**Best Practices**:

-   Use `RecyclerView` for new projects or when you need more flexibility and performance.
-   Optimize your layouts and avoid nested views to enhance performance.
-   Use `DiffUtil` in `RecyclerView` for efficient data updates.

## Conclusion

Both `ListView` and `RecyclerView` are powerful tools for displaying data in Android applications. While `ListView` is simpler, `RecyclerView` offers more features and better performance. Choose the one that fits your needs and follow best practices for optimal performance and user experience. For more details, refer to the official [Android developer documentation](https://developer.android.com/guide/topics/ui/layout/recyclerview).

---
