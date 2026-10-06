## MusicLibrary

> `/System/Library/SyncBundles/MusicLibrary.syncBundle/MusicLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c725c` | `0x1c76cc` | **`+0x470`** |
| `__TEXT.__gcc_except_tab` | `0xdbc` | `0xec8` | **`+0x10c`** |
| `__TEXT.__oslogstring` | `0x472a` | `0x4798` | **`+0x6e`** |
| `__TEXT.__objc_stubs` | `0x4ca0` | `0x4ce0` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x5f71` | `0x5f9d` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0x124c0` | `0x124e0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1880` | `0x1890` | **`+0x10`** |
| `__TEXT.__const` | `0x1e1f4` | `0x1e204` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x618` | `0x620` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x988` | `0x990` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-4026.110.62.2.0
+4026.100.68.0.0

-  Symbols:   387
-  CStrings:  1579
+  Symbols:   388
+  CStrings:  1582
Symbols:
+ _ML3TrackPropertyDateAdded
Functions:
~ sub_1a0560 : 256 -> 248
~ sub_1a0f50 -> sub_1a0f48 : 780 -> 776
~ sub_1a13bc -> sub_1a13b0 : 528 -> 524
~ sub_1a15cc -> sub_1a15bc : 660 -> 656
~ sub_1a1860 -> sub_1a184c : 2468 -> 2464
~ sub_1a2a28 -> sub_1a2a10 : 3400 -> 4052
~ sub_1a3770 -> sub_1a39e4 : 372 -> 588
~ sub_1a418c -> sub_1a44d8 : 748 -> 744
~ sub_1a4960 -> sub_1a4ca8 : 692 -> 688
~ sub_1a4c14 -> sub_1a4f58 : 3176 -> 3188
~ sub_1a587c -> sub_1a5bcc : 308 -> 356
~ sub_1a59b0 -> sub_1a5d30 : 2284 -> 2364
~ sub_1a629c -> sub_1a666c : 588 -> 600
~ sub_1a64e8 -> sub_1a68c4 : 1668 -> 1656
~ sub_1a78e8 -> sub_1a7cb8 : 296 -> 292
~ sub_1a7d1c -> sub_1a80e8 : 848 -> 840
~ sub_1a87e4 -> sub_1a8ba8 : 576 -> 572
~ sub_1a8a24 -> sub_1a8de4 : 1064 -> 1072
~ sub_1a9614 -> sub_1a99dc : 416 -> 412
~ sub_1a97b4 -> sub_1a9b78 : 492 -> 488
~ sub_1a9b90 -> sub_1a9f50 : 660 -> 656
~ sub_1a9e24 -> sub_1aa1e0 : 644 -> 640
~ sub_1aebf0 -> sub_1aefa8 : 2232 -> 2228
~ sub_1af578 -> sub_1af92c : 2100 -> 2116
~ sub_1b0330 -> sub_1b06f4 : 744 -> 760
~ sub_1b06f4 -> sub_1b0ac8 : 752 -> 776
~ sub_1b09e4 -> sub_1b0dd0 : 776 -> 784
~ sub_1b0f74 -> sub_1b1368 : 2952 -> 2956
~ sub_1b3d50 -> sub_1b4148 : 356 -> 352
~ sub_1b68b4 -> sub_1b6ca8 : 508 -> 504
~ sub_1b6b24 -> sub_1b6f14 : 380 -> 376
~ sub_1b84f4 -> sub_1b88e0 : 412 -> 408
~ sub_1b88ac -> sub_1b8c94 : 1100 -> 1096
~ sub_1ba3c0 -> sub_1ba7a4 : 308 -> 304
~ sub_1bb058 -> sub_1bb438 : 136 -> 132
~ sub_1bb768 -> sub_1bbb44 : 3308 -> 3300
~ sub_1bc998 -> sub_1bcd6c : 1212 -> 1200
~ sub_1bce54 -> sub_1bd21c : 288 -> 284
~ sub_1bcf78 -> sub_1bd33c : 2140 -> 2160
~ sub_1bda44 -> sub_1bde1c : 1264 -> 1260
~ sub_1be4a4 -> sub_1be878 : 524 -> 520
~ sub_1bf05c -> sub_1bf42c : 3508 -> 3676
~ sub_1bfe10 -> sub_1c0288 : 280 -> 276
~ sub_1c005c -> sub_1c04d0 : 264 -> 260
CStrings:
+ "<Reconcile Restore> Found %lu tracks to apply constraints to"
+ "<Reconcile Restore> Marking track as needing restore. pid=%lld, '%{public}@'. datePlayed = %{public}@, constrained = %{BOOL}u"
+ "dateWithTimeIntervalSinceReferenceDate:"
+ "now"
- "<Reconcile Restore> Marking track as needing restore. pid=%lld, '%{public}@'"
```
