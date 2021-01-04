# OUTDATED USE GOPRO's https://github.com/Gopro336/Phobos_1.7.2-BUILDABLE-SRC-Non-Chinese-

This source has been checked by two people, myself and a friend. My friend did not find anything as he briefly went through the files. I have scanned and gone through every file and lib to make sure it's clean. This is **safe to use.** 

<div align="center">
  <br />
  <p>
    <a href="https://discord.gg/bR6qxjT"><img src="https://images-ext-2.discordapp.net/external/8vkrj73wbL-US7CQ2UexT4ihFbcH6AGf-USl__danmM/%3Fsize%3D256/https/cdn.discordapp.com/avatars/540212584356249601/e7f1fd88c1f50069a4066a2b74665a3f.png" width="273" alt="2b2t" /></a>
  </p>
  <br />


## Changelog: 
- Blocklag(burrow)
- Godmodule
- Media
- Antiddos
- Cosmetics
- AutoAnvil
- PingBypass
- Companion

## Opening the ClickGUI:

**There is no default bind, you can do .bind clickgui key to bind it and it will work.** 

So what I've heard so far? Apparently this one got leaked by plivid but who cares lel. Enjoy this share. xd

## Running in a Dev Environment:
```gradle
gradlew setupDecompWorkspace
gradlew runClient
```

## Compiling the client:
```gradle
gradlew setupDecompWorkspace
gradlew build
```
You will find your built jar in the directory `builds/libs`. 

## Cosmetics; Adding them to yourself:
- Go to `managers/CosmeticsManager.java`
```java
        this.cosmeticsUserMap.put("YOUR-DASHED-UUID-HERE", Arrays.asList(new ModelBase[]{Cosmetics.INSTANCE.cloutGoggles}));
```
Then compile the client. - **There are also other options like squidLauncher and SantaHatModel as well, which you can find the file.** 

## Too lazy to build the jar yourself? 

[Click here to download the release.](https://github.com/Hqrion/Phobos-1.7.2-BUILDABLE-SRC/releases/download/1.7.2/Phobos-1.7.2-release.jar)

## Credits

Thank you [Phobos Developers](https://discord.gg/bR6qxjT) for Phobos 1.7.2. 


Thank you [Ciruu](https://github.com/ciruu1) for helping to fix the client and checking it with me. 

Thank you DRAINGANG/BLADDEE LOVEr reborn for providing Phobos 1.7.2 jar. 
