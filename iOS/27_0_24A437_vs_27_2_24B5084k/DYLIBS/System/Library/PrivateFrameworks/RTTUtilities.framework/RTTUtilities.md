## RTTUtilities

> `/System/Library/PrivateFrameworks/RTTUtilities.framework/RTTUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29cd8` | `0x29df8` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x38b1` | `0x38ec` | **`+0x3b`** |
| `__AUTH_CONST.__auth_got` | `0x5b8` | `0x5c0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1a50` | `0x1a58` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xb40` | `0xb48` | **`+0x8`** |

### Other Changes

```diff

-539.1.1.0.0
+543.2.0.0.0

-  Functions: 842
-  Symbols:   1606
-  CStrings:  614
+  Functions: 843
+  Symbols:   1608
+  CStrings:  615
Symbols:
+ GCC_except_table165
+ GCC_except_table183
+ GCC_except_table185
+ GCC_except_table189
+ GCC_except_table193
+ GCC_except_table206
+ GCC_except_table245
+ GCC_except_table247
+ GCC_except_table282
+ GCC_except_table288
+ GCC_except_table310
+ GCC_except_table315
+ GCC_except_table359
+ GCC_except_table362
+ GCC_except_table371
+ GCC_except_table385
+ GCC_except_table392
+ GCC_except_table400
+ GCC_except_table428
+ GCC_except_table438
+ GCC_except_table454
+ GCC_except_table459
+ GCC_except_table479
+ GCC_except_table484
+ GCC_except_table489
+ GCC_except_table493
+ GCC_except_table498
+ GCC_except_table503
+ GCC_except_table505
+ GCC_except_table508
+ GCC_except_table510
+ GCC_except_table512
+ GCC_except_table553
+ GCC_except_table660
+ GCC_except_table681
+ GCC_except_table697
+ GCC_except_table702
+ GCC_except_table746
+ GCC_except_table749
+ _AXIsBuddyCompleted
+ ___53-[RTTTelephonyUtilities context:capabilitiesChanged:]_block_invoke
- GCC_except_table164
- GCC_except_table182
- GCC_except_table184
- GCC_except_table188
- GCC_except_table192
- GCC_except_table204
- GCC_except_table244
- GCC_except_table246
- GCC_except_table281
- GCC_except_table287
- GCC_except_table309
- GCC_except_table314
- GCC_except_table358
- GCC_except_table361
- GCC_except_table370
- GCC_except_table384
- GCC_except_table391
- GCC_except_table399
- GCC_except_table427
- GCC_except_table437
- GCC_except_table453
- GCC_except_table458
- GCC_except_table478
- GCC_except_table483
- GCC_except_table488
- GCC_except_table492
- GCC_except_table497
- GCC_except_table502
- GCC_except_table504
- GCC_except_table507
- GCC_except_table509
- GCC_except_table511
- GCC_except_table552
- GCC_except_table659
- GCC_except_table680
- GCC_except_table696
- GCC_except_table701
- GCC_except_table745
- GCC_except_table748
Functions:
~ -[RTTTelephonyUtilities telephonyClient] : 8 -> 12
~ -[RTTSettings migrateSettings] : 548 -> 628
~ -[RTTTelephonyUtilities init] : 708 -> 712
~ -[RTTTelephonyUtilities dealloc] : 112 -> 128
~ -[RTTTelephonyUtilities context:capabilitiesChanged:] : 4 -> 180
+ ___53-[RTTTelephonyUtilities context:capabilitiesChanged:]_block_invoke
~ -[RTTTelephonyUtilities setTelephonyClient:] : 12 -> 8
CStrings:
+ "RTT LC language migration: deferring until Buddy completes"
```
