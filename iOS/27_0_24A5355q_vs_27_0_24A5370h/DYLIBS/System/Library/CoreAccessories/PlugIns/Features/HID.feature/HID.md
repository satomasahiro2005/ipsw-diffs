## HID

> `/System/Library/CoreAccessories/PlugIns/Features/HID.feature/HID`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c6c` | `0x3c50` | **`-0x1c`** |

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1
Functions:
~ _ascii_to_hex : 156 -> 160
~ _printBytes : 136 -> 156
~ ___46-[ACCFeaturePluginHIDProvider stopHIDProvider]_block_invoke : 260 -> 256
~ ___51-[ACCFeaturePluginHIDProvider deleteHIDDescriptor:]_block_invoke : 372 -> 368
~ ___55-[ACCFeaturePluginHIDProvider processInReport:forUUID:]_block_invoke : 320 -> 316
~ ___84-[ACCFeaturePluginHIDProvider processGetReportResponse:reportType:reportID:forUUID:]_block_invoke : 328 -> 324
~ ___45-[ACCFeaturePluginHIDProvider getDescriptor:]_block_invoke : 320 -> 316
~ -[ACCFeaturePluginHIDDescriptor handleHIDComponentUpdate:] : 928 -> 924
~ ___init_logging_modules_block_invoke : 608 -> 588
~ _createHexString : 408 -> 400
```
