## Navigation-iOS

> `/System/Library/CoreAccessories/PlugIns/Features/Navigation-iOS.feature/Navigation-iOS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x40c8` | `0x40b4` | **`-0x14`** |

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1
Functions:
~ ___init_logging_modules_block_invoke : 608 -> 588
~ -[ACCNavigationShimAccessory create_xpc_representation] : 948 -> 944
~ -[ACCNavigationShim convertIAP2ACCRouteGuidanceInfo:forAccessory:] : 356 -> 352
~ -[ACCNavigationShim convertIAP2ACCManeuverInfo:forAccessory:] : 356 -> 352
~ -[ACCNavigationShim tryProcessXPCMessage:connection:server:] : 1888 -> 1884
~ _ascii_to_hex : 156 -> 160
~ _printBytes : 136 -> 156
~ _createHexString : 408 -> 400
```
