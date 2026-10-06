## storagekitd

> `/usr/libexec/storagekitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ce74` | `0x2cef8` | **`+0x84`** |
| `__TEXT.__oslogstring` | `0x2784` | `0x27c5` | **`+0x41`** |
| `__TEXT.__const` | `0x90` | `0x98` | **`+0x8`** |

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

-1076.40.3.0.0
+1076.40.4.0.0

-  CStrings:  2156
+  CStrings:  2157
Functions:
~ sub_100021400 : 276 -> 408
CStrings:
+ "IO entry for %{public}@ does not conform to %{public}@, refusing"
```
