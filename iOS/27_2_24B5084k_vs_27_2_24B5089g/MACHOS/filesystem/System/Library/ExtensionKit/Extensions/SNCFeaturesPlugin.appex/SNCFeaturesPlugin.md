## SNCFeaturesPlugin

> `/System/Library/ExtensionKit/Extensions/SNCFeaturesPlugin.appex/SNCFeaturesPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x56b8` | `0x15c4` | **`-0x40f4`** |
| `__DATA.__bss` | `0x800` | `0x180` | **`-0x680`** |
| `__TEXT.__auth_stubs` | `0x8d0` | `0x410` | **`-0x4c0`** |
| `__TEXT.__const` | `0x5c8` | `0x1d2` | **`-0x3f6`** |
| `__DATA_CONST.__const` | `0x395` | `0x120` | **`-0x275`** |
| `__DATA_CONST.__auth_got` | `0x470` | `0x210` | **`-0x260`** |
| `__TEXT.__oslogstring` | `0x195` | `—` | **`-0x195`** |
| `__TEXT.__eh_frame` | `0x2e8` | `0x190` | **`-0x158`** |
| `__DATA_CONST.__auth_ptr` | `0x1f8` | `0xb8` | **`-0x140`** |
| `__TEXT.__swift5_typeref` | `0x175` | `0x6e` | **`-0x107`** |
| `__TEXT.__cstring` | `0x152` | `0x4f` | **`-0x103`** |
| `__TEXT.__unwind_info` | `0x1f8` | `0x100` | **`-0xf8`** |
| `__TEXT.__swift5_reflstr` | `0xf9` | `0xe` | **`-0xeb`** |
| `__DATA.__data` | `0x1c0` | `0xe8` | **`-0xd8`** |
| `__TEXT.__swift5_fieldmd` | `0xbc` | `0x20` | **`-0x9c`** |
| `__DATA_CONST.__got` | `0x108` | `0x90` | **`-0x78`** |
| `__TEXT.__constg_swiftt` | `0xb8` | `0x64` | **`-0x54`** |
| `__TEXT.__swift5_assocty` | `0x60` | `0x18` | **`-0x48`** |
| `__TEXT.__swift5_proto` | `0x40` | `0xc` | **`-0x34`** |
| `__TEXT.__objc_stubs` | `0x40` | `0x20` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0x20` | `—` | **`-0x20`** |
| `__TEXT.__swift5_types` | `0x14` | `0x8` | **`-0xc`** |
| `__TEXT.__objc_methname` | `0x20` | `0x15` | **`-0xb`** |
| `__DATA.__objc_selrefs` | `0x10` | `0x8` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x18` | `0x14` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x24` | `0x20` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x18` | `0x14` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-44.0.0.0.0
+46.0.0.0.0

+  - /usr/lib/swift/libswiftAppleArchive.dylib

+  - /usr/lib/swift/libswiftMetalKit.dylib
+  - /usr/lib/swift/libswiftModelIO.dylib

-  Functions: 129
-  Symbols:   107
-  CStrings:  21
+  Functions: 42
+  Symbols:   71
+  CStrings:  5
Symbols:
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ __swift_FORCE_LOAD_$_swiftMetalKit
+ __swift_FORCE_LOAD_$_swiftModelIO
- _OBJC_CLASS_$_NSNumber
- ___chkstk_darwin
- __os_log_impl
- __swiftEmptyArrayStorage
- __swiftEmptyDictionarySingleton
- __swiftImmortalRefCount
- _bzero
- _malloc_size
- _memcpy
- _memmove
- _objc_release_x20
- _os_log_type_enabled
- _swift_allocError
- _swift_arrayDestroy
- _swift_beginAccess
- _swift_bridgeObjectRelease_n
- _swift_bridgeObjectRetain
- _swift_bridgeObjectRetain_n
- _swift_cvw_assignWithCopy
- _swift_cvw_assignWithTake
- _swift_cvw_destroy
- _swift_cvw_initWithCopy
- _swift_cvw_initializeBufferWithCopyOfBuffer
- _swift_deallocObject
- _swift_dynamicCast
- _swift_getDynamicType
- _swift_getObjectType
- _swift_initStackObject
- _swift_isUniquelyReferenced_nonNull_native
- _swift_release_x19
- _swift_release_x21
- _swift_release_x22
- _swift_release_x23
- _swift_retain_x23
- _swift_setDeallocating
- _swift_slowAlloc
- _swift_slowDealloc
- _swift_unknownObjectRetain
- _swift_willThrow
CStrings:
- ",\n    trainingFunction: "
- "Failed to convert all model_diff entries to Float32 (%ld/%ld)"
- "Hyper Parameters: %s"
- "Morpheus program attachment not found: %s"
- "Morpheus training returned unexpected result type: %s"
- "MorpheusDecoding"
- "MorpheusExecution"
- "PreparePFLResult"
- "SNCFeaturesHyperParams(\n    morpheusTrainingProgramFileName: "
- "Training metrics: %s"
- "Weight vector count: %ld, first 5: %s"
- "floatValue"
- "metrics (index 0) not a dict in training result list"
- "model_diff (index 1) not an array in training result list"
- "morpheus_training_program_file_name"
- "training_function"
```
