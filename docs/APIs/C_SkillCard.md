# C_SkillCard



**Members:** 15  •  **Functions:** 15  •  **Interface calls:** 20 (across up to 2 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| GetCardAtIndex | function | C_SkillCard.GetCardAtIndex(arg1, arg2) | if C_SkillCard.GetCardAtIndex("SKILL_CARD_DEFAULT_NORMAL", i-1) == 0 then |
| GetCardCount | function | C_SkillCard.GetCardCount(...) |  |
| GetCardID | function | C_SkillCard.GetCardID(arg1) | local cardID, cardRank = C_SkillCard.GetCardID(itemID) |
| GetCardRankAtIndex | function | C_SkillCard.GetCardRankAtIndex(...) |  |
| GetCardSpellID | function | C_SkillCard.GetCardSpellID(arg1, arg2) | local spellID = C_SkillCard.GetCardSpellID(cardID, cardRank) |
| GetMaxCardCount | function | C_SkillCard.GetMaxCardCount(arg1) | for i = 1, C_SkillCard.GetMaxCardCount("SKILL_CARD_DEFAULT_NORMAL") do |
| GetSkillCardInfo | function | C_SkillCard.GetSkillCardInfo(arg1, arg2) | return C_SkillCard.GetSkillCardInfo(cardID, rank) |
| GetSkillCardInfoAtIndex | function | C_SkillCard.GetSkillCardInfoAtIndex(arg1, arg2) | return C_SkillCard.GetSkillCardInfoAtIndex(cardType, index) |
| GetSkillCardQuality | function | C_SkillCard.GetSkillCardQuality(arg1, arg2) | local quality = C_SkillCard.GetSkillCardQuality(cardData.CardID, displayedRank) or cardData.Quality |
| IsCardAtIndexActive | function | C_SkillCard.IsCardAtIndexActive(arg1, arg2) | return C_SkillCard.IsCardAtIndexActive(cardType, index) |
| IsCardAtIndexBlocked | function | C_SkillCard.IsCardAtIndexBlocked(arg1, arg2) | return C_SkillCard.IsCardAtIndexBlocked(isGolden and self.cardTypeGolden or self.cardTypeNormal, ... |
| IsCardedID | function | C_SkillCard.IsCardedID(...) |  |
| IsCardedSpellID | function | C_SkillCard.IsCardedSpellID(arg1) |  |
| RemoveCardAtIndex | function | C_SkillCard.RemoveCardAtIndex(arg1, arg2) | C_SkillCard.RemoveCardAtIndex(cardType, index) |
| SetCardAtIndex | function | C_SkillCard.SetCardAtIndex(arg1, arg2, arg3) | C_SkillCard.SetCardAtIndex(cardType, index, cardID) |



## Notes


- 3 member(s) had a runtime probe marked `ok` in the scan data.
