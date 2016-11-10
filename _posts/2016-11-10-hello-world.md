---
title:  "Hello World"
date:   2016-11-10
categories: [programming-languages]
tags: [c++, java, php, javascript, .net, c#, vb.net, objective-c, kotlin, swift, scala]

---
It's a common situation in Development's World, that when someone tackle a new programming language,
the first thing he learn is how to write a **HelloWorld** program.

And I cannot find a better way to start this blogging journey that write it in all the languages I have touched alongs those years.
<!--more-->
Let me start with the oldy **C++**.

```c++
 // Hello world in C++
#include <iostream>

int main()
{
    std::cout << "Hello World!" << std::endl;
}
```

Both in my first job and in college I usually wrote **Java** programs.

```java
// Hello world in Java
public final class HelloWorld {
  public static void main( String args[] ) {
    System.out.println( "Hello World!" );
  }
}
```

Some time after I get into the wild territory of Web development, and I work with **PHP** in the Backend side (in those time we call it Backoffice)

```php
// Hello world in PHP
<?php
  echo 'Hello World!';
?>
```

Fighting also with my loved language **JavaScript** in the Frontend side.

```html
<html>
<body>
<script language="JavaScript" type="text/javascript">
  // Hello World in JavaScript
  document.write('Hello World');
</script>
</body>
</html>
```
Luckily for me working with those languages only took place during a short period of time,
until start working with **.NET** Platform.

```c#
//Hello World in C#
class HelloWorld
{
    static void Main()
    {
        System.Console.WriteLine("Hello, World!");
    }
}
```

```vb
'Hello World in Visual Basic .NET (VB.NET)
Imports System.Console

Class HelloWorld
    Public Shared Sub Main()
        WriteLine("Hello, world!")
    End Sub
End Class
```
Just after that is when my mobile development journey begins with Android development and **Objective-C** for iOS.

```objective_c
// Hello world in Objective-C
#import <Foundation/Foundation.h>
int main (int argc, const char * argv[])
{
    NSAutoreleasePool *pool = [[NSAutoreleasePool alloc] init];
    NSLog (@"Hello, World!");
    [pool drain];
    return 0;
}
```
Until now, where I research with some new programming languages like **Swift** and **Kotlin**

```swift
// Hello world in Swift
println("Hello, world!")
```

```kotlin
// Hello world in Kotlin
fun main(args : Array) {
    println("Hello, world!")
}
```
Extra Ball: **Scala** and **Functional programming** draws my attention and although I do not use it at work, sooner rather than later I will mess with him.

```scala
// Hello world in Scala
object HelloWorld extends App {
  println("Hello world!")
}
```
These and alot more **Hell World** will be find in [helloworldcollection.de][hello-world-collection]

[//]: # "links"

[hello-world-collection]: http://helloworldcollection.de/ "Hello World collection"
