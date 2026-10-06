## SoftwareUpdateServicesUI

> `/System/Library/PrivateFrameworks/SoftwareUpdateServicesUI.framework/SoftwareUpdateServicesUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9538` | `0x9594` | **`+0x5c`** |
| `__AUTH_CONST.__cfstring` | `0x1960` | `0x19a0` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x1ad0` | `0x1b00` | **`+0x30`** |
| `__TEXT.__cstring` | `0x134d` | `0x1360` | **`+0x13`** |
| `__DATA_CONST.__const` | `0x2568` | `0x2578` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x898` | `0x8a0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xb28` | `0xb30` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xa0` | `0xa4` | **`+0x4`** |

### Other Changes

```diff

-302.0.0.0.0
+305.0.0.0.0

-  Functions: 223
-  Symbols:   725
-  CStrings:  246
+  Functions: 224
+  Symbols:   729
+  CStrings:  248
Symbols:
+ -[SUSUIPreferences ddmDelay]
+ _OBJC_IVAR_$_SUSUIPreferences._ddmDelay
+ _kCoreBrightnessDisplayInfoDisplayUniqueID
+ _kSUSUIPreferenceDDMDelay
CStrings:
+ "ddmDelay"
+ "uniqueId"
```
