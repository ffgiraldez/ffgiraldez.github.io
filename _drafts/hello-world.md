---
title:  "Hello World"
date:   2016-11-08 
---
Como viene siendo un clasico en el mundo de la programación, cuando alguien se enfrenta a un lenguaje nuevo, 
lo primero que le enseñan es a escribir este mitico programa, no encuentro otra forma mejor de comenzar esta andadura que escribiendolo en los lenguajes por los que he pasado a lo largo de estos años.
<!--more-->
comenzamos con el viejuno de C++

```c++
 // Hello world in C++
#include <iostream>

int main()
{
    std::cout << "Hello World!" << std::endl;
}
```

tanto en la universidad como en mi primer trabajo escribia en Java

```java
// Hello world in Java
public final class HelloWorld {
  public static void main( String args[] ) {
    System.out.println( "Hello World!" );
  }
}
```

mas adelante me adentre en el salvaje territorio web, y desarrolle tanto en PHP en backend( por aquel entonces backoffice)

```php
// Hello world in PHP
<?php
  echo 'Hello World!';
?>
```

lidiando ademas con mi odiado JS en la parte frontend( antes a esta gente de toda la vida se le llamaba webmaster)

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

por suerte para mi, esos lenguajes duraron poco tiempo, y trabaje un poco con la plataforma .NET

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

justo despues de eso, empezo mi andadura con el desarrollo mobile y especialmente Android y objective-c

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
hasta ahora, donde ando trasteando con nuevos lenguajes como swift y kotlin

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

como extra y para terminar, Scala, la FP me atrae mucho, y aunque no lo uso en el trabajo, más temprano que tarde
trasteare con el.

```scala
// Hello world in Scala
object HelloWorld extends App {
  println("Hello world!")
}
```

Estos y muchos mas han sido estraidos de [helloworldcollection.de][hello-world-collection] podeis echarle un ojo

[//]: # "links"

[hello-world-collection]: http://helloworldcollection.de/ "Hello World collection"