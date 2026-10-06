## AlarmUIPlugin

> `/System/Library/Snippets/UIPlugins/AlarmUIPlugin.bundle/AlarmUIPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xde4` | `0x29ec` | **`+0x1c08`** |
| `__TEXT.__swift5_typeref` | `0x4c` | `0x4cc` | **`+0x480`** |
| `__TEXT.__auth_stubs` | `0x1a0` | `0x410` | **`+0x270`** |
| `__DATA.__data` | `0xd0` | `0x238` | **`+0x168`** |
| `__TEXT.__const` | `0x10a` | `0x26e` | **`+0x164`** |
| `__DATA_CONST.__auth_got` | `0xd0` | `0x208` | **`+0x138`** |
| `__DATA_CONST.__auth_ptr` | `0x80` | `0x150` | **`+0xd0`** |
| `__DATA.__bss` | `0x180` | `0x210` | **`+0x90`** |
| `__DATA_CONST.__got` | `0x88` | `0x110` | **`+0x88`** |
| `__TEXT.__unwind_info` | `0x98` | `0x120` | **`+0x88`** |
| `__DATA_CONST.__const` | `0x160` | `0x1d8` | **`+0x78`** |
| `__TEXT.__constg_swiftt` | `0x64` | `0xb4` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x80` | `0x48` | **`-0x38`** |
| `__TEXT.__swift5_capture` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x2c` | `0x48` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0x18` | `0x30` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0x41` | `0x51` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0xc` | `0x10` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x8` | `0xc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__objc_classlist`

### Other Changes

```diff

-3600.20.7.0.0
+3600.26.5.0.0

-  Functions: 23
-  Symbols:   40
+  Functions: 65
+  Symbols:   63
Symbols:
+ __swiftEmptyArrayStorage
+ _malloc_size
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithCopy
+ _swift_cvw_initWithTake
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_deallocObject
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getKeyPath
+ _swift_getSingletonMetadata
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_release_x20
+ _swift_release_x21
+ _swift_release_x22
+ _swift_release_x25
+ _swift_release_x8
+ _swift_storeEnumTagSinglePayloadGeneric
- _swift_release_x27
```
