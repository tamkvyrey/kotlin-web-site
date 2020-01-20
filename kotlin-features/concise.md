``` kotlin
/*
 Create a POJO with getters, setters, `equals()`, `hashCode()`, `toString()` and `copy()` in a single line:
*/

data class Customer(val name: String, val email: String, val company: String)
```

``` kotlin
// Or filter a list using a lambda expression:

val positiveNumbers = list.filter { it > 0 }
```

``` kotlin
// Want a singleton? Create an object:

object ThisIsASingleton {
    val companyName: String = "JetBrains"
}
```