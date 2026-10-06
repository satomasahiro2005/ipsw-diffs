## logd_reporter

> `/usr/libexec/logd_reporter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e4c` | `0x3eb8` | **`+0x6c`** |
| `__TEXT.__oslogstring` | `0x633` | `0x67f` | **`+0x4c`** |
| `__TEXT.__const` | `0xb0` | `0xa8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1958.0.0.0.1
+1965.0.0.0.0

-  CStrings:  257
+  CStrings:  258
Functions:
~ sub_10000275c : 5560 -> 5564
~ sub_10000485c -> sub_100004860 : 852 -> 956
CStrings:
+ "DiagnosticRequest unavailable; %@ report at %{public}@ not submitted to DP."
```
