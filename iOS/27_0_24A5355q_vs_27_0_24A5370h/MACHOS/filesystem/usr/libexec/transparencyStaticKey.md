## transparencyStaticKey

> `/usr/libexec/transparencyStaticKey`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x13bc` | `0x13fd` | **`+0x41`** |
| `__TEXT.__objc_stubs` | `0x6700` | `0x6720` | **`+0x20`** |
| `__TEXT.__text` | `0x6b1b4` | `0x6b194` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x8195` | `0x81aa` | **`+0x15`** |
| `__TEXT.__objc_methlist` | `0x7be0` | `0x7bf0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x2418` | `0x2420` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x27e0` | `0x27e8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1751.0.0.502.1
+1766.0.13.0.0

-  Functions: 3715
+  Functions: 3716

-  CStrings:  2776
+  CStrings:  2779
CStrings:
+ "announceMismatchType"
+ "confirm: dropping stale announce"
+ "finish: dropping stale announce"
```
