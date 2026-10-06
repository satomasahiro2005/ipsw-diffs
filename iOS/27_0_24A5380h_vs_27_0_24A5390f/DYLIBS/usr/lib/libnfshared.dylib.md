## libnfshared.dylib

> `/usr/lib/libnfshared.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24ab4` | `0x24da8` | **`+0x2f4`** |
| `__AUTH_CONST.__cfstring` | `0x4740` | `0x4780` | **`+0x40`** |
| `__TEXT.__cstring` | `0x4cb7` | `0x4ceb` | **`+0x34`** |
| `__TEXT.__objc_methlist` | `0x234c` | `0x2364` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x13f0` | `0x1400` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1c8` | `0x1d0` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x658` | `0x660` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6f8` | `0x700` | **`+0x8`** |

### Other Changes

```diff

-370.38.2.0.0
+370.40.2.0.0

-  Functions: 751
-  Symbols:   403
-  CStrings:  943
+  Functions: 753
+  Symbols:   404
+  CStrings:  945
Symbols:
+ ___NSDictionary0__struct
CStrings:
+ "+[NFHashes validateNFCCHashes:reference:expectedVersion:hashResults:]"
+ "nfcDeviceModeStateChangeCount"
+ "validHash"
- "+[NFHashes validateNFCCHashes:reference:expectedVersion:]"
```
