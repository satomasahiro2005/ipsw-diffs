## com.apple.FontServices.FontProviderLoader

> `/System/Library/PrivateFrameworks/FontServices.framework/XPCServices/com.apple.FontServices.FontProviderLoader.xpc/com.apple.FontServices.FontProviderLoader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f88` | `0x5c08` | **`+0x2c80`** |
| `__TEXT.__auth_stubs` | `0x460` | `0x8e0` | **`+0x480`** |
| `__DATA_CONST.__const` | `0x1b8` | `0x458` | **`+0x2a0`** |
| `__DATA_CONST.__auth_got` | `0x240` | `0x480` | **`+0x240`** |
| `__TEXT.__oslogstring` | `—` | `0x1e9` | **`+0x1e9`** |
| `__TEXT.__const` | `0x68` | `0x1f2` | **`+0x18a`** |
| `__DATA.__bss` | `0x40` | `0x170` | **`+0x130`** |
| `__TEXT.__eh_frame` | `—` | `0x110` | **`+0x110`** |
| `__TEXT.__cstring` | `0x603` | `0x6e3` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x108` | `0x1c8` | **`+0xc0`** |
| `__DATA.__objc_data` | `0xf0` | `0x1a0` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `—` | `0xab` | **`+0xab`** |
| `__TEXT.__constg_swiftt` | `—` | `0xa4` | **`+0xa4`** |
| `__TEXT.__objc_methname` | `0xd8b` | `0xe12` | **`+0x87`** |
| `__TEXT.__objc_stubs` | `0xa20` | `0xaa0` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `—` | `0x7c` | **`+0x7c`** |
| `__DATA_CONST.__auth_ptr` | `—` | `0x68` | **`+0x68`** |
| `__TEXT.__swift5_capture` | `—` | `0x54` | **`+0x54`** |
| `__DATA.__data` | `0x1e0` | `0x228` | **`+0x48`** |
| `__DATA.__objc_const` | `0x578` | `0x5c0` | **`+0x48`** |
| `__TEXT.__swift5_reflstr` | `—` | `0x41` | **`+0x41`** |
| `__TEXT.__objc_methlist` | `0x428` | `0x460` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x100` | `0x130` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x470` | `0x490` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0xc5` | `0xe2` | **`+0x1d`** |
| `__TEXT.__objc_methtype` | `0x3e5` | `0x402` | **`+0x1d`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__swift5_types` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `—` | `0xc` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_imageinfo`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-174.0.0.0.0
+176.0.0.0.0

+  - /System/Library/PrivateFrameworks/ManagedBackgroundAssets.framework/ManagedBackgroundAssets
+  - /System/Library/PrivateFrameworks/ManagedBackgroundAssetsHelper.framework/ManagedBackgroundAssetsHelper

-  Functions: 39
-  Symbols:   132
-  CStrings:  258
+  - /usr/lib/swift/libswiftAppleArchive.dylib
+  - /usr/lib/swift/libswiftCompression.dylib
+  - /usr/lib/swift/libswiftCore.dylib
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftXPC.dylib
+  - /usr/lib/swift/libswift_Builtin_float.dylib
+  - /usr/lib/swift/libswift_Concurrency.dylib
+  - /usr/lib/swift/libswiftos.dylib
+  Functions: 108
+  Symbols:   195
+  CStrings:  274
Symbols:
+ _NSOSStatusErrorDomain
+ _OBJC_CLASS_$_FSAssetPackAccess
+ _OBJC_METACLASS_$_FSAssetPackAccess
+ __Block_copy
+ __Block_release
+ ___chkstk_darwin
+ __os_feature_enabled_impl
+ __os_log_impl
+ __swiftEmptyArrayStorage
+ __swiftImmortalRefCount
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftObjectiveC
+ __swift_FORCE_LOAD_$_swiftXPC
+ __swift_FORCE_LOAD_$_swift_Builtin_float
+ __swift_FORCE_LOAD_$_swiftos
+ _malloc_size
+ _memcpy
+ _memmove
+ _objc_allocWithZone
+ _objc_opt_self
+ _objc_retainBlock
+ _objc_retain_x26
+ _os_log_type_enabled
+ _swift_allocObject
+ _swift_arrayDestroy
+ _swift_beginAccess
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRelease_n
+ _swift_bridgeObjectRetain
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initWithCopy
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_deallocObject
+ _swift_dynamicCast
+ _swift_errorRelease
+ _swift_errorRetain
+ _swift_getForeignTypeMetadata
+ _swift_getObjectType
+ _swift_getTypeByMangledNameInContext2
+ _swift_getWitnessTable
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_once
+ _swift_release
+ _swift_release_x19
+ _swift_release_x24
+ _swift_release_x8
+ _swift_retain
+ _swift_retain_x20
+ _swift_retain_x24
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_switch
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
CStrings:
+ "@40@0:8@16@24@?32"
+ "AppleHostedAssetPackFonts"
+ "Asset-pack access requested with a %ld-byte audit token; expected %ld."
+ "Cannot reach the Managed Background Assets helper (%{public}s) at stage=%{public}s; every asset-pack font will be rejected. canRetry=%{bool}d %{public}s"
+ "FSAssetPackAccess"
+ "FontServices"
+ "com.apple.FontServices"
+ "com.apple.backgroundassets.managed.helper.service"
+ "connecting-to-helper"
+ "dataWithBytes:length:"
+ "dealloc"
+ "initWithDomain:code:userInfo:"
+ "requesting-access"
+ "runBlockWithAccessToAssetPackContainingURL:onBehalfOfAuditTokenData:block:"
+ "stage=connecting-to-helper: cannot obtain the Managed Background Assets helper; every asset-pack font will be rejected. %{public}s"
+ "stage=requesting-access: no Apple-hosted asset pack grants access to “%{public}s”. %{public}s"
```
