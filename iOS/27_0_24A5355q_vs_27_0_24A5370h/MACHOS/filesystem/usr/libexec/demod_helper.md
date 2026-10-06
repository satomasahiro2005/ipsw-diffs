## demod_helper

> `/usr/libexec/demod_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e6ac` | `0x2e81c` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x6226` | `0x62c7` | **`+0xa1`** |
| `__DATA_CONST.__cfstring` | `0x50c0` | `0x50e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x6469` | `0x6487` | **`+0x1e`** |
| `__TEXT.__const` | `0x128` | `0x130` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x960` | `0x958` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1865.0.0.0.0
+1871.0.14.0.0

-  Functions: 1048
+  Functions: 1051

-  CStrings:  2171
+  CStrings:  2175
CStrings:
+ "/var/mobile/Home/DemoContent/"
+ "Cannot remove stale symlink at %{public}@ - Error: %{public}@"
+ "Removing stale symlink at %{public}@"
+ "Unexpected non-symlink entry (type=%{public}@) at %{public}@ "
```
