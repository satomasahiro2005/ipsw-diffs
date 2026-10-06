## VoiceOverServices

> `/System/Library/PrivateFrameworks/VoiceOverServices.framework/VoiceOverServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x349ac` | `0x34aa0` | **`+0xf4`** |
| `__DATA_DIRTY.__bss` | `0x12b8` | `0x12f0` | **`+0x38`** |
| `__DATA.__bss` | `0x9a0` | `0x978` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0x8f20` | `0x8f40` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x3b40` | `0x3b60` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x43e0` | `0x43f0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x21b8` | `0x21c8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x7397` | `0x73a1` | **`+0xa`** |
| `__TEXT.__objc_methlist` | `0x2f24` | `0x2f2c` | **`+0x8`** |

### Other Changes

```diff

-3232.3.0.0.0
+3234.5.0.0.0

-  Functions: 1475
-  Symbols:   3316
-  CStrings:  1210
+  Functions: 1477
+  Symbols:   3319
+  CStrings:  1211
Symbols:
+ +[VOSCommand StartSiri]
+ GCC_except_table1260
+ GCC_except_table1323
+ GCC_except_table1331
+ GCC_except_table1447
+ GCC_except_table1453
+ _StartSiri._Command
+ _StartSiri.onceToken
+ ___23+[VOSCommand StartSiri]_block_invoke
- GCC_except_table1258
- GCC_except_table1321
- GCC_except_table1329
- GCC_except_table1445
- GCC_except_table1451
- _AXDeviceSupportsAppleIntelligence
CStrings:
+ "StartSiri"
```
