## SidecarRelay

> `/usr/libexec/SidecarRelay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x87abc` | `0x87b4c` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x1020` | `0x1068` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x1d70` | `0x1d80` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x500` | `0x4f8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-412.2.0.0.0
+412.4.0.0.0

-  Functions: 4571
-  Symbols:   774
+  Functions: 4574
+  Symbols:   773
Symbols:
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
- _$s10Foundation4DateVSLAAMc
- _$sSL2leoiySbx_xtFZTj
CStrings:
+ "412.4"
- "412.2"
```
