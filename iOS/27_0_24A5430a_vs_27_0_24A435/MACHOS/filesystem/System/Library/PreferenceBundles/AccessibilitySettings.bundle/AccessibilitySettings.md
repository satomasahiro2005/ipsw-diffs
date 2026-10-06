## AccessibilitySettings

> `/System/Library/PreferenceBundles/AccessibilitySettings.bundle/AccessibilitySettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d30e0` | `0x1d37d0` | **`+0x6f0`** |
| `__TEXT.__objc_methname` | `0x36239` | `0x364a9` | **`+0x270`** |
| `__TEXT.__objc_stubs` | `0x25e80` | `0x26040` | **`+0x1c0`** |
| `__DATA_CONST.__cfstring` | `0x1d400` | `0x1d520` | **`+0x120`** |
| `__TEXT.__cstring` | `0x19499` | `0x19597` | **`+0xfe`** |
| `__DATA.__objc_const` | `0x1ef78` | `0x1f008` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x15e2c` | `0x15ea4` | **`+0x78`** |
| `__DATA.__objc_selrefs` | `0xd078` | `0xd0e8` | **`+0x70`** |
| `__TEXT.__auth_stubs` | `0x5bc0` | `0x5bd0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xde4` | `0xdf0` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x2df0` | `0x2df8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2a28` | `0x2a30` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6b60` | `0x6b68` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
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
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

+  - /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry

-  Functions: 9936
-  Symbols:   20206
-  CStrings:  13503
+  Functions: 9946
+  Symbols:   20235
+  CStrings:  13533
Symbols:
+ -[SoundDetectionController _pairedWatchSupportsSoundRecognition]
+ -[SoundDetectionController allowForwardingSoundRecognitionToSupportedWatch]
+ -[SoundDetectionController setAllowForwardingSoundRecognitionToSupportedWatch:]
+ -[SoundDetectionController setTrailingEmptyGroupSpecifier:]
+ -[SoundDetectionController setWatchForwardingGroupSpecifier:]
+ -[SoundDetectionController setWatchForwardingSpecifier:]
+ -[SoundDetectionController trailingEmptyGroupSpecifier]
+ -[SoundDetectionController updateWatchForwardingSpecifiersAnimated:]
+ -[SoundDetectionController watchForwardingGroupSpecifier]
+ -[SoundDetectionController watchForwardingSpecifier]
+ GCC_except_table4400
+ GCC_except_table4433
+ GCC_except_table4548
+ GCC_except_table4580
+ GCC_except_table4638
+ GCC_except_table4676
+ GCC_except_table4707
+ GCC_except_table4745
+ GCC_except_table4763
+ GCC_except_table4903
+ GCC_except_table4986
+ GCC_except_table4991
+ GCC_except_table4994
+ GCC_except_table5019
+ GCC_except_table5026
+ GCC_except_table5068
+ GCC_except_table5111
+ GCC_except_table5217
+ GCC_except_table5234
+ GCC_except_table5307
+ GCC_except_table5319
+ GCC_except_table5362
+ GCC_except_table5437
+ GCC_except_table5569
+ GCC_except_table5699
+ GCC_except_table5701
+ GCC_except_table5703
+ GCC_except_table5705
+ GCC_except_table5707
+ GCC_except_table5728
+ GCC_except_table5730
+ GCC_except_table5732
+ GCC_except_table5734
+ GCC_except_table5736
+ GCC_except_table5749
+ GCC_except_table5761
+ GCC_except_table5794
+ GCC_except_table5917
+ GCC_except_table5918
+ GCC_except_table5921
+ GCC_except_table5922
+ GCC_except_table5961
+ GCC_except_table5966
+ GCC_except_table6033
+ GCC_except_table6354
+ GCC_except_table6357
+ GCC_except_table6378
+ GCC_except_table6528
+ GCC_except_table6601
+ GCC_except_table6717
+ GCC_except_table6788
+ GCC_except_table6828
+ GCC_except_table6865
+ GCC_except_table6965
+ GCC_except_table6989
+ GCC_except_table6992
+ GCC_except_table7102
+ GCC_except_table7107
+ GCC_except_table7139
+ GCC_except_table7156
+ GCC_except_table7189
+ GCC_except_table7215
+ GCC_except_table7220
+ GCC_except_table7224
+ GCC_except_table7227
+ GCC_except_table7229
+ GCC_except_table7248
+ GCC_except_table7303
+ GCC_except_table7351
+ GCC_except_table7358
+ OBJC_IVAR_$_SoundDetectionController._trailingEmptyGroupSpecifier
+ OBJC_IVAR_$_SoundDetectionController._watchForwardingGroupSpecifier
+ OBJC_IVAR_$_SoundDetectionController._watchForwardingSpecifier
+ _AXDeviceSupports8TouchesInBSI
+ _AXPairedWatchSupportsSoundRecognition
+ _OBJC_CLASS_$_NRPairedDeviceRegistry
+ _objc_msgSend$_pairedWatchSupportsSoundRecognition
+ _objc_msgSend$allowForwardingSoundRecognitionToSupportedWatch
+ _objc_msgSend$bridgeSettings
+ _objc_msgSend$getActivePairedDevice
+ _objc_msgSend$hasValidCustomDetector
+ _objc_msgSend$overrideSupportWatchSoundRecognition
+ _objc_msgSend$setAllowForwardingSoundRecognitionToSupportedWatch:
+ _objc_msgSend$setTrailingEmptyGroupSpecifier:
+ _objc_msgSend$setWatchForwardingGroupSpecifier:
+ _objc_msgSend$setWatchForwardingSpecifier:
+ _objc_msgSend$trailingEmptyGroupSpecifier
+ _objc_msgSend$updateWatchForwardingSpecifiersAnimated:
+ _objc_msgSend$watchForwardingGroupSpecifier
+ _objc_msgSend$watchForwardingSpecifier
- GCC_except_table4394
- GCC_except_table4423
- GCC_except_table4538
- GCC_except_table4570
- GCC_except_table4628
- GCC_except_table4666
- GCC_except_table4697
- GCC_except_table4735
- GCC_except_table4753
- GCC_except_table4893
- GCC_except_table4976
- GCC_except_table4981
- GCC_except_table4984
- GCC_except_table5009
- GCC_except_table5016
- GCC_except_table5058
- GCC_except_table5101
- GCC_except_table5207
- GCC_except_table5224
- GCC_except_table5297
- GCC_except_table5299
- GCC_except_table5352
- GCC_except_table5427
- GCC_except_table5559
- GCC_except_table5669
- GCC_except_table5671
- GCC_except_table5673
- GCC_except_table5675
- GCC_except_table5687
- GCC_except_table5700
- GCC_except_table5702
- GCC_except_table5704
- GCC_except_table5706
- GCC_except_table5718
- GCC_except_table5739
- GCC_except_table5751
- GCC_except_table5784
- GCC_except_table5907
- GCC_except_table5908
- GCC_except_table5911
- GCC_except_table5912
- GCC_except_table5951
- GCC_except_table5956
- GCC_except_table6023
- GCC_except_table6344
- GCC_except_table6347
- GCC_except_table6368
- GCC_except_table6518
- GCC_except_table6591
- GCC_except_table6707
- GCC_except_table6778
- GCC_except_table6818
- GCC_except_table6855
- GCC_except_table6955
- GCC_except_table6979
- GCC_except_table6982
- GCC_except_table7092
- GCC_except_table7097
- GCC_except_table7129
- GCC_except_table7146
- GCC_except_table7179
- GCC_except_table7205
- GCC_except_table7210
- GCC_except_table7214
- GCC_except_table7217
- GCC_except_table7219
- GCC_except_table7238
- GCC_except_table7293
- GCC_except_table7338
- GCC_except_table7341
- _AXDeviceSupportsManyTouches
CStrings:
+ "ALWAYS_USE_EIGHT_DOTS_IN_COMMAND_MODE"
+ "ALWAYS_USE_EIGHT_DOTS_IN_COMMAND_MODE_DESCRIPTION"
+ "Accessibility-V64"
+ "MORE_CALIBRATE_HOLD"
+ "SoundDetection-N237"
+ "SoundRecognition_WatchSupport"
+ "T@\"PSSpecifier\",&,N,V_trailingEmptyGroupSpecifier"
+ "T@\"PSSpecifier\",&,N,V_watchForwardingGroupSpecifier"
+ "T@\"PSSpecifier\",&,N,V_watchForwardingSpecifier"
+ "WATCH_FORWARDING"
+ "WATCH_FORWARDING_FOOTER"
+ "WatchForwarding"
+ "WatchForwardingGroup"
+ "_pairedWatchSupportsSoundRecognition"
+ "_trailingEmptyGroupSpecifier"
+ "_watchForwardingGroupSpecifier"
+ "_watchForwardingSpecifier"
+ "allowForwardingSoundRecognitionToSupportedWatch"
+ "bridgeSettings"
+ "getActivePairedDevice"
+ "hasValidCustomDetector"
+ "overrideSupportWatchSoundRecognition"
+ "setAllowForwardingSoundRecognitionToSupportedWatch:"
+ "setTrailingEmptyGroupSpecifier:"
+ "setWatchForwardingGroupSpecifier:"
+ "setWatchForwardingSpecifier:"
+ "trailingEmptyGroupSpecifier"
+ "updateWatchForwardingSpecifiersAnimated:"
+ "watchForwardingGroupSpecifier"
+ "watchForwardingSpecifier"
```
