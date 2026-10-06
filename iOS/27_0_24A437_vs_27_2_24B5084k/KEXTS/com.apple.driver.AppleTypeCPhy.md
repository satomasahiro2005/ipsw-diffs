## com.apple.driver.AppleTypeCPhy

> `com.apple.driver.AppleTypeCPhy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1306c` | `0x13558` | **`+0x4ec`** |
| `__TEXT.__cstring` | `0x1970` | `0x19f7` | **`+0x87`** |
| `__TEXT.__os_log` | `0x1440` | `0x149a` | **`+0x5a`** |

### Other Changes

```diff

-317.0.1.0.0
+317.40.3.0.0

-  CStrings:  178
+  CStrings:  183
Functions:
~ __ZN13AppleTypeCPhy5startEP9IOService : 4292 -> 4796
~ sub_fffffff0099ba188 -> sub_fffffff009a7e560 : 276 -> 316
~ __ZN13AppleTypeCPhy13configureUSB2E23AppleTypeCPhyPowerLevelj : 1608 -> 2324
CStrings:
+ "%s@%s: %s::%s: failed to configure usb-repeater %s\n"
+ "%s@%s: %s::%s: found usb-repeater %s\n"
+ "1211111212221212111111112121212121112111122"
+ "IOService"
+ "usb-repeater"
+ "usb-repeater-options"
- "121111121222121211111112121212121112111122"
```
