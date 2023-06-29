# Minecraft development resources ![GitHub last commit](https://img.shields.io/github/last-commit/cryptizism/minecraft-development-resources?label=Last%20updated&style=for-the-badge)
_A repo containing resources that will aid you in the process of doing anything you need to do in your development process for Java Minecraft_

- [Server managment](#server-management)
  - [Server implmentations/warpper](#server-implementationswrappers)
  - [Server software](#server-software)
- [Plugin development](#plugin-development)
  - [Spigot/BukkitCraft](#spigotbukkitcraft)
  - [NMS](#nms)
  - [Minigames](#minigames)
  - [APIs/helpers](#apishelpers)
  - [Datapacks](#datapacks)
  - [Snippets](#snippets)
- [Mod development](#mod-development)
  - [Forge](#forge)
  - [Fabric](#fabric)
  - [Mixins](#mixins)
- [Resource pack development](#resource-pack-development)
  - [General](#general)
  - [Model Development](#model-development)
  - [Vanilla Shaders](#vanilla-shaders)
- [Map development](#map-development) 
  - [Mods](#mods)
  - [Software](#software)
- [Contributors](#contributors)
## Server Management
### Server Implementations/Wrappers
| Name | Client-Side? | Plugins? | Latest Version | Description |
| - | - | - | - | - |
| [Vanilla](https://www.minecraft.net/en-us/download/server) | No | No | Latest | Pure vanilla experience with no modification, official server implementation |
| [PaperMC](https://papermc.io/) | No | Yes | Latest | Optimized version of Spigot, one of the most popular implementations |
| [Spigot](https://www.spigotmc.org/wiki/buildtools/#what-is-it) | No | Yes | Latest | Spigot is the most common server. |
| [Forge](https://files.minecraftforge.net/net/minecraftforge/forge/) | Yes | Yes | Latest | Forge is the most common server for client-side modifications. |
| [Fabric](https://fabricmc.net/use/server/) | Yes | Yes | Latest | Fabric is another common server for client-side modifications namely for modern versions of Minecraft. |
| [SpongeForge](https://www.spongepowered.org/downloads/spongeforge) | Yes | Yes | <1.16.5 | Forge implementation and also allows sponge plugins. |
| [SpongeVanilla](https://www.spongepowered.org/downloads/spongevanilla) | No | Yes | Latest |SpongeForge but without the Forge aspect |
| [PurPur](https://purpurmc.org/) | No | Yes | Latest | A more configurable and optimized "drop-in replacement for Paper servers" |
| [Pufferfish](https://pufferfish.host/downloads) | No | Yes | Latest | A Paper fork with a focus on large servers, performance and stability |
### Server Software
- [GeyserMC](https://geysermc.org/download) A plugin/standalone implementation that allows crossplay between bedrock and Java players
- [Bungeecord](https://www.spigotmc.org/wiki/bungeecord/) A simple proxy allowing the bridge between multiple Minecraft servers
- [Waterfall](https://papermc.io/software/waterfall) A fork of Bungeecord with a focus on performance, stability, compatibility and security
- [Velocity](https://papermc.io/software/velocity) A fork of Bungeecord with a focus on performance and stability
## Plugin Development
_Resources that will aid you in the development of plugins for Minecraft_
### Spigot/BukkitCraft
_General plugin development under spigot/bukkitcraft_
- [Spigot's official Plugin Development wiki](https://www.spigotmc.org/wiki/spigot-plugin-development/) (**Latest Versions of Minecraft**) An official resource provided by Spigot, goes over a limited amount of scenarios 
- [Kody Simpson's Spigot playlist](https://www.youtube.com/watch?v=tnJZMaoMPhE&list=PLfu_Bpi_zcDNEKmR82hnbv9UxQ16nUBF7) (**Latest Versions of Minecraft**) Extremely extensive with ≈100 videos, well-paced video tutorials that build up on difficulty each video
- [CodedRed's 1.15 Spigot Playlist](https://www.youtube.com/watch?v=pTEZiAUrYJY&list=PL65-DKRLvp3Yn7iglPfxKoc7bl0N80XgG&index=27) (**1.15+**) Well-sized videos that go over most scenarios you will end up in and may be the only ones on youtube
### NMS
_Dealing with server-bound packets/net.minecraft.server_
- [Kody Simpson's Advanced Spigot playlist](https://www.youtube.com/watch?v=2FcnwD2MHOA&list=PLfu_Bpi_zcDMWE15USaR7k5jqTufhWDy6) Limited amount of videos, explained extremely well
- [CodedRed's Advanced tutorials](https://www.youtube.com/c/CodedRed/playlists?view=50&sort=dd&shelf_id=3) (**Not all are NMS**) Tutorials on specific versions of minecraft and for those at a higher skill level
- [Maven & NMS tutorial Spigot Thread](https://www.spigotmc.org/threads/maven-nms-tutorial.347254/) Leads you through your first steps of getting ready with NMS
### Minigames
_Materials that specifically hone on minigames_
- [Jordan Osterberg's minigame development playlist](https://www.youtube.com/watch?v=GW8xWDMqwtc&list=PL_PpCEhxOB-0vyS2V-iddLkE8PvNf1-9R) Extremely limited amount of videos, very specific and good if you plan to make minigames, gives a look into thought process
- [TheSourceCode's TNT Tag series](https://www.youtube.com/watch?v=R30xVZ1-vOw&list=PLdnyVeMcpY79WCCGsHW0_XHhGDmsPJBtC) An end to finish video series on the creation of a TNT tag plugin like hypixel
- [MinigamesLib](https://www.spigotmc.org/resources/minigameslib.23844) **(Legacy, outdated)** A library that makes making minigames and minigame servers easier
### APIs/helpers
_APIs/Helpers that will make development way easier_
- [ProtocolLib](https://www.spigotmc.org/resources/protocollib.1997/) Helps with the modification of packets which are impossible to perform  with the standard Bukkit API, widely used
- [Citizens](https://citizensnpcs.co/) Makes creating NPCs incredibly easy and intuitive with numerous additional features, widely used
- [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245/) A plugin for Spigot servers that allows server owners to display information from various plugins with a uniform format
- [Multiverse](https://www.spigotmc.org/resources/multiverse-core.390/) Allows you to make multiple worlds, have their own rules, inventories, permissions and more
- [MinigamesLib](https://www.spigotmc.org/resources/minigameslib.23844) **(Legacy, outdated)** A library that makes making minigames and minigame servers easier
### Datapacks
_Resources that will aid you in learning how to make datapacks_
- [LegitMoose Tutorial](https://www.youtube.com/watch?v=ac6V5-KT6Rg) A short small tutorial by LegitMoose that will get you started creating datapacks
- [Datapack Generator/Utility website](https://misode.github.io/) Allows you to easily generate datapacks and view a versions pack version
- [Visual Studio Code Extension](https://marketplace.visualstudio.com/items?itemName=SPGoding.datapack-language-server) Makes developing datapacks easier with syntax and more useful utilities
### Snippets
_Code snippets that you will be using in your day-to-day development_
- [Spigot's official Code Snippets](https://www.spigotmc.org/wiki/plugin-snippets/) A rather extensive list of plugin code snippets and explains you through them
## Mod Development
_Resources that will aid you in the development of mods for Minecraft_
### Forge
_Resources that will help you make forge mods_
- [Forge's official Wiki](https://docs.minecraftforge.net/en/latest/gettingstarted/) An official extensive wiki for getting started with forge, allows you to pick what version of the game you want a tutorial for
- [Forge Tutorial 1.19 Playlist](https://www.youtube.com/playlist?list=PLKGarocXCE1HrC60yuTNTGRoZc6hf5Uvl) Tutorials by 'Modding by Kaupenjoe' that go through modding for 1.19 Forge comprised of 40 videos that touches on nearly every aspect of modding
### Fabric
_Resources that will help you make fabric mods_
- [Fabric's official Wiki](https://fabricmc.net/wiki/doku.php#tutorials_for_developing_with_fabric) An official extensive wiki for getting started with fabric, goes through specific examples
- [Fabric Tutorial 1.19 Playlist](https://www.youtube.com/playlist?list=PLKGarocXCE1HrC60yuTNTGRoZc6hf5Uvl) Tutorials by 'Modding by Kaupenjoe' that go through modding for 1.19 Fabric comprised of 41 videos that touches on nearly every aspect of modding
### Mixins
_Resources that will help you with mixins_
- [Fabric's mixin Wiki](https://fabricmc.net/wiki/tutorial:mixin_introduction) An official wiki page by Fabric which has a coherent explanation of how to use mixins, it also has examples and code snippets with explanations
- [Mixin's official Wiki](https://github.com/SpongePowered/Mixin/wiki) Mixin's official wiki that delves into a deeper example and explanation of how to use mixins and how they work with diagrams
## Resource Pack Development
_Resources that will help you in the process of making resource packs and will give you a better understanding of how it works_
### General
_Resources that will help you make a resource pack using every feature_
- [Love & Tolerance Resource Pack Guide](https://github.com/Love-and-Tolerance/Resource-Pack-Guide) Arguably the holy bible of resources when it comes to resource packs, goes through nearly everything you need to know for making a texture pack and more such as even more resources and software
- [Minecraft Style Guide](https://itemsadder.devs.beer/plugin-usage/minecraft-style-guide) A guide that goes through thoroughly of the dos and don'ts of making a resource pack in the Minecraft style
- [Custom UI Bar Tutorial](https://www.youtube.com/watch?v=EL2X6ppZSCQ) A tutorial that shows you how to make the increasingly popular custom ui bars
- [OptiFine Docs](https://github.com/sp614x/optifine/tree/master/OptiFineDoc/doc) Documentation that will explain all OptiFine-specific texture-related things such as CIT, CEM, CTM and more.
### Model Development
_Resources that will help you with importing custom models into the game_
- [Blockbench](https://www.blockbench.net) - The most popular software for making voxel-based blocks/entities for Minecraft.
  - [Blockbench Quickstart](https://www.blockbench.net/quickstart) - Tells you your first steps for learning how to use blockbench for your use
  - ["The ULTIMATE Blockbench Tutorial"](https://www.youtube.com/watch?v=fdo_E61vVlw) A comprehensive and thorough explanation of blockbench, how to use it and specifically for Minecraft
- [GeckoLib](https://geckolib.com/) Bring model animation to forge/fabric mods with a number of other different features and tools
  - [GeckoLib BlockBench Tutorial](https://www.youtube.com/playlist?list=PLsbs474s4wcoC63HEguP3GhualODOcFqB) A start to finish 3 video long tutorial series which will help you create all you need in blockbench for Fabric/Forge
    - [Fabric GeckoLib Tutorial](https://www.youtube.com/playlist?list=PLKGarocXCE1H7lMgKRVakmRnNDOA9aN8o) A tutorial to implement geckolib entities in Fabric
    - [Forge GeckoLib Tutorial](https://www.youtube.com/playlist?list=PLKGarocXCE1HEf7Z65pg7znqsVJHMGCKJ) A tutorial to implement geckolib entities in Forge
- [Minecraft Style Guide](https://www.blockbench.net/wiki/guides/minecraft-style-guide/) A guide that goes through thoroughly of the dos and don'ts of making a model in the Minecraft style
- [OBJMc](https://github.com/Godlander/objmc) Allows you to import animated/non-animated OBJs into Minecraft using texture packs
  - [OBJMc Tutorial](https://www.youtube.com/watch?v=R6l0thbLN48) OBJMc is rather confusing and this tutorial may help with any issues you may face
### Vanilla Shaders
_Resources that will help aid you create vanilla shaders that were added as of 1.17_
- [Minecraft Shaders Wiki](https://github.com/McTsts/Minecraft-Shaders-Wiki/blob/main/README.md) A community ran, up-to-date resource filled with various examples, documentation, images and more! One of the largest resources.
- [Minecraft Shaders Repo](https://github.com/ShockMicro/Minecraft-Shaders/wiki/) Community documentation of shaders with image examples and explanations
- [Minecraft Vanilla Shaders Guide](https://docs.google.com/document/d/15TOAOVLgSNEoHGzpNlkez5cryH3hFF3awXL5Py81EMk/edit?usp=sharing) A doc made in the early ages of Vanilla shaders that cover the basics
- [Example implementation of shaders GitHub](https://github.com/HalbFettKaese/common-shaders) Allows you to get more hands-on with shaders and get a better understanding of how they work
- [Text Shader Wiki](https://github.com/Vekhove/Minecraft-Text-Shaders/wiki) A wiki specifically on text-based vanilla shaders
## Map Development
_Resources that will help you in the process of making maps/worlds for Minecraft_
### Mods
- [WorldEdit](https://www.curseforge.com/minecraft/mc-mods/worldedit) **(Forge/Fabric)** A mod that makes building easier using: selections, schematics, brushes, shapes functions and more!
  - [WorldEdit CUI Fabric](https://www.curseforge.com/minecraft/mc-mods/worldeditcui-fabric) A mod that helps you visualize selections and data of world edit
  - [WorldEdit CUI Forge](https://www.curseforge.com/minecraft/mc-mods/worldeditcui-forge-edition-3) A mod that helps you visualize selections and data of world edit
- [Axiom (W.I.P)](https://discord.gg/jDuUqnkjxV) **(Fabric)** A mod with various vanilla tweaks for building regularly as well as a visual editor with brushes, selections, operators and more!
### Software
- [WorldPainter](https://www.worldpainter.net/) Software that makes sculpting and painting terrain and structures easier
- [Amulet](https://www.amuletmc.com/) Software that allows you to alter blocks, chunks and biomes and also copy and paste structures with the ability of operations and free transform
## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="http://www.cryptizism.com"><img src="https://avatars.githubusercontent.com/u/60571306?v=4?s=100" width="100px;" alt="Cryptizism"/><br /><sub><b>Cryptizism</b></sub></a><br /><a href="#doc-Cryptizism" title="Documentation">📖</a> <a href="#code-Cryptizism" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
