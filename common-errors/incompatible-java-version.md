---
description: Troubleshooting Java Version Errors
icon: java
---

# Incompatible Java Version

## Vanilla

1. Download JDK 21 from any of the links below
   1. [https://adoptium.net/temurin/releases?version=21\&os=any\&arch=any](https://adoptium.net/temurin/releases?version=21\&os=any\&arch=any)
   2. [https://www.oracle.com/java/technologies/downloads/#java21](https://www.oracle.com/java/technologies/downloads/#java21)
2. Either refresh the app by pressing `ctrl + r` or restart the app by fully closing it (ensure you close it from your tray as well)
3. Now when setting up the server, on Step 1 - The Java Selection Step, select the newly downloaded Java 21 from the list

> Still not seeing it?&#x20;
>
> Restart the app again or manually select the **FOLDER** that you downloaded the java in

4. Now click launch server again!

> Still receiving what looks like Java errors? Create a ticket using the #support-ticket channel in [our discord](https://discord.com/squidservers)

## Paper

<div align="center"><figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption><p>Excerpt from <a href="https://docs.papermc.io/paper/getting-started/">Paper's Docs</a></p></figcaption></figure></div>

## Fabric

### Determining Which Java Version to Run

| Minecraft Version | Java Version |
| ----------------- | ------------ |
| 1.17 - 1.20.4     | Java 17      |
| 1.20.5 and higher | Java 21      |

### Selected Modpack From App

The only supported java version for pre made modpacks are `Java 8, Java 16, Java 17, and Java 21`&#x20;

> Still having issues? First consult the [fabric documentation](incompatible-java-version.md#official-fabric-docs) below then open a ticket using  #support-ticket channel in [our discord](https://discord.com/squidservers)

### Official Fabric Docs

* Windows: [https://docs.fabricmc.net/players/installing-java/windows](https://docs.fabricmc.net/players/installing-java/windows)
* Mac: [https://wiki.fabricmc.net/player:tutorials:java:mac](https://wiki.fabricmc.net/player:tutorials:java:mac)
* Linux: [https://docs.fabricmc.net/players/installing-java/linux](https://docs.fabricmc.net/players/installing-java/linux)

