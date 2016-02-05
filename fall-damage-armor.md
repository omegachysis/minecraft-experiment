# Abstract

This experiment was set up in response to a Reddit thread where several competing views are offered about the effect of armor
on fall damage in Minecraft.

The following *will* be tested:
- Is fall damage in Minecraft affected by diamond armor below or at 22 blocks of falling?
- Is fall damage in Minecraft affected by feather falling enchanted boots below or at 22 blocks of falling?
- Do boots modify fall damage differently than other armor below or at 22 blocks of falling?

The following will *not* be tested:
- Is fall damage affected by difficulty setting
- Is fall damage affected by Protection enchantment?
- Whether fall damage is calculated significantly differently at greater than 22 blocks of falling (suspected to be unlikely)

## Variables
- Independent - configuration of armor worn
- Dependent - fall damage taken in Peaceful mode (according to many sources, difficulty setting does not affect fall damage
- Controls:
  - armor tier (diamond)
  - fall height
  - difficulty
  - hunger
  - armor condition
  
# Procedure

- Minecraft 1.8 was used
- Superflat creative map with cheats enabled was used
- A pillar of dirt 22 blocks high was created to maximize damage and reduce percent error
- Gamemode was switched between creative and survival to speed experiment along
- Perform trial by dropping with given armor configuration and fly back up after recording health lost

# Results

All values are measured in units of *half-hearts* - the damage done to the subject.

| Armor Configuration                           | Trial 1 | Trial 2 | Trial 3 | Trial 4 | Trial 5 |
|-----------------------------------------------|---------|---------|---------|---------|---------|
| no armor                                      | 18      | 19      | 19      | 19      | 19      |
| full armor unenchanted                        | 19      | 19      | 19      | 19      | 19      |
| only boots unenchanted                        | 19      | 19      | 19      | 19      | 19      |
| all armor except boots unenchanted            | 19      | 19      | 19      | 19      | 19      |
| all armor with boots with feather falling IV  | 7       | 8       | 5       | 11      | 11      |
| no armor except boots with feather falling IV | 5       | 11      | 13      | 9       | 7       |

It is worth noting for future reference that no armor was damaged during the test.  This appears to give the impression that armor is not damaged from falling.

# Conclusions

- enchanted armor does not affect fall damage below or at 22 blocks of falling
- fall damage can vary by a small amount with armor below or at 22 blocks of falling - probably due to hearts regenerating immediately after damage taken, further research required
- fall damage can vary by a large amount with feather falling IV below or at 22 blocks of falling - odd effect, no explanation for now, futher research required
- fall damage is greatly affected by feather falling IV below or at 22 blocks of falling
- it does not matter whether boots are worn excluding the effects of feather falling IV below or at 22 blocks of falling

It is impossible from this data to conclude whether the results would be different at larger heights, though it is reasonable to assume that it would no be different with the exception of the expected damage increase.
