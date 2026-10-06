## QueryParser

> `/System/Library/PrivateFrameworks/QueryParser.framework/QueryParser`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x115de8` | `0x116d10` | **`+0xf28`** |
| `__TEXT.__gcc_except_tab` | `0x13558` | `0x1369c` | **`+0x144`** |
| `__DATA_CONST.__const` | `0x3410` | `0x3500` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x5210` | `0x52c0` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x79ae` | `0x7a0e` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x20f0` | `0x2130` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x29b4` | `0x29ec` | **`+0x38`** |
| `__TEXT.__cstring` | `0xd2e5` | `0xd315` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x2f50` | `0x2f70` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x4630` | `0x4650` | **`+0x20`** |
| `__DATA.__bss` | `0x1550` | `0x1560` | **`+0x10`** |
| `__TEXT.__const` | `0x2d18` | `0x2d28` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x15e0` | `0x15d8` | **`-0x8`** |
| `__DATA.__data` | `0x11b8` | `0x11b0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x728` | `0x730` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x308` | `0x30c` | **`+0x4`** |

### Other Changes

```diff

-3600.31.18.0.0
+3600.31.21.0.0

-  Functions: 4276
-  Symbols:   5934
-  CStrings:  3394
+  Functions: 4295
+  Symbols:   5954
+  CStrings:  3396
Symbols:
+ +[QPNeuralParserBridge _locked_cooldown]
+ +[QPNeuralParserBridge _locked_groundPersonPhrase:locale:argLabel:]
+ +[QPNeuralParserBridge _locked_groundTimePhrase:]
+ +[QPNeuralParserBridge _locked_prewarmForContext:]
+ +[QPNeuralParserBridge _locked_prewarm]
+ +[QPNeuralParserBridge _locked_sharedParserForContext:]
+ +[QPNeuralParserBridge _locked_sharedParser]
+ -[QPAssetManager(Testing) _test_scopedRBSAssertionAcquireFailureCount]
+ -[QPAssetManager(Testing) _test_waitForInvalidateCount:timeout:]
+ _OBJC_CLASS_$_NSThread
+ _OBJC_IVAR_$_QPAssetManager._locked_scopedRBSAcquireFailureCount
+ __OBJC_$_CLASS_METHODS_QPAssetManager
+ __ZL11bridgeQueuev
+ __ZZL11bridgeQueuevE5queue
+ __ZZL11bridgeQueuevE9onceToken
+ ___31+[QPNeuralParserBridge prewarm]_block_invoke
+ ___32+[QPNeuralParserBridge cooldown]_block_invoke
+ ___41+[QPNeuralParserBridge groundTimePhrase:]_block_invoke
+ ___42+[QPNeuralParserBridge prewarmForContext:]_block_invoke
+ ___49+[QPNeuralParserBridge parse:options:completion:]_block_invoke
+ ___59+[QPNeuralParserBridge groundPersonPhrase:locale:argLabel:]_block_invoke
+ ___70-[QPAssetManager(Testing) _test_scopedRBSAssertionAcquireFailureCount]_block_invoke
+ ____ZL11bridgeQueuev_block_invoke
+ ___block_descriptor_48_ea8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
+ ___block_descriptor_48_ea8_32s_e5_v8?0ls32l8
+ ___block_descriptor_56_ea8_32s40r_e5_v8?0lr40l8s32l8
+ ___block_descriptor_72_ea8_32s40s48s56r_e5_v8?0lr56l8s32l8s40l8s48l8
+ ___block_descriptor_88_ea8_32s40s48s56r64r72r_e5_v8?0ls32l8s40l8s48l8r56l8r64l8r72l8
+ ___block_descriptor_97_ea8_32s40s48s56r64r72r80r_e5_v8?0ls32l8s40l8s48l8r56l8r64l8r72l8r80l8
- +[QPAssetManager(Testing) _test_scopedAssertionInvalidateDelayNsec]
- +[QPAssetManager(Testing) _test_setScopedAssertionInvalidateDelayNsec:]
- +[QPNeuralParserBridge sharedParserForContext:]
- +[QPNeuralParserBridge sharedParser]
- __OBJC_$_CLASS_METHODS_QPAssetManager(Testing)
- __ZL16_parserOnceToken
- __ZL37sQPScopedAssertionInvalidateDelayNsec
- ___47+[QPNeuralParserBridge sharedParserForContext:]_block_invoke
- _dispatch_after
CStrings:
+ "[UAF] invalidateWithQueue:completion: reported error (flock marked released regardless): %s"
+ "com.apple.QueryParser.NeuralParserBridge"
```
