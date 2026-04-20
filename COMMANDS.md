# 🏁 SupraBot Commands

A complete list of all slash commands available in SupraBot.

---

## 🎲 Gacha & Rewards

| Command | Description |
|---------|-------------|
| `/roll` | Roll for a random car! You get a set number of rolls per hour. If the car is already owned in the server, you can collect Carkera instead. |
| `/daily` | Claim your daily Carkera reward. Resets every 24 hours. |
| `/dailyreset` | Claim your daily roll reset to refill your rolls. Resets every 24 hours. |
| `/resetrolls` | Use one of your roll resets to instantly refill your rolls. |
| `/sparekey` | Use your spare key to reset your claim cooldown. Requires the Spare Key upgrade. |

---

## 🏎️ Garage & Profile

| Command | Description |
|---------|-------------|
| `/me` | View your player profile, including your Carkera balance, garage worth, rolls, cooldowns, and upgrades. |
| `/garage [page] [member]` | Browse your car collection with paginated navigation. You can also view another player's garage. |
| `/search <query>` | Search the global car catalog by name. Returns matching cars with specs, value, and global ranking. |
| `/top` | Browse the full car catalog ranked by global value, with paginated navigation. |

---

## 💰 Economy & Trading

| Command | Description |
|---------|-------------|
| `/sell <car>` | Sell a car from your garage for Carkera. Shows a detailed value breakdown including global value, parts refund, and any bonuses. |
| `/give <player> [car] [carkera]` | Gift a car and/or Carkera to another player. Requires confirmation before the transfer goes through. |
| `/trade <player> [mycar] [theircar] [myoffer] [theiroffer]` | Propose a trade with another player. You can exchange cars, Carkera, or both. The other player must accept the trade. |

---

## 🔧 Tuning & Upgrades

| Command | Description |
|---------|-------------|
| `/tune <car> <group>` | Install performance parts and visual modifications on your car. Available categories: Exhaust, Spoiler, Wheels, Intake, Brakes, Bodywork. Parts increase your car's value. |
| `/upgrades` | Browse and purchase permanent player upgrades such as extra rolls, bigger garage capacity, the Spare Key, and more. |
| `/upgradesinfo` | A detailed guide explaining what each player upgrade does, its cost, and requirements. |
| `/refund <upgrade>` | Sell back a player upgrade for 70% of its original cost. Cannot refund upgrades that are prerequisites for others you own. |
| `/refundparts <car>` | Remove installed performance parts from a car and receive a partial refund. |

---

## 📊 Server Rankings

| Command | Description |
|---------|-------------|
| `/servertop` | Leaderboard of the most valuable cars currently owned in this server. |
| `/servertopgarage` | Ranking of players by total garage value, showing each player's worth and car count. |
| `/serverprogress` | Overview of the server's overall progress — total cars acquired, total server value, and player count. |

---

## 🛠️ Utility & Support

| Command | Description |
|---------|-------------|
| `/help [command]` | Show all available commands or get detailed instructions for a specific command. |
| `/suggestfix <car_id> [hp] [top_speed] [engine] [displacement]` | Suggest a correction for a car's stats. The developer will review and apply valid fixes. |
| `/invite` | Get the bot's invite link and a link to vote on Top.gg. |
| `/vote` | Check your current roll resets and get a direct link to vote for SupraBot. |

---

## 📝 Notes

- Arguments in `<angle brackets>` are **required**.
- Arguments in `[square brackets]` are **optional**.
- Most commands with a `car` argument support **autocomplete** — just start typing the car name.
- All in-game currency (Carkera) and items are virtual and hold no real-world value.
