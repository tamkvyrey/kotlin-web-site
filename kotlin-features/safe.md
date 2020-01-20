``` kotlin
/*
 Get rid of those pesky NullPointerExceptions, you know, The Billion Dollar Mistake
*/

var output: String
output = null   // Compilation error
```

``` kotlin
// Kotlin protects you from mistakenly operating on nullable types

val name: String? = null    // Nullable type
println(name.length())      // Compilation error
```

``` kotlin
// And if you check a type is right, the compiler will auto-cast it for you

fun calculateTotal(obj: Any) {
    if (obj is Invoice)
        obj.calculateTotal()
}
```