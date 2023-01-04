# BlinkMyView-Kotlin-Library
BlinkMyView Kotlin Library

How to
To get a Git project into your build:

## Step 1. Add the JitPack repository to your build file
#Add it in your root build.gradle at the end of repositories:

```gradle
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
#Step 2. Add the dependency

```gradle
    dependencies {
            implementation 'com.github.dheeraj-bhadoria:BlinkMyView-Kotlin-Library:0.0.1'
    }
```
