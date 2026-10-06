## FrontBoardServices

> `/System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__delay_helper` | `0xdc` | `—` | **`-0xdc`** |
| `__TEXT.__lazy_helpers` | `—` | `0x54` | **`+0x54`** |
| `__TEXT.__cstring` | `0xc0cb` | `0xc079` | **`-0x52`** |
| `__AUTH.__objc_data` | `0xe10` | `0xdc0` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x1f90` | `0x1fe0` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x870` | `0x878` | **`+0x8`** |
| `__AUTH_CONST.__lazy_load_got` | `—` | `0x8` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x1d0` | `0x1c8` | **`-0x8`** |

### Other Changes

```diff

-1149.0.0.0.0
+1150.0.0.0.0

-  - /System/Library/PrivateFrameworks/MobileInstallation.framework/MobileInstallation

-  Symbols:   6486
-  CStrings:  1936
+  Symbols:   6487
+  CStrings:  1935
Symbols:
+ _OBJC_CLASS_$_AITransactionLog$lazyGOT
+ _OBJC_CLASS_$_AITransactionLog$lazyGOT$loadHelper_x8
+ __dyld_lazy_load
+ _lazyLoadFlag$MobileInstallation
- _OBJC_CLASS_$_AITransactionLog$loadHelper_x8
- _dlopenHelper$MobileInstallation
- _dlopenHelperFlag$MobileInstallation
CStrings:
- "/System/Library/PrivateFrameworks/MobileInstallation.framework/MobileInstallation"
```
