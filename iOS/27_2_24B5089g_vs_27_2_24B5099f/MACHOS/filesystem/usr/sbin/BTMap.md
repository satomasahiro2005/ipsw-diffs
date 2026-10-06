## BTMap

> `/usr/sbin/BTMap`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x44e4` | `0x44bc` | **`-0x28`** |
| `__TEXT.__auth_stubs` | `0x610` | `0x620` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x318` | `0x320` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2701.2.0.0.0
+2701.4.0.0.0

-  Symbols:   154
+  Symbols:   155
Symbols:
+ _objc_retain_x25
Functions:
~ sub_100003f8c : 1848 -> 1824
~ sub_1000046c4 -> sub_1000046ac : 1512 -> 1496
```
