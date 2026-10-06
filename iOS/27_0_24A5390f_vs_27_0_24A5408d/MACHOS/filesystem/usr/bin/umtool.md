## umtool

> `/usr/bin/umtool`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15504` | `0x15544` | **`+0x40`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-490.0.0.0.0
+490.0.3.0.0
Functions:
~ sub_1000066ec : 8 -> 12
~ sub_1000066f4 -> sub_1000066f8 : 12 -> 28
~ sub_100006700 -> sub_100006714 : 16 -> 8
~ sub_100006710 -> sub_10000671c : 28 -> 16
~ sub_1000067e8 : 12 -> 20
~ sub_1000067f4 -> sub_1000067fc : 20 -> 12
~ sub_10000d93c : 160 -> 200
~ sub_10000da6c -> sub_10000da94 : 64 -> 88
```
