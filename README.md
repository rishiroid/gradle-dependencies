# gradle-dependencies

// compose navigation <br>
    implementation("androidx.navigation:navigation-compose:2.7.6")

// Retrofit for handling API requests<br>
    implementation ("com.squareup.retrofit2:retrofit:2.9.0")

// Gson converter for JSON serialization/deserialization<br>
    implementation ("com.squareup.retrofit2:converter-gson:2.9.0")

// Logging HTTTP request and response<br>
    implementation ("com.squareup.okhttp3:okhttp:4.12.0")
    implementation ("com.squareup.okhttp3:logging-interceptor:4.9.1")

// viewmodel<br>
    implementation ("androidx.lifecycle:lifecycle-viewmodel-ktx:2.6.2")

// For coroutines support<br>
    implementation("org.jetbrains.kotlinx:kotlinx-coroutines-core:1.7.3")

// KotlinX Serialization<br>
    implementation("org.jetbrains.kotlinx:kotlinx-serialization-json:1.6.0")

// Coil Image Loading<br>
    implementation("io.coil-kt:coil-compose:2.5.0")

// Dagger Hilt<br>
    implementation("com.google.dagger:hilt-android:${rootProject.extra["hiltVersion"]}")<br>
    kapt("com.google.dagger:hilt-android-compiler:${rootProject.extra["hiltVersion"]}")<br>
    kapt("androidx.hilt:hilt-compiler:${rootProject.extra["hiltCompilerVersion"]}")<br>
    implementation("androidx.hilt:hilt-navigation-compose:${rootProject.extra["hiltComposeVersion"]}")<br>
    implementation("androidx.hilt:hilt-common:${rootProject.extra["hiltCompilerVersion"]}")<br>
    kapt("com.google.dagger:hilt-compiler:${rootProject.extra["hiltVersion"]}")<br>

//Swipe refresh<br>
    implementation ("com.google.accompanist:accompanist-swiperefresh:0.27.0")
    
