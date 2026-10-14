## IMDiagnosticExtension

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/IMDiagnosticExtension.appex/IMDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe8c` | `0xadc` | **`-0x3b0`** |
| `__TEXT.__objc_stubs` | `0x4e0` | `0x360` | **`-0x180`** |
| `__DATA_CONST.__cfstring` | `0x1a0` | `0xa0` | **`-0x100`** |
| `__TEXT.__objc_methname` | `0x3b7` | `0x2de` | **`-0xd9`** |
| `__TEXT.__cstring` | `0x2b3` | `0x241` | **`-0x72`** |
| `__DATA.__objc_selrefs` | `0x158` | `0xf8` | **`-0x60`** |
| `__TEXT.__oslogstring` | `0x1c8` | `0x1a4` | **`-0x24`** |
| `__DATA_CONST.__got` | `0x78` | `0x68` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x230` | `0x220` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x74` | `0x64` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x120` | `0x118` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1491.200.95.0.0
+1491.200.101.2.5

-  Functions: 22
-  Symbols:   61
-  CStrings:  79
+  Functions: 19
+  Symbols:   58
+  CStrings:  58
Symbols:
- _OBJC_CLASS_$_IMMutedChatList
- _OBJC_CLASS_$_NSMutableString
- _objc_release_x28
CStrings:
- "%@\n\tunmute date: %@ (%@)\n"
- "Failed to write muted chat list: %@"
- "Generated: %@\n\n"
- "Muted Chat List (%lu %@)\n"
- "MutedChatList.txt"
- "_collectMutedChatList"
- "allKeys"
- "appendFormat:"
- "compare:"
- "dateWithTimeIntervalSince1970:"
- "doubleValue"
- "entries"
- "entry"
- "expired"
- "muted"
- "mutedChatList"
- "objectForKeyedSubscript:"
- "sharedList"
- "sortedArrayUsingSelector:"
- "string"
- "writeToURL:atomically:encoding:error:"
```
