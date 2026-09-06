# Onimusha-Way-of-the-Sword---Trainer


# Onimusha: Way of the Sword — Trainer

**Infinite Health, Infinite Stamina, Max Oni Gauge, Infinite Items, One-Hit Kills**
Free, open source, no installer. Opens with `Insert`.

![Version](https://img.shields.io/badge/version-1.0.0-c25640?style=flat-square)
![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-1c1c1c?style=flat-square)
![Store](https://img.shields.io/badge/Steam%20%C2%B7%20Epic-supported-4a8c5a?style=flat-square)
![Options](https://img.shields.io/badge/options-20%2B-6a6a6a?style=flat-square)
![Licence](https://img.shields.io/badge/licence-MIT-d9c47a?style=flat-square)
![Boards](https://img.shields.io/badge/leaderboards-blocked%20by%20default-c25640?style=flat-square)

**[⬇ Download the latest release]()** · [Hotkeys](#hotkeys) · [FAQ](#faq)

---

> [!IMPORTANT]
> Onimusha: Way of the Sword has leaderboards — the one place a single-player tool spills onto other people.
>
> **Submission blocking ships enabled** and keeps assisted runs off the boards. Please leave it on.

## What it does

Onimusha: Way of the Sword is a character-action game about Miyamoto Musashi cutting through a demon-infested Edo-period Kyoto . The combat revolves around precise parries, deflections, and the high-risk Issen counter — and the game expects you to *master* them . Reviews call the swordplay electrifying, but also mention a sluggish start, overlong stretches, and bosses that demand perfect timing .

A trainer for this game is not about skipping the fights — it is about removing the *frustration* while keeping the *rhythm*. The `Easier Issen` and `Always Deflect` options are the real value here: they let you feel like a master swordsman without a hundred deaths worth of muscle memory. This is the difference between *playing* Onimusha and *fighting* its combat system .

## Features

| Option | Hotkey | What it does |
|---|---|---|
| God Mode / Ignore Hits | `Num 1` | Absolute invulnerability — stagger and damage do not touch you  |
| Infinite Health | `Num 2` | Health pool locked to maximum |
| Infinite Stamina | `Num 3` | Unlimited stamina for parries, dodges and attacks  |
| Max Oni Power Gauge | `Num 4` | Oni meter stays capped at 100% for ultimate arts |
| Fast Bow Charge | `Num 5` | Bows charge instantly to maximum power |
| Infinite Buff Duration | `Num 6` | Active enhancements and combat states locked permanently |
| Super Stamina Damage / One Hit Breaks | `Num 7` | Enemy poise depletes in a single strike |
| Stamina Damage Multiplier | slider | `1x`–`50x`, default `3x` |
| Stamina Defense Multiplier | slider | `0%`–`100%` — mitigates stamina drain while guarding |
| Super Damage / One Hit Kills | `Num 0` | Dispatches normal enemies and bosses in one hit  |
| Damage Multiplier | slider | `0x`–`10x`, default `2x` |
| Defense Multiplier | slider | `0%`–`100%` |
| Edit Red Soul | `Ctrl + Num 1` | Directly edit your Red Soul reserves |
| Red Soul Multiplier | `Ctrl + Num 2` | Multiplies absorbed Red Soul yields |
| Infinite Consumables | `Ctrl + Num 3` | Items and recovery supplies are not depleted upon use  |
| Edit Selected Item (On Hand) | `Ctrl + Num 4` | Modify active inventory stack quantities |
| Edit Selected Item (In Storage) | `Ctrl + Num 5` | Modify camp/storage item quantities |
| Ignore Enhance Equipment Requirements | `Ctrl + Num 6` | Upgrade weapons without material costs  |
| Ignore Enhance Ability Requirements | `Ctrl + Num 7` | Unlock skills freely without prerequisite costs |
| Set Game Speed | `Ctrl + Num 8` | Accelerate or slow down global simulation speed |
| Easier Issen | `~` menu | Widens the execution window for Issen counters  |
| Always Deflect | `~` menu | Converts blocking into frame-perfect timed guard  |
| Auto Absorb Souls | `~` menu | Automatically pulls in nearby souls without the absorb stance  |
| Soul Multiplier | `~` menu | `1x`–`10x`, default `2x` |
| Free Camera | `F10` | Detach from the character |
| Hide HUD | `F11` | For screenshots |

<sub>Tags — **`bypass`**: removes the work the game is built around · **`save`**: writes persistent data. Anything tagged `bypass` ships off.</sub>

## Hotkeys

`Insert` opens the menu · `End` resets everything · `Num 1`–`Num 0`, `Ctrl + Num` as above, all rebindable · arrow keys and `Enter` navigate without a mouse

> [!TIP]
> Enable `Easier Issen` (set the window to `+50%`), `Always Deflect`, and `Soul Multiplier` at `2x`. This removes the timing frustration while keeping the flow of combat intact — you still need to position yourself and choose your moments, but the game stops *punishing* your reflexes. The core swordplay rhythm stays, only the pain goes away.

> [!WARNING]
> `Super Damage / One Hit Kills` (`Num 0`) ruins the game fastest. It turns every boss into a cutscene and removes the entire reason Onimusha exists. Use it only for farming or bug-testing, not for a first playthrough.
>
> Options tagged `save` write persistent data that a patch can invalidate. Back up first and disable cloud sync while you experiment.

## FAQ

<details>
<summary>Will I get banned?</summary>
No. Single-player only, no ranked mode, no anti-cheat. Leaderboard submissions are blocked by default — keep that on and you are fine .
</details>

<details>
<summary>Issen is too hard — does this actually help?</summary>
Yes. The `Easier Issen` option widens the counter window significantly. Set it to `+50%` or `+100%` and you will land counters consistently without the frame-perfect timing the game demands. This is the single most requested feature .
</details>

<details>
<summary>The game's camera is annoying — can this fix it?</summary>
Free camera (`F10`) lets you detach and frame shots however you want. It does not fix the combat camera issues reviews mention — that is on Capcom — but it helps for screenshots and exploration .
</details>

<details>
<summary>Does it work on Steam Deck or Linux?</summary>
No. Windows only. Proton changes how the game's memory is laid out and this build does not handle that.
</details>

<details>
<summary>Windows Defender flagged the download.</summary>
Trainers read and write another process's memory, which is what a lot of malware also does, so heuristic scanners flag them on principle. Every release ships with a SHA256 checksum and full source. Add an exclusion if you are comfortable with that — and if you would rather not, don't. That is a reasonable call.
</details>

<details>
<summary>Options stopped working after an update.</summary>
Patches move memory offsets and options fail independently, so some will keep working. Check the Releases page for a build matching your game version. This trainer uses REFramework hooks, so updating REFramework may also help .
</details>

## Troubleshooting

| Symptom | Fix |
|---|---|
| Nothing happens on `Insert` | Another overlay grabbed the key — Steam, Discord or RTSS. Rebind the menu key. |
| "Process not found" | The game must be running with a save loaded. Launch it first, then attach. |
| `~` menu does not open | Ensure you installed REFramework correctly. The `dinput8.dll` must be in the game root folder . |
| `Easier Issen` does nothing | Issen only works in active combat. Get into a fight first, then toggle. |
| `Ignore Enhance Requirements` not working | Open the enhancement menu at an altar first, then toggle — the game allocates those values only when the UI is open. |
| Unlocks vanished after a patch | A persistent write was invalidated. Restore a backup from before the update. |



## Changelog

**v1.0.0** — 5 September 2026 — first release. 20+ options across Combat, Souls/Inventory, and QoL. `Leaderboard blocking` and `Always Deflect` enabled by default — the first protects other players, the second makes the game feel fair from the start.

---

<div align="center">
<sub>Unofficial fan tool. Not affiliated with Capcom. Onimusha: Way of the Sword and all related names and assets belong to Capcom. Modifying a running game's memory carries some risk of crashes and save corruption — back up first, use at your own risk. MIT licensed.</sub>
</div>
