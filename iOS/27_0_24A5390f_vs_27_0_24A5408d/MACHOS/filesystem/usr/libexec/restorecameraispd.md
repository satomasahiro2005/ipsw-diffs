## restorecameraispd

> `/usr/libexec/restorecameraispd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x3aec00` | `0x3bdc00` | **`+0xf000`** |
| `__TEXT.__text` | `0x1ce9c` | `0x1cf84` | **`+0xe8`** |
| `__TEXT.__cstring` | `0x3203` | `0x3259` | **`+0x56`** |
| `__TEXT.__oslogstring` | `0x2280` | `0x22c4` | **`+0x44`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-20.57.3.0.0
+20.62.0.0.0

-  CStrings:  627
+  CStrings:  630
Functions:
~ sub_100000db0 : 1192 -> 1276
~ sub_100013a48 -> sub_100013a9c : 264 -> 300
~ sub_100014630 -> sub_1000146a8 : 2188 -> 2300
CStrings:
+ "/usr/local/share/firmware/isp/0227_01XX.dat"
+ "/usr/local/share/firmware/isp/2226_01XX.dat"
+ "20.62"
+ "ISP still in use by another session; keeping shared interface open\n"
- "20.57.3"
```
