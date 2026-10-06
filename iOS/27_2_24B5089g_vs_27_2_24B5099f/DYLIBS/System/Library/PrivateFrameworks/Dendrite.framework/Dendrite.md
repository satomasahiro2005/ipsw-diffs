## Dendrite

> `/System/Library/PrivateFrameworks/Dendrite.framework/Dendrite`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x37d0` | `0x3a50` | **`+0x280`** |
| `__DATA_DIRTY.__bss` | `0x800` | `0x580` | **`-0x280`** |
| `__DATA_DIRTY.__data` | `0x2018` | `0x2288` | **`+0x270`** |
| `__AUTH.__data` | `0x220` | `—` | **`-0x220`** |
| `__TEXT.__const` | `0x5390` | `0x5410` | **`+0x80`** |
| `__DATA.__data` | `0x1040` | `0xfd8` | **`-0x68`** |
| `__AUTH.__objc_data` | `0x48` | `—` | **`-0x48`** |
| `__DATA_DIRTY.__objc_data` | `0x1d8` | `0x220` | **`+0x48`** |
| `__TEXT.__text` | `0x70898` | `0x708c8` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x5260` | `0x5258` | **`-0x8`** |

### Other Changes

```diff

-7.1.0.0.0
+8.0.0.0.0
Functions:
~ sub_263712678 -> sub_2629ff590 : 624 -> 628
~ sub_2637133b8 -> sub_262a002d4 : 180 -> 172
~ sub_2637134b4 -> sub_262a003c8 : 292 -> 304
~ sub_263719154 -> sub_262a06074 : 1676 -> 1716
```
