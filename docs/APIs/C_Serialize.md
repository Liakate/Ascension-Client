# C_Serialize



**Members:** 14  •  **Functions:** 14  •  **Interface calls:** 58 (across up to 12 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `SharedXML/Util/C_Serialize.lua` line 1




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| CompressForURI | function | C_Serialize:CompressForURI(arg1) | function C_Serialize:CompressForURI(uncompressedStr) |
| DecompressFromURI | function | C_Serialize:DecompressFromURI(arg1) | function C_Serialize:DecompressFromURI(inputStr) |
| Deserialize | function | C_Serialize:Deserialize(arg1) | * ** C_Serialize:Deserialize(input) ** |
| DeserializeDecompressFromPrint | function | C_Serialize:DeserializeDecompressFromPrint(arg1) | local deserializedBuild = C_Serialize:DeserializeDecompressFromPrint(build) |
| DeserializeValue | function | C_Serialize:DeserializeValue(arg1) | * ** C_Serialize:DeserializeValue(input) ** |
| FromJSON | function | C_Serialize:FromJSON(arg1) | local jsonObject = C_Serialize:FromJSON(json) |
| FromJSONCategory | function | C_Serialize:FromJSONCategory(arg1) | function C_Serialize:FromJSONCategory(category) |
| FromJSONData | function | C_Serialize:FromJSONData(arg1, arg2) | function C_Serialize:FromJSONData(category, index) |
| IsSerializableType | function | C_Serialize:IsSerializableType(arg1) | * ** C_Serialize:IsSerializableType(...) ** |
| Serialize | function | C_Serialize:Serialize(arg1) | local serialized = C_Serialize:Serialize(data) |
| SerializeCompressForPrint | function | C_Serialize:SerializeCompressForPrint(arg1) | local serializedBuild = C_Serialize:SerializeCompressForPrint(build) |
| SerializeEx | function | C_Serialize:SerializeEx(arg1, arg2) | * ** C_Serialize:SerializeEx(opts, ...) ** |
| ToJSON | function | C_Serialize:ToJSON(arg1) | local json = C_Serialize:ToJSON(jsonObject) |
| jsonEncoder | function | C_Serialize.jsonEncoder(...) | C_Serialize.jsonEncoder = newencoder() |
