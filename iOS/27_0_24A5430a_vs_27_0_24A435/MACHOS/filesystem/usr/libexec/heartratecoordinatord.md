## heartratecoordinatord

> `/usr/libexec/heartratecoordinatord`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27c68` | `0x27d14` | **`+0xac`** |
| `__TEXT.__cstring` | `0x22cd` | `0x231b` | **`+0x4e`** |
| `__TEXT.__gcc_except_tab` | `0x44d8` | `0x44e4` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  1632
+  CStrings:  1638
Functions:
~ sub_10000461c : 1944 -> 1996
~ sub_100004db4 -> sub_100004de8 : 184 -> 220
~ sub_100004e6c -> sub_100004ec4 : 2688 -> 2772
CStrings:
+ "Device1,8240"
+ "Device1,8242"
+ "Device1,8245"
+ "Device1,8246"
+ "Device1,8247"
+ "Device1,8248"
```
