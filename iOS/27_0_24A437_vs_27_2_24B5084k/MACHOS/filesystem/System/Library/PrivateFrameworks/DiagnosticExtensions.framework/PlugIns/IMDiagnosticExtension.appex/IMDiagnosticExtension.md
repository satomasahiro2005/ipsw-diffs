## IMDiagnosticExtension

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/IMDiagnosticExtension.appex/IMDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa64` | `0xe8c` | **`+0x428`** |
| `__TEXT.__objc_stubs` | `0x360` | `0x4e0` | **`+0x180`** |
| `__DATA_CONST.__cfstring` | `0xa0` | `0x1a0` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x2de` | `0x3b7` | **`+0xd9`** |
| `__TEXT.__oslogstring` | `0x14c` | `0x1c8` | **`+0x7c`** |
| `__TEXT.__cstring` | `0x241` | `0x2b3` | **`+0x72`** |
| `__DATA.__objc_selrefs` | `0xf8` | `0x158` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x68` | `0x78` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x220` | `0x230` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x64` | `0x74` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x118` | `0x120` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1491.100.1.2.25
+1491.200.63.2.1

-  Functions: 19
-  Symbols:   58
-  CStrings:  56
+  Functions: 22
+  Symbols:   61
+  CStrings:  79
Symbols:
+ _OBJC_CLASS_$_IMMutedChatList
+ _OBJC_CLASS_$_NSMutableString
+ _objc_release_x28
CStrings:
+ "%@\n\tunmute date: %@ (%@)\n"
+ "Failed to write muted chat list: %@"
+ "Generated: %@\n\n"
+ "Messages log archive archived successfully."
+ "Messages log archive captured successfully."
+ "Muted Chat List (%lu %@)\n"
+ "MutedChatList.txt"
+ "_collectMutedChatList"
+ "allKeys"
+ "appendFormat:"
+ "compare:"
+ "dateWithTimeIntervalSince1970:"
+ "doubleValue"
+ "entries"
+ "entry"
+ "expired"
+ "muted"
+ "mutedChatList"
+ "objectForKeyedSubscript:"
+ "sharedList"
+ "sortedArrayUsingSelector:"
+ "string"
+ "writeToURL:atomically:encoding:error:"
```
