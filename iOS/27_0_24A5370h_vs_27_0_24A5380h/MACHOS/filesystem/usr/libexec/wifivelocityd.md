## wifivelocityd

> `/usr/libexec/wifivelocityd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__got` | `0x580` | `0x5b0` | **`+0x30`** |
| `__DATA_CONST.__objc_intobj` | `0xe88` | `0xeb8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1b40` | `0x1b38` | **`-0x8`** |
| `__TEXT.__text` | `0x99898` | `0x99894` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1190.18.0.0.0
+1190.20.0.0.0
Symbols:
+ _RPOptionStatusFlags
- _RPOptionAllowUnauthenticated
Functions:
~ sub_10007581c : 796 -> 844
~ sub_100075f78 -> sub_100075fa8 : 3076 -> 2908
~ sub_1000888d0 -> sub_100088858 : 604 -> 708
~ sub_100097814 -> sub_100097804 : 128 -> 236
~ sub_1000982c0 -> sub_10009831c : 432 -> 336
```
