## GeoFlowTools

> `/System/Library/FlowTools/Tools/GeoFlowTools.flowtool/GeoFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b4e4` | `0x1b028` | **`-0x4bc`** |
| `__DATA.__bss` | `0x23b0` | `0x21a8` | **`-0x208`** |
| `__TEXT.__const` | `0x1a58` | `0x18f0` | **`-0x168`** |
| `__TEXT.__oslogstring` | `0xb31` | `0xc82` | **`+0x151`** |
| `__DATA_CONST.__const` | `0xe08` | `0xe50` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x84` | `0xc4` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x584` | `0x544` | **`-0x40`** |
| `__TEXT.__eh_frame` | `0xe30` | `0xdf8` | **`-0x38`** |
| `__TEXT.__auth_stubs` | `0xc50` | `0xc80` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x748` | `0x720` | **`-0x28`** |
| `__TEXT.__swift5_typeref` | `0x74b` | `0x72c` | **`-0x1f`** |
| `__TEXT.__constg_swiftt` | `0x29c` | `0x280` | **`-0x1c`** |
| `__DATA.__data` | `0x768` | `0x750` | **`-0x18`** |
| `__DATA_CONST.__auth_got` | `0x628` | `0x640` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x180` | `0x168` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0x11c` | `0x10c` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x500` | `0x4f8` | **`-0x8`** |
| `__TEXT.__swift5_reflstr` | `0x413` | `0x40d` | **`-0x6`** |
| `__TEXT.__cstring` | `0x5b8` | `0x5b4` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x50` | `0x4c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__objc_classname`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.147.12.501.3
+3600.151.4.501.6

-  Functions: 826
-  Symbols:   94
-  CStrings:  86
+  Functions: 769
+  Symbols:   97
+  CStrings:  90
Symbols:
+ _objc_release_x27
+ _swift_release_x22
+ _swift_release_x23
+ _swift_retain_x26
- _swift_release_x28
CStrings:
+ "MapsUpdateNavigationWaypointsIntent"
+ "StartNavigationFlowTool: Origin %s encoded successfully"
+ "StartNavigationFlowTool: companion mode for watch — using NanoMaps bundle ID for AppIntent lookup"
+ "StartNavigationFlowTool: destinations encoded successfully"
+ "StartNavigationFlowTool: param[%s] = %{private}s"
+ "UpdateWayPointsFlowTool executing"
+ "UpdateWayPointsFlowTool: calling tool %s with parameters %{sensitive}s"
+ "UpdateWayPointsFlowTool: could not find intents implementing assistantSchema %s for bundleId: %s. Exiting FlowTool"
+ "UpdateWayPointsFlowTool: done"
+ "UpdateWayPointsFlowTool: found %ld tools conforming to %s schema for bundleId: %s. Only using the first tool"
+ "_TtC12GeoFlowTools23UpdateWayPointsFlowTool"
+ "com.apple.NanoMaps"
- "AddWayPointsFlowTool executing"
- "AddWayPointsFlowTool: calling tool %s with parameters %{sensitive}s"
- "AddWayPointsFlowTool: could not find intents implementing assistantSchema %s for bundleId: %s. Exiting FlowTool"
- "AddWayPointsFlowTool: done"
- "AddWayPointsFlowTool: found %ld tools conforming to %s schema for bundleId: %s. Only using the first tool"
- "MapsAddNavigationWaypointsIntent"
- "PlaceDescriptorEntity"
- "_TtC12GeoFlowTools20AddWayPointsFlowTool"
```
