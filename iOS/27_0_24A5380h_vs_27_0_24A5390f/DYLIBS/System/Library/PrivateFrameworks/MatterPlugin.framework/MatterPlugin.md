## MatterPlugin

> `/System/Library/PrivateFrameworks/MatterPlugin.framework/MatterPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a318` | `0x4a8bc` | **`+0x5a4`** |
| `__TEXT.__oslogstring` | `0x5db9` | `0x5e5b` | **`+0xa2`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d68` | `0x1d88` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1a90` | `0x1ab0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x49cc` | `0x49ec` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1220` | `0x1240` | **`+0x20`** |

### Other Changes

```diff

-85.0.0.0.0
+86.0.0.0.0

-  Functions: 1705
-  Symbols:   2756
-  CStrings:  622
+  Functions: 1713
+  Symbols:   2762
+  CStrings:  625
Symbols:
+ -[MTRPluginResidentClientSession _readyDeviceForNodeID:controller:]
+ -[MTRPluginServer _safeQueryIsNodeReady:homeUUID:]
+ -[MTRPluginServer _unsafeQueryIsNodeReady:homeUUID:]
+ GCC_except_table26
+ GCC_except_table39
+ GCC_except_table47
+ ___50-[MTRPluginServer _safeQueryIsNodeReady:homeUUID:]_block_invoke
- GCC_except_table23
CStrings:
+ "%@ Not querying node readiness, we are not running"
+ "%@ isNodeReady response was: %@ for nodeID: %@ homeUUID: %@"
+ "%@ nodeID %@ not ready - refusing to create device"
```
