## cameraispd

> `/usr/libexec/cameraispd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f3e4` | `0x7f404` | **`+0x20`** |
| `__TEXT.__const` | `0x2c08` | `0x2c20` | **`+0x18`** |
| `__TEXT.__cstring` | `0x7f0f` | `0x7f0d` | **`-0x2`** |

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

-20.106.4.0.0
+20.109.0.0.0
Functions:
~ sub_1000049d8 : 1804 -> 1800
~ sub_1000757cc -> sub_1000757c8 : 80 -> 116
CStrings:
+ "20.109"
- "20.106.4"
```
