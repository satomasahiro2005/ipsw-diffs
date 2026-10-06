## eligibilityd

> `/usr/libexec/eligibilityd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__objc_dictobj` | `0xafa0` | `0xb270` | **`+0x2d0`** |
| `__TEXT.__unwind_info` | `0x12c8` | `0x1058` | **`-0x270`** |
| `__DATA_CONST.__objc_arraydata` | `0xc288` | `0xc4d0` | **`+0x248`** |
| `__TEXT.__text` | `0x43924` | `0x43a24` | **`+0x100`** |
| `__DATA_CONST.__objc_arrayobj` | `0x2ee0` | `0x2f88` | **`+0xa8`** |
| `__TEXT.__cstring` | `0x7063` | `0x7087` | **`+0x24`** |
| `__DATA_CONST.__cfstring` | `0x55c0` | `0x55e0` | **`+0x20`** |
| `__DATA.__bss` | `0x2de0` | `0x2df0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1a70` | `0x1a60` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xd48` | `0xd40` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x3b0` | `0x3a8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-432.0.0.0.2
+443.0.0.502.2

-  Functions: 1401
-  Symbols:   647
-  CStrings:  2017
+  Functions: 1402
+  Symbols:   644
+  CStrings:  2018
Symbols:
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _swift_willThrowTypedImpl
CStrings:
+ "21:42:02"
+ "443.0.0.502.2"
+ "AgeAssuranceWaterfallAccountOptTX"
+ "Jun 29 2026"
- "00:36:44"
- "432.0.0.0.2"
- "Jun 12 2026"
```
