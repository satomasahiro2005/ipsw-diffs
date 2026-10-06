## companion_proxy

> `/usr/libexec/companion_proxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x944c` | `0x942c` | **`-0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff
Functions:
~ sub_100001b28 : 3264 -> 3260
~ sub_100003b58 -> sub_100003b54 : 1612 -> 1600
~ sub_100006208 -> sub_1000061f8 : 420 -> 416
~ sub_1000063ac -> sub_100006398 : 564 -> 560
~ sub_100007db8 -> sub_100007da0 : 5116 -> 5108
CStrings:
+ "19:05:55"
+ "Jun  9 2026"
- "09:53:29"
- "May 21 2026"
```
