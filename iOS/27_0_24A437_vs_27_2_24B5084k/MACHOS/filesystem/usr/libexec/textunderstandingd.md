## textunderstandingd

> `/usr/libexec/textunderstandingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x844` | `0xd08` | **`+0x4c4`** |
| `__TEXT.__auth_stubs` | `0x2e0` | `0x3f0` | **`+0x110`** |
| `__DATA_CONST.__auth_got` | `0x178` | `0x200` | **`+0x88`** |
| `__DATA.__data` | `0x1e0` | `0x210` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x30` | `0x60` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xb0` | `0xd8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xc8` | `0xf0` | **`+0x28`** |
| `__DATA_CONST.__auth_ptr` | `0x8` | `0x18` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x17d` | `0x18d` | **`+0x10`** |
| `__TEXT.__const` | `0xba` | `0xc8` | **`+0xe`** |
| `__TEXT.__swift5_typeref` | `0x48` | `0x52` | **`+0xa`** |
| `__DATA.__common` | `0x8` | `0x10` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-176.3.0.1.0
+186.0.0.0.0

+  - /usr/lib/swift/libswift_DarwinFoundation3.dylib

-  Functions: 29
-  Symbols:   63
-  CStrings:  72
+  Functions: 39
+  Symbols:   76
+  CStrings:  73
Symbols:
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _OBJC_CLASS_$_OS_dispatch_source
+ __NSConcreteStackBlock
+ ___chkstk_darwin
+ __swiftEmptyArrayStorage
+ _exit
+ _objc_release_x27
+ _signal
+ _swift_getObjectType
+ _swift_getTypeByMangledNameInContext2
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_getWitnessTable
+ _swift_retain_x2
CStrings:
+ "v8@?0"
```
