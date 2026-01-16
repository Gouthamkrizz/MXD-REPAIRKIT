🔧 MXD RepairKit

MXD RepairKit is a lightweight and optimized FiveM vehicle repair script built for the QBCore framework with full ox_inventory support. It allows players to repair nearby vehicles using a repair kit item, complete with animations and a progress bar for an immersive experience.

✨ Features

✅ QBCore framework support

🎒 ox_inventory usable item support

🚗 Repairs nearest vehicle when used close to it

⏳ QB Progressbar integration

🎬 Repair animation while fixing the vehicle

⚙️ Fully configurable settings

🚀 Optimized & low resource usage

📦 Dependencies

Make sure you have the following resources installed:

qb-core

ox_inventory

qb-progressbar

qb-menu (optional, if extended later)

📁 Installation

Download or clone this repository:

git clone https://github.com/yourname/mxd-repairkit


Place the folder into your resources directory.

Add the resource to your server.cfg:

ensure mxd-repairkit


Add the repair kit item to ox_inventory.

🎒 ox_inventory Item Example
['repairkit'] = {
    label = 'Repair Kit',
    weight = 2000,
    stack = true,
    close = true,
    description = 'Used to repair vehicles',
}

⚙️ Configuration

All important settings such as:

Repair duration

Animation dictionary & name

Repair amount

Item name

can be adjusted easily in the config.lua file.

🕹️ How It Works

Player uses the repairkit item from ox_inventory

Script checks for a nearby vehicle

Progress bar & animation start

Vehicle gets repaired on completion

Repair kit is removed (configurable)

🧠 Framework

Framework: QBCore

Inventory: ox_inventory

📜 License

This project is open-source. You are free to modify and use it for your server.
Selling this script without permission is not allowed.

❤️ Credits

Developed by MXD Developments
Feel free to contribute or report issues!
