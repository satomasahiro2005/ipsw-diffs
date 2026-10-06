## PerfPowerServicesSignpostReader

> `/System/Library/PrivateFrameworks/PowerlogCore.framework/XPCServices/PerfPowerServicesSignpostReader.xpc/PerfPowerServicesSignpostReader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d780` | `0x1d8f0` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x1289` | `0x12c1` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x1a8` | `0x1b8` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x6dc` | `0x6e8` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3486.0.21.502.1
+3486.0.46.502.1

-  CStrings:  1428
+  CStrings:  1429
Functions:
~ sub_100001f68 : 776 -> 892
~ sub_100004acc -> sub_100004b40 : 652 -> 756
~ sub_100005138 -> sub_100005214 : 232 -> 392
~ sub_100005220 -> sub_10000539c : 1840 -> 1828
CStrings:
+ "Implausible AppResume duration detected: %llu ms for %@"
```
