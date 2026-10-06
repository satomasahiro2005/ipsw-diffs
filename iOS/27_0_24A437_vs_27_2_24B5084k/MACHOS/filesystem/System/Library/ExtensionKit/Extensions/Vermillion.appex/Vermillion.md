## Vermillion

> `/System/Library/ExtensionKit/Extensions/Vermillion.appex/Vermillion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10b24` | `0x10bbc` | **`+0x98`** |
| `__DATA_CONST.__const` | `0x799` | `0x741` | **`-0x58`** |
| `__TEXT.__auth_stubs` | `0xff0` | `0xfb0` | **`-0x40`** |
| `__TEXT.__objc_methtype` | `0x60` | `0x24` | **`-0x3c`** |
| `__TEXT.__objc_methname` | `0x28f` | `0x25c` | **`-0x33`** |
| `__TEXT.__cstring` | `0x1a0` | `0x170` | **`-0x30`** |
| `__TEXT.__eh_frame` | `0xcf0` | `0xd18` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x800` | `0x7e0` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x2e0` | `0x2c0` | **`-0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x360` | `0x370` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x10` | `—` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x37f` | `0x38b` | **`+0xc`** |
| `__DATA.__data` | `0x4a0` | `0x498` | **`-0x8`** |
| `__DATA.__objc_selrefs` | `0xb8` | `0xb0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x4f8` | `0x4f0` | **`-0x8`** |
| `__TEXT.__const` | `0xe92` | `0xe90` | **`-0x2`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-42.0.0.0.0
+44.0.0.0.0

-  - /usr/lib/swift/libswiftAppleArchive.dylib

-  Functions: 319
-  Symbols:   144
-  CStrings:  59
+  Functions: 315
+  Symbols:   139
+  CStrings:  56
Symbols:
+ _swift_arrayInitWithCopy
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_retain_x27
- _OBJC_CLASS_$_HKSampleQuery
- __objc_autoreleasePoolPop
- __objc_autoreleasePoolPush
- __swift_FORCE_LOAD_$_swiftAppleArchive
- _objc_retain_x19
- _swift_continuation_await
- _swift_continuation_init
- _swift_deallocObject
- _swift_retain_x25
CStrings:
+ "predicate"
- "executeQuery:"
- "initWithQueryDescriptors:limit:resultsHandler:"
- "querySamples(queryDescriptors:limit:)"
- "v32@?0@\"HKSampleQuery\"8@\"NSArray\"16@\"NSError\"24"
```
