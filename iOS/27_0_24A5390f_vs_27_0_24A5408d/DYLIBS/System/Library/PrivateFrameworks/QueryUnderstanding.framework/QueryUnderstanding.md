## QueryUnderstanding

> `/System/Library/PrivateFrameworks/QueryUnderstanding.framework/QueryUnderstanding`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6fcc` | `0x7c58` | **`+0xc8c`** |
| `__AUTH_CONST.__objc_const` | `0xe78` | `0xfb0` | **`+0x138`** |
| `__TEXT.__gcc_except_tab` | `0x94c` | `0xa28` | **`+0xdc`** |
| `__TEXT.__oslogstring` | `0x59a` | `0x655` | **`+0xbb`** |
| `__DATA_CONST.__const` | `0x6d8` | `0x778` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xe22` | `0xebd` | **`+0x9b`** |
| `__TEXT.__objc_methlist` | `0x754` | `0x7ec` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x2b0` | `0x340` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x650` | `0x6d8` | **`+0x88`** |
| `__AUTH_CONST.__cfstring` | `0x520` | `0x5a0` | **`+0x80`** |
| `__AUTH.__objc_data` | `—` | `0x50` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x80` | `0xc0` | **`+0x40`** |
| `__DATA.__bss` | `0x8` | `0x28` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x158` | `0x178` | **`+0x20`** |
| `__TEXT.__const` | `0xa8` | `0xc0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x80` | `0x94` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x48` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x30` | `0x38` | **`+0x8`** |

### Other Changes

```diff

-3600.31.18.0.0
+3600.31.21.0.0

+  - /System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices

-  Functions: 143
-  Symbols:   438
-  CStrings:  254
+  Functions: 167
+  Symbols:   495
+  CStrings:  261
Symbols:
+ +[QUAssetHelper log]
+ +[QUAssetHelper sharedHelper]
+ -[QUAssetHelper .cxx_destruct]
+ -[QUAssetHelper filePathsForLocale:]
+ -[QUAssetHelper initWithAssetSetManager:]
+ -[QUAssetHelper init]
+ -[QUAssetHelper(Testing) _test_drainQueue]
+ -[QUAssetHelper(Testing) _test_scopedRBSAssertionAcquireCount]
+ -[QUAssetHelper(Testing) _test_scopedRBSAssertionAcquireFailureCount]
+ -[QUAssetHelper(Testing) _test_scopedRBSAssertionInvalidateCount]
+ -[QUAssetHelper(Testing) _test_waitForInvalidateCount:timeout:]
+ GCC_except_table10
+ GCC_except_table16
+ GCC_except_table25
+ GCC_except_table5
+ GCC_except_table9
+ _OBJC_CLASS_$_NSThread
+ _OBJC_CLASS_$_QUAssetHelper
+ _OBJC_CLASS_$_RBSAssertion
+ _OBJC_CLASS_$_RBSDomainAttribute
+ _OBJC_CLASS_$_RBSTarget
+ _OBJC_IVAR_$_QUAssetHelper._assetSetManager
+ _OBJC_IVAR_$_QUAssetHelper._locked_scopedRBSAcquireCount
+ _OBJC_IVAR_$_QUAssetHelper._locked_scopedRBSAcquireFailureCount
+ _OBJC_IVAR_$_QUAssetHelper._locked_scopedRBSInvalidateCount
+ _OBJC_IVAR_$_QUAssetHelper._queue
+ _OBJC_METACLASS_$_QUAssetHelper
+ __OBJC_$_CLASS_METHODS_QUAssetHelper
+ __OBJC_$_INSTANCE_METHODS_QUAssetHelper(Testing)
+ __OBJC_$_INSTANCE_VARIABLES_QUAssetHelper
+ __OBJC_CLASS_RO_$_QUAssetHelper
+ __OBJC_METACLASS_RO_$_QUAssetHelper
+ __ZSt9terminatev
+ __ZZ20+[QUAssetHelper log]E3log
+ __ZZ20+[QUAssetHelper log]E9onceToken
+ __ZZ29+[QUAssetHelper sharedHelper]E12sharedHelper
+ __ZZ29+[QUAssetHelper sharedHelper]E9onceToken
+ ___20+[QUAssetHelper log]_block_invoke
+ ___29+[QUAssetHelper sharedHelper]_block_invoke
+ ___36-[QUAssetHelper filePathsForLocale:]_block_invoke
+ ___42-[QUAssetHelper(Testing) _test_drainQueue]_block_invoke
+ ___62-[QUAssetHelper(Testing) _test_scopedRBSAssertionAcquireCount]_block_invoke
+ ___65-[QUAssetHelper(Testing) _test_scopedRBSAssertionInvalidateCount]_block_invoke
+ ___69-[QUAssetHelper(Testing) _test_scopedRBSAssertionAcquireFailureCount]_block_invoke
+ ___Block_byref_object_copy_
+ ___Block_byref_object_dispose_
+ ___block_descriptor_48_ea8_32s40r_e5_v8?0lr40l8s32l8
+ ___block_descriptor_48_ea8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
+ ___block_descriptor_48_ea8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_56_ea8_32s40s48r_e5_v8?0ls32l8s40l8r48l8
+ ___clang_call_terminate
+ ___cxa_begin_catch
+ _dispatch_async
+ _dispatch_queue_create
+ _dispatch_sync
+ _objc_begin_catch
+ _objc_end_catch
+ _objc_exception_rethrow
- GCC_except_table2
CStrings:
+ "(nil)"
+ "FinishTaskUninterruptable"
+ "QueryUnderstanding holding UAFAssetSet during retrieve+enumerate"
+ "[UAF] Failed to acquire scoped RBS assertion; skipping OTA retrieval this call (locale=%@): %@"
+ "[UAF] invalidateWithQueue:completion: reported error (flock marked released regardless): %@"
+ "com.apple.QueryUnderstanding.AssetHelper"
+ "com.apple.common"
```
