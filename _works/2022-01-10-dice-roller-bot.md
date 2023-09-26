---
title: diceRoller
description: Inspired by the "Ability Checks" game mechanic in the game titled Baldur's Gate 3 -- this is a simple bot that simulates that mechanic.
category: Discord Bot
date: 2023-08-31 08:01:35 +0300
client: Self
role: Software Engineer
image: '/images/work-dice-roller.jpg'
image_caption: 'Photo by Andrew Magdurulan'
---

This discord bot uses a simple /roll command to generate 2 numbers for the users. One number represents the "Difficulty Class" which is the number that users have to check against. To "Succeed" a check the subsequent number generated/rolled must be greater than or equal (>=) to the Difficulty Class number. Conversly, to "Fail" a check means the subsequent generated number is less than (<) the Difficulty Class number.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/work-1-2.jpg" loading="lazy" alt="Project">
    <img src="/images/work-1-3.jpg" loading="lazy" alt="Project">
  </div>
  <em>Photo by Andrew Magdurulan</em>
</div>

Currently, the /roll command's parameters are case-insensitive and input strings must match the valid Ability Check types in the pre-determined set of ability check types.

The current set of valid ability checks to perform are: "athletics", "acrobatics", "sleight of hand", "stealth", "arcana", "history", "investigation", "nature", "religion", "animalhandling", "insight", "medicine", "perception", "survival", "deception",  "intimidation", "performance", "persuasion".

> Example Usage: /roll Sleight Of Hand

See video below for another usage example and live bot functionality within a discord server:

<p><iframe src="/videos/diceRollerBot example - 2023-09-25 23-48-16.mp4" loading="lazy" width="640" height="360" frameborder="0" allowfullscreen></iframe></p>

The diceRoller discord bot is still being actively maintained by myself. Plans are set for additional functionality. This includes but is not limited to adding classes that are unique to each member in the server, modifiers that can be applied to rolls based on the member's chosen class, and consequences/benefits based on successful or failed checks.