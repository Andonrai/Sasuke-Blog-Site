---
title: Slash Commads Updates
date: 2021-09-02
published: true
tags: ['Sasuke Bot', 'Updates', 'Slash']
series: false
cover_image: ./images/slash_commands.png
canonical_url: false
description: "Updating sasuke commands to slash commands!"
author: "!!Josue#3820 - Developer"
author_image: https://cdn.discordapp.com/avatars/577205997748092939/3e90059aa304d5dbb6cfe05fcdbcea84.webp?size=1024
---

## v2.5.7 patch | 2021-09-02

This Change has been applied due to changes that have occurred and are about to occur in the Discord api and also due to the new Functions granted by discord to the Bots

---

## Major Changes
- Implement a “absolute” 404 to fallback to if the route or bot doesn’t exist thus avoiding hanging and timeouts. 
- Same as above ^ but for 500 (Internal Error) prevents the API from hanging if an error occurs which would most likely result in a timeout 
- Updated the POST method errors to show a `400 (Client Error)` or `401 (Unauthorized)` for null, undefined, or invalid Auth Token

## Minor Changes
- Begin support and implementation of a `All Approved Bots` route for the Infinity Bots API

## NPM Changes
- Updated and Cleaned up the NPM Module.
- Implememt a `GET` bot method.
- Implement a `GET` user method.

---


