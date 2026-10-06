## profiled

> `/usr/libexec/profiled`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc85b4` | `0xc8678` | **`+0xc4`** |
| `__DATA_CONST.__got` | `0x20a8` | `0x2118` | **`+0x70`** |
| `__TEXT.__auth_stubs` | `0x28e0` | `0x2910` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x1480` | `0x1498` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1b50` | `0x1b58` | **`+0x8`** |

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
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-2482.0.0.0.0
+2483.0.1.0.0

-  Functions: 2733
-  Symbols:   1794
+  Functions: 2734
+  Symbols:   1797
Symbols:
+ _MCSendEnablingRestrictionsChangedNotification
+ _swift_retain_x19
+ _swift_retain_x21
```
