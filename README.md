# Dalib
A library made for any mod made by the UnknownGroup.

## Developing with Dalib
If you are using this library, do the following:

### Step 1: Adding a dependency
In your `build.gradle`, under `dependencies` write:
```groovy
dependencies {
    modImplementation("xyz.theunknowngroup:dalib:0.0.0")
    /* include("xyz.theunknowngroup:dalib:0.0.0") ; If you choose*/
}
```
### Step 2: Adding the repo 
In your `settings.gradle` write:
```groovy
pluginManagement {
    repositories {
        maven {
            
        }
    }
}
```