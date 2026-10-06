## Spotlight

> `/System/Library/PrivateFrameworks/Spotlight.framework/Spotlight`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9ab9c` | `0x9ad0c` | **`+0x170`** |
| `__AUTH_CONST.__cfstring` | `0x2f40` | `0x2f80` | **`+0x40`** |
| `__DATA.__bss` | `0x890` | `0x8b0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x558c` | `0x556c` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x6d0` | `0x6c0` | **`-0x10`** |
| `__TEXT.__cstring` | `0x38ca` | `0x38da` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e70` | `0x2e78` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1678` | `0x1670` | **`-0x8`** |

### Other Changes

```diff

-2451.1.101.0.0
+2454.100.0.0.0

-  Symbols:   3223
-  CStrings:  935
+  Symbols:   3224
+  CStrings:  937
Symbols:
+ __ZN12_GLOBAL__N_125sPhoneFavoritesUpdateLockE
+ __ZZ25canLogIdentifierForBundleP8NSStringE30ALLOWED_BUNDLES_FOR_ID_LOGGING
- __ZZ25canLogIdentifierForBundleP8NSStringE30ALLOWED_BUNDELS_FOR_ID_LOGGING
CStrings:
+ "sender"
+ "subject"
```
