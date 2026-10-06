## thermalmonitord

> `/usr/libexec/thermalmonitord`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5740c` | `0x5256c` | **`-0x4ea0`** |
| `__DATA.__objc_const` | `0xd1d8` | `0xc948` | **`-0x890`** |
| `__TEXT.__const` | `0x1cc0` | `0x1560` | **`-0x760`** |
| `__DATA.__objc_data` | `0x36b0` | `0x3340` | **`-0x370`** |
| `__DATA_CONST.__objc_intobj` | `0xa08` | `0x7b0` | **`-0x258`** |
| `__TEXT.__objc_methlist` | `0x426c` | `0x4014` | **`-0x258`** |
| `__TEXT.__objc_classname` | `0x1484` | `0x1303` | **`-0x181`** |
| `__DATA_CONST.__objc_arraydata` | `0x1348` | `0x1280` | **`-0xc8`** |
| `__TEXT.__unwind_info` | `0x12d0` | `0x1230` | **`-0xa0`** |
| `__DATA_CONST.__objc_arrayobj` | `0x2b8` | `0x228` | **`-0x90`** |
| `__DATA_CONST.__cfstring` | `0x67e0` | `0x6780` | **`-0x60`** |
| `__DATA_CONST.__got` | `0x688` | `0x630` | **`-0x58`** |
| `__DATA_CONST.__objc_classlist` | `0x578` | `0x520` | **`-0x58`** |
| `__TEXT.__objc_methname` | `0x83da` | `0x8388` | **`-0x52`** |
| `__DATA.__objc_ivar` | `0xa78` | `0xa30` | **`-0x48`** |
| `__DATA.__bss` | `0xb05c` | `0xb024` | **`-0x38`** |
| `__DATA_CONST.__objc_superrefs` | `0x308` | `0x2d0` | **`-0x38`** |
| `__TEXT.__oslogstring` | `0x9d83` | `0x9d54` | **`-0x2f`** |
| `__TEXT.__objc_stubs` | `0x4f20` | `0x4f00` | **`-0x20`** |
| `__TEXT.__cstring` | `0x4e09` | `0x4df6` | **`-0x13`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-2081.0.0.0.1
+2083.0.0.0.0

-  Functions: 2056
+  Functions: 2000

-  CStrings:  3764
+  CStrings:  3744
CStrings:
- "<Notice> %4d %4d %4d %4d %4d"
- "<Notice> 5x6 Grid"
- "TP6D"
- "TT7D"
- "_filteredArcModuleTemperature"
- "_filteredTP3R"
- "_filteredTP3R_2DGrid"
- "_filteredTempArc"
- "maxLI_RR"
- "tm02cd0d89343c2a73d6860abb70b388bd"
- "tm0624042662bdd34b4bbbfc0f7da95deb"
- "tm11ac97aa803917d90e120a9af82ff31b"
- "tm1999e121298b648399d013196e64b976"
- "tm2c2215485370d730a0de95e9234264e9"
- "tm5cd9ac578b7f2f459a93162f6787f535"
- "tm71ea1d52d4b62b0d91147eed52e11fbb"
- "tm94e2445bba4a565b83e88425e97b1ef1"
- "tma6b2eecc4252564f599b9a979e4e0602"
- "tmbb7eeddea74c8fcfad763f3ffbf59d08"
- "tmd86fe6187ee41b8649354ac4ec3a992b"
```
