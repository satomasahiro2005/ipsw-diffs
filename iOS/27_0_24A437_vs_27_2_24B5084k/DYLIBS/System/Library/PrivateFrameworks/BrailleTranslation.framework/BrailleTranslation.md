## BrailleTranslation

> `/System/Library/PrivateFrameworks/BrailleTranslation.framework/BrailleTranslation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x32374` | `0x32f74` | **`+0xc00`** |
| `__TEXT.__oslogstring` | `0x59f` | `0x6e7` | **`+0x148`** |
| `__DATA_CONST.__const` | `0x590` | `0x638` | **`+0xa8`** |
| `__AUTH_CONST.__objc_const` | `0x33e8` | `0x3488` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1168` | `0x11d0` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x1d1c` | `0x1d84` | **`+0x68`** |
| `__AUTH_CONST.__auth_got` | `0x718` | `0x748` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xa60` | `0xa80` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x164` | `0x178` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x268` | `0x278` | **`+0x10`** |
| `__TEXT.__cstring` | `0x7d9` | `0x7da` | **`+0x1`** |

### Other Changes

```diff

-465.0.0.0.0
+467.3.0.0.0

+  - /System/Library/PrivateFrameworks/KeyboardServices.framework/KeyboardServices

+  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Functions: 1088
-  Symbols:   1209
-  CStrings:  189
+  Functions: 1102
+  Symbols:   1240
+  CStrings:  194
Symbols:
+ -[BRLTJMecabraWrapper _applyPendingUserWordKeyPairsIfNeeded]
+ -[BRLTJMecabraWrapper _moveToNextRawCandidate]
+ -[BRLTJMecabraWrapper _reloadUserWordKeyPairs]
+ -[BRLTJMecabraWrapper _setPendingUserWordKeyPairs:]
+ -[BRLTJMecabraWrapper _startObservingUserDictionary]
+ -[BRLTJMecabraWrapper initWithUnitTesting:requiresFullAnalysisCoverage:]
+ -[BRLTJMecabraWrapper(Testing) setUserWordKeyPairsForTesting:]
+ -[BRLTTranslationService _queue_replyOnce:]
+ -[BRLTTranslationService _queue_serviceProxyWithErrorHandler:]
+ GCC_except_table112
+ GCC_except_table114
+ GCC_except_table482
+ _BRLTJTextReplacementsDidChange
+ _CFNotificationCenterAddObserver
+ _CFNotificationCenterGetDarwinNotifyCenter
+ _CFNotificationCenterRemoveObserver
+ _KSTextReplacementDidChangeNotification
+ _MecabraSetBuildDynamicDictionariesAsynchronously
+ _MecabraSetUserWordKeyPairs
+ _OBJC_CLASS_$__KSTextReplacementClientStore
+ _OBJC_IVAR_$_BRLTJMecabraWrapper._appliedUserWordKeyPairs
+ _OBJC_IVAR_$_BRLTJMecabraWrapper._pendingUserWordKeyPairs
+ _OBJC_IVAR_$_BRLTJMecabraWrapper._pendingUserWordKeyPairsLock
+ _OBJC_IVAR_$_BRLTJMecabraWrapper._requiresFullAnalysisCoverage
+ _OBJC_IVAR_$_BRLTJMecabraWrapper._textReplacementStore
+ __OBJC_$_INSTANCE_METHODS_BRLTJMecabraWrapper(Testing)
+ ___43-[BRLTTranslationService _queue_replyOnce:]_block_invoke
+ ___43-[BRLTTranslationService _queue_replyOnce:]_block_invoke_2
+ ___block_descriptor_40_e8_32bs_e17_v16?0"NSError"8ls32l8
+ ___block_descriptor_48_e8_32s40bs_e17_v16?0"NSError"8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40bs48r_e29_v24?0"NSString"8"NSData"16ls32l8r48l8s40l8
+ ___block_descriptor_64_e8_32s40s48bs56r_e5_v8?0lr56l8s48l8s32l8s40l8
+ __swift_FORCE_LOAD_$_swiftNaturalLanguage
+ __swift_FORCE_LOAD_$_swiftNaturalLanguage_$_BrailleTranslation
+ _objc_retainBlock
- GCC_except_table106
- GCC_except_table108
- GCC_except_table468
- __OBJC_$_INSTANCE_METHODS_BRLTJMecabraWrapper
CStrings:
+ "Input back-translation on an invalidated service, replying empty. service:%@"
+ "Input back-translation unavailable, replying empty. service:%@ / %@"
+ "Output translation on an invalidated service, replying empty"
+ "Output translation unavailable, replying empty. %@"
+ "Text Replacement query returned no result; keeping previous user words"
```
