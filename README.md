# gradle-dependencies

## Jetpack Compose <br>
```kotlin
   dependencies {
    // compose navigation 
    implementation("androidx.navigation:navigation-compose:2.7.6")
}
```

## Retrofit for handling API requests<br>
```kotlin
   dependencies {
   //retrofit 
   implementation ("com.squareup.retrofit2:retrofit:2.9.0")
   //Gson converter for JSON serialization/deserialization
   implementation ("com.squareup.retrofit2:converter-gson:2.9.0")
}
```

 ## Logging HTTTP request and response<br>
 ```kotlin
   dependencies {
    implementation ("com.squareup.okhttp3:okhttp:4.12.0")
    implementation ("com.squareup.okhttp3:logging-interceptor:4.9.1")
}
```
    
## viewmodel<br>
 ```kotlin
   dependencies {
    implementation ("androidx.lifecycle:lifecycle-viewmodel-ktx:2.6.2")
    //lifecycle-aware
    implementation("androidx.lifecycle:lifecycle-runtime-ktx:2.4.0")
}
```

## Coroutines<br>
```kotlin
   
    dependencies {
     // For coroutines support
     implementation("org.jetbrains.kotlinx:kotlinx-coroutines-core:1.7.3")
     implementation("org.jetbrains.kotlinx:kotlinx-coroutines-android:1.3.9")

     // KotlinX Serialization
     implementation("org.jetbrains.kotlinx:kotlinx-serialization-json:1.6.0")
}
```

## Coil Image Loading<br>
```kotlin
    dependencies{
    implementation("io.coil-kt:coil-compose:2.5.0")
}
```

## Dagger Hilt<br>
``` kotlin
    dependencies{
    implementation("com.google.dagger:hilt-android:${rootProject.extra["hiltVersion"]}")
    kapt("com.google.dagger:hilt-android-compiler:${rootProject.extra["hiltVersion"]}")
    kapt("androidx.hilt:hilt-compiler:${rootProject.extra["hiltCompilerVersion"]}")
    implementation("androidx.hilt:hilt-navigation-compose:${rootProject.extra["hiltComposeVersion"]}")
    implementation("androidx.hilt:hilt-common:${rootProject.extra["hiltCompilerVersion"]}")
    kapt("com.google.dagger:hilt-compiler:${rootProject.extra["hiltVersion"]}")
}
```

## Swipe refresh
```kotlin
   dependencies{
    implementation ("com.google.accompanist:accompanist-swiperefresh:0.27.0")
}
```
    
