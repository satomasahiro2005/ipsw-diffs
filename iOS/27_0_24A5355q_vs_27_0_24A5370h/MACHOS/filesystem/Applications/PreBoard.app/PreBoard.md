## PreBoard

> `/Applications/PreBoard.app/PreBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x640` | `0x650` | **`+0x10`** |
| `__TEXT.__text` | `0xca28` | `0xca18` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x330` | `0x338` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4615.3.107.0.0
+4621.0.0.0.0

-  Symbols:   223
+  Symbols:   224
Symbols:
+ _objc_retain_x28
Functions:
~ sub_10000375c : 964 -> 960
~ sub_1000046b8 -> sub_1000046b4 : 1940 -> 1932
~ sub_10000b884 -> sub_10000b878 : 396 -> 392
```
