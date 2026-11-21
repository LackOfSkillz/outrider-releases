# Outrider public data packs

**Publication decision:** Gary Mix approved public release of all Outrider data and quest packs on **2026-11-18**. The repository is public. This page distinguishes actual committed source from releases and local-only build products.

| Pack | License | Public standalone source in this repository |
|---|---|---|
| Outrider_Data_Words | English Speller Database (Kevin Atkinson), see pack LICENSE.txt | **Committed**: [Words](Outrider_Data_Words/) |
| Outrider_Data_NPC | Derived from QuestieDB; GPLv3 with upstream historical-contributor caveat | **Committed**: [Outrider_Data_NPC](Outrider_Data_NPC/) |
| Outrider_Data_Gear | Derived from QuestieDB; GPLv3 with upstream historical-contributor caveat | **Committed**: [Outrider_Data_Gear](Outrider_Data_Gear/) |
| Outrider_Data_Mobs | Derived from QuestieDB; GPLv3 with upstream historical-contributor caveat | **Committed**: [Outrider_Data_Mobs](Outrider_Data_Mobs/) |
| Outrider_Data_Nodes | Derived from QuestieDB; GPLv3 with upstream historical-contributor caveat | **Committed**: [Outrider_Data_Nodes](Outrider_Data_Nodes/) |
| Outrider_Data_Dungeons | Derived from QuestieDB; GPLv3 with upstream historical-contributor caveat | **Committed**: [Outrider_Data_Dungeons](Outrider_Data_Dungeons/) |
| Outrider_Data_Quests | Derived from QuestieDB; GPLv3 with upstream historical-contributor caveat | **Committed**: [Outrider_Data_Quests](Outrider_Data_Quests/) |

The November 17 [Outrider family release](https://github.com/LackOfSkillz/outrider-releases/releases/tag/build-20261117-0742) has a downloadable ZIP, but its contents have **not** been extracted and independently reviewed in this publication pass. It is not evidence that all current generator outputs have been committed to this source repository.

## Origin and copyright

Outrider was created by **Gary Mix**. Outrider's original software is made available under GPL-3.0-only. The QuestieDB-originated content is **not** copyrighted by Gary Mix merely because it is included here. See [QuestieDB LICENSE.md](https://github.com/Questie/QuestieDB/blob/master/LICENSE.md), [QuestieDB provenance](https://github.com/Questie/QuestieDB/blob/master/PROVENANCE.md), the [complete GPLv3 license](../LICENSE) and [copyright notice](../COPYRIGHT.md). QuestieDB documents an outstanding historical-contributor rights issue.

To publish the remaining six packs, regenerate or export the actual original build output from the local OAR checkout with `tools/publish_public_packs.py`. The script requires an explicit public-repo checkout and a deliberate commit/push action. Review the preview and generated license/provenance documents before pushing.

No SavedVariables, character or realm names, chat, personal observations, secret tokens, local settings or machine paths should be placed here. The optional `Outrider_Data_Shared` user-observation pack is deliberately **excluded** from automatic publishing pending a separate privacy scrub and explicit review.
