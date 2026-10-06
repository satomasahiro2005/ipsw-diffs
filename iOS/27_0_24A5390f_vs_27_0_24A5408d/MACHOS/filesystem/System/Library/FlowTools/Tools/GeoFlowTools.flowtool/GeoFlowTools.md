## GeoFlowTools

> `/System/Library/FlowTools/Tools/GeoFlowTools.flowtool/GeoFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b028` | `0x21704` | **`+0x66dc`** |
| `__TEXT.__cstring` | `0x5b4` | `0x94f` | **`+0x39b`** |
| `__TEXT.__eh_frame` | `0xdf8` | `0x10a0` | **`+0x2a8`** |
| `__DATA.__bss` | `0x21a8` | `0x2028` | **`-0x180`** |
| `__DATA_CONST.__const` | `0xe50` | `0xdc0` | **`-0x90`** |
| `__TEXT.__auth_stubs` | `0xc80` | `0xd10` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x720` | `0x798` | **`+0x78`** |
| `__TEXT.__swift5_reflstr` | `0x40d` | `0x39d` | **`-0x70`** |
| `__DATA_CONST.__auth_got` | `0x640` | `0x688` | **`+0x48`** |
| `__DATA_CONST.__auth_ptr` | `0x4f8` | `0x4b8` | **`-0x40`** |
| `__TEXT.__swift_as_cont` | `0x8c` | `0xc8` | **`+0x3c`** |
| `__DATA_CONST.__got` | `0x248` | `0x280` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x544` | `0x510` | **`-0x34`** |
| `__TEXT.__swift5_typeref` | `0x72c` | `0x758` | **`+0x2c`** |
| `__DATA.__data` | `0x750` | `0x778` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0xc82` | `0xca2` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x280` | `0x264` | **`-0x1c`** |
| `__TEXT.__swift_as_entry` | `0x4c` | `0x68` | **`+0x1c`** |
| `__TEXT.__swift_as_ret` | `0x68` | `0x84` | **`+0x1c`** |
| `__TEXT.__const` | `0x18f0` | `0x18d8` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0x10c` | `0x100` | **`-0xc`** |
| `__TEXT.__swift5_types` | `0x4c` | `0x48` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-3600.151.4.501.6
+3600.156.3.501.1

-  Functions: 769
-  Symbols:   97
-  CStrings:  90
+  Functions: 834
+  Symbols:   100
+  CStrings:  104
Symbols:
+ _swift_dynamicCast
+ _swift_errorRelease
+ _swift_errorRetain
+ _swift_release_x12
- _objc_release_x8
CStrings:
+ " does not support reporting incidents on this device"
+ " does not support the requested navigation preferences"
+ " does not support the requested transportation type"
+ " does not support this location action on this device"
+ " does not support updating navigation waypoints on this device"
+ " was found for bundleId "
+ "Could not start navigation with "
+ "Failed to construct a navigation ToolInvocation for "
+ "No entity conforming to MapsCurrentLocationEntity was found for bundleId "
+ "No entity conforming to MapsPlaceEntity was found for bundleId "
+ "No enum conforming to MapsIncidentEnum was found for bundleId "
+ "No enum conforming to MapsNavigationPreferencesEnum was found for bundleId "
+ "No enum conforming to MapsTransportTypeEnum was found for bundleId "
+ "No intent implementing "
+ "ReportIncidentFlowTool: calling ReportIncidentTool with parameters %{sensitive}s"
+ "StartNavigationFlowTool: companion mode for watch — using NanoMaps bundle ID for AppIntent lookup, target device %{public}s"
+ "StartNavigationFlowTool: param[%s] = %{sensitive}s"
+ "entityTypeIdentifier(conforming:fromApp:onDevice:)"
+ "enumTypeIdentifier(conforming:fromApp:onDevice:)"
+ "ru.yandex.traffic"
- "ReportIncidentFlowTool: calling ReportIncidentTool with parameters %s"
- "StartNavigationFlowTool: companion mode for watch — using NanoMaps bundle ID for AppIntent lookup"
- "StartNavigationFlowTool: param[%s] = %{private}s"
- "entityTypeIdentifier(conforming:fromApp:)"
- "enumTypeIdentifier(conforming:fromApp:)"
- "ru.yandex.maps"
```
