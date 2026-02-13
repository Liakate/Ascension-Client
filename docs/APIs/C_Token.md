# C_Token



**Members:** 3  •  **Functions:** 3  •  **Interface calls:** 3 (across up to 2 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| GetTokenAmount | function | C_Token.GetTokenAmount(arg1) | C_Token.GetTokenAmount(string type) -> int amount |
| GetTokenInfo | function | C_Token.GetTokenInfo(arg1) | local name, _, _, icon = C_Token.GetTokenInfo(tokenID) |
| GetTokenTypes | function | C_Token.GetTokenTypes(...) | C_Token.GetTokenTypes() -> array types |



## Notes


- 1 member(s) had a runtime probe marked `ok` in the scan data.
