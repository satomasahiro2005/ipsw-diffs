## QueryUnderstanding

> `/System/Library/PrivateFrameworks/QueryUnderstanding.framework/QueryUnderstanding`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7c58` | `0x8b84` | **`+0xf2c`** |
| `__TEXT.__gcc_except_tab` | `0xa28` | `0xbc8` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x655` | `0x73a` | **`+0xe5`** |
| `__DATA_CONST.__const` | `0x778` | `0x820` | **`+0xa8`** |
| `__DATA_CONST.__objc_selrefs` | `0x6d8` | `0x778` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x340` | `0x3d8` | **`+0x98`** |
| `__TEXT.__objc_methlist` | `0x7ec` | `0x87c` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x5a0` | `0x620` | **`+0x80`** |
| `__AUTH_CONST.__objc_const` | `0xfb0` | `0x1010` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x280` | `0x2d0` | **`+0x50`** |
| `__TEXT.__cstring` | `0xebd` | `0xef5` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0xc0` | `0xe0` | **`+0x20`** |
| `__DATA.__bss` | `0x28` | `0x18` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x178` | `0x188` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x70` | `0x80` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x94` | `0xa0` | **`+0xc`** |
| `__TEXT.__const` | `0xc0` | `0xc8` | **`+0x8`** |

### Other Changes

```diff

-3605.7.1.0.0
+3605.7.1.1.1

-  Functions: 167
-  Symbols:   495
-  CStrings:  261
+  Functions: 187
+  Symbols:   542
+  CStrings:  269
Symbols:
+ +[QUAssetHelper _acquireAssetLockAssertion]
+ -[QUAssetHelper _cacheKeyForLocale:]
+ -[QUAssetHelper _onQueueHandleAssetSetUpdate]
+ -[QUAssetHelper _populateForLocale:]
+ -[QUAssetHelper _registerAssetObserver]
+ -[QUAssetHelper _requestSandboxExtension]
+ -[QUAssetHelper _unregisterAssetObserver]
+ -[QUAssetHelper dealloc]
+ -[QUAssetHelper(Testing) _test_pathCacheCount]
+ -[QUAssetHelper(Testing) _test_populateForLocale:]
+ -[QUAssetHelper(Testing) _test_populateShortCircuitCount]
+ -[QUAssetHelper(Testing) _test_simulateAssetUpdate]
+ GCC_except_table11
+ GCC_except_table12
+ GCC_except_table17
+ GCC_except_table2
+ GCC_except_table20
+ GCC_except_table21
+ GCC_except_table23
+ GCC_except_table45
+ GCC_except_table6
+ GCC_except_table7
+ GCC_except_table8
+ _OBJC_CLASS_$_NSNull
+ _OBJC_CLASS_$_RBSAcquisitionCompletionAttribute
+ _OBJC_IVAR_$_QUAssetHelper._assetSetCache
+ _OBJC_IVAR_$_QUAssetHelper._locked_populateShortCircuitCount
+ _OBJC_IVAR_$_QUAssetHelper._updateObserverToken
+ __ZL22kQUAssetHelperQueueKey
+ ___36-[QUAssetHelper _populateForLocale:]_block_invoke
+ ___36-[QUAssetHelper _populateForLocale:]_block_invoke_2
+ ___36-[QUAssetHelper filePathsForLocale:]_block_invoke_2
+ ___39-[QUAssetHelper _registerAssetObserver]_block_invoke
+ ___41-[QUAssetHelper _requestSandboxExtension]_block_invoke
+ ___41-[QUAssetHelper _unregisterAssetObserver]_block_invoke
+ ___46-[QUAssetHelper(Testing) _test_pathCacheCount]_block_invoke
+ ___51-[QUAssetHelper(Testing) _test_simulateAssetUpdate]_block_invoke
+ ___57-[QUAssetHelper(Testing) _test_populateShortCircuitCount]_block_invoke
+ ___block_descriptor_40_ea8_32s_e17_v16?0"NSError"8ls32l8
+ ___block_descriptor_40_ea8_32s_e5_v8?0ls32l8
+ ___block_descriptor_40_ea8_32w_e5_v8?0lw32l8
+ ___block_descriptor_56_ea8_32s40s48s_e17_v16?0"NSError"8ls32l8s40l8s48l8
+ ___block_descriptor_64_ea8_32s40s48r56r_e5_v8?0ls32l8s40l8r48l8r56l8
+ _dispatch_get_specific
+ _dispatch_queue_set_specific
+ _dispatch_semaphore_create
+ _dispatch_semaphore_signal
+ _dispatch_semaphore_wait
+ _dispatch_time
+ _objc_opt_isKindOfClass
- GCC_except_table10
- GCC_except_table25
- ___block_descriptor_48_ea8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
CStrings:
+ ""
+ "%@.%@.%@"
+ "UAFAssetAccess"
+ "[UAF] Asset set changed during enumeration for locale %@ — discarding"
+ "[UAF] Failed to acquire scoped RBS assertion: %@"
+ "[UAF] Failed to request sandbox extension for %@: %@"
+ "[UAF] Timed out waiting for UAF flock release; skipping enumeration (locale=%@)"
+ "[UAF] UAFAssetAccess unavailable, using FinishTaskUninterruptable: %@"
+ "com.apple.UnifiedAssetFramework"
- "[UAF] Failed to acquire scoped RBS assertion; skipping OTA retrieval this call (locale=%@): %@"
```
