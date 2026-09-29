# Cobblemon Experiment

A large Fabric 1.21.1 Cobblemon modpack focused on exploration, collecting, breeding, shiny hunting, cooking, building, cosmetics, custom progression, gacha systems, structures, and general Pokémon chaos.

This pack is distributed as a Modrinth `.mrpack`.

## Version

- Modpack: **1.2.0**
- Minecraft: **1.21.1**
- Fabric Loader: **0.19.2**
- Cobblemon: **1.7.3**

## Installation

1. Download the latest `.mrpack` release from GitHub.
2. Open the Modrinth App.
3. Select **Add content / Import from file**.
4. Import the `.mrpack`.
5. Let Modrinth download all indexed mods and resources.
6. Launch the instance.

The pack already includes its required configs, datapacks, resource packs and shader packs.

---

# Datapacks

Cobblemon Experiment includes several Cobblemon content and cosmetic datapacks.

## Included Cobblemon datapacks

- Storybook Hybrids — v1.15
- PokePaintings — v1.1
- Ceruledge Knight — v2.0
- Pinkan Pokémon Pack — v1.5
- Tually's Cosmetics — v1.11
- Extra Paradox Mons — 1.7
- CobblemonMoreCosmetics — v1.1.7
- Muddie's Cosmetics
- Syn. Eevees — v0.1.0
- Styles Upon Styles — v1.6.1
- Cobblemon Cosmetic Expansion — v2.0

Several of these packs also contain resource-pack assets such as models,
textures or cosmetic variants.

---

# Custom Cobblemon Experiment Datapacks

These datapacks were made specifically for this modpack.

## ShebisCobbleGamble v0.3

A custom expansion for **Cobbled Gacha**.

It modifies the Pokémon pools used by:

- Gacha Machine 4
- Rocket Ball

### Shiny system

Every supported Pokémon entry has both a normal and shiny version.

For each species pair:

- Normal weight = original weight × 511
- Shiny weight = original weight

This gives the shiny entry a **1 / 512 share within that species pair**.

The datapack also adds Legendary / Mythical jackpot entries to the
Cobbled Gacha pools.

### Capsule bonus loot

ShebisCobbleGamble also adds a separate addon reward pool to capsules,
without replacing the original Cobbled Gacha rewards.

Bonus reward chance:

- A1: 35%
- A2: 50%
- A3: 65%
- A4: 80%
- A5: 100%

Added reward categories include:

- Cobbled Gacha yarns
- Cobblemon Cards booster packs
- God Pack Essence / God Pack Ticket
- Lucky Block Cobblemon rewards
- My Lucky Block
- CobbleCuisine items
- SimpleTMs
- Bottle Caps
- Gold Bottle Caps
- Mega Showdown items
- Mega Stones
- Z-Crystals
- Dynamax-related items
- transformation accessories
- Legendary Monuments-related rewards

Mega Showdown rewards are distributed by progression tier, with basic
resources appearing earlier and rarer / more specialized items appearing
in higher capsules.

---

## ShebisCobbleGamble Food Expansion v0.4

An addon for **ShebisCobbleGamble v0.3**.

Both datapacks must remain enabled.

This expansion creates a dedicated food reward family using items from
the cooking and food mods included in Cobblemon Experiment.

Food is divided into three capsule tiers:

### Verdant Capsule — Tier 1

Raw and basic ingredients, including:

- fruits
- vegetables
- crops
- seeds
- raw ingredients
- basic pantry items

### Citrine Capsule — Tier 2

Processed and intermediate ingredients, including:

- cooked ingredients
- dairy
- juices
- dough
- sauces
- prepared components
- cooking intermediates

### Roseate Capsule — Tier 3

Finished and premium foods, including:

- prepared meals
- desserts
- drinks
- soups and stews
- sandwiches
- premium dishes

Food-family weights:

- Verdant: 30
- Citrine: 15
- Roseate: 6

Total food-family weight: **51**

The datapack uses optional item references so missing registry IDs do not
invalidate an entire food tier.

---

## ShebisLuckyWorldgen v0.1

A lightweight world-generation tweak for the Lucky Block mods used in
Cobblemon Experiment.

It increases the frequency of Lucky Blocks appearing naturally in newly
generated chunks.

### Cobblemon Lucky Block

Worldgen rarity changed from:

`235 -> 80`

Approximately **2.94× more frequent**.

### My Lucky Block

Surface worldgen rarity changed from:

`48 -> 32`

Approximately **1.5× more frequent**.

### Important

This datapack does **not** modify:

- Lucky Block loot pools
- events
- Pokémon chances
- shiny chances
- legendary pools

It only changes world-generation frequency.

Changes only affect **newly generated chunks**.

---

# Resource Packs

The modpack includes a large number of visual resource packs.

Some are standalone visual packs while others provide assets required by
Cobblemon addons.

Notable included resource packs:

- BetterShinyMon v8
- E19 Cobblemon Minimap Icons
- Even Better Enchants
- Cobblemon Cosmetic Expansion
- Muddie's Cosmetics
- Cosmo's Comfy Cherry GUI
- Better Vanilla Building Remake
- PokePaintings
- Ceruledge Knight
- Emissive Trims
- Pinkan Pokémon Pack
- Emissive Cobblemon Ores
- Extra Paradox Mons
- Storybook Hybrids
- Cobblemon Music Pack
- Pink Quartz Trims
- Cobblemon Pink Pastel
- Styles Upon Styles
- Shiny Gholdengo Fix
- Pink Netherite
- CobblemonMoreCosmetics
- Fairy Wings Elytra
- Tually's Cosmetics

`CloudianMons_1.3.zip` is included in the instance but currently disabled.

Some additional resource packs visible in Minecraft are built directly
into mods and do not need to be downloaded separately.

---

# Shader Packs

The instance includes:

- Complementary Unbound
- Rethinking Voxels
- Photon

Shaders are optional and may have a significant performance impact.

---

# Notes

Cobblemon Experiment is intentionally a large gameplay-focused modpack.

The goal is not to be minimalist.

It is built around:

- Pokémon collecting
- shiny hunting
- breeding
- Mega Evolution
- Dynamax / Gigantamax systems
- custom gacha rewards
- Lucky Blocks
- Fakemon and cosmetic forms
- exploration and structures
- cooking
- building and decoration
- quality-of-life features
- questionable levels of Pokémon-related industrialization

In other words:

**maximum creature collecting while still keeping the instance playable.**

---

# Updating Custom Datapacks

If manually replacing one of the custom datapacks in an existing world:

1. Remove the older version.
2. Add the new `.zip`.
3. Restart the world/server or use `/reload` where appropriate.
4. Run:

`/datapack list`

to confirm the correct version is active.

Do not keep multiple versions of the same Shebis datapack enabled at the
same time.

---

# Credits

Cobblemon Experiment contains mods, datapacks, resource packs and other
content made by many different creators.

All third-party mods and assets belong to their respective authors.

The custom datapacks:

- ShebisCobbleGamble
- ShebisCobbleGamble Food Expansion
- ShebisLuckyWorldgen

were created specifically for Cobblemon Experiment.

This project is not affiliated with Mojang, Microsoft, Nintendo,
Game Freak, The Pokémon Company, Cobblemon or Modrinth.
