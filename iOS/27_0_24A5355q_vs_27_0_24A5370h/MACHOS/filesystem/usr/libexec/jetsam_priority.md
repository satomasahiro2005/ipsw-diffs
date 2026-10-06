## jetsam_priority

> `/usr/libexec/jetsam_priority`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb03c` | `0xb018` | **`-0x24`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-10838.0.0.0.0
+10845.0.0.0.0
Functions:
~ sub_100000b7c : 27256 -> 27196
~ sub_100007664 -> sub_100007628 : 512 -> 528
~ sub_100007864 -> sub_100007838 : 732 -> 728
~ sub_100009424 -> sub_1000093f4 : 416 -> 412
~ sub_1000095c4 -> sub_100009590 : 80 -> 84
~ sub_1000097a8 -> sub_100009778 : 132 -> 128
~ sub_1000098cc -> sub_100009898 : 168 -> 164
~ sub_10000a208 -> sub_10000a1d0 : 104 -> 120
~ sub_10000a270 -> sub_10000a248 : 904 -> 928
~ sub_10000a8e0 -> sub_10000a8d0 : 524 -> 516
~ sub_10000aaec -> sub_10000aad4 : 396 -> 380
~ sub_10000ad3c -> sub_10000ad14 : 208 -> 224
~ sub_10000b5e4 -> sub_10000b5cc : 220 -> 208
```
