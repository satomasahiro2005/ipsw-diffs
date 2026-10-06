## TipsDaemon

> `/System/Library/PrivateFrameworks/TipsDaemon.framework/TipsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa0878` | `0xa0654` | **`-0x224`** |
| `__TEXT.__oslogstring` | `0x2474` | `0x24c3` | **`+0x4f`** |
| `__AUTH_CONST.__cfstring` | `0x2a40` | `0x2a00` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1238` | `0x1218` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x3898` | `0x38b8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2688` | `0x2698` | **`+0x10`** |
| `__TEXT.__cstring` | `0x428c` | `0x427c` | **`-0x10`** |
| `__DATA.__data` | `0x8b0` | `0x8a8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xd18` | `0xd20` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x1182` | `0x117a` | **`-0x8`** |

### Other Changes

```diff

-866.0.0.0.0
+866.2.2.0.0

-  Functions: 3315
-  Symbols:   3458
+  Functions: 3317
+  Symbols:   3460
Symbols:
+ +[TPSRegulatoryImageManager fetchELabelURLsForAccessoryModel:completion:]
+ -[TPSTipsManager welcomeCollectionOverrideFromContentPackage:]
+ GCC_except_table123
+ GCC_except_table36
+ GCC_except_table46
+ GCC_except_table54
+ GCC_except_table62
+ _TPSCommonDefinesCollectionNameHardware
+ _TPSCommonDefinesCollectionOverrideMajorVersion
- GCC_except_table122
- GCC_except_table33
- GCC_except_table35
- GCC_except_table45
- GCC_except_table53
- GCC_except_table61
- _symbolic _____Sg 18AppIntentsServices0bC0O14InterfaceIdiomO
CStrings:
+ "Welcome collection override not found %@"
+ "Welcome collection override set to %@"
- "27"
- "Hardware"
```
