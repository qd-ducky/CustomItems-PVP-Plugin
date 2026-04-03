# ⚔️ CustomItems-PVP-Plugin

Custom Minecraft plugin for creating **custom PvP items with abilities, effects, and configurable systems**.

---

## ✨ Features

* 🧪 Fully configurable custom items
* ⚡ Ability system (on hit, right click, etc.)
* 🎯 Custom effects, sounds and behaviors
* 📦 Easy-to-edit config
* 🛠️ Lightweight and performance-focused

<details>
<summary>📜 Full items list</summary>


* DashBlade --> Iron sword with a dash ability upon right clicking
* FrostBlade --> Diamond sword that freezes enemies for a time on hit after its ability has been activated via right clicking
* RageBlade --> Netherite sword with a rage ability activated via right clicking. Gives the player strenght 2 and makes all hits critical hits
* DashMace --> A mace with a dash ability upon right clicking
* SpiderMace --> A mace that has a % chance to web the opponent on hit
* VoidAxe --> A netherite axe that curses enemies with darkness, slowness and blindness on hit after its ability has been activated via right clicking
* SkyPiercer --> A trident that when thrown dashes the player throu the path of the throw dealing damage to all enemies in a certian range
* MagicSwapper --> An egg that swaps the places of 2 players when one of them hits another with it

! Note / All of the cooldowns, durations and damage amounts can be edited in the config.yml


</details>

---

## 📥 Download

👉 Always download the latest version here:
https://github.com/qd-ducky/CustomItems-PVP-Plugin/releases/latest

---

## ⚙️ Installation

1. Download the latest `.jar` from releases
2. Place it into your `/plugins` folder
3. Start or restart your server
4. Edit the config file generated in `/plugins/CustomItems/`
5. Reload or restart the server

---

## 📄 Configuration Example

```yaml id="lq6v8c"
  dashblade:
    name: "&f&l🪶 Swiftwind Blade"
    cooldown-seconds: 15
    speed: 3.5
    trail-count: 25
```

<details>
<summary>📄 Full config.yml</summary>

```yaml
items:
  frostblade:
    name: "&b&l❄ Frostbound Blade"
    cooldown-seconds: 25
    freeze-seconds: 5

  rageblade:
    name: "&4&l⚔ Crimson Rageblade"
    duration-seconds: 10
    cooldown-seconds: 25

  dashblade:
    name: "&f&l🪶 Swiftwind Blade"
    cooldown-seconds: 15
    speed: 3.5
    trail-count: 25

  dashmace:
    name: "&f&l🔨 Dash Mace"
    cooldown-seconds: 15
    speed: 3.2
    trail-count: 18

  voidaxe:
    name: "&8&l🌙 Void Axe"
    duration-seconds: 10
    cooldown-seconds: 20

  spidermace:
    name: "&7&l🕷 &7&lS&8&lp&f&li&7&ld&8&le&f&lr &f&lM&7&la&8&lc&f&le"
    web-chance-percent: 50

  skypiercer:
    name: "&b&l☁ Sky &3&lPiercer 🗡"
    limit-blocks: 8
    raw-damage: 9.0
    radius: 2.0
    cooldown-seconds: 25

  magicswapper:
    name: "&9&l🔮 Magic Swapper"
    cooldown-seconds: 3
```

</details>

---

## 🎮 Commands

* `/customitem <item>` — Recive a custom item
* `/ci <item>` — Recive a custom item

### Items listed below

* `frostblade`
* `rageblade`
* `dashblade`
* `dashmace`
* `voidaxe`
* `spidermace`
* `skypiercer`
* `magicswapper`


---

## 🔐 Permissions

* `customitem.use` ---> Allows players to use the command /customitem or /ci

### Individual permissions for each custom item below

* `frost.give`
* `rage.give`
* `swiftwind.give`
* `dashmace.give`
* `void.give`
* `spider.give`
* `skypiercer.give`
* `swapper.give`

*! Note / A player needs both the command permission and the item permission to be able to recive it via commands.*

---

## 💡 Notes

* Designed for Paper servers
* Works best for you with a properly configured config
* Performance optimized for real server environments

---

## 💬 Support / Contact

Need help or a custom plugin?

👉 Discord: https://discord.com/users/876238056275984435
Or add: `qd_ducky`

---

## ⭐ Support

If you like this project, consider starring the repository — it helps a lot!

---

## 📜 License

This project is licensed under the MIT License.
