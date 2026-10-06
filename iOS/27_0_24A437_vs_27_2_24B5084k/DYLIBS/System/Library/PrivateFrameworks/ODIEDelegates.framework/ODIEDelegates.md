## ODIEDelegates

> `/System/Library/PrivateFrameworks/ODIEDelegates.framework/ODIEDelegates`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a13c` | `0xb898` | **`-0xe8a4`** |
| `__DATA.__bss` | `0x800` | `0x200` | **`-0x600`** |
| `__TEXT.__eh_frame` | `0x8f8` | `0x378` | **`-0x580`** |
| `__AUTH_CONST.__auth_got` | `0xb20` | `0x620` | **`-0x500`** |
| `__TEXT.__const` | `0x860` | `0x418` | **`-0x448`** |
| `__TEXT.__unwind_info` | `0x3b0` | `0x1d0` | **`-0x1e0`** |
| `__DATA.__data` | `0x290` | `0x108` | **`-0x188`** |
| `__TEXT.__cstring` | `0x6e2` | `0x58e` | **`-0x154`** |
| `__TEXT.__swift5_typeref` | `0x3cc` | `0x2ae` | **`-0x11e`** |
| `__AUTH_CONST.__const` | `0x368` | `0x288` | **`-0xe0`** |
| `__TEXT.__oslogstring` | `0xb4` | `—` | **`-0xb4`** |
| `__AUTH.__data` | `0x2a0` | `0x220` | **`-0x80`** |
| `__TEXT.__constg_swiftt` | `0x208` | `0x188` | **`-0x80`** |
| `__TEXT.__swift5_assocty` | `0x60` | `—` | **`-0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x21c` | `0x1c8` | **`-0x54`** |
| `__DATA_CONST.__objc_selrefs` | `0xf8` | `0xa8` | **`-0x50`** |
| `__TEXT.__swift_as_cont` | `0x4c` | `—` | **`-0x4c`** |
| `__TEXT.__swift5_reflstr` | `0x137` | `0x105` | **`-0x32`** |
| `__TEXT.__swift5_proto` | `0x40` | `0x10` | **`-0x30`** |
| `__TEXT.__swift5_builtin` | `0x3c` | `0x14` | **`-0x28`** |
| `__TEXT.__swift_as_ret` | `0x1c` | `—` | **`-0x1c`** |
| `__TEXT.__swift_as_entry` | `0x14` | `—` | **`-0x14`** |
| `__TEXT.__swift5_capture` | `0x24` | `0x14` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x30` | `0x24` | **`-0xc`** |
| `__DATA_CONST.__const` | `0x58` | `0x50` | **`-0x8`** |

### Other Changes

```diff

-3600.83.2.11.1
-  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
-  - /System/Library/Frameworks/CryptoKit.framework/CryptoKit
+3605.5.4.0.0

-  - /usr/lib/libMobileGestalt.dylib

-  - /usr/lib/swift/libswiftOSLog.dylib

-  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 266
-  Symbols:   160
-  CStrings:  42
+  Functions: 126
+  Symbols:   116
+  CStrings:  32
Symbols:
- _MGGetSInt64Answer
- _NSFileModificationDate
- _NSFileSize
- _NSURLFileSizeKey
- _NSURLIsRegularFileKey
- _OBJC_CLASS_$_MPSGraphDelegatePrecompilationDescriptor
- _OBJC_CLASS_$_NSBundle
- _OBJC_CLASS_$_NSFileManager
- _OBJC_CLASS_$_NSProcessInfo
- _OBJC_CLASS_$_OS_os_log
- __os_log_impl
- __swiftEmptySetSingleton
- __swiftImmortalRefCount
- __swift_FORCE_LOAD_$_swiftOSLog
- __swift_stdlib_bridgeErrorToNSError
- _clock_gettime_nsec_np
- _objc_retain
- _objc_retain_x23
- _objc_retain_x26
- _os_log_type_enabled
- _swift_allocBox
- _swift_arrayInitWithTakeBackToFront
- _swift_arrayInitWithTakeFrontToBack
- _swift_bridgeObjectRelease_n
- _swift_cvw_initStructMetadataWithLayoutString
- _swift_cvw_initWithTake
- _swift_errorRetain
- _swift_getEnumTagSinglePayloadGeneric
- _swift_getForeignTypeMetadata
- _swift_getObjectType
- _swift_getSingletonMetadata
- _swift_getTypeByMangledNameInContextInMetadataState2
- _swift_once
- _swift_release
- _swift_release_x12
- _swift_release_x23
- _swift_retain
- _swift_retain_x28
- _swift_slowAlloc
- _swift_slowDealloc
- _swift_storeEnumTagSinglePayloadGeneric
- _swift_task_alloc
- _swift_task_dealloc
- _swift_task_switch
CStrings:
- "BNNSCompiler unrecognized target: "
- "Compiling bytecode at %s"
- "Expected compiler input to be an MLIR text or bytecode file, not "
- "Failed to load cached model at %s, recompiling: %@"
- "Failed to retrieve compiled asset from cache after commit"
- "Load Compiled Asset"
- "ODIEDelegates/Compiler+Delegates.swift"
- "ODIEDelegates/Compiler.Options+BNNS.swift"
- "ODIE_ENABLE_DEFAULT_PROFILER"
- "The model asset is missing a specialization for the current architecture %{public}s"
```
