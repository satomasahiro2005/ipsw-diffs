## tvremoted

> `/usr/libexec/tvremoted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x110c8` | `0x110bc` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x218` | `0x220` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-627.0.9.0.0
+627.0.14.0.0
Functions:
~ sub_10000b3ac : 696 -> 692
~ sub_10000c6a0 -> sub_10000c69c : 696 -> 692
~ sub_10000d248 -> sub_10000d240 : 792 -> 788
```
