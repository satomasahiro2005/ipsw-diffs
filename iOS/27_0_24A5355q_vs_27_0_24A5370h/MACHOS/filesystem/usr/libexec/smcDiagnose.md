## smcDiagnose

> `/usr/libexec/smcDiagnose`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3df8` | `0x3e28` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x130` | `0x138` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-159.0.0.0.0
+162.0.0.0.0
Functions:
~ sub_100000b80 : 100 -> 96
~ sub_100001188 -> sub_100001184 : 244 -> 240
~ sub_10000127c -> sub_100001274 : 440 -> 436
~ sub_1000020dc -> sub_1000020d0 : 720 -> 728
~ sub_1000023ac -> sub_1000023a8 : 92 -> 100
~ sub_100002408 -> sub_10000240c : 784 -> 792
~ sub_100003dac -> sub_100003db8 : 524 -> 540
~ sub_100003fb8 -> sub_100003fd4 : 444 -> 464
```
