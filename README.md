# ProbablyBackpacks Expansion

A configuration pack for **ProbablyBackpacks** that extends the default backpack progression to **21 backpack tiers**, featuring balanced crafting recipes and a fully integrated **DeluxeMenus** interface.

> **Note**
> This repository is **not** a plugin or a fork of ProbablyBackpacks. It is a community-made configuration pack that extends the original plugin.

---

## DeluxeMenus Interface
Craft backpacks & upgrades directly from the GUI.

![Backpacks](images/backpacks.jpg)
![Backpacks Details](images/backpacks-details.jpg)
![Upgrades](images/upgrades.jpg)

---

# Features

## 21 Backpack Tiers

This expansion extends the default ProbablyBackpacks progression to a total of **21 backpack tiers**, providing a complete progression from early-game to end-game.

Backpack capacities range from **27 slots** up to **765 slots**, allowing players to gradually unlock larger storage as they progress.

Each new tier builds upon the previous backpack, creating a balanced and rewarding progression.

---

## Balanced Progression

Every backpack has its own crafting recipe designed around Minecraft progression.

Higher tiers require:

- Previous backpack
- Rare materials
- Exploration
- Nether progression
- End progression
- Advanced crafting

This prevents players from skipping directly to end-game backpacks.

---

## DeluxeMenus Integration

Includes a complete GUI for backpack crafting.

Features:

- Two menu pages
- Easy navigation
- Material validation
- Automatic crafting
- Sound effects
- Error messages
- Previous/Next page navigation

Players never need to remember crafting recipes.

Everything is available through the graphical interface.

---

## Backpack Upgrades

The menu also provides access to ProbablyBackpacks upgrades such as:

- Crafting Upgrade
- Pickup Upgrade
- Magnet Upgrade
- Feeding Upgrade
- Refill Upgrade
- Tool Swapper
- Compacting
- Furnace
- Blast Furnace
- Smoker
- Smithing
- Anvil
- Jukebox
- Stack Upgrades

---

# Repository Structure

```
ProbablyBackpacks-Expansion/

├── ProbablyBackpacks/
│   └── backpacks.yml

└── DeluxeMenus/
    ├── config.yml
    ├── probablybackpacks_menu.yml
    └── probablybackpacks_menu_page2.yml
```

---

# Compatibility

Tested with:

- Paper v26.1.2
- ProbablyBackpacks v2.3
- CuriosPaper v2.0.0
- DeluxeMenus v1.14.1
- PlaceholderAPI v2.12.3
- CheckItem Expansion v2.7.9

---

# Requirements

Before installing this pack, make sure your server already has the following plugins installed:

## Required

- ProbablyBackpacks
- CuriosPaper
- DeluxeMenus

## Required for the DeluxeMenus interface

If you plan to use the included DeluxeMenus GUI, you must also install:

- PlaceholderAPI
- CheckItem PlaceholderAPI Expansion

Without the CheckItem expansion, the crafting validation inside the GUI will not work correctly.

You can install it using:

```text
/papi ecloud download CheckItem
/papi reload
```

---

# Language

The included DeluxeMenus interface is fully translated into **Spanish**.

You are free to translate the menu files into any language by editing:

- probablybackpacks_menu.yml
- probablybackpacks_menu_page2.yml

---

# Installation

## Step 1

Install ProbablyBackpacks.

Start your server once so the plugin generates its default configuration.

---

## Step 2

Replace:

```
plugins/ProbablyBackpacks/backpacks.yml
```

with the file included in this repository.

---

## Step 3

Copy the DeluxeMenus files.

```
plugins/DeluxeMenus/

config.yml

gui_menus/probablybackpacks_menu.yml

gui_menus/probablybackpacks_menu_page2.yml
```

Replace existing files if necessary.

---

## Step 4

Reload DeluxeMenus.

```
/dm reload
```

or simply restart the server.

---

# Opening the Menu

The included DeluxeMenus configuration registers commands that open the backpack menu.

Example commands include:

```
/backpacks

/mochilas

/tmochilas

/bps
```

Depending on your server configuration you may customize these aliases.

---

# Crafting System

Instead of using the crafting table, players can craft backpacks directly from the GUI.

The menu automatically:

- checks required materials
- removes ingredients
- gives the crafted backpack
- plays confirmation sounds
- displays failure messages when requirements are missing

---

# Backpack Progression

The default ProbablyBackpacks progression has been extended to a total of **21 backpack tiers**, each requiring the previous backpack as part of its crafting recipe.

Each backpack tier includes its own balanced crafting recipe designed to match the progression of the game.

The complete backpack progression is shown below:

| Tier | Backpack   | Slots | Upgrades |
| ---- | ---------- | ----- | -------- |
| 1    | Leather    | 27    | 1        |
| 2    | Copper     | 45    | 2        |
| 3    | Iron       | 54    | 3        |
| 4    | Gold       | 81    | 4        |
| 5    | Diamond    | 108   | 5        |
| 6    | Netherite  | 126   | 6        |
| 7    | Emerald    | 144   | 7        |
| 8    | Amethyst   | 162   | 7        |
| 9    | Quartz     | 180   | 7        |
| 10   | Prismarine | 198   | 8        |
| 11   | Echo       | 216   | 8        |
| 12   | Ender      | 243   | 8        |
| 13   | Dragon     | 270   | 9        |
| 14   | Beacon     | 324   | 9        |
| 15   | Ancient    | 378   | 9        |
| 16   | Master     | 432   | 9        |
| 17   | Supreme    | 486   | 9        |
| 18   | Mythic     | 540   | 9        |
| 19   | Divine     | 594   | 9        |
| 20   | Infinite   | 648   | 9        |
| 21   | Ultimate   | 765   | 9        |

