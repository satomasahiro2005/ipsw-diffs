## SoftwareUpdateServicesUI

> `/System/Library/PrivateFrameworks/SoftwareUpdateServicesUI.framework/SoftwareUpdateServicesUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x1860` | `0x1960` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x24a8` | `0x2568` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x12e2` | `0x134d` | **`+0x6b`** |
| `__TEXT.__text` | `0x94f4` | `0x9538` | **`+0x44`** |
| `__AUTH_CONST.__objc_const` | `0x1aa0` | `0x1ad0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xb18` | `0xb28` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x890` | `0x898` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x9c` | `0xa0` | **`+0x4`** |

### Other Changes

```diff

-300.0.0.0.0
+302.0.0.0.0

-  Functions: 222
-  Symbols:   715
-  CStrings:  238
+  Functions: 223
+  Symbols:   725
+  CStrings:  246
Symbols:
+ -[SUSUIPreferences inSetupModeOverride]
+ _MA_KNOX_URL_OVERRIDE_DEFAULT_KEY
+ _MA_WKMS_URL_OVERRIDE_DEFAULT_KEY
+ _OBJC_IVAR_$_SUSUIPreferences._inSetupModeOverride
+ _kCBBrightnessBoostEnd
+ _kCBBrightnessBoostFull
+ _kCBBrightnessBoostFullEnd
+ _kCBBrightnessBoostScaler
+ _kCBBrightnessBoostStart
+ _kSUSUIPreferenceInSetupModeOverride
Functions:
~ -[SUSUIPreferences _loadPreferences] : 544 -> 580
+ -[SUSUIPreferences inSetupModeOverride]
CStrings:
+ "KnoxURLOverride"
+ "WKMSURLOverride"
+ "boostEnd"
+ "boostFull"
+ "boostFullEnd"
+ "boostScaler"
+ "boostStart"
+ "inSetupModeOverride"
```
