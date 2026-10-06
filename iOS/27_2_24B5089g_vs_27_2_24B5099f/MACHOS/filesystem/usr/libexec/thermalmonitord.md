## thermalmonitord

> `/usr/libexec/thermalmonitord`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x526b0` | `0x52568` | **`-0x148`** |
| `__TEXT.__oslogstring` | `0x9e28` | `0x9de9` | **`-0x3f`** |
| `__DATA.__objc_const` | `0xc948` | `0xc928` | **`-0x20`** |
| `__DATA_CONST.__cfstring` | `0x6780` | `0x6760` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x839a` | `0x838f` | **`-0xb`** |
| `__TEXT.__cstring` | `0x4df6` | `0x4df1` | **`-0x5`** |
| `__DATA.__objc_ivar` | `0xa30` | `0xa2c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2087.40.7.0.0
+2087.40.8.0.1

-  CStrings:  3748
+  CStrings:  3745
Functions:
~ sub_100003204 : 660 -> 636
~ sub_1000037cc -> sub_1000037b4 : 1384 -> 1184
~ sub_10002a8d8 -> sub_10002a7f8 : 656 -> 584
~ sub_10002ab68 -> sub_10002aa40 : 240 -> 212
~ sub_10002ae44 -> sub_10002ad00 : 36 -> 32
CStrings:
- "<Notice> AOP sensor update found for sensor# %d with value: %d"
- "aopSensors"
- "zEAO"
```
