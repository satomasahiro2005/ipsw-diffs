## PhotoImaging

> `/System/Library/PrivateFrameworks/PhotoImaging.framework/PhotoImaging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27c598` | `0x27cc3c` | **`+0x6a4`** |
| `__TEXT.__cstring` | `0x46e60` | `0x46f77` | **`+0x117`** |
| `__TEXT.__oslogstring` | `0x6c42` | `0x6cef` | **`+0xad`** |
| `__AUTH_CONST.__cfstring` | `0x26da0` | `0x26e40` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x4b34` | `0x4b6c` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x4100` | `0x4128` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xb5b8` | `0xb5d0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x165d0` | `0x165e0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x5888` | `0x5898` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x25b8` | `0x25c0` | **`+0x8`** |

### Other Changes

```diff

-912.0.111.0.0
+912.0.232.0.0

-  Functions: 9134
-  Symbols:   15826
-  CStrings:  7095
+  Functions: 9139
+  Symbols:   15832
+  CStrings:  7103
Symbols:
+ +[PICinematicVideoUtilities loadCinematographyScriptWithVideoURLString:changesDictionary:error:]
+ +[PISegmentationLoader _baseLayout:reusableForConfiguration:]
+ +[PISegmentationLoader ensureLayoutsForAllDisplayContexts:preservesLayout:completion:]
+ GCC_except_table6082
+ GCC_except_table6122
+ GCC_except_table6196
+ GCC_except_table6515
+ GCC_except_table6763
+ GCC_except_table6764
+ GCC_except_table6854
+ GCC_except_table6861
+ GCC_except_table6866
+ GCC_except_table6867
+ GCC_except_table6869
+ GCC_except_table6875
+ GCC_except_table6884
+ GCC_except_table6900
+ GCC_except_table6951
+ GCC_except_table7003
+ GCC_except_table7004
+ GCC_except_table7005
+ GCC_except_table7006
+ GCC_except_table7038
+ GCC_except_table7041
+ GCC_except_table7109
+ GCC_except_table7119
+ GCC_except_table7223
+ GCC_except_table7276
+ GCC_except_table7278
+ GCC_except_table7372
+ GCC_except_table7384
+ GCC_except_table7385
+ GCC_except_table7393
+ GCC_except_table7399
+ GCC_except_table7400
+ GCC_except_table7401
+ GCC_except_table7402
+ GCC_except_table7457
+ GCC_except_table7465
+ GCC_except_table7479
+ GCC_except_table7480
+ GCC_except_table7481
+ GCC_except_table7516
+ GCC_except_table7517
+ GCC_except_table7520
+ GCC_except_table7523
+ GCC_except_table7568
+ GCC_except_table7570
+ GCC_except_table7714
+ GCC_except_table7724
+ GCC_except_table7733
+ GCC_except_table7734
+ GCC_except_table7735
+ GCC_except_table7736
+ GCC_except_table7737
+ GCC_except_table7780
+ GCC_except_table7966
+ GCC_except_table8194
+ GCC_except_table8196
+ GCC_except_table8197
+ GCC_except_table8259
+ GCC_except_table8261
+ GCC_except_table8263
+ GCC_except_table8333
+ GCC_except_table8358
+ GCC_except_table8361
+ GCC_except_table8365
+ GCC_except_table8367
+ GCC_except_table8383
+ GCC_except_table8400
+ GCC_except_table8412
+ GCC_except_table8413
+ GCC_except_table8421
+ GCC_except_table8431
+ GCC_except_table8435
+ GCC_except_table8437
+ GCC_except_table8441
+ GCC_except_table8443
+ GCC_except_table8444
+ GCC_except_table8456
+ _OBJC_CLASS_$_NURenderPipelineRegistry
+ ___86+[PISegmentationLoader ensureLayoutsForAllDisplayContexts:preservesLayout:completion:]_block_invoke
+ ___96+[PICinematicVideoUtilities loadCinematographyScriptWithVideoURLString:changesDictionary:error:]_block_invoke
+ ___block_descriptor_56_e8_32s40r48r_e20_v20?0B8"NSError"12lr40l8r48l8s32l8
- +[PISegmentationLoader ensureLayoutsForAllDisplayContexts:completion:]
- GCC_except_table6118
- GCC_except_table6192
- GCC_except_table6511
- GCC_except_table6759
- GCC_except_table6760
- GCC_except_table6850
- GCC_except_table6853
- GCC_except_table6858
- GCC_except_table6863
- GCC_except_table6865
- GCC_except_table6871
- GCC_except_table6880
- GCC_except_table6896
- GCC_except_table6947
- GCC_except_table6999
- GCC_except_table7000
- GCC_except_table7001
- GCC_except_table7002
- GCC_except_table7033
- GCC_except_table7036
- GCC_except_table7104
- GCC_except_table7114
- GCC_except_table7218
- GCC_except_table7271
- GCC_except_table7273
- GCC_except_table7367
- GCC_except_table7373
- GCC_except_table7376
- GCC_except_table7379
- GCC_except_table7380
- GCC_except_table7387
- GCC_except_table7389
- GCC_except_table7395
- GCC_except_table7452
- GCC_except_table7460
- GCC_except_table7474
- GCC_except_table7475
- GCC_except_table7476
- GCC_except_table7510
- GCC_except_table7511
- GCC_except_table7512
- GCC_except_table7518
- GCC_except_table7563
- GCC_except_table7565
- GCC_except_table7709
- GCC_except_table7719
- GCC_except_table7726
- GCC_except_table7727
- GCC_except_table7728
- GCC_except_table7729
- GCC_except_table7730
- GCC_except_table7775
- GCC_except_table7961
- GCC_except_table8189
- GCC_except_table8191
- GCC_except_table8192
- GCC_except_table8254
- GCC_except_table8256
- GCC_except_table8258
- GCC_except_table8328
- GCC_except_table8351
- GCC_except_table8353
- GCC_except_table8360
- GCC_except_table8362
- GCC_except_table8378
- GCC_except_table8395
- GCC_except_table8403
- GCC_except_table8407
- GCC_except_table8416
- GCC_except_table8426
- GCC_except_table8427
- GCC_except_table8430
- GCC_except_table8436
- GCC_except_table8438
- GCC_except_table8439
- GCC_except_table8451
- ___70+[PISegmentationLoader ensureLayoutsForAllDisplayContexts:completion:]_block_invoke
CStrings:
+ "+[PICinematicVideoUtilities loadCinematographyScriptWithVideoURLString:changesDictionary:error:]"
+ "+[PISegmentationLoader ensureLayoutsForAllDisplayContexts:preservesLayout:completion:]"
+ "Failed to load cinematography script"
+ "Invalid video URL for cinematography script"
+ "Missing %{public}@ layout configuration, skipping layout property recalculation"
+ "Resetting per-display layouts (dynamic config changed: %d, segmentation version changed: %d)"
+ "Timeout waiting for cinematography script to load"
+ "Unexpected videoURL type"
+ "landscape"
- "+[PISegmentationLoader ensureLayoutsForAllDisplayContexts:completion:]"
```
