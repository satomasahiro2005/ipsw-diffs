## AccessibilityUtilities

> `/System/Library/PrivateFrameworks/AccessibilityUtilities.framework/AccessibilityUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ff6ec` | `0x20259c` | **`+0x2eb0`** |
| `__DATA_DIRTY.__bss` | `0x2090` | `0x37c0` | **`+0x1730`** |
| `__DATA.__bss` | `0xa300` | `0x8d30` | **`-0x15d0`** |
| `__TEXT.__cstring` | `0x1d463` | `0x1d74b` | **`+0x2e8`** |
| `__DATA_DIRTY.__data` | `0x648` | `0x880` | **`+0x238`** |
| `__AUTH_CONST.__objc_const` | `0x1bc70` | `0x1bea0` | **`+0x230`** |
| `__TEXT.__swift5_reflstr` | `0xb50c` | `0xb6fc` | **`+0x1f0`** |
| `__DATA.__data` | `0x5290` | `0x5128` | **`-0x168`** |
| `__TEXT.__const` | `0x8a78` | `0x8b88` | **`+0x110`** |
| `__DATA_DIRTY.__objc_data` | `0x3128` | `0x3230` | **`+0x108`** |
| `__TEXT.__objc_methlist` | `0xfb04` | `0xfbfc` | **`+0xf8`** |
| `__AUTH_CONST.__const` | `0xa2b0` | `0xa390` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0x5978` | `0x5a40` | **`+0xc8`** |
| `__DATA_CONST.__objc_selrefs` | `0xa0a8` | `0xa150` | **`+0xa8`** |
| `__AUTH.__objc_data` | `0x29f8` | `0x2958` | **`-0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x133c0` | `0x13460` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x43f0` | `0x448c` | **`+0x9c`** |
| `__TEXT.__oslogstring` | `0x67d6` | `0x6870` | **`+0x9a`** |
| `__TEXT.__eh_frame` | `0x7990` | `0x7a00` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x25ac` | `0x2614` | **`+0x68`** |
| `__TEXT.__constg_swiftt` | `0x16e0` | `0x1720` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x29c4` | `0x2a04` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x1338` | `0x1374` | **`+0x3c`** |
| `__TEXT.__unwind_info` | `0x98f0` | `0x9928` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x2d10` | `0x2d40` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x918` | `0x948` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `0x5a0` | `0x5c8` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x2318` | `0x2328` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x5b4` | `0x5c0` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x238` | `0x240` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x110` | `0x10c` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x158` | `0x154` | **`-0x4`** |

### Other Changes

