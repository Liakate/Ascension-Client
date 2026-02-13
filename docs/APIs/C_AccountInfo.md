# C_AccountInfo



**Members:** 6  •  **Functions:** 6  •  **Interface calls:** 16 (across up to 8 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| GetCharacterAtIndex | function | C_AccountInfo.GetCharacterAtIndex(arg1) | return C_AccountInfo.GetCharacterAtIndex(self.selectedCharacter - 2).CharacterName |
| GetGMLevel | function | C_AccountInfo.GetGMLevel() | local isGM = C_AccountInfo.GetGMLevel() >= 4 |
| GetNumCharacters | function | C_AccountInfo.GetNumCharacters() | self.ChooseAffectedCharacter.CharacterList:SetGetNumResultsFunction(function() return (C_AccountI... |
| IsGM | function | C_AccountInfo.IsGM() | if C_AccountInfo.IsGM() then |
| IsGuide | function | C_AccountInfo.IsGuide(...) |  |
| IsNewcomer | function | C_AccountInfo.IsNewcomer(...) |  |



## Notes


- 2 member(s) had a runtime probe marked `ok` in the scan data.
