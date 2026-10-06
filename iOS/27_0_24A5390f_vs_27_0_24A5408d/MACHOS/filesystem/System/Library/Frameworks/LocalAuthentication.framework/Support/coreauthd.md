## coreauthd

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/coreauthd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38600` | `0x38640` | **`+0x40`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2319.0.46.0.0
+2319.0.63.0.0
Functions:
~ sub_100013ee0 : 8 -> 12
~ sub_100013ee8 -> sub_100013eec : 12 -> 28
~ sub_100013ef4 -> sub_100013f08 : 16 -> 8
~ sub_100013f04 -> sub_100013f10 : 28 -> 16
~ sub_100013fdc : 12 -> 20
~ sub_100013fe8 -> sub_100013ff0 : 20 -> 12
~ sub_1000239f0 : 160 -> 200
~ sub_100023b20 -> sub_100023b48 : 64 -> 88
```
