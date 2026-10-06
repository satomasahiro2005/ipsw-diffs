## WalletBlastDoorService

> `/System/Library/PrivateFrameworks/WalletBlastDoorSupport.framework/XPCServices/WalletBlastDoorService.xpc/WalletBlastDoorService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x464` | `0x8290` | **`+0x7e2c`** |
| `__TEXT.__auth_stubs` | `0x120` | `0xb50` | **`+0xa30`** |
| `__DATA_CONST.__auth_got` | `0x90` | `0x5b0` | **`+0x520`** |
| `__TEXT.__const` | `0x5a` | `0x242` | **`+0x1e8`** |
| `__TEXT.__eh_frame` | `—` | `0x190` | **`+0x190`** |
| `__DATA.__data` | `0x18` | `0x180` | **`+0x168`** |
| `__TEXT.__swift5_typeref` | `0x8` | `0x144` | **`+0x13c`** |
| `__TEXT.__swift5_reflstr` | `—` | `0x103` | **`+0x103`** |
| `__DATA.__bss` | `—` | `0x100` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x60` | `0x160` | **`+0x100`** |
| `__DATA_CONST.__const` | `0xd0` | `0x1a8` | **`+0xd8`** |
| `__DATA_CONST.__auth_ptr` | `0x10` | `0xd0` | **`+0xc0`** |
| `__DATA_CONST.__got` | `0x30` | `0xd8` | **`+0xa8`** |
| `__TEXT.__swift5_fieldmd` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `—` | `0x94` | **`+0x94`** |
| `__TEXT.__cstring` | `—` | `0x48` | **`+0x48`** |
| `__TEXT.__objc_stubs` | `—` | `0x40` | **`+0x40`** |
| `__TEXT.__objc_methname` | `—` | `0x25` | **`+0x25`** |
| `__TEXT.__swift5_assocty` | `—` | `0x18` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__swift5_types` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__swift5_entry`

### Other Changes

```diff

-322.100.2.2.1
+324.100.2.0.0

+  - /System/Library/Frameworks/FinanceKit.framework/FinanceKit

+  - /System/Library/PrivateFrameworks/CollectionsInternal.framework/CollectionsInternal

+  - /usr/lib/swift/libswiftCompression.dylib

-  Functions: 4
-  Symbols:   30
-  CStrings:  0
+  Functions: 75
+  Symbols:   85
+  CStrings:  4
Symbols:
+ _OBJC_CLASS_$_NSFileManager
+ __swiftEmptyDictionarySingleton
+ __swiftEmptySetSingleton
+ __swift_FORCE_LOAD_$_swiftCompression
+ _bzero
+ _malloc_size
+ _memmove
+ _objc_msgSend
+ _objc_opt_self
+ _objc_release_x19
+ _objc_release_x20
+ _objc_release_x22
+ _objc_release_x25
+ _objc_retainAutoreleasedReturnValue
+ _objc_retain_x8
+ _swift_allocError
+ _swift_allocObject
+ _swift_arrayInitWithCopy
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_beginAccess
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithCopy
+ _swift_cvw_initWithTake
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getSingletonMetadata
+ _swift_isUniquelyReferenced_native
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_release
+ _swift_release_n
+ _swift_release_x19
+ _swift_release_x20
+ _swift_release_x21
+ _swift_release_x22
+ _swift_release_x23
+ _swift_release_x24
+ _swift_release_x25
+ _swift_release_x26
+ _swift_release_x27
+ _swift_release_x28
+ _swift_release_x8
+ _swift_retain
+ _swift_retain_x19
+ _swift_retain_x20
+ _swift_retain_x23
+ _swift_retain_x26
+ _swift_retain_x8
+ _swift_storeEnumTagSinglePayloadGeneric
+ _swift_willThrow
Functions:
~ _main : 872 -> 916
+ sub_1000016c8
CStrings:
+ "WorkingDirectoryInvalid"
+ "com.apple.BlastDoor.WalletOrderPreview"
+ "defaultManager"
+ "isWritableFileAtPath:"
```
