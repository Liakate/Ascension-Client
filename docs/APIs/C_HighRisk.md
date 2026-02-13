# C_HighRisk



**Members:** 5  •  **Functions:** 5  •  **Interface calls:** 8 (across up to 3 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| CanToggleFelCommutation | function | C_HighRisk.CanToggleFelCommutation(arg1) | local canToggle, reason = C_HighRisk.CanToggleFelCommutation(not isFelCommutated) |
| GetInsuranceCostPerSlot | function | C_HighRisk.GetInsuranceCostPerSlot() | local cost = C_HighRisk.GetInsuranceCostPerSlot() |
| GetInsuranceTotalCost | function | C_HighRisk.GetInsuranceTotalCost() | self.FelCommutationNotice.Cost:SetFormattedText(FEL_COMMUTATION_DEATH_COST_S, GetMoneyString(C_Hi... |
| IsFelCommutationActive | function | C_HighRisk.IsFelCommutationActive() | if not C_HighRisk.IsFelCommutationActive() then |
| ToggleFelCommutation | function | C_HighRisk.ToggleFelCommutation(arg1) | C_HighRisk.ToggleFelCommutation(not isFelCommutated) |
