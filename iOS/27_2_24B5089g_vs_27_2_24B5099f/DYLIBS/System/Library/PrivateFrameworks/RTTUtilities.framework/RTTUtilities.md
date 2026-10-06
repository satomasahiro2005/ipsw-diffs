## RTTUtilities

> `/System/Library/PrivateFrameworks/RTTUtilities.framework/RTTUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29df8` | `0x2a000` | **`+0x208`** |
| `__TEXT.__oslogstring` | `0x38ec` | `0x3994` | **`+0xa8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1a58` | `0x1a68` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1ec8` | `0x1ed8` | **`+0x10`** |
| `__DATA.__bss` | `0xf0` | `0xf8` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0xe0` | `0xd8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xb48` | `0xb50` | **`+0x8`** |

### Other Changes

```diff

-543.2.1.0.0
+543.2.3.0.0

-  Functions: 843
-  Symbols:   1608
-  CStrings:  615
+  Functions: 845
+  Symbols:   1610
+  CStrings:  617
Symbols:
+ -[RTTTelephonyUtilities simIsPresentForContext:]
+ GCC_except_table152
+ GCC_except_table157
+ GCC_except_table163
+ GCC_except_table167
+ GCC_except_table187
+ GCC_except_table191
+ GCC_except_table195
+ GCC_except_table207
+ GCC_except_table208
+ GCC_except_table249
+ GCC_except_table284
+ GCC_except_table290
+ GCC_except_table312
+ GCC_except_table317
+ GCC_except_table361
+ GCC_except_table364
+ GCC_except_table373
+ GCC_except_table387
+ GCC_except_table394
+ GCC_except_table402
+ GCC_except_table430
+ GCC_except_table440
+ GCC_except_table456
+ GCC_except_table461
+ GCC_except_table481
+ GCC_except_table486
+ GCC_except_table491
+ GCC_except_table495
+ GCC_except_table500
+ GCC_except_table507
+ GCC_except_table514
+ GCC_except_table555
+ GCC_except_table662
+ GCC_except_table683
+ GCC_except_table699
+ GCC_except_table704
+ GCC_except_table748
+ GCC_except_table751
+ ___48-[RTTTelephonyUtilities simIsPresentForContext:]_block_invoke
- GCC_except_table150
- GCC_except_table155
- GCC_except_table159
- GCC_except_table165
- GCC_except_table183
- GCC_except_table189
- GCC_except_table193
- GCC_except_table205
- GCC_except_table206
- GCC_except_table245
- GCC_except_table282
- GCC_except_table288
- GCC_except_table310
- GCC_except_table315
- GCC_except_table359
- GCC_except_table362
- GCC_except_table371
- GCC_except_table385
- GCC_except_table392
- GCC_except_table400
- GCC_except_table428
- GCC_except_table438
- GCC_except_table454
- GCC_except_table459
- GCC_except_table479
- GCC_except_table484
- GCC_except_table489
- GCC_except_table493
- GCC_except_table498
- GCC_except_table503
- GCC_except_table508
- GCC_except_table553
- GCC_except_table660
- GCC_except_table681
- GCC_except_table697
- GCC_except_table702
- GCC_except_table746
- GCC_except_table749
CStrings:
+ "Error getting subscription info to check SIM presence, assuming present: %@"
+ "No SIM present for this slot, treating RTT as supported so the prompt is not suppressed: %@"
```
