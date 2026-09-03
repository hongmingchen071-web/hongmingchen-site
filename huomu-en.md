---
layout: page
title: "HUOMU (working title)"
permalink: /huomu/en/
lang: en
image: /assets/images/huomu/og.jpg
---

<p class="lang-switch"><a href="/huomu/">中文</a></p>

A first-person stealth tomb-robbing prototype: you go down alone, take what's worth money, and climb back out. Unreal Engine 5.8, C++, made by one person, started mid-August 2026. HUOMU is a working title.

The game is in Chinese for now, so the captions below say what you're looking at.

![Down in the tomb, torch on](/assets/images/huomu/descent.jpg)

## The loop

Go down → find things → climb out → sell the grave goods at a black market → buy batteries, a chisel, a gas mask, filters, food, or a bigger pack → go down again.

Parts of the tomb hold mercury vapour, light or heavy; a gas mask with a filter in it keeps that off you. The torch runs on batteries and they run out. So the money from each trip has to be split between those things.

![The screen after a trip: cash at the top, then goods to sell, then the shop list, then "go down again"](/assets/images/huomu/market.jpg)

## Water level

There is a pool in the middle of the chamber. Chisel through the channel wall and the water pours into the level below and leaves through a grate at the bottom. As the water drops, the buoyancy holding up the three coffin lids goes with it. The lids come loose one by one, and the guards inside wake up.

So draining is a decision. While the pool is full you can dive for what is lying on the bottom, though you can only hold your breath so long. Once it is drained you can reach the way down, and the guards are out.

![The third chisel hit opens the channel wall. The text reads "channel 3/3, water level dropping"](/assets/images/huomu/breach.jpg)

![Water pouring into the chamber from above](/assets/images/huomu/waterfall.jpg)

## Weight and hearing

Two numbers stay in the top-left corner: how many kilograms you are carrying, and how far your noise carries right now, in metres. The heavier you are, the further your footsteps carry. Sprinting carries further. Landing from a height makes noise too, and the bigger the drop the louder it is.

Guards run on hearing alone. Which is why throwing a stone somewhere else pulls one away.

![Top-left: 17.5 kg, and "heard within 25 m". The word at the bottom is "sprinting"](/assets/images/huomu/weight-hud.jpg)

![A guard walking towards the noise](/assets/images/huomu/guard.jpg)

## No take-backs

The channel you broke, the water you drained, the things you took, the stone you dropped on the floor: all of it is still where you left it on the next trip. Nothing resets. A one-time change stays a one-time change.

The bronze sword makes that explicit. Picking it up opens a confirmation box first: take it, and guard hearing goes up 50%, permanently. Press yes and it goes into the save file.

![The box before you take the bronze sword: "Guard hearing +50% (permanent). Take it?", with yes and no](/assets/images/huomu/sword-prompt.jpg)

## Where it is now

One chamber, playable end to end: go down, drain the pool, get chased, climb out, sell, go down again.

## Next

Most of my time, seven parts in ten or more, goes into the game itself. The hearing and weight system is what I keep working on: the first and second spaces will get ground materials, so the same load sounds different on rock, soil and standing water. The rest goes into development videos.

## Contact

[me@hongmingchen.tech](mailto:me@hongmingchen.tech). The development journal (in Chinese) is [here](/#journal).
