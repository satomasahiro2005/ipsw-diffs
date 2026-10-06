## tzinit

> `/usr/libexec/tzinit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10344` | `0x102dc` | **`-0x68`** |
| `__TEXT.__gcc_except_tab` | `0xc00` | `0xbfc` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ sub_100002b04 : 176 -> 156
~ sub_10000a9c4 -> sub_10000a9b0 : 532 -> 508
~ sub_10000abd8 -> sub_10000abac : 176 -> 152
~ sub_10000ac88 -> sub_10000ac44 : 228 -> 204
~ sub_10000e954 -> sub_10000e8f8 : 484 -> 472
```
