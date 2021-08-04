---
author: v-josjones
ms.author: v-josjones
title: Potion Brewing Container Recipe
ms.prod: gaming
---

# Potion Brewing Container Recipe

Represents a Potion Brewing Container Recipe.

## Parameters

|Name |Type |Description |
|:-----------|:-----------|:-----------|
|input| potion| input potion used in the brewing container recipe. |
|output| potion| output potion from the brewing container recipe. |
|reagent| item| item used in the brewing container recipe with the input potion. |
|tags|String array | Item used in a Brewing Container Recipe. |

## Potion Brewing Container Recipe Example

```JSON
{
"format_version": "1.17",
    "minecraft:recipe_brewing_container": {
    "description": {
        "identifier": "minecraft:brew_potion_sulphur"
    },
    "tags": [ "brewing_stand" ],
    "input": "minecraft:potion",
    "reagent": "minecraft:gunpowder",
    "output": "minecraft:splash_potion",
    }
}
```

## Vanilla Example

:::code language="json" source="../../../../Source/VanillaBehaviorPack_Snippets/recipes/brew_slow_falling_redstone.json":::