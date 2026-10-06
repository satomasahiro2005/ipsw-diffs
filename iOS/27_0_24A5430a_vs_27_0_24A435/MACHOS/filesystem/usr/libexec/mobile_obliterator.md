## mobile_obliterator

> `/usr/libexec/mobile_obliterator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ba48` | `0x1bc18` | **`+0x1d0`** |
| `__TEXT.__cstring` | `0xadf4` | `0xaeae` | **`+0xba`** |
| `__DATA.__bss` | `0x2a48` | `0x2ae0` | **`+0x98`** |
| `__DATA_CONST.__cfstring` | `0x2140` | `0x2180` | **`+0x40`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  1411
+  CStrings:  1417
Functions:
~ sub_100014104 : 828 -> 856
~ sub_100014440 -> sub_10001445c : 472 -> 480
~ sub_1000150c4 -> sub_1000150e8 : 1132 -> 1176
~ sub_100016380 -> sub_1000163d0 : 1936 -> 2320
CStrings:
+ "IODeviceTree:/product/display%d"
+ "ctx[%d]: display \"%s\" (display index %d)\n"
+ "display%d: display-boot-rotation = %u\n"
+ "display%d: display-rotation = %u\n"
+ "display-boot-rotation"
+ "display-rotation"
```
