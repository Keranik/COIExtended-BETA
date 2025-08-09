# COIExtended Unification FAQ: Update 3 and the 65k Product Limit

Welcome to the COIExtended Unification FAQ! The unified COIExtended core mod enters public beta on August 9, 2025, combining several modlets into a comprehensive overhaul, made possible by the game’s new 65,000 product limit. This FAQ outlines the unification process, beta details, and what users can expect. Whether you’re a seasoned mod user or new to COIExtended, this guide keeps you informed in a clear and approachable way.

## Why is COIExtended being unified into a core overhaul mod?

The original split into standalone modlets (e.g., COIExtended.Solar, COIExtended.StoragePlus) was due to the game’s 255 product limit, which restricted mod additions. With Update 3 adding 40 new products, only 25 slots remained, forcing cuts for compatibility. The new 65,000 product limit removes this constraint, enabling COIExtended’s full vision. Unifying modlets reduces maintenance overhead—managing one core mod is simpler than handling 12 separate Unity projects for AssetBundles. This enables faster updates, less mod bloat, and seamless feature additions (e.g., a Tier 3 truck).

## Which mods are included in the unified core overhaul mod?

The core COIExtended overhaul mod includes:
- **COIExtended.Logistics**: Enhanced logistics chains, with rewritten and improved Update 2 features for Update 3.
- **COIExtended.World**: Random world generation, ship combat, and upgrades.
- **COIExtended.Solar**: Solar power systems and mechanics.
- **COIExtended.Structures**: Additional buildings and structures to expand gameplay.

The initial beta includes the first part of the Agriculture "DLC"—fishing. Additional Agriculture features (new crops, animals, logistics chains) will be added incrementally during the beta. Future updates will integrate into the core mod for a seamless, vanilla-feel experience.

## Which mods remain standalone, and why?

The following mods remain standalone to preserve their unique functions:
- **COIExtended.ItemSink**: Kept separate to maintain the core mod’s vanilla feel, as it introduces cheat-like mechanics. It cannot merge with COIExtended.Cheats due to prototype restrictions preventing mod removal from saves.
- **COIExtended.Cheats**: Offers cheat features, with optional integration for additional functionality with the core mod.
- **COIExtended.Tweaks**: Provides non-cheat quality-of-life features (e.g., speed controls) for players who want tweaks without cheating.
- **COIExtended.StoragePlus**: A UI-focused mod with cheat-like storage capacity adjustments for customization without the full overhaul.
- **COIExtended.Difficulty**: Adds customizable difficulty options for a near-vanilla experience with variety.

These modlets cater to specific playstyles and offer flexibility for players who prefer minimal modding. They are included in the beta for compatibility testing but will only receive compatibility updates for existing saves, not new core mod features.

## What’s new in the unified core overhaul mod?

The unified core mod restores the Update 2 vision (including 40+ products) and expands it significantly. Many Update 2 features were integrated into the base game, so the core mod enhances modlet content (e.g., Logistics, World, Solar, Structures) with better performance for Update 3. New mod settings allow extensive customization, including:
- Liquid dump recipe multiplier
- Food market capacity multiplier
- Allowing all product storage
- Removing throughput limits
- Transport maintenance and electricity multipliers
- Belt speeds
- Train capacity and build speed

Suggest more settings in the game’s official Discord #modding channel! The Agriculture "DLC" starts with fishing in the beta, with crops, animals, and logistics chains (over 70 products) to follow incrementally.

## How do I access the public beta?

