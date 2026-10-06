## Spotlight

> `/System/Library/PrivateFrameworks/Spotlight.framework/Spotlight`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x2fe0` | `0x3000` | **`+0x20`** |
| `__TEXT.__cstring` | `0x35bc` | `0x35cc` | **`+0x10`** |
| `__TEXT.__text` | `0x9beb8` | `0x9bec4` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x17e0` | `0x17e8` | **`+0x8`** |

### Other Changes

```diff

-2459.102.0.0.0
+2459.105.0.0.0

-  CStrings:  932
+  CStrings:  933
Functions:
~ +[SPClientSession initialize] : 296 -> 272
~ -[SPKGenerativeSearchMailQuery postProcessSections:withQueryContext:] : 1676 -> 1712
CStrings:
+ "com.apple.campo"
```
