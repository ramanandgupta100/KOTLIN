# IF ELSE Statements

#### <mark style="color:$danger;">SAME AS JAVASCRIPT</mark>



### `if` statement

```kotlin
fun main(){

    val age = 20;

    if (age > 18){
        println("You can vote");
    }

    if (age < 18){
        println("You cannot vote");
    }

}
```

### `if else` statement

```kotlin
fun main(){

    val age = 20;

    if (age > 18){
        println("You can vote");
    } else {
        println("You cannot vote");
    }

}
```

### `if, else if, else` statement

```kotlin
fun main(){

    val age = 20;

    if (age > 18){
        println("You can vote");
    } else if (age < 18) {
        println("You cannot vote");
    } else {
        println("Something went wrong. Please try again");
    }

}
```
