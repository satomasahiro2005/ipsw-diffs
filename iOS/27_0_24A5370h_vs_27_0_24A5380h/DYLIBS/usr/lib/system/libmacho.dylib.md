## libmacho.dylib

> `/usr/lib/system/libmacho.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2968` | `0x28ec` | **`-0x7c`** |
| `__TEXT.__unwind_info` | `0xc0` | `0xb8` | **`-0x8`** |

### Other Changes

```diff

-27056.0.0.0.0
+27059.3.0.0.0
Functions:
~ _getsectbynamefromheader_64 : 236 -> 216
~ _getsectiondata : 496 -> 512
~ _NXGetArchInfoFromCpuType : 360 -> 344
~ _NXGetArchInfoFromName : 92 -> 76
~ _NXFreeArchInfo : 108 -> 96
~ _getsectbynamefromheader : 236 -> 216
~ _getsectbynamefromheaderwithswap : 328 -> 300
~ _getsectbynamefromheaderwithswap_64 : 328 -> 300
```
