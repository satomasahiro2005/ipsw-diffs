## SoftwareUpdateSettings

> `/System/Library/PrivateFrameworks/SoftwareUpdateSettings.framework/SoftwareUpdateSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0xd48` | `0xf10` | **`+0x1c8`** |
| `__AUTH_CONST.__cfstring` | `0x2180` | `0x2260` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x203a` | `0x208a` | **`+0x50`** |
| `__TEXT.__text` | `0x1f244` | `0x1f274` | **`+0x30`** |

### Other Changes

```diff

-772.0.0.0.0
+772.0.3.0.0

-  Symbols:   1107
-  CStrings:  333
+  Symbols:   1114
+  CStrings:  340
Symbols:
+ _MA_KNOX_URL_OVERRIDE_DEFAULT_KEY
+ _MA_WKMS_URL_OVERRIDE_DEFAULT_KEY
+ _kCBBrightnessBoostEnd
+ _kCBBrightnessBoostFull
+ _kCBBrightnessBoostFullEnd
+ _kCBBrightnessBoostScaler
+ _kCBBrightnessBoostStart
Functions:
~ sub_2a4215fcc -> sub_2a57e7fcc : 532 -> 536
~ sub_2a4216444 -> sub_2a57e8448 : 776 -> 772
~ ___swift_closure_destructor : 128 -> 136
~ sub_2a421682c -> sub_2a57e8834 : 256 -> 260
~ sub_2a4216b30 -> sub_2a57e8b3c : 532 -> 536
~ sub_2a42171bc -> sub_2a57e91cc : 256 -> 276
~ sub_2a4217a7c -> sub_2a57e9aa0 : 844 -> 848
~ ___swift_closure_destructor : 128 -> 136
~ sub_2a4217e48 -> sub_2a57e9e78 : 256 -> 260
~ sub_2a4219cbc -> sub_2a57ebcf0 : 280 -> 276
CStrings:
+ "KnoxURLOverride"
+ "WKMSURLOverride"
+ "boostEnd"
+ "boostFull"
+ "boostFullEnd"
+ "boostScaler"
+ "boostStart"
```
