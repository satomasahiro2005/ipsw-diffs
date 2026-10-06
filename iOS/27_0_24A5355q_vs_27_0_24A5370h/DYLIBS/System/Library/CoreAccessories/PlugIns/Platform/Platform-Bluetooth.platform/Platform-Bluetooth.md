## Platform-Bluetooth

> `/System/Library/CoreAccessories/PlugIns/Platform/Platform-Bluetooth.platform/Platform-Bluetooth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ec0` | `0x3e8c` | **`-0x34`** |

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1
Functions:
~ ___init_logging_signpost_modules_block_invoke : 608 -> 588
~ -[ACCPlatformPluginBluetooth accessoryDetached:] : 840 -> 836
~ -[ACCPlatformPluginBluetooth iterateRegisteredComponentsForKnownAddresses:allOFF:] : 544 -> 540
~ __BTSessionCallback : 1300 -> 1296
~ ___init_logging_modules_block_invoke : 608 -> 588
```
