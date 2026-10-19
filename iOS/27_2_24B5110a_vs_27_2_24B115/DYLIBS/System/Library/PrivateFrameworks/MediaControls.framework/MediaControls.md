## MediaControls

> `/System/Library/PrivateFrameworks/MediaControls.framework/MediaControls`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2299c0` | `0x229328` | **`-0x698`** |
| `__DATA_CONST.__const` | `0x30e0` | `0x3090` | **`-0x50`** |
| `__TEXT.__objc_methlist` | `0x15e2c` | `0x15de4` | **`-0x48`** |
| `__TEXT.__cstring` | `0x6f64` | `0x6f24` | **`-0x40`** |
| `__AUTH_CONST.__objc_const` | `0x44878` | `0x44848` | **`-0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xa820` | `0xa7f0` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x8a20` | `0x8a00` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0x18d8` | `0x18d4` | **`-0x4`** |

### Other Changes

```diff

-4026.210.2.0.0
+4026.210.3.0.0

-  Functions: 14503
-  Symbols:   13907
-  CStrings:  1624
+  Functions: 14489
+  Symbols:   13893
+  CStrings:  1623
Symbols:
- -[MRUSpatialAudioController bluetoothQueue]
- -[MRUSpatialAudioController didRetrievePreferences:forBundleID:]
- -[MRUSpatialAudioController didSetPreferences:forBundleID:success:]
- -[MRUSpatialAudioController requestPreferenceForBundleID:outputDevice:]
- -[MRUSpatialAudioController setBluetoothQueue:]
- -[MRUSpatialAudioController updateAccessoryStereoHFPStatus:headTrackingAvailable:]
- _OBJC_IVAR_$_MRUSpatialAudioController._bluetoothQueue
- ___56-[MRUSpatialAudioController updateHeadTrackingAvailable]_block_invoke
- ___57-[MRUSpatialAudioController headTrackChangedNotification]_block_invoke
- ___69-[MRUSpatialAudioController setPreferences:forBundleID:outputDevice:]_block_invoke
- ___70-[MRUSpatialAudioController accessibilityHeadTrackChangedNotification]_block_invoke
- ___71-[MRUSpatialAudioController requestPreferenceForBundleID:outputDevice:]_block_invoke
- ___block_descriptor_57_e8_32s40s48w_e5_v8?0lw48l8s32l8s40l8
- ___block_descriptor_64_e8_32s40s48s56w_e5_v8?0ls32l8s40l8s48l8w56l8
CStrings:
- "com.apple.MediaControls.MRUSpatialAudioController/bluetoothQueue"
```
