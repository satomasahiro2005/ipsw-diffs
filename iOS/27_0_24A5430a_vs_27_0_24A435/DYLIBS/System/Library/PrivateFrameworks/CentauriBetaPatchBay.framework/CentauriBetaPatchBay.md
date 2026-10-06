## CentauriBetaPatchBay

> `/System/Library/PrivateFrameworks/CentauriBetaPatchBay.framework/CentauriBetaPatchBay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe60` | `0xf10` | **`+0xb0`** |
| `__TEXT.__const` | `0x20` | `0x34` | **`+0x14`** |

### Other Changes

```diff

+  - /usr/lib/libMobileGestalt.dylib

-  Symbols:   48
+  Symbols:   49
Symbols:
+ _MGIsDeviceOfType
Functions:
~ _getGpioConfigType : 16 -> 140
~ _CentauriBetaPatchBayCopyData : 796 -> 848
```
