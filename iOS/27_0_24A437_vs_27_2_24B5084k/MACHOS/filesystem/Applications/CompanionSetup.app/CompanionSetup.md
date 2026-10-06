## CompanionSetup

> `/Applications/CompanionSetup.app/CompanionSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa1f4c` | `0xa3874` | **`+0x1928`** |
| `__TEXT.__eh_frame` | `0x4680` | `0x48c8` | **`+0x248`** |
| `__DATA.__objc_data` | `0x1ff0` | `0x21e0` | **`+0x1f0`** |
| `__TEXT.__unwind_info` | `0x1fb0` | `0x2020` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x1583` | `0x15e3` | **`+0x60`** |
| `__DATA.__objc_const` | `0x1ce8` | `0x1d28` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x27b0` | `0x27f0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3c1a` | `0x3bda` | **`-0x40`** |
| `__TEXT.__constg_swiftt` | `0x1804` | `0x183c` | **`+0x38`** |
| `__TEXT.__const` | `0x3714` | `0x3744` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x4c1d` | `0x4c4d` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x1904` | `0x192e` | **`+0x2a`** |
| `__DATA_CONST.__auth_got` | `0x13e0` | `0x1400` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x1c0b` | `0x1c2b` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x47c` | `0x49c` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x12c0` | `0x12d8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xd90` | `0xda0` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1654` | `0x1664` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x3200` | `0x31f4` | **`-0xc`** |
| `__TEXT.__swift_as_ret` | `0x198` | `0x1a4` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x85e8` | `0x85e0` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x194` | `0x19c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-524.0.56.0.0
+524.10.88.0.0

-  - /usr/lib/swift/libswiftAppleArchive.dylib

-  Functions: 2472
-  Symbols:   1264
-  CStrings:  1409
+  Functions: 2489
+  Symbols:   1269
+  CStrings:  1411
Symbols:
+ _$s17CompanionSetupKit21CSKBluetoothExtensionO15reenableAndWait6loggery2os6LoggerV_tYaF
+ _$s17CompanionSetupKit21CSKBluetoothExtensionO15reenableAndWait6loggery2os6LoggerV_tYaFTu
+ _$s5Nexus22NXProximityServiceDataO17remoteDiagnosticsyA2C06RemotefD0VcACmFWC
+ _$ss15ContinuousClockV3nowAB7InstantVvgZ
+ _$ss15ContinuousClockV7InstantV1loiySbAD_ADtFZ
+ _$ss15ContinuousClockV7InstantV8advanced2byADs8DurationV_tF
- __swift_FORCE_LOAD_$_swiftAppleArchive
CStrings:
+ "Prox card transaction denied: delay to retry: error=%@"
+ "Prox card transaction timed out: not showing"
+ "configureTask"
+ "flowSceneDidDisconnect()"
+ "settings-navigation://com.apple.Settings.General/SOFTWARE_UPDATE_LINK?ShowLatestUpdatePane=YES"
+ "shouldPresent"
- "UNSUPPORTED_LANGUAGE_SUBTITLE_MATCHING"
- "UNSUPPORTED_LANGUAGE_TITLE_MATCHING"
- "prox card transaction failed: %@"
- "settings-navigation://com.apple.Settings.General/SOFTWARE_UPDATE_LINK"
```
