## TextInputAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/TextInputAppIntentsExtension.appex/TextInputAppIntentsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bc` | `0x3b80` | **`+0x39c4`** |
| `__DATA.__bss` | `0x100` | `0xb80` | **`+0xa80`** |
| `__TEXT.__auth_stubs` | `0x70` | `0x740` | **`+0x6d0`** |
| `__TEXT.__const` | `0x90` | `0x696` | **`+0x606`** |
| `__DATA_CONST.__auth_got` | `0x38` | `0x3a8` | **`+0x370`** |
| `__DATA_CONST.__auth_ptr` | `0x48` | `0x3a0` | **`+0x358`** |
| `__TEXT.__swift5_typeref` | `0x46` | `0x289` | **`+0x243`** |
| `__TEXT.__eh_frame` | `—` | `0x1f0` | **`+0x1f0`** |
| `__TEXT.__unwind_info` | `0x80` | `0x220` | **`+0x1a0`** |
| `__DATA.__data` | `0x10` | `0x1a8` | **`+0x198`** |
| `__DATA_CONST.__const` | `0x98` | `0x1f8` | **`+0x160`** |
| `__TEXT.__cstring` | `—` | `0x105` | **`+0x105`** |
| `__DATA_CONST.__got` | `0x8` | `0x108` | **`+0x100`** |
| `__TEXT.__constg_swiftt` | `0x28` | `0xe0` | **`+0xb8`** |
| `__TEXT.__swift5_reflstr` | `0xe` | `0xb3` | **`+0xa5`** |
| `__TEXT.__objc_methname` | `—` | `0xa4` | **`+0xa4`** |
| `__TEXT.__objc_stubs` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__swift5_assocty` | `0x18` | `0xa8` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x10` | `0x70` | **`+0x60`** |
| `__TEXT.__swift5_proto` | `0x8` | `0x5c` | **`+0x54`** |
| `__TEXT.__oslogstring` | `—` | `0x41` | **`+0x41`** |
| `__DATA.__common` | `—` | `0x30` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x4` | `0x10` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `—` | `0xc` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `—` | `0xc` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__swift5_entry`

### Other Changes

```diff

+  - /System/Library/Frameworks/CoreTransferable.framework/CoreTransferable

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 9
-  Symbols:   22
-  CStrings:  0
+  Functions: 137
+  Symbols:   80
+  CStrings:  13
Symbols:
+ _OBJC_CLASS_$_NSPropertyListSerialization
+ _OBJC_CLASS_$_TIPreferencesController
+ ___chkstk_darwin
+ ___stack_chk_fail
+ ___stack_chk_guard
+ __os_log_impl
+ __swiftEmptyArrayStorage
+ __swiftEmptyDictionarySingleton
+ __swiftImmortalRefCount
+ _bzero
+ _malloc_size
+ _memcpy
+ _memmove
+ _objc_msgSend
+ _objc_opt_self
+ _objc_release_x19
+ _objc_release_x20
+ _objc_release_x21
+ _objc_release_x23
+ _objc_release_x24
+ _objc_release_x26
+ _objc_release_x27
+ _objc_retainAutoreleasedReturnValue
+ _objc_retain_x19
+ _objc_retain_x8
+ _os_log_type_enabled
+ _swift_allocObject
+ _swift_arrayDestroy
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initWithCopy
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_errorRelease
+ _swift_getObjectType
+ _swift_getTypeByMangledNameInContext2
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_once
+ _swift_release
+ _swift_release_x19
+ _swift_release_x21
+ _swift_release_x23
+ _swift_release_x26
+ _swift_release_x8
+ _swift_retain_x19
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _swift_task_alloc
+ _swift_task_dealloc
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
+ _swift_task_switch
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
+ _swift_willThrow
CStrings:
+ "Fetch Keyboard Preferences Intent"
+ "IDS identifier of remote device"
+ "Keyboard Preferences"
+ "Personal Unique Identifier of this device"
+ "Register remote device: %s as %s"
+ "TextInputAppIntentsExtension/FetchKeyboardPreferencesIntent.swift"
+ "Unregister remote device"
+ "_appIntentPreferencesKeys"
+ "com.apple.TextInput"
+ "dataWithPropertyList:format:options:error:"
+ "registerRemoteDeviceWithIDSIdentifier:user:"
+ "sharedPreferencesController"
+ "valueForPreferenceKey:"
```
