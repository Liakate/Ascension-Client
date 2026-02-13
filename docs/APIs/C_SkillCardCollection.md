# C_SkillCardCollection



**Members:** 21  •  **Functions:** 21  •  **Interface calls:** 26 (across up to 3 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| CanClaimPendingSkillCardAtIndex | function | C_SkillCardCollection.CanClaimPendingSkillCardAtIndex(...) |  |
| CanPurchaseSealedCard | function | C_SkillCardCollection.CanPurchaseSealedCard(arg1, arg2) | local canPurchase, reason = C_SkillCardCollection.CanPurchaseSealedCard(cardType, 1) |
| CanPurchaseSealedCardBoosterPack | function | C_SkillCardCollection.CanPurchaseSealedCardBoosterPack(arg1) | local canPurchase, errors = C_SkillCardCollection.CanPurchaseSealedCardBoosterPack(self.claimAmount) |
| ClaimAllPendingSkillCards | function | C_SkillCardCollection.ClaimAllPendingSkillCards(...) |  |
| ClaimPendingSkillCard | function | C_SkillCardCollection.ClaimPendingSkillCard(arg1) | dprint("C_SkillCardCollection.ClaimPendingSkillCard "..UUID) |
| GetBonusSealedCardPacksProgress | function | C_SkillCardCollection:GetBonusSealedCardPacksProgress() | return C_SkillCardCollection:GetBonusSealedCardPacksProgress()*100 |
| GetMaxNumPurchasableSealedCardBoosterPacks | function | C_SkillCardCollection.GetMaxNumPurchasableSealedCardBoosterPacks() | self.PurchaseButton.UpButton:SetEnabled(self.claimAmount < C_SkillCardCollection.GetMaxNumPurchas... |
| GetMaxRank | function | C_SkillCardCollection.GetMaxRank(...) |  |
| GetNumPendingSkillCards | function | C_SkillCardCollection.GetNumPendingSkillCards() | return C_SkillCardCollection.GetNumPendingSkillCards() |
| GetNumSkillCards | function | C_SkillCardCollection.GetNumSkillCards(arg1) | return C_SkillCardCollection.GetNumSkillCards(cardType) |
| GetPendingSkillCardAtIndex | function | C_SkillCardCollection.GetPendingSkillCardAtIndex(arg1) | return C_SkillCardCollection.GetPendingSkillCardAtIndex(index) |
| GetProgress | function | C_SkillCardCollection.GetProgress(arg1) | local progress = C_SkillCardCollection.GetProgress(cardID) |
| GetSealedCardBoosterPackCost | function | C_SkillCardCollection.GetSealedCardBoosterPackCost(arg1) | local cost = C_SkillCardCollection.GetSealedCardBoosterPackCost(self.claimAmount) |
| GetSealedCardCost | function | C_SkillCardCollection.GetSealedCardCost(arg1, arg2) | local itemID, count = C_SkillCardCollection.GetSealedCardCost(cardType, 1) |
| GetSkillCardAtIndex | function | C_SkillCardCollection.GetSkillCardAtIndex(arg1, arg2) | return C_SkillCardCollection.GetSkillCardAtIndex(cardType, index) |
| HasAnySkillCardsCollected | function | C_SkillCardCollection.HasAnySkillCardsCollected(arg1) | return C_SkillCardCollection.HasAnySkillCardsCollected(cardType) |
| IsCollected | function | C_SkillCardCollection.IsCollected(arg1) | if (C_SkillCardCollection.IsCollected(self:GetCardID())) and (cardData.CollectedRank == cardData.... |
| PurchaseAllSealedCards | function | C_SkillCardCollection.PurchaseAllSealedCards(...) |  |
| PurchaseSealedCard | function | C_SkillCardCollection.PurchaseSealedCard(arg1, arg2) | C_SkillCardCollection.PurchaseSealedCard(cardType, count) |
| PurchaseSealedCardBoosterPack | function | C_SkillCardCollection.PurchaseSealedCardBoosterPack(arg1) | C_SkillCardCollection.PurchaseSealedCardBoosterPack(self.claimAmount) |
| SetSkillCardFilter | function | C_SkillCardCollection.SetSkillCardFilter(arg1, arg2, arg3) | C_SkillCardCollection.SetSkillCardFilter(cardType, searchString or "", filters) |
