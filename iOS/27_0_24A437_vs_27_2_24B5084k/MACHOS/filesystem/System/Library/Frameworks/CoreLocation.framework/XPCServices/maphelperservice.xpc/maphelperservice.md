## maphelperservice

> `/System/Library/Frameworks/CoreLocation.framework/XPCServices/maphelperservice.xpc/maphelperservice`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1b11` | `0x1a7b` | **`-0x96`** |
| `__TEXT.__text` | `0x126ac` | `0x126d4` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x13a0` | `0x1380` | **`-0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3185.0.6.0.3
+3186.0.12.0.0

-  CStrings:  398
+  CStrings:  397
Functions:
~ sub_10000b0dc : 1600 -> 1632
~ sub_10000b71c -> sub_10000b73c : 1900 -> 1908
CStrings:
- "CLTSP,CLMM,MaphelperService,findTunnelEndPoint ENTRY,roadID,%llu,clRoadID,%llu,projection,%.3lf,snapCourse,%.1lf,allowNetwork,%d,preferCachedTiles,%d"
```
