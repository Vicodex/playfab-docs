---
title: Multiplayer with PlayFab
author: v-thopra
description: Learn how PlayFab services can be used for multiplayer.
ms.author: v-thopra
ms.date: 03/04/2019
ms.topic: article
ms.prod: playfab
keywords: playfab, multiplayer
ms.localizationpriority: medium
---

# Multiplayer with PlayFab

Multiplayer action can be a great addition to many games, and PlayFab provides several services focused on multiplayer scenarios:

- **Leaderboards** - Track and respond to player activity with statistics and leaderboards.
- **Matchmaking** - Deploy custom matchmaking rules to group players quickly.
- **Servers** - Dynamically scale custom multiplayer servers in Azure.
- **Party** - Connect players with networking and accessible in-game chat.

Leaderboards and Matchmaking are both production services offered in PlayFab Essentials, our core services package, without any additional cost.

Servers is a production service, which costs extra (see [Multiplayer Server billing](./servers/billing-for-thunderhead.md)).

Party is a pre-production service still being finalized. It is offered with very limited quota, and is free (for the time being). It will become a premium service when production support is enabled later this year.

|Service|Production Readiness|Billing|
|--|--|--|
|[Leaderboards](../social/tournaments-leaderboards/using-resettable-statistics-and-leaderboards.md)|Production|Included in PlayFab essentials|
|[Matchmaking](./matchmaking/index.md)|Production (Preview)|Included in PlayFab essentials|
|[Servers](./servers/index.md)|Production (Preview)|Premium Service - 30% Preview Discount|
|[Party](./networking/index.md)|Pre-production (Beta)|Premium Service - Free during beta|