```diff

-3232.3.0.0.0
+3234.5.0.0.0

-  Functions: 15195
-  Symbols:   10825
-  CStrings:  4350
+  Functions: 15303
+  Symbols:   10852
+  CStrings:  4371
Symbols:
+ -[AXPasscodeAccessor _migrateAccessType]
+ -[AXSettings(LegacyImplementation) brailleAccessAppOpenCounts]
+ -[AXSettings(LegacyImplementation) setBrailleAccessAppOpenCounts:]
+ -[AXSettings(LegacyImplementation) setVoiceOverBrailleDisplayLastConnectedTimestamps:]
+ -[AXSettings(LegacyImplementation) voiceOverBrailleDisplayLastConnectedTimestamps]
+ -[AXVoiceOverAutomationClient _runCommand:name:timeout:error:]
+ -[AXVoiceOverAutomationClient _waitForServiceReachableWithTimeout:error:]
+ GCC_except_table1805
+ GCC_except_table1820
+ GCC_except_table1845
+ GCC_except_table1846
+ GCC_except_table1847
+ GCC_except_table1848
+ GCC_except_table2172
+ GCC_except_table2175
+ GCC_except_table2184
+ GCC_except_table2186
+ GCC_except_table2274
+ GCC_except_table2312
+ GCC_except_table2379
+ GCC_except_table2388
+ GCC_except_table2414
+ GCC_except_table2450
+ GCC_except_table2459
+ GCC_except_table2474
+ GCC_except_table2497
+ GCC_except_table2631
+ GCC_except_table2690
+ GCC_except_table2711
+ GCC_except_table2865
+ GCC_except_table2935
+ GCC_except_table2945
+ GCC_except_table2947
+ GCC_except_table2954
+ GCC_except_table3068
+ GCC_except_table3080
+ GCC_except_table3416
+ GCC_except_table3445
+ GCC_except_table3449
+ GCC_except_table3554
+ GCC_except_table3567
+ GCC_except_table3577
+ GCC_except_table3682
+ GCC_except_table3687
+ GCC_except_table3773
+ GCC_except_table4275
+ GCC_except_table4284
+ GCC_except_table4293
+ GCC_except_table4297
+ GCC_except_table4299
+ GCC_except_table4406
+ GCC_except_table4419
+ GCC_except_table4636
+ GCC_except_table4641
+ GCC_except_table4663
+ GCC_except_table4835
+ GCC_except_table4869
+ GCC_except_table4912
+ GCC_except_table4931
+ _AFIsChinaSKU
+ _AXSpringBoardActionKeyAccessibilityShortcutBannerSubtitle
+ _AXSpringBoardActionKeyAccessibilityShortcutBannerTitle
+ _CFDictionaryGetValue
+ _OBJC_IVAR_$_AXVirtualHIDService._pendingEvents
+ ___36-[AXVirtualHIDService postHIDEvent:]_block_invoke
+ ___62-[AXVoiceOverAutomationClient _runCommand:name:timeout:error:]_block_invoke
+ ___62-[AXVoiceOverAutomationClient _runCommand:name:timeout:error:]_block_invoke_2
+ ___65-[AXVoiceOverAutomationClient disableVoiceOverWithTimeout:error:]_block_invoke_2
+ ___73-[AXVoiceOverAutomationClient _waitForServiceReachableWithTimeout:error:]_block_invoke
+ ___block_descriptor_40_e5_B8?0l
+ ___block_descriptor_40_e8_32s_e5_B8?0ls32l8
+ ___block_descriptor_48_e8_32s40r_e18_v16?0"NSString"8lr40l8s32l8
+ ___block_descriptor_64_e8_32s40bs48r56r_e5_B8?0ls40l8s32l8r48l8r56l8
+ ___swift_closure_destructor.1013Tm
+ ___swift_closure_destructor.136Tm
+ ___swift_closure_destructor.150Tm
+ ___swift_closure_destructor.154Tm
+ _isRestrictedForAAC.token
+ _kSecAttrAccessibleAfterFirstUnlock
+ _kSecReturnAttributes
+ _keypath_get.689Tm
+ _keypath_get.705Tm
+ _keypath_get.763Tm
+ _keypath_get.945Tm
+ _keypath_set.35Tm
+ _keypath_set.878Tm
+ _symbolic _____ 12TextToSpeech11TTSExecutorC
+ _symbolic _____ So28AXVoiceOverBraille2DTextModeV
+ _symbolic _____ So29AXSVoiceOverImageCaptionsModeV
+ _symbolic _____ySiSgG 15AXCoreUtilities15AXSettingRecordC
+ _symbolic _____ySiSgGSg 15AXCoreUtilities15AXSettingRecordC
+ _symbolic _____y_____G 15AXCoreUtilities15AXSettingRecordC So28AXVoiceOverBraille2DTextModeV
+ _symbolic _____y_____G 15AXCoreUtilities15AXSettingRecordC So29AXSVoiceOverImageCaptionsModeV
+ _symbolic _____y_____GSg 15AXCoreUtilities15AXSettingRecordC So28AXVoiceOverBraille2DTextModeV
+ _symbolic _____y_____GSg 15AXCoreUtilities15AXSettingRecordC So29AXSVoiceOverImageCaptionsModeV
- GCC_except_table1801
- GCC_except_table1837
- GCC_except_table1838
- GCC_except_table1839
- GCC_except_table1844
- GCC_except_table2168
- GCC_except_table2171
- GCC_except_table2174
- GCC_except_table2176
- GCC_except_table2270
- GCC_except_table2308
- GCC_except_table2375
- GCC_except_table2384
- GCC_except_table2410
- GCC_except_table2446
- GCC_except_table2455
- GCC_except_table2470
- GCC_except_table2493
- GCC_except_table2627
- GCC_except_table2686
- GCC_except_table2707
- GCC_except_table2861
- GCC_except_table2931
- GCC_except_table2941
- GCC_except_table2943
- GCC_except_table2950
- GCC_except_table3064
- GCC_except_table3076
- GCC_except_table3408
- GCC_except_table3437
- GCC_except_table3441
- GCC_except_table3546
- GCC_except_table3559
- GCC_except_table3569
- GCC_except_table3674
- GCC_except_table3679
- GCC_except_table3765
- GCC_except_table4259
- GCC_except_table4268
- GCC_except_table4277
- GCC_except_table4289
- GCC_except_table4291
- GCC_except_table4397
- GCC_except_table4410
- GCC_except_table4623
- GCC_except_table4627
- GCC_except_table4654
- GCC_except_table4826
- GCC_except_table4860
- GCC_except_table4903
- GCC_except_table4922
- _OBJC_IVAR_$_AXVirtualHIDService._waitForEventSystemGroup
- ___55-[AXVoiceOverAutomationClient _navigate:timeout:error:]_block_invoke
- ___63-[AXVoiceOverAutomationClient _navigateInteract:timeout:error:]_block_invoke
- ___64-[AXVoiceOverAutomationClient enableVoiceOverWithTimeout:error:]_block_invoke_2
- ____AXVOWarmUpVoiceOver_block_invoke
- ___block_descriptor_48_e8_32s40bs_e5_B8?0ls40l8s32l8
- ___block_descriptor_56_e8_32s40bs48r_e5_B8?0ls40l8s32l8r48l8
- ___swift_closure_destructor.134Tm
- ___swift_closure_destructor.148Tm
- ___swift_closure_destructor.973Tm
- _dispatch_group_wait
- _kSecAttrAccessibleWhenUnlockedThisDeviceOnly
- _keypath_get.664Tm
- _keypath_get.678Tm
- _keypath_get.910Tm
- _keypath_set.29Tm
- _keypath_set.845Tm
CStrings:
+ "$braille2DTextMode"
+ "$brailleConnectSuccessCount"
+ "$braillePanCount"
+ "$brailleRoutingKeyCount"
+ "$contentCleanupMaxCharactersFirstPage"
+ "$contentCleanupMaxCharactersPerPage"
+ "$functionKeysDoNotRequireModifier"
+ "$imageCaptionsMode"
+ "$voiceOverHasActiveUserBrailleDisplay"
+ "%02X:%02X:%02X:%02X:%02X:%02X"
+ "AXSVoiceOverFunctionKeysDoNotRequireModifier"
+ "AXSVoiceOverTouchBraille2DTextMode"
+ "AXSpringBoardActionKeyAccessibilityShortcutBannerSubtitle"
+ "AXSpringBoardActionKeyAccessibilityShortcutBannerTitle"
+ "AccessibilityReaderContentCleanupMaxCharactersFirstPage"
+ "AccessibilityReaderContentCleanupMaxCharactersPerPage"
+ "Could not migrate passcode accessibility class. Error code: %ld"
+ "Migrated passcode accessibility class."
+ "VoiceOverHasActiveUserBrailleDisplay"
+ "VoiceOverTouchImageCaptionsMode"
+ "brailleAccessAppOpenCounts"
+ "clearLastSpokenPhrases failed (timedOut=%d error=%{public}@); warming up against stale phrase"
+ "com.apple.accessibility.guidedaccess.restrictedForAAC"
+ "moveBackward"
+ "moveForward"
+ "no settled VoiceOver speech within %.1fs"
+ "voiceOverBrailleConnectSuccessCount"
+ "voiceOverBrailleDisplayLastConnectedTimestamps"
+ "voiceOverBraillePanCount"
+ "voiceOverBrailleRoutingKeyCount"
- "$hasConfirmedContentCleanUpPrivacy"
- "$hasShownAppleIntelligencePrivacyPrompt"
- "$imageCaptionsEnabled"
- "%02x:%02x:%02x:%02x:%02x:%02x"
- "AccessibilityReaderHasConfirmedContentCleanUpPrivacy"
- "Failed to send navigation command"
- "ImageExplorerHasShownAppleIntelligencePrivacyPrompt"
- "VoiceOver warmup: spoke=%d after %.3fs (cap %.1fs)"
- "no VoiceOver speech within %.1fs"
```
