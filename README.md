[![EssentialsX](https://i.imgur.com/CP4SZpB.png)](https://essentialsx.github.io)

[![Build Status](https://travis-ci.org/Telesphoreo/TF-EssentialsX.svg?branch=1.13)](https://travis-ci.org/Telesphoreo/TF-EssentialsX)

[<img alt="Discord" src="https://img.shields.io/badge/-Chat_on_Discord-7289DA.svg?logo=discord&style=flat-square&logoColor=white" height=32>](https://discord.gg/casfFyh)

[<img alt="Patreon" src="https://img.shields.io/badge/-Support_on_Patreon-F96854.svg?logo=patreon&style=flat-square&logoColor=white" height=32>](https://www.patreon.com/essentialsx)

This is a fork of Essentials called EssentialsX.

If you are using this, do **NOT** ask Essentials for support.

The official upstream repository is at https://github.com/Essentials/Essentials.


Why use EssentialsX?
--------

EssentialsX is an unofficial continuation of EssentialsX, updated to support modern Minecraft and Spigot versions. It provides several performance enhancements and fixes that are currently not available in Essentials and Spigot-Essentials. [For more details, see the wiki.](https://essentialsx.github.io/#/Improvements)

EssentialsX is almost a completely drop-in replacement for Essentials. However, it has different requirements:

* **EssentialsX requires [Vault](http://dev.bukkit.org/bukkit-plugins/vault/) to enable chat prefix/suffixes and group support if you have a supported permissions plugin.** We recommend using [LuckPerms](https://luckperms.github.io).

* **If you have an unsupported permissions plugin but still wish to use wildcards, enable `use-bukkit-permissions` in the configuration.** Otherwise, the plugin will fall back to config-based permissions.

* **EssentialsX requires Java 8 or higher.** On older versions, the plugin may not work properly. 

* **EssentialsX supports Minecraft versions 1.8.8, 1.9.4, 1.10.2, 1.11.2 and 1.12.2.** Support for 1.13.2 is coming soon.


Support
-------

Need help with using EssentialsX? Join the [MOSS Discord community](https://discord.gg/casfFyh) to ask for help and discuss EssentialsX.

If you need to report a bug or want to suggest a new feature, you can [open an issue on GitHub](https://github.com/EssentialsX/Essentials/issues/new/choose).


Building
--------

EssentialsX builds against the Spigot/CraftBukkit server software for legacy support.
To compile EssentialsX, you first need to run [BuildTools](https://www.spigotmc.org/wiki/buildtools) several times:

```
java -jar BuildTools.jar --rev 1.8
java -jar BuildTools.jar --rev 1.8.3
java -jar BuildTools.jar --rev 1.9
java -jar BuildTools.jar --rev 1.9.4
```

Then, to build with Maven, run the following command:
```
mvn clean install
```

Each module's jar can be found in `target/` inside each module's directory. 


Contributing
------------

Want to help improve EssentialsX? There are numerous ways you can contribute to the project.

If you'd like to make a financial contribution to the project, you can join our [Patreon](https://www.patreon.com/essentialsx/).
If you can't make a donation, don't worry! There's lots of other ways to contribute:

* Do you run a server? Take a look at our ["help wanted" issues](https://github.com/EssentialsX/Essentials/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc+label%3A%22help+wanted%22), 
  where you can find issues that need extra testing and investigation. You can also join the [MOSS Discord community](https://discord.gg/casfFyh)
  and provide support to others.
* Do you speak multiple languages? If so, we always welcome pull requests to our [language files](https://essentialsx.github.io/#/Locale).
* If you're a developer, you could look through our ["open to PR" issues](https://github.com/EssentialsX/Essentials/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc+label%3A%22status%3A+open+to+PR%22).
  We're always happy to receive bug fixes and feature additions as pull requests.
