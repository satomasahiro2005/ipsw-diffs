## geod

> `/System/Library/PrivateFrameworks/GeoServices.framework/geod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x604a` | `0x6077` | **`+0x2d`** |
| `__DATA_CONST.__cfstring` | `0x3d20` | `0x3d40` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x9ed3` | `0x9ee3` | **`+0x10`** |
| `__TEXT.__text` | `0x511fc` | `0x511ec` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x13e8` | `0x13e0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-2075.30.6.12.8
+2075.30.6.12.12

-  CStrings:  2906
+  CStrings:  2907
Functions:
~ sub_10000b31c : 368 -> 352
~ sub_10003ad80 -> sub_10003ad70 : 784 -> 768
~ sub_10003b96c -> sub_10003b94c : 180 -> 176
~ sub_10003ba20 -> sub_10003b9fc : 372 -> 212
~ sub_10003bb94 -> sub_10003bad0 : 24 -> 136
~ sub_10004db4c -> sub_10004daf8 : 288 -> 356
CStrings:
+ "eval"
+ "networkEventFileDescriptorForRepresentativeDate:inEvalMode:"
+ "v24@?0@\"_GEOCountryConfigurationInfo\"8@\"NSError\"16"
+ "v28@?0I8@\"_GEOCountryConfigurationInfo\"12@\"NSError\"20"
- "networkEventFileDescriptorForRepresentativeDate:"
- "v24@?0@\"NSString\"8@\"NSError\"16"
- "v28@?0I8@\"NSString\"12@\"NSError\"20"
```
