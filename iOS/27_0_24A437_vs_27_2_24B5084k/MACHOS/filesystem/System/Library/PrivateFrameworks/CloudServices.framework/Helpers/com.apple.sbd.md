## com.apple.sbd

> `/System/Library/PrivateFrameworks/CloudServices.framework/Helpers/com.apple.sbd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ef90` | `0x4ef58` | **`-0x38`** |
| `__TEXT.__cstring` | `0x43ff` | `0x43fb` | **`-0x4`** |
| `__TEXT.__oslogstring` | `0x836f` | `0x836b` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-747.0.6.0.0
+747.40.7.0.0
Functions:
~ sub_100015498 : 444 -> 396
~ sub_10004cbac -> sub_10004cb7c : 60 -> 52
CStrings:
+ "attempt to enable backup with non-decimal digits in SMS target"
- "attempt to enable backup with non-decimal digits in SMS target: %@"
```
