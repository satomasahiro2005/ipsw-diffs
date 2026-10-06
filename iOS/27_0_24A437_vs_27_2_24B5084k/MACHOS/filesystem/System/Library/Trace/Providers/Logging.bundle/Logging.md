## Logging

> `/System/Library/Trace/Providers/Logging.bundle/Logging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaebc` | `0xb238` | **`+0x37c`** |
| `__TEXT.__objc_stubs` | `0x320` | `0x380` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0xa80` | `0xad0` | **`+0x50`** |
| `__TEXT.__cstring` | `0x1c75` | `0x1cb5` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x548` | `0x578` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x61c` | `0x64c` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x400` | `0x428` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x2b0` | `0x2d0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x188` | `0x1a0` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x338` | `0x34e` | **`+0x16`** |
| `__TEXT.__const` | `0x95e` | `0x94e` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2fc` | `0x308` | **`+0xc`** |
| `__DATA.__data` | `0x4e8` | `0x4e0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xd8` | `0xe0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-206.0.0.0.0
+210.0.0.0.0
+  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

-  Functions: 388
-  Symbols:   129
-  CStrings:  209
+  Functions: 389
+  Symbols:   138
+  CStrings:  214
Symbols:
+ _ATSPredicateFromFormatString
+ _OBJC_EHTYPE_$_NSException
+ __Unwind_Resume
+ ___objc_personality_v0
+ _objc_begin_catch
+ _objc_claimAutoreleasedReturnValue
+ _objc_end_catch
+ _objc_retainAutorelease
+ _swift_release_x23
CStrings:
+ ". Logging will be disabled."
+ "Invalid predicate '"
+ "description"
+ "predicateWithFormat:"
+ "reason"
```
