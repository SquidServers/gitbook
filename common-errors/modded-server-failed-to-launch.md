---
description: How to resolve modpack always failing or infinitely stuck on server launching
icon: scroll-old
---

# Modded Server Failed to Launch

## Why it's failing

Sometimes, certain modpacks you can choose to install on your server may not work correctly. This usually happens because the mods in the modpack don't work well together on the server-side. Unfortunately, this is an issue that comes from the creators of the modpack, and our application can't fix it directly.

## Workaround

But don't worry, we have a workaround for you! Here's what you can do:

1. When you select a Fabric server, skip the "Modded" step. This means you won't upload or select any modpack.
2. In the "World Setup" screen, choose the Minecraft version that matches the modpack you want to use.
3. Continue through the setup process until you launch a basic Fabric server with no mods.
4. Now, download the modpack you want to use on your client (your personal computer), either from Modrinth or CurseForge.

> Its good to check if the modpack has a dedicated server pack to download as well, if there's one available then completely copy and paste over the contents of that folder.&#x20;
>
> If there's a fabric server jar in the pack then rename that to server.jar, as our application looks for this file name to run the server.

5. Upload the following folders from the modpack to the Fabric server folder:
   1. mods
   2. config
6. Finally, restart the server, and your modpack should start up!

This workaround allows you to use the modpack you want, even if it doesn't work directly with our application's modded server setup. Let us know if you have any other questions!







