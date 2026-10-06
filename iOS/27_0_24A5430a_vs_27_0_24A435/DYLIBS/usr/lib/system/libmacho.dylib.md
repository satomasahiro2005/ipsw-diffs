## libmacho.dylib

> `/usr/lib/system/libmacho.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28ec` | `0x2910` | **`+0x24`** |
| `__DATA_CONST.__const` | `0x7a0` | `0x7c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x492` | `0x49c` | **`+0xa`** |
| `__TEXT.__unwind_info` | `0xb8` | `0xc0` | **`+0x8`** |

### Other Changes

```diff

-  CStrings:  122
+  CStrings:  123
Functions:
~ _internal_NXFindBestFatArch : 2616 -> 2652
CStrings:
+ "arm64e.x1"
```
