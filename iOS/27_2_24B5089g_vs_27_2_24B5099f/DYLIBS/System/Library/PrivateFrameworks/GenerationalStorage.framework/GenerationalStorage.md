## GenerationalStorage

> `/System/Library/PrivateFrameworks/GenerationalStorage.framework/GenerationalStorage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x300` | `—` | **`-0x300`** |
| `__DATA_DIRTY.__data` | `0xc8` | `0x3c8` | **`+0x300`** |
| `__DATA_CONST.__const` | `0x658` | `0x660` | **`+0x8`** |
| `__TEXT.__text` | `0x16d34` | `0x16d38` | **`+0x4`** |
| `__TEXT.__cstring` | `0x129d` | `0x129b` | **`-0x2`** |

### Other Changes

```diff

-411.0.0.0.0
+413.0.0.0.0

-  Symbols:   880
+  Symbols:   881
Symbols:
+ _GSSTORAGE_FP_PROVIDER_CONTENT_VERSION_XATTR_NAME
Functions:
~ _GSSetProviderContentVersion : 572 -> 576
CStrings:
+ "com.apple.genstore.fp_provider_cver"
- "com.apple.genstore.fp_provider_cver#C"
```
