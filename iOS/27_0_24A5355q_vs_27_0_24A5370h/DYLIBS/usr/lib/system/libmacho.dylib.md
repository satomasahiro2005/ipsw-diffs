## libmacho.dylib

> `/usr/lib/system/libmacho.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2860` | `0x2968` | **`+0x108`** |

### Other Changes

```diff

-27050.4.0.0.0
+27056.0.0.0.0
Functions:
~ _getsectbynamefromheader_64 : 216 -> 236
~ _getsectiondata : 444 -> 496
~ _NXGetArchInfoFromCpuType : 344 -> 360
~ _NXGetArchInfoFromName : 76 -> 92
~ _NXFreeArchInfo : 96 -> 108
~ _internal_NXFindBestFatArch : 2696 -> 2616
~ _getsectbynamefromheader : 216 -> 236
~ _getsectbynamefromheaderwithswap : 300 -> 328
~ _getsectbynamefromheaderwithswap_64 : 300 -> 328
~ _swap_fat_arch : 48 -> 60
~ _swap_fat_arch_64 : 60 -> 68
~ _swap_section : 52 -> 64
~ _swap_section_64 : 52 -> 64
~ _swap_twolevel_hint : 56 -> 64
~ _swap_build_tool_version : 32 -> 40
~ _swap_nlist : 64 -> 76
~ _swap_nlist_64 : 64 -> 72
~ _swap_ranlib : 32 -> 40
~ _swap_ranlib_64 : 28 -> 36
~ _swap_relocation_info : 168 -> 172
~ _swap_indirect_symbols : 32 -> 40
~ _swap_dylib_reference : 56 -> 64
~ _swap_dylib_module : 64 -> 80
~ _swap_dylib_module_64 : 68 -> 80
~ _swap_dylib_table_of_contents : 32 -> 40
```
