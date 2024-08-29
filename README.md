# Doc-SimpleInventorySystem

![Plugin](https://github.com/Mecanes/Images/blob/main/SIS_Logo.png)

## Plan
<!--ts-->
* [Description](#Description)
* [Objective](#Objective)
* [Requirement](#Requirement)
* [Warning](#Warning)
* [Installation](#Installation)
* [Contents](#Contents)
* [Advantages and uses](#Advantages-and-uses)
* [Function](#Function)
* [Features & applications](#features-&-usages)
* [License](#License)
* [Author](#Author)
* [History](#History)

## Description

The Simple Inventory System plugin provides a simple and effective solution for managing items in your games. It lets players collect, store and organize items, so you can easily interact with their inventory. Ideal for projects requiring item tracking, this plugin makes it easy to collect, use and manage resources in your games, while providing a solid foundation for more advanced functionality.

## Objective

The aim of the Simple Inventory System is to provide a lightweight, easy-to-integrate solution for managing the collection, organization and use of items in a game, enabling developers to quickly create functional inventory systems without the problems of excessive complexity.

## Requirement

Target version : UE5.2 ～ 5.4

Target platform : Windows, Mac

## Warning
The plugin may not work properly, so feel free to join the Discord for more information. We're working hard on this plugin and will be updating it regularly to make it more effective.


## Installation

Install the plugin via the marketplace .

If the functionality isn’t available after installing the plugin, it’s possible that the plugin hasn’t been activated. Please make sure the plugin is enabled by going to Edit > Plugins.

## Contents
There are 2 actor components:
* AC ItemsBag
* AC Item

> **AC Item is used in your Actor ( Item )**

> **AC ItemsBag is used in your Character**

![Actor Component]( https://github.com/Mecanes/Images/blob/main/UE_SIS.png )

## Advantages and uses
***Advantage*** :
* **Simple Inventory System** facilitates integration and customization, offering developers a fast way to set up an efficient and intuitive inventory system, without the need for complex coding.

**Here are a few use cases for your** ***Simple Inventory System plugin***: :
* **Role-playing games (RPG)**: Manage items, potions and equipment collected by players
* **Survival games**: Track collected resources (food, materials, tools) and manage players' limited inventories, adding a strategic dimension to survival.
* **Rapid game prototyping**: Offer developers a ready-to-use solution for rapidly testing game concepts based on the collection and use of objects.
* **and other...**

### Function

- [x] ***AC ItemsBag***
> ![AC ItemsBag](https://github.com/Mecanes/Images/blob/main/AC_ItemsBagFunction.png)

- ***Remove Item and Remove Item by Index*** : Return true , if the item have being remove

- ***Set Item Quantity and Set Item Quantity by Index*** : Modify the quantity of item

  
- [x] **AC Item**
> ![AC Item](https://github.com/Mecanes/Images/blob/main/AC_ItemFunction.png)

- ***Has Space For*** : Returns TRUE IF THERE IS ROOM, OTHERWISE FALSE

- ***Add To Bag*** : Stores an object in the bag. Returns true if the object is stored, otherwise false if the actor has no bag
- > check Delete actor if you want the actor to be deleted if it no longer exists.


## Features & applications

#### Code Example : AC Item
![AC Item Example](https://github.com/Mecanes/Images/blob/main/example_AC_Item.png)

## Licence

[MIT License](https://en.wikipedia.org/wiki/MIT_License)

## Author

[Mecanes](https://linktr.ee/mecanes)

## History

- [x] [29/08/2024] Creation of official documentation
