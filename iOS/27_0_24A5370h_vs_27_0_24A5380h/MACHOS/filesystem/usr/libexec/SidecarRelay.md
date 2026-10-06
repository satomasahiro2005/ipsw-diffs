## SidecarRelay

> `/usr/libexec/SidecarRelay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x87934` | `0x8788c` | **`-0xa8`** |
| `__TEXT.__eh_frame` | `0x1090` | `0x1020` | **`-0x70`** |
| `__DATA_CONST.__got` | `0x508` | `0x4f8` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x1cf0` | `0x1ce0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1d80` | `0x1d70` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xe80` | `0xe78` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
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

-400.37.0.0.0
+400.39.0.0.0

-  Functions: 4568
-  Symbols:   776
+  Functions: 4566
+  Symbols:   773
Symbols:
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _swift_willThrowTypedImpl
CStrings:
+ "400.39"
- "400.37"
```
