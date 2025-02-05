---
{"dg-publish":true,"permalink":"/nas-upgrade/","title":"NAS upgrade","noteIcon":"1","created":"2025-02-05T18:55:01.063+11:00","updated":"2025-02-05T20:20:56.334+11:00"}
---


Here’s where things took an unexpected turn. While my original goal of building a NAS was simply to store photos, I found myself using the streaming server way more than anticipated. Watching my movies directly on my TV, just like Netflix but without the monthly bill, was too good to resist. However, my [[Raspberry Pi 4 as a tiny NAS\|tiny NAS]] struggled to stream some video formats due to the limit of hardware. That’s when I knew: it was time for an upgrade.

I leveled up to an Intel NUC 11, a mini PC equipped with [Intel QuickSync](https://en.wikipedia.org/wiki/Intel_Quick_Sync_Video), a game-changer for video streaming. QuickSync allows on-the-fly transcoding, meaning if a movie format isn’t compatible with my TV or iPad, the NUC magically converts it in real time smoothly and seamlessly. This is what was missing with my tiny NAS.

Currently, I’m running [OpenMediaVault 7](https://www.openmediavault.org/) on my NUC, a lightweight OS widely recommended in the self-hosting community. While CasaOS had its perks, especially its beginner-friendly app store, OMV gives me more flexibility and control, making it the better choice for my growing needs.

If you’ve ever thought about building your own NAS, I highly recommend starting small and upgrading as you go. Once you experience the joy of self-hosting, there’s no turning back!

