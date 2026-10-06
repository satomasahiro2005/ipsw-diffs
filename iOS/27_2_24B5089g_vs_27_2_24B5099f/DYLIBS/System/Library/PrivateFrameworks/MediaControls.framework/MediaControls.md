## MediaControls

> `/System/Library/PrivateFrameworks/MediaControls.framework/MediaControls`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2268f8` | `0x2272d0` | **`+0x9d8`** |
| `__TEXT.__cstring` | `0x6f74` | `0x6ec4` | **`-0xb0`** |
| `__TEXT.__objc_methlist` | `0x15de4` | `0x15e2c` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x44848` | `0x44878` | **`+0x30`** |
| `__DATA.__data` | `0x4d68` | `0x4d98` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xa7e8` | `0xa818` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x8990` | `0x89c0` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x2030` | `0x2058` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x3090` | `0x30b8` | **`+0x28`** |
| `__TEXT.__const` | `0xbd04` | `0xbd24` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x3398` | `0x33aa` | **`+0x12`** |
| `__AUTH.__objc_data` | `0x82a8` | `0x82b0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x18a8` | `0x18b0` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x77fc` | `0x7804` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x18d4` | `0x18d8` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-4026.200.15.0.0
+4026.200.23.0.0

-  Functions: 14463
-  Symbols:   13884
-  CStrings:  1624
+  Functions: 14478
+  Symbols:   13898
+  CStrings:  1620
Symbols:
+ -[MRUSpatialAudioController bluetoothQueue]
+ -[MRUSpatialAudioController didRetrievePreferences:forBundleID:]
+ -[MRUSpatialAudioController didSetPreferences:forBundleID:success:]
+ -[MRUSpatialAudioController requestPreferenceForBundleID:outputDevice:]
+ -[MRUSpatialAudioController setBluetoothQueue:]
+ -[MRUSpatialAudioController updateAccessoryStereoHFPStatus:headTrackingAvailable:]
+ _OBJC_IVAR_$_MRUSpatialAudioController._bluetoothQueue
+ ___56-[MRUSpatialAudioController updateHeadTrackingAvailable]_block_invoke
+ ___57-[MRUSpatialAudioController headTrackChangedNotification]_block_invoke
+ ___69-[MRUSpatialAudioController setPreferences:forBundleID:outputDevice:]_block_invoke
+ ___70-[MRUSpatialAudioController accessibilityHeadTrackChangedNotification]_block_invoke
+ ___71-[MRUSpatialAudioController requestPreferenceForBundleID:outputDevice:]_block_invoke
+ ___block_descriptor_57_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ _symbolic Say_____G So6UIViewC5UIKitE14ReservedRegionV12QueryOptionsV
+ _symbolic _____Sg So6UIViewC5UIKitE14ReservedRegionV
- __UISheetContainerInsets
CStrings:
+ "[%s] foldAvoidanceInsets=%s"
+ "com.apple.MediaControls.MRUSpatialAudioController/bluetoothQueue"
- "[%s] _UISheetContainerInsets=%s"
- "cayenne.debugSheetContainerInsets.bottom"
- "cayenne.debugSheetContainerInsets.left"
- "cayenne.debugSheetContainerInsets.right"
- "cayenne.debugSheetContainerInsets.top"
- "cayenne.usesDebugSheetContainerInsets"
```
