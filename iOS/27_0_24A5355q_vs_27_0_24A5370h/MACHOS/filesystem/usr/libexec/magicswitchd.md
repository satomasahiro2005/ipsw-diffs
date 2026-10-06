## magicswitchd

> `/usr/libexec/magicswitchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xad74` | `0xad48` | **`-0x2c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff
Functions:
~ sub_1000012b4 : 648 -> 644
~ sub_100002f08 -> sub_100002f04 : 524 -> 520
~ sub_1000032fc -> sub_1000032f4 : 1576 -> 1572
~ sub_100004cbc -> sub_100004cb0 : 620 -> 616
~ sub_10000556c -> sub_10000555c : 348 -> 344
~ sub_1000056c8 -> sub_1000056b4 : 596 -> 588
~ sub_10000591c -> sub_100005900 : 400 -> 396
~ sub_1000068a8 -> sub_100006888 : 948 -> 940
~ sub_100006c5c -> sub_100006c34 : 368 -> 364
CStrings:
+ "MagicSwitchEnabler --- Launching; \"MagicSwitch-43\" \"1635\""
- "MagicSwitchEnabler --- Launching; \"MagicSwitch-43\" \"1060\""
```
