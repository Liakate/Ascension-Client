# C_CharacterCreate



**Members:** 25  •  **Functions:** 25  •  **Interface calls:** 40 (across up to 2 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| AddPet | function | C_CharacterCreate.AddPet(...) |  |
| CanCreateClass | function | C_CharacterCreate.CanCreateClass(arg1) | if C_CharacterCreate.CanCreateClass(Enum.Class.HERO) and IsRaceClassValid(race, Enum.Class.HERO) ... |
| CanCreateCoA | function | C_CharacterCreate.CanCreateCoA() |  |
| CanCreateHero | function | C_CharacterCreate.CanCreateHero() |  |
| CanCreateWCR | function | C_CharacterCreate.CanCreateWCR() |  |
| Dress | function | C_CharacterCreate.Dress(...) |  |
| GetArchetypeCategories | function | C_CharacterCreate.GetArchetypeCategories(arg1) | local categories = C_CharacterCreate.GetArchetypeCategories(roleID) |
| GetArchetypeCategoryInfo | function | C_CharacterCreate.GetArchetypeCategoryInfo(arg1) | local iconArtwork, _, name = C_CharacterCreate.GetArchetypeCategoryInfo(categoryID) |
| GetArchetypeInfo | function | C_CharacterCreate.GetArchetypeInfo(arg1) | local buildID, primarySpell, primaryStat, weaponType, armorType, icon, iconArtwork, infoArtwork, ... |
| GetArchetypeRoleInfo | function | C_CharacterCreate.GetArchetypeRoleInfo(arg1) | local artwork, name, shortDescription, description = C_CharacterCreate.GetArchetypeRoleInfo(roleID) |
| GetArchetypeRoles | function | C_CharacterCreate.GetArchetypeRoles() | local roles = C_CharacterCreate.GetArchetypeRoles() |
| GetArchetypeSpellDescription | function | C_CharacterCreate.GetArchetypeSpellDescription(arg1, arg2) | local archetypeDesc = C_CharacterCreate.GetArchetypeSpellDescription(archetypeID, spellID) |
| GetArchetypes | function | C_CharacterCreate.GetArchetypes(arg1) | local archetypes = C_CharacterCreate.GetArchetypes(categoryID) |
| GetCameraPosition | function | C_CharacterCreate.GetCameraPosition() |  |
| PlayCastAnimation | function | C_CharacterCreate.PlayCastAnimation(...) |  |
| PlayPetCastAnimation | function | C_CharacterCreate.PlayPetCastAnimation(...) |  |
| ResetCameraPosition | function | C_CharacterCreate.ResetCameraPosition() |  |
| SetCameraPosition | function | C_CharacterCreate.SetCameraPosition(arg1) |  |
| SetSelectedArchetype | function | C_CharacterCreate.SetSelectedArchetype(arg1, arg2, arg3) |  |
| StopCastAnimation | function | C_CharacterCreate.StopCastAnimation(...) |  |
| StopPetCastAnimation | function | C_CharacterCreate.StopPetCastAnimation(...) |  |
| TryOnItem | function | C_CharacterCreate.TryOnItem(...) |  |
| Undress | function | C_CharacterCreate.Undress(...) |  |
| ZoomIn | function | C_CharacterCreate.ZoomIn(arg1) |  |
| ZoomOut | function | C_CharacterCreate.ZoomOut(arg1) |  |
