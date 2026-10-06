## remindd

> `/usr/libexec/remindd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80f6c8` | `0x80f7d0` | **`+0x108`** |
| `__TEXT.__oslogstring` | `0x618b0` | `0x618f0` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1bc40` | `0x1bc60` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x8c50` | `0x8c60` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x284b1` | `0x284c1` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x7cd8` | `0x7ce0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x4638` | `0x4640` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x10348` | `0x10340` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Symbols:   4278
-  CStrings:  11815
+  Symbols:   4279
+  CStrings:  11817
Symbols:
+ _swift_release_x11
CStrings:
+ "RDFeedbackProvider: Survey is not enabled for non-seed builds."
+ "enableGroceryFeedbackSurvey"
```
