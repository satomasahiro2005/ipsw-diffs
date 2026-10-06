## ShareSheet

> `/System/Library/PrivateFrameworks/ShareSheet.framework/ShareSheet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc6708` | `0xc6c6c` | **`+0x564`** |
| `__TEXT.__oslogstring` | `0x6ed5` | `0x70c4` | **`+0x1ef`** |
| `__AUTH_CONST.__objc_const` | `0x2a320` | `0x2a350` | **`+0x30`** |
| `__TEXT.__cstring` | `0x70f4` | `0x711a` | **`+0x26`** |
| `__AUTH_CONST.__cfstring` | `0x5980` | `0x59a0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x8bf8` | `0x8c10` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x112f4` | `0x1130c` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x14a0` | `0x14a4` | **`+0x4`** |

### Other Changes

```diff

-2118.10.4.2.3
+2122.10.2.2.1

-  Functions: 5883
-  Symbols:   10252
-  CStrings:  1598
+  Functions: 5894
+  Symbols:   10256
+  CStrings:  1608
Symbols:
+ -[UIActivityContentViewController ignoreCellTap]
+ -[UIActivityContentViewController setIgnoreCellTap:]
+ GCC_except_table113
+ GCC_except_table123
+ GCC_except_table126
+ _OBJC_IVAR_$_UIActivityContentViewController._ignoreCellTap
+ ___75-[UIActivityContentViewController collectionView:didSelectItemAtIndexPath:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e14_v20?0B8B12B16ls32l8
- GCC_except_table112
- GCC_except_table122
- GCC_except_table125
- ___block_descriptor_40_e8_32bs_e11_v16?0B8B12ls32l8
CStrings:
+ "Ignore cell tap currently enabled. Ignore selection."
+ "ShareSheetPrefersSheetPresentation"
+ "rdar://177809566 action=%@"
+ "rdar://177809566 duplicate identifiers across in-process buckets: excludeSectionTypes=%lu people=%@"
+ "rdar://177809566 duplicate proxy identifiers in incoming configuration: people=%@ share=%@ action=%@"
+ "rdar://177809566 extensionActionIdentifiers=%@"
+ "rdar://177809566 favoriteActionIdentifiers=%@"
+ "rdar://177809566 informationalActionIdentifiers=%@"
+ "rdar://177809566 share=%@"
+ "rdar://177809566 systemActionIdentifiers=%@"
+ "v20@?0B8B12B16"
- "v16@?0B8B12"
```
