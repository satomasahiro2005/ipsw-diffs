## UserActivity

> `/System/Library/PrivateFrameworks/UserActivity.framework/UserActivity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x411a4` | `0x413f0` | **`+0x24c`** |
| `__AUTH.__objc_data` | `0x550` | `0x5f0` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x230` | `0x190` | **`-0xa0`** |
| `__DATA.__bss` | `0x148` | `0x190` | **`+0x48`** |
| `__DATA_DIRTY.__bss` | `0x1b0` | `0x168` | **`-0x48`** |
| `__TEXT.__oslogstring` | `0x4dea` | `0x4e19` | **`+0x2f`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d58` | `0x1d80` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x24a0` | `0x24c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2869` | `0x2881` | **`+0x18`** |
| `__AUTH.__data` | `0x38` | `0x40` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x78` | `0x70` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1790` | `0x1798` | **`+0x8`** |

### Other Changes

```diff

-626.0.0.0.0
+628.0.0.0.0

-  CStrings:  734
+  CStrings:  736
Functions:
~ -[UASharedPasteboardTypeInfo description] : 572 -> 708
~ -[UAPBIRFileURLConverter convertPlatformDataToIR:] : 8 -> 460
CStrings:
+ ", fileContentType: %@"
+ "Updating referenceURL to filePathURL: %@ -> %@"
+ "info { %ld type: %@, uuid: %@%@%@%@}"
- "info { %ld type: %@, uuid: %@%@%@}"
```
