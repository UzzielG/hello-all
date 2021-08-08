# __Hello World__ en diferentes lenguajes

> Para todos los casos el **%** representa el **nombre del archivo**

## C
```c
#include <stdio.h>

int main()
{
    printf("Hello World in C");
    return 0;
}
```
**compile** and **run**: `gcc % -o % && ./%`

## C++
```c++
#include <iostream>
using namespace std;
int main()
{
    cout << "Hello World in C++";

    return 0;
}
```
**compile** and **run**: `g++ % -o % && ./%`

## Java
```java
class hello
{
	public static void main(String[] args)
	{
		System.out.println("Hello World in Java");
	}
}
```
**compile** and **run**: `javac % && java className`

## kotlin
```kotlin
fun main(args: Array <String>)
{
    println("Hello World in Kotlin")
}
```
**compile** and **run**: `kotlinc % -o % && ./%`

## Go
```go
package main
import "fmt"
func main() {
	fmt.Printf("Hello World in GO")
}
```
**run**: `go run %`
**compile** y **run**: `go build % && ./%`

## Python
```python
def main():
    print("Hello World in Python")

if __name__ == "__main__":
    main()
```
**run**: `python %`

## Ruby
```ruby
def main()
    puts "Hello World in Ruby"
end

main()
```
**run**: `ruby %`

## Dart
```dart
main() {
    print("Hello World in Dart");
}
```
**run**: `dart %`

## Javascript
```js
(function main(){
    console.log("Hello World in JavaScript")
}())
```
**run**: `node %`

## Perl
```perl
use strict;

print "Hello World in Perl";

exit;
```
**run**: `perl %`

## PHP
```php
<?php  
    echo "Hello World in PHP";
?>
```
**run**: `php %`
**run server**: `php -S localhost:8080`
Para acceder o ejecutar el programa o archivo php tenemos que escribir en el explorador:
```
localhost:8080/nombre_archivo.php
```

## C#
```c#
using System;

namespace sample1
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World in C#");
        }
    }
}
```
Only install .NET SDK and use dotnet
**create**: `dotnet new console -o name-proyect`
**get in**: `cd name-proyect`
**run**: `dotnet run`