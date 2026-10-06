## IMTransferServices

> `/System/Library/PrivateFrameworks/IMTransferServices.framework/IMTransferServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ff8` | `0x53a4` | **`+0x3ac`** |
| `__TEXT.__oslogstring` | `0x83c` | `0x8f7` | **`+0xbb`** |
| `__DATA_CONST.__const` | `0x188` | `0x1d8` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x6e4` | `0x718` | **`+0x34`** |
| `__TEXT.__const` | `0x80` | `0x88` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x230` | `0x238` | **`+0x8`** |

### Other Changes

```diff

-1132.100.1.0.0
+1134.100.1.0.0

-  Functions: 57
+  Functions: 58

-  CStrings:  111
+  CStrings:  114
CStrings:
+ "Received fallback upload completion message for transferID: %@"
+ "XPC error after fallback completion already handled, ignoring"
+ "XPC reply after fallback completion already handled, ignoring"
```
