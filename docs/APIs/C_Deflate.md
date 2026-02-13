# C_Deflate



**Members:** 24  •  **Functions:** 21  •  **Interface calls:** 27 (across up to 3 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `SharedXML/Util/C_Deflate.lua` line 1




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| Adler32 | function | C_Deflate:Adler32(arg1) | function C_Deflate:Adler32(str) |
| CompressDeflate | function | C_Deflate:CompressDeflate(arg1) | return { actionType, actionId, C_Deflate:CompressDeflate(name .. macro) } |
| CompressDeflateWithDict | function | C_Deflate:CompressDeflateWithDict(arg1, arg2, arg3) | function C_Deflate:CompressDeflateWithDict(str, dictionary, configs) |
| CompressZlib | function | C_Deflate:CompressZlib(arg1, arg2) | function C_Deflate:CompressZlib(str, configs) |
| CompressZlibWithDict | function | C_Deflate:CompressZlibWithDict(arg1, arg2, arg3) | function C_Deflate:CompressZlibWithDict(str, dictionary, configs) |
| CreateCodec | function | C_Deflate:CreateCodec(arg1, arg2, arg3) | function C_Deflate:CreateCodec(reserved_chars, escape_chars, map_chars) |
| CreateDictionary | function | C_Deflate:CreateDictionary(arg1, arg2, arg3) | function C_Deflate:CreateDictionary(str, strlen, adler32) |
| DecodeForPrint | function | C_Deflate:DecodeForPrint(arg1) | function C_Deflate:DecodeForPrint(str) |
| DecodeForWoWAddonChannel | function | C_Deflate:DecodeForWoWAddonChannel(arg1) | function C_Deflate:DecodeForWoWAddonChannel(str) |
| DecodeForWoWChatChannel | function | C_Deflate:DecodeForWoWChatChannel(arg1) | function C_Deflate:DecodeForWoWChatChannel(str) |
| DecompressDeflate | function | C_Deflate:DecompressDeflate(arg1) | function C_Deflate:DecompressDeflate(str) |
| DecompressDeflateWithDict | function | C_Deflate:DecompressDeflateWithDict(arg1, arg2) | function C_Deflate:DecompressDeflateWithDict(str, dictionary) |
| DecompressZlib | function | C_Deflate:DecompressZlib(arg1) | function C_Deflate:DecompressZlib(str) |
| DecompressZlibWithDict | function | C_Deflate:DecompressZlibWithDict(arg1, arg2) | function C_Deflate:DecompressZlibWithDict(str, dictionary) |
| EncodeForPrint | function | C_Deflate:EncodeForPrint(arg1) | function C_Deflate:EncodeForPrint(str) |
| EncodeForWoWAddonChannel | function | C_Deflate:EncodeForWoWAddonChannel(arg1) | function C_Deflate:EncodeForWoWAddonChannel(str) |
| EncodeForWoWChatChannel | function | C_Deflate:EncodeForWoWChatChannel(arg1) | function C_Deflate:EncodeForWoWChatChannel(str) |
| internals.InternalClearCache | function | C_Deflate.internals.InternalClearCache(...) |  |
| internals.IsEqualAdler32 | function | C_Deflate.internals.IsEqualAdler32(...) |  |
| internals.IsValidDictionary | function | C_Deflate.internals.IsValidDictionary(...) |  |
| internals.LoadStringToTable | function | C_Deflate.internals.LoadStringToTable(...) |  |
| internals | table | C_Deflate.internals | C_Deflate.internals = { |
| internals._6bit_to_byte | table | C_Deflate.internals._6bit_to_byte |  |
| internals._byte_to_6bit_char | table | C_Deflate.internals._byte_to_6bit_char |  |
