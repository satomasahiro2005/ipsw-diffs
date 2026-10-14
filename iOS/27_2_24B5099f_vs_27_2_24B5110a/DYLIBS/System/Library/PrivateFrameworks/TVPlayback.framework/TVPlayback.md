## TVPlayback

> `/System/Library/PrivateFrameworks/TVPlayback.framework/TVPlayback`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6adf0` | `0x6b018` | **`+0x228`** |
| `__TEXT.__oslogstring` | `0x725f` | `0x7293` | **`+0x34`** |
| `__TEXT.__cstring` | `0x6bed` | `0x6c12` | **`+0x25`** |
| `__AUTH_CONST.__cfstring` | `0x6da0` | `0x6dc0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x61b0` | `0x61c0` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x24e0` | `0x24e8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3f10` | `0x3f18` | **`+0x8`** |

### Other Changes

```diff

-635.10.14.0.0
+635.10.15.0.0

-  Functions: 2326
-  Symbols:   4278
-  CStrings:  1469
+  Functions: 2327
+  Symbols:   4280
+  CStrings:  1471
Symbols:
+ -[TVPPlayer setArtworkImageData:onPlayerItem:]
+ GCC_except_table396
+ GCC_except_table415
+ GCC_except_table423
+ GCC_except_table426
+ GCC_except_table429
+ GCC_except_table432
+ GCC_except_table435
+ GCC_except_table440
+ GCC_except_table443
+ GCC_except_table447
+ GCC_except_table451
+ GCC_except_table456
+ GCC_except_table461
+ GCC_except_table463
+ GCC_except_table465
+ GCC_except_table490
+ GCC_except_table492
+ GCC_except_table494
+ GCC_except_table497
+ GCC_except_table503
+ GCC_except_table510
+ GCC_except_table512
+ GCC_except_table514
+ GCC_except_table519
+ GCC_except_table523
+ GCC_except_table529
+ GCC_except_table537
+ GCC_except_table540
+ GCC_except_table552
+ GCC_except_table554
+ GCC_except_table557
+ GCC_except_table561
+ _TVPMediaItemMetadataArtworkImageData
- GCC_except_table395
- GCC_except_table414
- GCC_except_table421
- GCC_except_table424
- GCC_except_table427
- GCC_except_table430
- GCC_except_table433
- GCC_except_table439
- GCC_except_table442
- GCC_except_table446
- GCC_except_table450
- GCC_except_table455
- GCC_except_table460
- GCC_except_table462
- GCC_except_table464
- GCC_except_table489
- GCC_except_table491
- GCC_except_table493
- GCC_except_table496
- GCC_except_table502
- GCC_except_table509
- GCC_except_table511
- GCC_except_table513
- GCC_except_table518
- GCC_except_table522
- GCC_except_table528
- GCC_except_table536
- GCC_except_table539
- GCC_except_table551
- GCC_except_table553
- GCC_except_table556
- GCC_except_table560
Functions:
~ ___48-[TVPPlayer _currentMediaItemMetadataDidChange:]_block_invoke : 572 -> 592
+ -[TVPPlayer setArtworkImageData:onPlayerItem:]
CStrings:
+ "TVPMediaItemMetadataArtworkImageData"
+ "Updating player item external metadata with artwork"
```
