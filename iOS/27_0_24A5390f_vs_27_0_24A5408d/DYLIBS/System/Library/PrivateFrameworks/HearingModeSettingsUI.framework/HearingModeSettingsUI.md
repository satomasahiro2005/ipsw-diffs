## HearingModeSettingsUI

> `/System/Library/PrivateFrameworks/HearingModeSettingsUI.framework/HearingModeSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4df78` | `0x4e2f0` | **`+0x378`** |
| `__TEXT.__cstring` | `0x5701` | `0x5791` | **`+0x90`** |
| `__TEXT.__ustring` | `0x130` | `0x1a8` | **`+0x78`** |
| `__AUTH_CONST.__cfstring` | `0x1980` | `0x19c0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x114f` | `0x116f` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xe38` | `0xe50` | **`+0x18`** |
| `__DATA.__data` | `0xd80` | `0xd90` | **`+0x10`** |
| `__TEXT.__const` | `0x1d44` | `0x1d34` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1508` | `0x1510` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x113a` | `0x1142` | **`+0x8`** |

### Other Changes

```diff

-40.36.1.0.0
+40.41.1.1.4

-  Symbols:   1169
-  CStrings:  575
+  Symbols:   1170
+  CStrings:  577
Symbols:
+ _symbolic _____Sg 10Foundation6LocaleV6RegionV
Functions:
~ -[HMHearingAidManufacturerAddressViewController getManufactureAddress] : 116 -> 204
~ sub_26af8c9a4 -> sub_282b0b9fc : 1212 -> 1764
~ sub_26afb1968 -> sub_282b30be8 : 1040 -> 1164
~ sub_26afb1dac -> sub_282b310a8 : 1040 -> 1164
CStrings:
+ "%s: for %s, HA status: %hhu, HA capability: %hhd, isB698Family: %{bool}d, shouldShow: %{bool}d"
+ "%s: for %s, HT status: %hhu, HT capability: %hhd, isB698Family: %{bool}d, shouldShow: %{bool}d"
+ "CN"
+ "苹果贸易(上海)有限公司\n中国（上海）自由贸易试验区世纪大道1249号15层A区、16层(实际楼层13层A区、14层)"
- "%s: for %s, HA status: %hhu, HA capability: %hhd, shouldShow: %{bool}d"
- "%s: for %s, HT status: %hhu, HT capability: %hhd, shouldShow: %{bool}d"
```
