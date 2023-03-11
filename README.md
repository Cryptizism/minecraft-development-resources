# Minecraft development resources ![GitHub last commit](https://img.shields.io/github/last-commit/cryptizism/minecraft-development-resources?label=Last%20updated&style=for-the-badge)
_A repo containing resources that will aid you in the process of doing anything you need to do in your development process_

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
## Plugin Development
_Resources that will aid you in the development of plugins for minecraft_
### Spigot/BukkitCraft
_General plugin development under spigot/bukkitcraft_
- [Spigot's official Plugin Development wiki](https://www.spigotmc.org/wiki/spigot-plugin-development/) (**Latest Versions of Minecraft**) An official resource provided by Spigot, goes over a limited amount of scenarios 
- [Kody Simpson's Spigot playlist](https://www.youtube.com/watch?v=tnJZMaoMPhE&list=PLfu_Bpi_zcDNEKmR82hnbv9UxQ16nUBF7) (**Latest Versions of Minecraft**) Extremely extensive with ≈100 videos, well-paced video tutorials that build up on difficulty each video
- [CodedRed's 1.15 Spigot Playlist](https://www.youtube.com/watch?v=pTEZiAUrYJY&list=PL65-DKRLvp3Yn7iglPfxKoc7bl0N80XgG&index=27) (**1.15+**) Well-sized videos that go over most scenarios you will end up in and may be the only ones on youtube
### NMS
_Dealing with server bound packets/net.minecraft.server_
- [Kody Simpson's Advanced Spigot playlist](https://www.youtube.com/watch?v=2FcnwD2MHOA&list=PLfu_Bpi_zcDMWE15USaR7k5jqTufhWDy6) Limited amount of videos, explained extremely well
- [CodedRed's Advanced tutorials](https://www.youtube.com/c/CodedRed/playlists?view=50&sort=dd&shelf_id=3) (**Not all are NMS**) Tutorials on specific versions of minecraft and for those at a higher skill level
- [Maven & NMS tutorial Spigot Thread](https://www.spigotmc.org/threads/maven-nms-tutorial.347254/) Leads you through your first steps of getting ready with NMS
### Minigames
_Materials that specifically hone on minigames_
- [Jordan Osterberg's minigame development playlist](https://www.youtube.com/watch?v=GW8xWDMqwtc&list=PL_PpCEhxOB-0vyS2V-iddLkE8PvNf1-9R) Extremely limited amount of videos, very specific and good if you plan to make minigames, gives a look in to thought process
- [TheSourceCode's TNT Tag series](https://www.youtube.com/watch?v=R30xVZ1-vOw&list=PLdnyVeMcpY79WCCGsHW0_XHhGDmsPJBtC) An end to finish video series on the creation of a TNT tag plugin like hypixel
- [MinigamesLib](https://www.spigotmc.org/resources/minigameslib.23844) **(Legacy, outdated)** A library that makes making minigames and minigame servers easier
### APIs/helpers
_APIs/Helpers that will make development way easier_
- [ProtocolLib](https://www.spigotmc.org/resources/protocollib.1997/) Helps with the modification of packets which are impossible to preform  with the standard Bukkit API, widely used
- [Citizens](https://citizensnpcs.co/) Makes creating NPCs incredibly easy and intuiative with numerous additional features, widely used
- [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245/) A plugin for Spigot servers that allows server owners to display information from various plugins with a uniform format
- [Multiverse](https://www.spigotmc.org/resources/multiverse-core.390/) Allows you to make multiple worlds, have thier own rules, inventories, permissions and more
- [MinigamesLib](https://www.spigotmc.org/resources/minigameslib.23844) **(Legacy, outdated)** A library that makes making minigames and minigame servers easier
### Datapacks
_Resources that will aid you in learning how to make datapacks_
- [LegitMoose Tutorial](https://www.youtube.com/watch?v=ac6V5-KT6Rg) A short small tutorial by LegitMoose that will get you started creating datapacks
- [Datapack Generator/Utility website](https://misode.github.io/) Allows you to easily generate datapacks and view a versions pack version
- [Visual Studio Code Extension](https://marketplace.visualstudio.com/items?itemName=SPGoding.datapack-language-server) Makes developing datapacks easier with syntax and more useful utilities
### Snippets
_Code snippets that you will be using in your day to day devlopment_
- [Spigot's official Code Snippets](https://www.spigotmc.org/wiki/plugin-snippets/) A rather extensive list of plugin code snippets and explains you through them
## Mod Development
_Resources that will aid you in the development of mods for minecraft_
### Forge
_Resources that will help you make forge mods_
- [Forge's official Wiki](https://docs.minecraftforge.net/en/latest/gettingstarted/) An official extensive wiki for getting started with forge, allows you to pick what version of the game you want a tutorial for
- [Forge Tutorial 1.19 Playlist](https://www.youtube.com/playlist?list=PLKGarocXCE1HrC60yuTNTGRoZc6hf5Uvl) Tutorials by 'Modding by Kaupenjoe' that go through moddding for 1.19 Forge comprised of 40 videos that tocuhes on nearly every aspect of modding
### Fabric
_Resources that will help you make fabric mods_
- [Fabric's official Wiki](https://fabricmc.net/wiki/doku.php#tutorials_for_developing_with_fabric) An official extensive wiki for getting started with fabric, goes through specific examples
- [Fabric Tutorial 1.19 Playlist](https://www.youtube.com/playlist?list=PLKGarocXCE1HrC60yuTNTGRoZc6hf5Uvl) Tutorials by 'Modding by Kaupenjoe' that go through moddding for 1.19 Fabric comprised of 41 videos that tocuhes on nearly every aspect of modding
### Mixins
_Resources that will help you with mixins_
- [Fabric's mixin Wiki](https://fabricmc.net/wiki/tutorial:mixin_introduction) An official wiki page by fabric which has a coherent explanation of how to use mixins, it also has examples and code snippets with explanations
- [Mixin's official Wiki](https://github.com/SpongePowered/Mixin/wiki) Mixin's official wiki that delves into a deeper example and explanation of how to use mixins and how they work with diagrams
## Resource Pack Development
_Resources that will help you in the process of making resource packs and will give you a better understanding of how it works_
### General
_Resources that will help you make a resource pack using every feature_
- [Love & Tolerance Resource Pack Guide](https://github.com/Love-and-Tolerance/Resource-Pack-Guide) Arguably the holy bible of resources when it comes to resource packs, goes through nearly everything you need to know for making a texture pack and more such as even more resources and software
- [Minecraft Style Guide](https://itemsadder.devs.beer/plugin-usage/minecraft-style-guide) A guide that goes through thuroughly of the dos and don'ts of making a resource pack in the minecraft style
- [Custom UI Bar Tutorial](https://www.youtube.com/watch?v=EL2X6ppZSCQ) A tutorial that shows you how to make the increasingly popular custom ui bars
- [OptiFine Docs](https://github.com/sp614x/optifine/tree/master/OptiFineDoc/doc) Documentation that will explain all OptiFine specific texture related things such as CIT, CEM, CTM and more.
### Model Development
_Resources that will help you with importing custom models in to the game_
- [Blockbench](https://www.blockbench.net) - The most popular software for making voxel based blocks/entities for Minecraft.
  - [Blockbench Quickstart](https://www.blockbench.net/quickstart) - Tells you your first steps for learning how to use blockbench for your use
- [Minecraft Style Guide](https://itemsadder.devs.beer/plugin-usage/minecraft-style-guide) A guide that goes through thuroughly of the dos and don'ts of making a model in the minecraft style
- [OBJMc](https://github.com/Godlander/objmc) Allows you to import animated/non-animated OBJs in to minecraft using tetxure packs
  - [OBJMc Tutorial](https://www.youtube.com/watch?v=R6l0thbLN48) OBJMc is rather confusing and this tutorial may help with any issues you may face
### Vanilla Shaders
_Resources that will help aid you create vanilla shaders that were added as of 1.17_
- [Minecraft Shaders Wiki](https://github.com/ShockMicro/Minecraft-Shaders/wiki/) Largest community documentation of shaders with image examples and explanations
- [Minecraft Vanilla Shaders Guide](https://docs.google.com/document/d/15TOAOVLgSNEoHGzpNlkez5cryH3hFF3awXL5Py81EMk/edit?usp=sharing) A doc made in the early ages of Vanilla shaders that cover the basics
- [Example implementation of shaders GitHub](https://github.com/HalbFettKaese/common-shaders) Allows you to get more hands on with shaders and get a better understanding of how they work
- [Text Shader Wiki](https://github.com/Vekhove/Minecraft-Text-Shaders/wiki) A wiki specifically on text based vanilla shaders
## Map Development
_Resources that will help you in the process of making maps/worlds for minecraft_
### Mods
- [WorldEdit](https://www.curseforge.com/minecraft/mc-mods/worldedit) **(Forge/Fabric)** A mod that makes building easier using: slsections, schematics, brushes, shapes functions and more!
  - [WorldEdit CUI Fabric](https://www.curseforge.com/minecraft/mc-mods/worldeditcui-fabric) A mod that helps you visualize selections and data of world edit
  - [WorldEdit CUI Forge](https://www.curseforge.com/minecraft/mc-mods/worldeditcui-forge-edition-3) A mod that helps you visualize selections and data of world edit
### Software
- [WorldPainter](https://www.worldpainter.net/) Software that makes sculpting and and painting terrain and structures easier
- [Amulet](https://www.amuletmc.com/) Software that allows you to alter blocks, chunks and biomes and also copy and paste structures with the ability of operations and free transform
