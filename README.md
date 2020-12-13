<p align="center"><img src=".github/assets/batteries.png" /></p>
The Batteries Mod adds a few tiers of Battery items that the player can charge using Forge Energy (FE) that, when enabled and in the player's inventory, will provide power to other FE-based items automatically.

Shift+Right-Click with a Battery in-hand to enable/disable. An enabled battery will have a glowing Enchantment effect to indicate it is ready to charge other items.
A Creative Battery is also available.

Right-Click in the world with a battery in-hand to access its GUI (pictured above). Here, you can do the following:
  - Insert up to 9 references to items that you want to charge (or not) with this battery.
  - Toggle various charging behaviors. In order:
    - Whitelist/blacklist: Whitelist will only charge items that are referenced in the battery's inventory, while blacklist will charge everything except those item references
    - Charge Hotbar: Enable/disable charging of items in the hotbar
    - Charge Inventory: Enable/disable charging of items in the rest of the default inventory
    - Charge Armor: Enable/disable charging of worn armor
    - Charge Nearby Machines: Enable/disable charging of energy-capable machines in a radius around the user. Respects sidedness of the machine, ie if the machine only takes energy from the front, you'll need to stand in front of it to charge it. Spawns particles to let you know it's working.
    - Charge Fairly: Enable/disable fair charging. When disabled, the battery will be drained without restriction to charge items in your inventory. When enabled, the battery will not charge an item that has more energy stored than it currently does. For example, a battery with 100,000 FE remaining will not charge an item that has 150,000 FE in it -- the intention is to prevent large-capacity and/or fast-draining items from sucking up all the battery power.
  
Starting with v1.2.0, a new Charger block is available to charge your batteries. Insert a Battery into the Charger to use it as a stationary energy source for machines (not included) or to charge the battery. A Battery in a Charger can be charged from other mods' power generation/transfer methods, or by enabling the "Creative Charger" config option to allow the Charger to generate energy out of thin air!
Batteries will charge any item that accepts Forge Energy.

Starting with v1.3.0, a new tier of battery (Ender Battery) and a new block (Ender Battery Uplink) are available. The Ender Battery can be linked to an Ender Battery Uplink, and any energy received by the Uplink will be sent to the battery.