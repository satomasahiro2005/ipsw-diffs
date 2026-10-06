## CFNetwork

> `/System/Library/Frameworks/CFNetwork.framework/CFNetwork`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x16d0` | `0x1630` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x1900` | `0x19a0` | **`+0xa0`** |
| `__TEXT.__text` | `0x25692c` | `0x2569c4` | **`+0x98`** |
| `__AUTH_CONST.__objc_const` | `0x13e70` | `0x13ea0` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xeb60` | `0xeb80` | **`+0x20`** |
| `__TEXT.__cstring` | `0x18933` | `0x18949` | **`+0x16`** |
| `__AUTH_CONST.__auth_got` | `0x2be8` | `0x2bf0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x4d60` | `0x4d68` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x9c8c` | `0x9c94` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xb888` | `0xb890` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1364` | `0x1368` | **`+0x4`** |

### Other Changes

```diff

-3896.200.31.0.0
+3896.200.41.0.0

-  Functions: 12682
-  Symbols:   21450
-  CStrings:  4754
+  Functions: 12683
+  Symbols:   21453
+  CStrings:  4755
Symbols:
+ -[NSURLSessionTaskTransactionMetrics(SPI) _effectiveTrafficClass]
+ GCC_except_table12261
+ GCC_except_table12266
+ GCC_except_table12269
+ GCC_except_table12280
+ GCC_except_table12288
+ GCC_except_table12295
+ GCC_except_table12321
+ GCC_except_table12590
+ GCC_except_table12594
+ _OBJC_IVAR_$___CFN_ConnectionMetrics._effectiveTrafficClass
+ _nw_path_get_effective_traffic_class
- GCC_except_table12259
- GCC_except_table12265
- GCC_except_table12268
- GCC_except_table12277
- GCC_except_table12287
- GCC_except_table12290
- GCC_except_table12320
- GCC_except_table12589
- GCC_except_table12593
CStrings:
+ "effectiveTrafficClass"
```
