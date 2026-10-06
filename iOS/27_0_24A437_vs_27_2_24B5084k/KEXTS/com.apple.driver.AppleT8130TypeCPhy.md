## com.apple.driver.AppleT8130TypeCPhy

> `com.apple.driver.AppleT8130TypeCPhy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x4c5f0` | `0x4c1e8` | **`-0x408`** |
| `__TEXT.__cstring` | `0x9b80` | `0x9afa` | **`-0x86`** |
| `__TEXT.__os_log` | `0xfb65` | `0xfb0b` | **`-0x5a`** |

### Other Changes

```diff

-317.0.1.0.0
+317.40.3.0.0

-  CStrings:  511
+  CStrings:  506
Functions:
~ __ZN18AppleT8130TypeCPhy5startEP9IOService : 8064 -> 7808
~ sub_fffffff009a14810 -> sub_fffffff009ad8de0 : 524 -> 484
~ __ZN18AppleT8130TypeCPhy13eusb2phy_initEbb : 9944 -> 9292
~ sub_fffffff009a21a34 -> sub_fffffff009ae5d50 : 2436 -> 2352
CStrings:
+ "121111121222121211111111212121212111211112212222222222222222222222222112211221122112211221122112211221122112211221122112211221122112211221122112211221122112211221122112211221122112211221122112211221122111121"
- "%s@%s: %s::%s: failed to configure usb-repeater %s\n"
- "%s@%s: %s::%s: found usb-repeater %s\n"
- "121111121222121211111112121212121112111122122222222222222222222222221122112211221122112211221122112211221122112211221122112211221122112211221122112211221122112211221122112211221122112211221122112211221111211"
- "IOService"
- "usb-repeater"
- "usb-repeater-options"
```
