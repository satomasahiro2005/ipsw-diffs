## SiriTranslationFlowTools

> `/System/Library/FlowTools/Tools/SiriTranslationFlowTools.flowtool/SiriTranslationFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x144c` | `0x2ad4` | **`+0x1688`** |
| `__TEXT.__auth_stubs` | `0x360` | `0x4f0` | **`+0x190`** |
| `__TEXT.__cstring` | `0x3c` | `0x192` | **`+0x156`** |
| `__DATA_CONST.__const` | `0x80` | `0x1c8` | **`+0x148`** |
| `__TEXT.__eh_frame` | `0x118` | `0x260` | **`+0x148`** |
| `__DATA_CONST.__auth_got` | `0x1b8` | `0x280` | **`+0xc8`** |
| `__TEXT.__unwind_info` | `0xd0` | `0x120` | **`+0x50`** |
| `__DATA.__data` | `0xe8` | `0x128` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x58` | `0x98` | **`+0x40`** |
| `__TEXT.__const` | `0x180` | `0x1b8` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x43` | `0x77` | **`+0x34`** |
| `__DATA.__bss` | `0x100` | `0x120` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x58` | `0x78` | **`+0x20`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.10.1.0.0
+3600.10.2.0.0

-  Functions: 41
-  Symbols:   51
-  CStrings:  6
+  Functions: 55
+  Symbols:   64
+  CStrings:  13
Symbols:
+ ___chkstk_darwin
+ __swiftEmptyArrayStorage
+ __swiftEmptyDictionarySingleton
+ __swiftImmortalRefCount
+ _bzero
+ _objc_release_x19
+ _objc_release_x22
+ _swift_allocError
+ _swift_arrayDestroy
+ _swift_once
+ _swift_release_x19
+ _swift_release_x23
+ _swift_release_x27
+ _swift_retain_x26
+ _swift_setDeallocating
+ _swift_slowAlloc
+ _swift_slowDealloc
- _objc_release_x20
- _objc_release_x21
- _objc_release_x25
- _swift_retain
CStrings:
+ "\" has multiple dialects: "
+ "\" maps to multiple dialects and could not be automatically resolved."
+ ". Ask the user which dialect they prefer, then call translate_text again with that variant as target_language."
+ "Target language \""
+ "guangzhoucantonese"
+ "hongkongcantonese"
+ "taiwanesemandarin"
```
