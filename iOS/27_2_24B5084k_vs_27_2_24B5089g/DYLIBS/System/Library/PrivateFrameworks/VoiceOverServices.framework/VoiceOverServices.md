## VoiceOverServices

> `/System/Library/PrivateFrameworks/VoiceOverServices.framework/VoiceOverServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3595c` | `0x35a28` | **`+0xcc`** |
| `__DATA_DIRTY.__bss` | `0x12f0` | `0x1368` | **`+0x78`** |
| `__DATA.__bss` | `0xa10` | `0x9a8` | **`-0x68`** |
| `__AUTH_CONST.__cfstring` | `0x92c0` | `0x9300` | **`+0x40`** |
| `__TEXT.__cstring` | `0x7672` | `0x76a6` | **`+0x34`** |
| `__AUTH_CONST.__const` | `0x3ca0` | `0x3cc0` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x4480` | `0x4490` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x2fb4` | `0x2fc4` | **`+0x10`** |
| `__DATA.__data` | `0xe70` | `0xe78` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2238` | `0x2240` | **`+0x8`** |

### Other Changes

```diff

-3245.7.1.0.0
+3245.8.2.0.0

-  Functions: 1498
-  Symbols:   3371
-  CStrings:  1240
+  Functions: 1500
+  Symbols:   3376
+  CStrings:  1242
Symbols:
+ +[VOSCommand ReadCurrentItem]
+ GCC_except_table1280
+ GCC_except_table1346
+ GCC_except_table1354
+ GCC_except_table1470
+ GCC_except_table1476
+ _ReadCurrentItem._Command
+ _ReadCurrentItem.onceToken
+ ___29+[VOSCommand ReadCurrentItem]_block_invoke
+ _kVOTEventCommandOutputCurrentElement
- GCC_except_table1278
- GCC_except_table1344
- GCC_except_table1352
- GCC_except_table1468
- GCC_except_table1474
CStrings:
+ "ReadCurrentItem"
+ "VOTEventCommandOutputCurrentElement"
```
