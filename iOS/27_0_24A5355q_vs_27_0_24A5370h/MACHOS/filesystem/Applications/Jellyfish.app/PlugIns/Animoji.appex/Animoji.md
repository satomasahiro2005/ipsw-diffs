## Animoji

> `/Applications/Jellyfish.app/PlugIns/Animoji.appex/Animoji`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cc04` | `0x1cbe8` | **`-0x1c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-402.100.1.0.0
+403.100.1.0.0
Functions:
~ sub_100002b60 : 324 -> 320
~ sub_100002ca4 -> sub_100002ca0 : 260 -> 256
~ sub_100005bf8 -> sub_100005bf0 : 332 -> 336
~ sub_10000ca4c -> sub_10000ca48 : 1292 -> 1288
~ sub_10001827c -> sub_100018274 : 4520 -> 4508
~ sub_10001af20 -> sub_10001af0c : 540 -> 536
~ sub_10001c5ec -> sub_10001c5d4 : 640 -> 636
CStrings:
+ "403.100.1"
- "402.100.1"
```
