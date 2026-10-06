## tursd

> `/usr/libexec/tursd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x1b40` | `0x1ba0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x3af8` | `0x3b38` | **`+0x40`** |
| `__TEXT.__text` | `0x8474` | `0x84a4` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x800` | `0x820` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xd00` | `0xd18` | **`+0x18`** |
| `__DATA.__objc_const` | `0x17b8` | `0x17c8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x240` | `0x248` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x318` | `0x320` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1151.2.0.0.0
+1155.0.0.0.0

-  Symbols:   198
-  CStrings:  755
+  Symbols:   199
+  CStrings:  760
Symbols:
+ _OBJC_CLASS_$_NSLocale
Functions:
~ sub_10000292c : 272 -> 268
~ sub_100002a3c -> sub_100002a38 : 272 -> 268
~ sub_100002f3c -> sub_100002f34 : 264 -> 260
~ sub_100003680 -> sub_100003674 : 272 -> 268
~ sub_100003988 -> sub_100003978 : 272 -> 268
~ sub_100003a98 -> sub_100003a84 : 412 -> 408
~ sub_100003c34 -> sub_100003c1c : 428 -> 424
~ sub_100003f38 -> sub_100003f1c : 608 -> 604
~ sub_100004198 -> sub_100004178 : 392 -> 388
~ sub_100004a00 -> sub_1000049dc : 20 -> 124
~ sub_100005f8c -> sub_100005fd0 : 260 -> 256
~ sub_100006090 -> sub_1000060d0 : 332 -> 328
~ sub_100006500 -> sub_10000653c : 332 -> 328
~ sub_100006fc8 -> sub_100007000 : 828 -> 820
CStrings:
+ "currentLocale"
+ "en"
+ "isEqualToString:"
+ "languageCode"
+ "nph_isAutoDialedSOS"
```
