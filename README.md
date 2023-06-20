# Vanilla Fixes

A resource pack for Minecraft which aims to fix many of the bugs and issues present in the game's default assets, ranging from texture errors and inconsistencies, model issues, sound event problems, and even typos in the game's text to the many other overlooked details in Minecraft's assets.

This pack is currently built for the latest stable release of Minecraft: Java Edition, which is currently 1.20.1. Text fixes are only complete in English (EN-US), although translations are welcome.

*Although Vanilla Fixes tries to be as widely compatible with resource packs as possible, certain changes may need to be made to packs to ensure full compatibility. Please analyze the changes made by Vanilla Fixes carefully when using it with your own pack.*

## Fixes and Changes

This pack fixes the following issues:

### Texture/Model Issues

* [MC-2614](https://bugs.mojang.com/browse/MC-2614) - Chest walking/breaking particles use mismatched textures
* [MC-57935](https://bugs.mojang.com/browse/MC-57935) - Upside-down stairs have their top and bottom textures flipped
* [MC-68302](https://bugs.mojang.com/browse/MC-68302) - Multiple blocks are inconsistently shaded
* [MC-109087](https://bugs.mojang.com/browse/MC-109087) - Anvils, bells, brewing stands, chorus flowers, iron bars, and torches don't use `cullface` where possible
* [MC-120417](https://bugs.mojang.com/browse/MC-120417) - Dragon egg texture is partially squished by model
* [MC-122701](https://bugs.mojang.com/browse/MC-122701) - Sunflower heads are stretched relative to their texture
* [MC-144327](https://bugs.mojang.com/browse/MC-144327) - The bottom ends of a blaze's rods are miscolored
* [MC-137957](https://bugs.mojang.com/browse/MC-137957) - Sandstone and red sandstone walls use their side texture on their top and bottom
* [MC-150572](https://bugs.mojang.com/browse/MC-150572) - Cacti's bottom texture uses outdated palette
* [MC-160720](https://bugs.mojang.com/browse/MC-160720) - Bedrock layer of End Crystal texture not updated with texture update
* [MC-177452](https://bugs.mojang.com/browse/MC-177452) - Redstone repeaters render unneeded faces
* [MC-177453](https://bugs.mojang.com/browse/MC-177453) - Redstone comparators render unneeded faces
* [MC-182383](https://bugs.mojang.com/browse/MC-182383) - Blackstone walls use their side texture on their top and bottom
* [MC-183421](https://bugs.mojang.com/browse/MC-183421) - Bell stands' textures are stretched
* [MC-194192](https://bugs.mojang.com/browse/MC-194192) - Potted cacti have a different bottom texture than other flower pots
* [MC-198202](https://bugs.mojang.com/browse/MC-198202) - Options & world creation menu background textures don't match regular dirt texture
* [MC-199238](https://bugs.mojang.com/browse/MC-199238) - Dragon eggs render unneeded faces and don't use `cullface` where possible
* [MC-203483](https://bugs.mojang.com/browse/MC-203483) - Pumpkin stem and attached melon stem textures not updated with texture update
* [MC-205095](https://bugs.mojang.com/browse/MC-205095) - Surface of cauldron liquid not visible when submerged
* [MC-208191](https://bugs.mojang.com/browse/MC-208191) - Cakes with candles render an unneeded face
* [MC-213797](https://bugs.mojang.com/browse/MC-213797) - Large dripleaves phase through their stems when bent
* [MC-214625](https://bugs.mojang.com/browse/MC-214625) - Unlit redstone torches are unaffected by ambient occlusion
* [MC-221851](https://bugs.mojang.com/browse/MC-221851) - Tilted dripleaves are mirrored incorrectly from below
* [MC-222943](https://bugs.mojang.com/browse/MC-222943) - Candle wicks have incorrect and inconsistent mirroring behavior
* [MC-224433](https://bugs.mojang.com/browse/MC-224433) - Fast clouds' texture background isn't fully transparent
* [MC-225796](https://bugs.mojang.com/browse/MC-225796) - Deepslate random rotation behavior is inconsistent across axes
* [MC-232251](https://bugs.mojang.com/browse/MC-232251) - Attached melon/pumpkin stem models are asymmetric
* [MC-238242](https://bugs.mojang.com/browse/MC-238242) - Minimized inventory effect panels have an extra pixel in their corners
* [MC-238734](https://bugs.mojang.com/browse/MC-238734) - Fence gates render unneeded faces and don't use `cullface` where possible
* [MC-244789](https://bugs.mojang.com/browse/MC-244789) - Checkboxes' backgrounds are inconsistent
* [MC-248583](https://bugs.mojang.com/browse/MC-248583) - Iron golem's vines don't line up between body and arms
* [MC-249682](https://bugs.mojang.com/browse/MC-249682) - Piglin snout pattern can be seen on the back of banners
* [MC-260888](https://bugs.mojang.com/browse/MC-260888) - Recipe book button's appearance is inconsistent between menus

### Localization/Subtitle Issues

* [MC-167375](https://bugs.mojang.com/browse/MC-167375) - Baby turtle subtitles are inconsistent in format with other baby animal subtitles
* [MC-177078](https://bugs.mojang.com/browse/MC-177078) - Minecart riding noise lacks subtitles
* [MC-177079](https://bugs.mojang.com/browse/MC-177079) - Ghast affectionate scream *(unused)* lacks subtitles
* [MC-177094](https://bugs.mojang.com/browse/MC-177094) - Wolf howling noise *(unused)* lacks subtitles
* [MC-177522](https://bugs.mojang.com/browse/MC-177522) - Wolf panting/whining noises are imprecisely subtitled
* [MC-184681](https://bugs.mojang.com/browse/MC-184681) - Single biome world customization screen still refer to 'buffet' worlds
* [MC-193753](https://bugs.mojang.com/browse/MC-193753) - Respawn anchor ambient sound subtitle *(unused)* refers to it as a portal
* [MC-194948](https://bugs.mojang.com/browse/MC-194948) - Block breaking subtitle is in past tense, unlike other subtitles
* [MC-195836](https://bugs.mojang.com/browse/MC-195836) - Certain subtitles use incorrect tense/format
* [MC-204050](https://bugs.mojang.com/browse/MC-204050) - Hitting amethyst block with projectile is imprecisely subtitled
* [MC-204124](https://bugs.mojang.com/browse/MC-204124) - Underwater minecart riding noise lacks subtitles
* [MC-206439](https://bugs.mojang.com/browse/MC-206439) - Fishing bobber is referred to inconsistently across various subtitles
* [MC-218415](https://bugs.mojang.com/browse/MC-218415) - Redstone torch fizzing is imprecisely subtitled
* [MC-219541](https://bugs.mojang.com/browse/MC-219541) - Horse armor equipping subtitle is improperly capitalized
* [MC-221696](https://bugs.mojang.com/browse/MC-221696) - Generic long falling subtitle is in past tense, unlike other subtitles
* [MC-222876](https://bugs.mojang.com/browse/MC-222876) - Buffet (single biome) world customization screen title is inconsistently capitalized
* [MC-225314](https://bugs.mojang.com/browse/MC-225314) - Ender chest opening/closing subtitle refers to chests instead of ender chests
* [MC-226770](https://bugs.mojang.com/browse/MC-226770) - Zombie banging on iron door noise *(unused)* is imprecisely subtitled
* [MC-226772](https://bugs.mojang.com/browse/MC-226772) - Shulker box opening/closing subtitle refers to shulkers instead of shulker boxes
* [MC-226773](https://bugs.mojang.com/browse/MC-226773) - Armor stand placing/hitting/breaking sounds use generic subtitles
* [MC-226774](https://bugs.mojang.com/browse/MC-226774) - Armor stand falling subtitle is imprecise
* [MC-226775](https://bugs.mojang.com/browse/MC-226775) - Candle extinguishing subtitle is imprecise
* [MC-235064](https://bugs.mojang.com/browse/MC-235064) - "Singleplayer" is misspelled in Realms world download dialogue
* [MC-237590](https://bugs.mojang.com/browse/MC-237590) - "Chunks" is improperly capitalized in options menu render/simulation distance sliders
* [MC-241919](https://bugs.mojang.com/browse/MC-241919) - Middle initial punctuation is inconsistent in the credits
* [MC-250194](https://bugs.mojang.com/browse/MC-250194) - 'A Complete Catalog' advancement title uses the British spelling of "catalog"
* [MC-250197](https://bugs.mojang.com/browse/MC-250197) - 'Bee Our Guest' advancement description refers to glass bottle inconsistently to other advancements
* [MC-250968](https://bugs.mojang.com/browse/MC-250968) - Goat horn breaking subtitle refers to item instead of entity as sound source
* [MC-251754](https://bugs.mojang.com/browse/MC-251754) - "Third-party" is inconsistently spelled throughout game text

## License

The modifications to default Minecraft assets in this pack are licensed under the [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) license. Mojang Studios, however, is exempt from this licensing and may use this pack's content however they choose.
