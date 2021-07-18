# FirstAndroidLib
I am learning to write a library for distribution via jitpack.io


## The goal is to learn so that two steps are enough to connect the library

**Step 1.** Add the [JitPack](https://jitpack.io/#Muraveiko/FirstAndroidLib) repository to your build file. Add it in your root `/build.gradle` at the end of repositories:

```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

**Step 2.** Add the dependency in `/app/build.gradle` :

```
dependencies {
    ...
    implementation 'com.github.Muraveiko:FirstAndroidLib:0.0.1'
}
```

## First you need to
Android project with the library module

## Tag version
https://stackoverflow.com/questions/18216991/create-a-tag-in-a-github-repository

## Before implementing the library
Go to the jitpack website and click on the Get it button

## Enjoy