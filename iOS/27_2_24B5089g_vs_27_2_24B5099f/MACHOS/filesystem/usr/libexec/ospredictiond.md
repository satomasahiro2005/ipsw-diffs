## ospredictiond

> `/usr/libexec/ospredictiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x69570` | `0x69600` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x757d` | `0x75b1` | **`+0x34`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-288.40.6.0.0
+288.40.7.0.0

-  CStrings:  4815
+  CStrings:  4816
Functions:
~ sub_100011368 : 1116 -> 1260
CStrings:
+ "Motion sample: date=%@ stationary=%d confidence=%ld"
```
