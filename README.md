## Usage

**Gradle**

Add the following to your `build.gradle`:
```gradle
repositories {
    maven { url 'https://jitpack.io' }
}

dependencies {
    ...
    
    // add specific version
    implementation 'com.github.simplaapliko:design:0.6.0@aar'
    
    // or a snapshot
    // implementation 'com.github.simplaapliko:design:master-SNAPSHOT@aar'
}
```
