# Dalib
A library made for any mod made by the UnknownGroup.

## What does it do?
It helps ease the pain that is finding tutorials on how to make itemGroups, items, and blocks.

## Developing with Dalib
If you are using this library, do the following:

### Step 1: Adding a dependency
In your `build.gradle` write:
```groovy
// Under dependencies
dependencies {
    modImplementation("xyz.theunknowngroup:dalib:{version}")
    /* include("xyz.theunknowngroup:dalib:{version}") ; If you choose*/
}

// Under repositories 
repositories {
    maven {
        url = 'https://theunknownmaven.github.io/maven/'
    }
}
```

### Step 2: Finding your version
You can use the tags on [github](https://github.com/TheUnknownGroup/Dalib/tags) to find the version that works with your mod.

```groovy
/* For example: */
dependencies {
    modImplementation("xyz.theunknowngroup:dalib:0.0.0+1.21.11+b.3")
    /* include("xyz.theunknowngroup:dalib:0.0.0+1.21.11+b.3") ; If you choose*/
}
```

## Support
Please go check out our other mod, Unknown Mod on [Modrinth](https://modrinth.com/mod/unknown-mod), [Github](https://github.com/TheUnknownGroup/unknown-mod), and [Curseforge](https://www.curseforge.com/minecraft/mc-mods/unknown-mod-tug)! If you so choose, go check out the [patreon](https://www.patreon.com/theunknowngroup), or become a sponser [here](https://github.com/sponsors/devonk15).