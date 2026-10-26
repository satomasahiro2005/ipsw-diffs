## demod

> `/usr/libexec/demod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1052a8` | `0x105aa8` | **`+0x800`** |
| `__TEXT.__eh_frame` | `0xe90` | `0xef0` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x1dc6c` | `0x1dc8c` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x11d0` | `0x11e0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2580` | `0x2590` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3d80` | `0x3d90` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x12d0` | `0x12d8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xc8` | `0xd0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x78` | `0x7c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-1871.40.62.0.0
+1871.42.1.0.0

-  Functions: 6245
-  Symbols:   1220
-  CStrings:  11129
+  Functions: 6247
+  Symbols:   1223
+  CStrings:  11130
Symbols:
+ _$s17CompanionSetupKit11CSKStepMiscC5EventO18personalContentAskyA2EmFWC
+ _$s17CompanionSetupKit11CSKStepMiscC7CommandO23personalContentAnsweredyAESb_tcAEmFWC
+ _swift_release_x22
CStrings:
+ "Answering PersonalContent: yes"
```
