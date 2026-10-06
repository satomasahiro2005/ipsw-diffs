## jetsam_priority

> `/usr/libexec/jetsam_priority`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb018` | `0xafbc` | **`-0x5c`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-10845.0.0.0.0
+10848.0.9.0.0
Functions:
~ sub_100009cc0 : 408 -> 392
~ sub_10000a1d0 -> sub_10000a1c0 : 120 -> 104
~ sub_10000a248 -> sub_10000a228 : 928 -> 904
~ sub_10000a8d0 -> sub_10000a898 : 516 -> 500
~ sub_10000ad14 -> sub_10000accc : 224 -> 204
```
