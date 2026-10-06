## com.apple.driver.AppleActuatorDriver

> `com.apple.driver.AppleActuatorDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__os_log` | `0x34e` | `0x51d` | **`+0x1cf`** |
| `__TEXT_EXEC.__text` | `0x9e20` | `0x9f64` | **`+0x144`** |
| `__TEXT.__cstring` | `0x11fc` | `0x11ca` | **`-0x32`** |

### Other Changes

```diff

-10100.44.0.0.0
+10110.3.0.0.0

-  CStrings:  157
+  CStrings:  160
Functions:
~ __ZN19AppleActuatorDevice26_deviceSetReportWithLookUpEP21AADDeviceReportStructh : 416 -> 740
CStrings:
+ "[HID] [%s] [Error] %s::%s [0x%llx] ERROR - Invalid length : Report struct [ID:0x%02x] length [%u] is larger than max buffer size [%zu]\n"
+ "[HID] [%s] [Error] %s::%s [0x%llx] ERROR - OVERRUN: mtReportID 0x%02x has reportLength of %d, attempting to write %d bytes\n"
+ "[HID] [%s] [Error] %s::%s [0x%llx] ERROR - UNDERRUN: mtReportID 0x%02x has reportLength of %d, attempting to write %d bytes\n"
+ "[HID] [%s] [Error] %s::%s [0x%llx] _getFeatureReportInfo returned error 0x%x\n"
- "%s::%s _getFeatureReportInfo returned error 0x%x\n"
```
