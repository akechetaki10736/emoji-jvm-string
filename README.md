# emoji-jvm-string

> Let's access emoji like Enum and print it easily 😎

* Java
```java
System.out.printf("Damn it! Who writes these shit %s%s%s%n",Emoji.PILE_OF_POO,Emoji.PILE_OF_POO,Emoji.PILE_OF_POO);
```

* Kotlin
```kotlin
println("Damn it! Who writes these shit ${Emoji.PILE_OF_POO}${Emoji.PILE_OF_POO}${Emoji.PILE_OF_POO}")
```

<img width="404" alt="CleanShot 2022-05-26 at 13 32 31@2x" src="https://user-images.githubusercontent.com/6296280/170422970-f5a9f4bc-21c9-4a3d-8eac-2c184105dbd4.png">

# For Gradle Dependency

```groovy
repositories {
    maven { url "https://jitpack.io" }
}

dependencies {
    implementation "com.github.PureFuncInc:emoji-jvm-string:1.0.0"
}
```

# For Gradle Kotlin Dependency

```kotlin
repositories {
    maven {
        url = uri("https://jitpack.io")
    }
}

dependencies {
    implementation("com.github.PureFuncInc:emoji-jvm-string:1.0.0")
}
```
