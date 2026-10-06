## NFC

> `/System/Library/CoreAccessories/PlugIns/Transports/NFC.transport/NFC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x94ec` | `0x9490` | **`-0x5c`** |
| `__AUTH_CONST.__cfstring` | `0xfe0` | `0x1000` | **`+0x20`** |
| `__TEXT.__cstring` | `0xd76` | `0xd8e` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x900` | `0x910` | **`+0x10`** |

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1

-  Symbols:   643
-  CStrings:  269
+  Symbols:   644
+  CStrings:  270
Symbols:
+ _ACCUserDefaultsKey_PretendWirelessCTAMatch
+ _kCFACCUserDefaultsKey_PretendWirelessCTAMatch
- _objc_retain_x28
CStrings:
+ "PretendWirelessCTAMatch"
```