> **Note**
> Each backpack tier requires the previous backpack as part of its crafting recipe, creating a natural progression from early-game to end-game storage.

---

# Custom Recipes

All custom backpack recipes are defined in:

```text
backpacks.yml
```

You can customize every backpack without modifying the plugin itself, including:

- Ingredients
- Crafting Shape
- Backpack Capacity (Slots)
- Display Name
- Lore
- Item Model
- Custom Model Data

Below are all crafting recipes included in this expansion:

<table>
<tr>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_de_cuero.webp">
<img src="images/backpacks-crafting/Mochila_de_cuero.webp" alt="Leather Backpack">
</a>
</td>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_de_cobre.webp">
<img src="images/backpacks-crafting/Mochila_de_cobre.webp" alt="Copper Backpack">
</a>
</td>
</tr>

<tr>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_de_hierro.webp">
<img src="images/backpacks-crafting/Mochila_de_hierro.webp" alt="Iron Backpack">
</a>
</td>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_de_oro.webp">
<img src="images/backpacks-crafting/Mochila_de_oro.webp" alt="Gold Backpack">
</a>
</td>
</tr>

<tr>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_de_diamante.webp">
<img src="images/backpacks-crafting/Mochila_de_diamante.webp" alt="Diamond Backpack">
</a>
</td>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_de_netherita.webp">
<img src="images/backpacks-crafting/Mochila_de_netherita.webp" alt="Netherite Backpack">
</a>
</td>
</tr>

<tr>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_de_esmeralda.webp">
<img src="images/backpacks-crafting/Mochila_de_esmeralda.webp" alt="Emerald Backpack">
</a>
</td>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_de_amatista.webp">
<img src="images/backpacks-crafting/Mochila_de_amatista.webp" alt="Amethyst Backpack">
</a>
</td>
</tr>

<tr>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_de_cuarzo.webp">
<img src="images/backpacks-crafting/Mochila_de_cuarzo.webp" alt="Quartz Backpack">
</a>
</td>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_de_prismarina.webp">
<img src="images/backpacks-crafting/Mochila_de_prismarina.webp" alt="Prismarine Backpack">
</a>
</td>
</tr>

<tr>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_echo.webp">
<img src="images/backpacks-crafting/Mochila_echo.webp" alt="Echo Backpack">
</a>
</td>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_ender.webp">
<img src="images/backpacks-crafting/Mochila_ender.webp" alt="Ender Backpack">
</a>
</td>
</tr>

<tr>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_dragon.webp">
<img src="images/backpacks-crafting/Mochila_dragon.webp" alt="Dragon Backpack">
</a>
</td>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_faro.webp">
<img src="images/backpacks-crafting/Mochila_faro.webp" alt="Beacon Backpack">
</a>
</td>
</tr>

<tr>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_ancestral.webp">
<img src="images/backpacks-crafting/Mochila_ancestral.webp" alt="Ancient Backpack">
</a>
</td>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_maestra.webp">
<img src="images/backpacks-crafting/Mochila_maestra.webp" alt="Master Backpack">
</a>
</td>
</tr>

<tr>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_suprema.webp">
<img src="images/backpacks-crafting/Mochila_suprema.webp" alt="Supreme Backpack">
</a>
</td>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_mitica.webp">
<img src="images/backpacks-crafting/Mochila_mitica.webp" alt="Mythic Backpack">
</a>
</td>
</tr>

<tr>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_divina.webp">
<img src="images/backpacks-crafting/Mochila_divina.webp" alt="Divine Backpack">
</a>
</td>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_infinita.webp">
<img src="images/backpacks-crafting/Mochila_infinita.webp" alt="Infinite Backpack">
</a>
</td>
</tr>

<tr>
<td width="50%" align="center">
<a href="images/backpacks-crafting/Mochila_definitiva.webp">
<img src="images/backpacks-crafting/Mochila_definitiva.webp" alt="Ultimate Backpack">
</a>
</td>
<td width="50%" align="center">
&nbsp;
</td>
</tr>
</table>

> 💡 **Tip:** Click any image to view it in full resolution.

---

# DeluxeMenus

The included GUI is designed for Spanish-speaking servers and provides an intuitive interface so players can craft backpacks and upgrades without memorizing recipes.

- Backpack crafting
- Backpack upgrades
- Stack upgrades
- Navigation between pages

The menus also validate the player's inventory before allowing any craft.

---

# Customization

You may safely modify:

- recipes
- display names
- lore
- commands
- sounds
- permissions
- icons
- menu layout

to match your server.

---

# Notes

Do not delete existing backpack IDs.

Changing IDs may break existing player backpacks.

Always keep a backup before modifying recipes.

After changing DeluxeMenus configuration remember to run:

```
/dm reload
```

or restart the server.

---

# Credits

## Original Plugin

- ProbablyBackpacks by Brothergaming52

## Dependencies

- CuriosPaper
- DeluxeMenus
- PlaceholderAPI
- CheckItem Expansion

## Expansion Pack

Created and maintained by **Angel Ramirez**.

GitHub contributions, suggestions and improvements are always welcome.