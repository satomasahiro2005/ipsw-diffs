## AppleMCTF

> `/System/Library/Video/Plug-Ins/AppleMCTF.bundle/AppleMCTF`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x85ea4` | `0x85e20` | **`-0x84`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff
Functions:
~ sub_18fc0 : 2236 -> 2216
~ sub_25aa0 -> sub_25a8c : 1100 -> 1108
~ sub_25eec -> sub_25ee0 : 1132 -> 1140
~ sub_26358 -> sub_26354 : 1700 -> 1708
~ sub_388e8 -> sub_388ec : 1552 -> 1556
~ sub_3dd9c -> sub_3dda4 : 28272 -> 28220
~ sub_60d78 -> sub_60d4c : 1056 -> 1060
~ sub_67ab4 -> sub_67a8c : 908 -> 888
~ sub_68168 -> sub_6812c : 484 -> 472
~ sub_69574 -> sub_6952c : 144 -> 140
~ sub_697a8 -> sub_6975c : 256 -> 244
~ sub_698a8 -> sub_69850 : 820 -> 808
~ sub_6a834 -> sub_6a7d0 : 152 -> 148
~ sub_6aa90 -> sub_6aa28 : 284 -> 276
~ sub_6abac -> sub_6ab3c : 820 -> 808
~ sub_822d4 -> sub_82258 : 116 -> 108
CStrings:
+ "21:23:03"
+ "Jun 29 2026"
- "19:43:30"
- "Jun 18 2026"
```
