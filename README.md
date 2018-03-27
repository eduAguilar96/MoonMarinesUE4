# Moon Marines v1.0
---

![MoonMarinesGIF](https://i.imgur.com/MSkuSVY.gif)

README last updated 3/26/2018

## Setup
---

### Engine

This project utilizes Unreal Engine 4.19.

Download version via the Epic Launcher

![GetVersion](https://i.imgur.com/F84xryp.png)

Launch engine version and open project folder from directory.

### Source Control

This project utilizes git LFS(Large File Storage) so be sure to download the respective dependencies if you wish to commit/push.

[LFS Download](https://git-lfs.github.com/)

**NOTE:** We only have LFS **50 GB** quota, be mindfull with file compression. 50 GB more would mean an
**extra $5** a month.

## Project
---

### Directory

* Name *:Description*

Root: **Content**


* 3rdParty *:Content directories imported from alien* sources
  * LuosCaves
  * Muzzles
* Characters
  * Animations *:Source animation pack* [Soon tobe DEPRECATED]
  * BlendSpaces *:Source blendspace pack* [Soon tobe DEPRECATED]
  * EnemyCharacter
  * Models *:All character model assets*
  * PlayerCharacter
* GameFiles *:Generally unified game assets*
* Materials
* Scenes
* StarterContent [Soon tobe DEPRECATED]

Before creating/adding new content be mindful of your directory placement. If it is not developer and future friendly it **will not** me merged.

### Playing/Testing

Easily run the game without building by pressing the **play** button.

To test multiplayer, change *Number of Players* in the play dropdown menu **[#2 in image]**. If you select/enable *Run Dedicated Server* all player windows will act as *Clients* while a *Server* runs in the background **[#2 in image]**. If disabled, one player window will act as the *Active Host*. Notice physical window title/header to differentiate the host (Actual target architecture).

![EditorWindow](https://i.imgur.com/wHSKDcb.jpg)

**Protip:** Select *New Editor Window* **[#1 in image]** and change *Play in new window/NewWindowSize* in *Advanced Settings* **[#3 in image]** to better acomodate windows.

![ProTip](https://i.imgur.com/LVWODAI.png)

## Contribution
---

## Backlog

Please see the product Backlog at Taiga.io before tackling a feature.

[Project Link](https://tree.taiga.io/project/eduaguilar96-moonmarines/)

## Branch Hierarchy

* master
* development
  * feature

**Never** try to push to *development* or *master*, even if they are locked.

## Workflow

Always *branch* out of the most updated development branch and name your new branch based off the feature you want to implement. *Ex: player-state*.

**NOTE:** Branch naming conventions demand Kebab case, **word-word**

After committing changes in personal/local branch push to this newly created branch and manage merge request via the github repo plataform.

## Commits

Commit messages must be concise and clear, if not deamed *good* they **will not** be merged. Commit messages must also comply with the *If this commit is merged it will* [message] format. Likewise first word must be a verb with capitalized first letter.

*Ex: If this commit is merged it will* **Add player state to PlayerCharacter**

so...

`git commit -m "Add player state to PlayerCharacter"`

## Credits
---

#### Dev Team
- Eduardo Aguilar Leal
- ChurbloxXx69
- El Guad
- Dan Scissors

#### Software
- Unreal Engine 4.19

#### 3rd-Pary assets and tools
- Luos's Modular Rocks & Caves by Luos
- Muzzle Flashes by W3 Studios
- Sci Fi Space Soldier by PolygonR
- Dead Walker by mr.Necturus
- Mega Sci-Fi Particle FX Bundle 3in1 by Level One Games

This Project is being created for the VideoGames class at the *Tecnologico de Estudios Superiores de Monterrey*