The beta is available starting August 9, 2025, on the [COIExtended-BETA GitHub repository](https://github.com/Keranik/COIExtended-BETA). Download the core mod and standalone modlets from the repository’s release page (look for the beta version tag). Join the game’s official [Discord server](https://discord.com/invite/JxmUbGsNRU) in the #modding channel for updates, beta instructions, and support. Check my [Patreon](https://www.patreon.com/Keranik) for additional details and ways to support development.

## How do I install the unified core mod?

To ensure a clean installation:
1. **Remove all mods** from your game’s mod directory.
2. **Download and install the core mod** from the [COIExtended-BETA repository](https://github.com/Keranik/COIExtended-BETA).
3. **Start a new game** with the unified core mod, as existing saves are incompatible.

Failure to uninstall standalone modlets may cause conflicts. No changes to system requirements or performance are expected compared to previous modlets.

## What does the transition look like for current modlet users?

Existing saves using standalone modlets (e.g., COIExtended.Solar, COIExtended.StoragePlus) or Update 2 are not compatible with the unified core mod after testing. **Users must start new games** with the core mod and remove all standalone modlets from the mod directory to avoid issues. This is necessary for stability and to realize the core mod’s potential. Standalone modlets will receive compatibility updates for existing saves for a limited time, pushed to the main branch post-beta, but new features are exclusive to the core mod.

## What’s the timeline for the beta and full release?

- **Public Beta**: Starts August 9, 2025, via the [COIExtended-BETA repository](https://github.com/Keranik/COIExtended-BETA).
- **Full Release**: As soon as possible after the beta, once major issues are resolved.

Join the beta and share feedback to shape the final release! Contact me (Keranik) in the game’s official Discord #modding channel.

## Are there any known issues in the beta?

Some items in the unified core mod lack visual representations on belts in the game world. This will be addressed during the beta. Report other bugs, performance issues, or balance concerns via Discord or GitHub issues.

## How do I provide feedback during the beta?

Submit feedback in the #modding channel on the game’s official [Discord server](https://discord.com/invite/JxmUbGsNRU), via DMs to Keranik, or by filing issues on the [COIExtended-BETA GitHub repository](https://github.com/Keranik/COIExtended-BETA). GitHub Discussions will not be monitored. Focus on:
- Bugs (e.g., crashes, visual issues)
- Performance (e.g., lag, load times)
- Balance (e.g., fishing mechanics, mod settings)
- Suggestions for additional mod settings

Your feedback is vital for refining the core mod!

## Will Update 2 saves or modlet saves work with the unified mod?

No. Update 2 saves are incompatible with Update 3, and modlet saves are not compatible with the unified core mod. Users must start new games with the core mod after uninstalling standalone modlets. Modlets will receive compatibility updates for existing saves for a limited time, but new features are exclusive to the core mod.

## What about hotfixes for Update 3 modlets?

Hotfixes for Update 3 modlets (e.g., StoragePlus saving/export fixes, Tweaks speed control/menu fixes) are specific to standalone versions and not backported to the core mod, which includes improved versions of these fixes. Standalone modlets will receive compatibility updates for existing saves for a limited time, pushed to the main branch post-beta, but won’t get new core mod features. Start new games with the core mod for the latest updates.

## How is the unified mod future-proofed?

The core mod’s framework adapts to base game changes with minimal code tweaks, leveraging the 65k product limit for growth. It’s designed to handle future updates, like the Agriculture "DLC," without compatibility issues, ensuring COIExtended remains a robust addition.

## How does user feedback influence this unification?

User feedback drove key changes:
- **Copy/Paste Settings**: Enabled via mod settings for in-game entity configuration.
- **Customizable Features**: Mod settings allow enabling/disabling and fine-tuning features, offering more control than modlets.
- **Reduced Mod Bloat**: Unification streamlines updates and testing, addressing concerns about managing multiple modlets.

Suggest more mod settings in the #modding channel!

## What new content is planned?

The Agriculture "DLC" starts with fishing in the beta, with new crops, animals, and logistics chains (over 70 products) added incrementally during the beta. This ensures frequent updates and feedback integration, keeping content fresh.

## How will compatibility with other mods work?

All COIExtended mods (core and standalone) are fully compatible with each other. Compatibility with non-COIExtended mods is the responsibility of their authors. Modders can contact me (Keranik) in the #modding channel on Discord for collaboration. The 65k product limit reduces conflicts by providing ample product space.

## What challenges are expected, and how will they be addressed?

The main challenge is transitioning users from modlets to the core mod, as existing saves are incompatible. I’ll provide clear guides and support in the #modding channel to explain starting new games and uninstalling modlets. Standalone modlets will remain supported for a short period with compatibility updates, pushed to the main branch post-beta, to avoid disrupting existing saves. New features are core mod-exclusive, and clear communication will address confusion.

## How can users get involved or learn more?

Join the public beta starting August 9, 2025, via the [COIExtended-BETA repository](https://github.com/Keranik/COIExtended-BETA). Share feedback or report issues in the #modding channel on the game’s official [Discord server](https://discord.com/invite/JxmUbGsNRU) or via [GitHub issues](https://github.com/Keranik/COIExtended-BETA). Check my [Patreon](https://www.patreon.com/Keranik) for updates and support options. Modders can reach out for compatibility collaboration. Your input shapes COIExtended’s future!

## TL;DR: Key Points
- **Beta Release**: Starts August 9, 2025, on the [COIExtended-BETA repository](https://github.com/Keranik/COIExtended-BETA). Includes unified modlets (Logistics, World, Solar, Structures), standalone modlets, and fishing from the Agriculture "DLC."
- **Installation**: Remove all mods, download core mod from the repository, and start a new game. Existing saves are incompatible.
- **Standalone Mods**: ItemSink, Cheats, Tweaks, StoragePlus, and Difficulty remain separate, with compatibility updates for existing saves but no new core mod features.
- **New Features**: Enhanced Update 2 content, customizable mod settings (e.g., belt speeds, train capacity), and incremental Agriculture "DLC" releases.
- **Feedback**: Submit via #modding channel on [Discord](https://discord.com/invite/JxmUbGsNRU) or [GitHub issues](https://github.com/Keranik/COIExtended-BETA). Focus on bugs, performance, balance, and setting suggestions.
- **Known Issue**: Some items lack visual representations on belts.
- **Get Involved**: Join the beta, share feedback, and contact Keranik on Discord or Patreon.

Thank you for your support as COIExtended evolves into a bigger, better, and seamless experience!
