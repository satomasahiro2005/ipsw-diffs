## com.apple.printactivityservice

> `/System/Library/PrivateFrameworks/PrintKit.framework/XPCServices/com.apple.printactivityservice.xpc/com.apple.printactivityservice`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa150` | `0xb284` | **`+0x1134`** |
| `__TEXT.__eh_frame` | `0x3c0` | `0x4c8` | **`+0x108`** |
| `__TEXT.__auth_stubs` | `0xa40` | `0xad0` | **`+0x90`** |
| `__DATA_CONST.__auth_got` | `0x528` | `0x570` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x5b8` | `0x600` | **`+0x48`** |
| `__DATA.__objc_const` | `0x470` | `0x4b0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x350` | `0x380` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x260` | `0x240` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x9e0` | `0x9c0` | **`-0x20`** |
| `__DATA.__data` | `0x3b8` | `0x3d0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1b0` | `0x1c8` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x374` | `0x38c` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x8c` | `0xa0` | **`+0x14`** |
| `__DATA.__objc_data` | `0x1d0` | `0x1e0` | **`+0x10`** |
| `__TEXT.__const` | `0x832` | `0x842` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x28d` | `0x29d` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x8` | `0x18` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x283` | `0x28f` | **`+0xc`** |
| `__TEXT.__objc_methname` | `0xaea` | `0xaf3` | **`+0x9`** |
| `__DATA.__objc_selrefs` | `0x378` | `0x370` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0xc` | `0x14` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xc` | `0x10` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-42.0.0.0.0
+44.1.0.0.0

-  Functions: 253
-  Symbols:   164
-  CStrings:  215
+  Functions: 264
+  Symbols:   163
+  CStrings:  216
Symbols:
+ _objc_retain_x22
+ _objc_retain_x25
+ _objc_retain_x26
+ _objc_retain_x27
+ _swift_retain_x27
- _OBJC_CLASS_$_NSNumber
- _PCCancelPrintJobNotification
- _PKCopiesKey
- _swift_release_x21
- _swift_release_x24
- _swift_retain_x25
CStrings:
+ "isStopped"
+ "printingJob"
- "integerValue"
```
