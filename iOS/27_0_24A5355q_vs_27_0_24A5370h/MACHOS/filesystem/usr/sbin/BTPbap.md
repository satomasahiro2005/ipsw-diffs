## BTPbap

> `/usr/sbin/BTPbap`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6c08` | `0x6bd8` | **`-0x30`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2700.30.2.0.0
+2700.34.0.0.0
Functions:
~ sub_1000029ac : 516 -> 512
~ sub_100002bb0 -> sub_100002bac : 528 -> 524
~ sub_100002dc0 -> sub_100002db8 : 628 -> 624
~ sub_100003034 -> sub_100003028 : 3368 -> 3352
~ sub_100004030 -> sub_100004014 : 552 -> 548
~ sub_100004258 -> sub_100004238 : 664 -> 660
~ sub_1000044f0 -> sub_1000044cc : 604 -> 600
~ sub_10000474c -> sub_100004724 : 660 -> 656
~ sub_100004e68 -> sub_100004e3c : 608 -> 604
```
