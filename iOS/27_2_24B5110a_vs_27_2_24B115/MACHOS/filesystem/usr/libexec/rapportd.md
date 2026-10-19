## rapportd

> `/usr/libexec/rapportd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3e016` | `0x3e426` | **`+0x410`** |
| `__TEXT.__text` | `0x1a92d0` | `0x1a958c` | **`+0x2bc`** |
| `__DATA_CONST.__cfstring` | `0xa400` | `0xa6a0` | **`+0x2a0`** |
| `__DATA.__objc_const` | `0x12d18` | `0x12d58` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x1eac0` | `0x1eaf0` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x1200` | `0x1208` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-751.200.92.0.0
+751.200.101.0.0

-  Functions: 9010
+  Functions: 9012

-  CStrings:  11947
+  CStrings:  11971
CStrings:
+ "Debouncing stale BLE prune, deferring %.1fs"
+ "_lastBLEStalePruneTime"
+ "_pendingBLEStalePruneTimer"
+ "com.apple.SpeakerGroupSetup.calibrationConfiguration"
+ "com.apple.SpeakerGroupSetup.client.done"
+ "com.apple.SpeakerGroupSetup.client.invalidated"
+ "com.apple.SpeakerGroupSetup.done"
+ "com.apple.SpeakerGroupSetup.highlightPing"
+ "com.apple.SpeakerGroupSetup.ping"
+ "com.apple.SpeakerGroupSetup.playCelebration"
+ "com.apple.SpeakerGroupSetup.startScene"
+ "com.apple.SpeakerGroupSetup.stop"
+ "com.apple.SpeakerGroupSetup.stopScene"
+ "com.apple.audio.acousticcalibrationd.NetworkInterfaceRequest"
+ "com.apple.audio.acousticcalibrationd.StopSceneRequest"
+ "com.apple.audio.acousticcalibrationd.StopSessionRequest"
+ "com.apple.audio.acousticcalibrationd.collectCapturesRequest"
+ "com.apple.audio.acousticcalibrationd.derivedDataRequest"
+ "com.apple.audio.acousticcalibrationd.performTimeSyncRequest"
+ "com.apple.audio.acousticcalibrationd.prepareParticipantRequest"
+ "com.apple.audio.acousticcalibrationd.scheduleCalibrationRequest"
+ "com.apple.audio.acousticcalibrationd.setRolesRequest"
+ "requestSetupStateFromSurroundCompanions"
+ "synchSetupStateFromSurroundCompanions"
```
