## Intents

> `/System/Library/Frameworks/Intents.framework/Intents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x17430` | `0x16a80` | **`-0x9b0`** |
| `__DATA_DIRTY.__objc_data` | `0x27b0` | `0x3160` | **`+0x9b0`** |
| `__TEXT.__text` | `0x45fddc` | `0x4602e0` | **`+0x504`** |
| `__TEXT.__oslogstring` | `0x606c` | `0x617f` | **`+0x113`** |
| `__TEXT.__cstring` | `0x479e1` | `0x47a5d` | **`+0x7c`** |
| `__DATA_CONST.__const` | `0xb800` | `0xb850` | **`+0x50`** |
| `__DATA.__bss` | `0xd78` | `0xd48` | **`-0x30`** |
| `__DATA_DIRTY.__bss` | `0x170` | `0x1a0` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x28c8` | `0x28d0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x154b8` | `0x154c0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x78c54` | `0x78c5c` | **`+0x8`** |

### Other Changes

```diff

-4016.0.43.5.0
+4016.0.45.3.0

-  Functions: 30705
-  Symbols:   51839
-  CStrings:  9687
+  Functions: 30707
+  Symbols:   51843
+  CStrings:  9700
Symbols:
+ +[_INSiriAuthorizationManager _rawSiriAccessAuthorizationStatusForAppID:]
+ GCC_except_table10228
+ GCC_except_table10781
+ GCC_except_table10906
+ GCC_except_table10910
+ GCC_except_table11023
+ GCC_except_table11136
+ GCC_except_table11164
+ GCC_except_table11386
+ GCC_except_table11828
+ GCC_except_table12118
+ GCC_except_table12561
+ GCC_except_table12568
+ GCC_except_table12571
+ GCC_except_table12579
+ GCC_except_table12600
+ GCC_except_table13205
+ GCC_except_table13739
+ GCC_except_table13779
+ GCC_except_table13783
+ GCC_except_table14028
+ GCC_except_table14555
+ GCC_except_table15235
+ GCC_except_table15239
+ GCC_except_table16379
+ GCC_except_table16482
+ GCC_except_table16490
+ GCC_except_table16491
+ GCC_except_table16793
+ GCC_except_table18439
+ GCC_except_table19094
+ GCC_except_table19264
+ GCC_except_table19291
+ GCC_except_table19858
+ GCC_except_table19861
+ GCC_except_table19939
+ GCC_except_table20939
+ GCC_except_table21034
+ GCC_except_table21256
+ GCC_except_table22324
+ GCC_except_table22327
+ GCC_except_table22330
+ GCC_except_table22945
+ GCC_except_table22962
+ GCC_except_table23678
+ GCC_except_table25152
+ GCC_except_table25164
+ GCC_except_table27035
+ GCC_except_table27040
+ GCC_except_table27041
+ GCC_except_table28737
+ GCC_except_table28747
+ GCC_except_table28756
+ GCC_except_table29804
+ GCC_except_table29812
+ GCC_except_table29813
+ GCC_except_table29819
+ GCC_except_table29822
+ GCC_except_table29830
+ GCC_except_table29833
+ GCC_except_table30022
+ _INImageDataHasSupportedImageSignature
+ _INImageDataHasSupportedImageSignature.kHEIFBrands
+ _kTCCServiceSiriAccess
- GCC_except_table10227
- GCC_except_table10780
- GCC_except_table10905
- GCC_except_table10909
- GCC_except_table11022
- GCC_except_table11135
- GCC_except_table11162
- GCC_except_table11385
- GCC_except_table11827
- GCC_except_table12117
- GCC_except_table12560
- GCC_except_table12567
- GCC_except_table12570
- GCC_except_table12578
- GCC_except_table12599
- GCC_except_table13204
- GCC_except_table13738
- GCC_except_table13777
- GCC_except_table13781
- GCC_except_table14026
- GCC_except_table14553
- GCC_except_table15233
- GCC_except_table15237
- GCC_except_table16377
- GCC_except_table16480
- GCC_except_table16488
- GCC_except_table16489
- GCC_except_table16791
- GCC_except_table18437
- GCC_except_table19092
- GCC_except_table19262
- GCC_except_table19289
- GCC_except_table19854
- GCC_except_table19859
- GCC_except_table19937
- GCC_except_table20937
- GCC_except_table21032
- GCC_except_table21254
- GCC_except_table22322
- GCC_except_table22325
- GCC_except_table22328
- GCC_except_table22943
- GCC_except_table22960
- GCC_except_table23676
- GCC_except_table25150
- GCC_except_table25162
- GCC_except_table27033
- GCC_except_table27036
- GCC_except_table27037
- GCC_except_table28731
- GCC_except_table28743
- GCC_except_table28754
- GCC_except_table29802
- GCC_except_table29810
- GCC_except_table29811
- GCC_except_table29815
- GCC_except_table29816
- GCC_except_table29824
- GCC_except_table29827
- GCC_except_table30020
Functions:
~ +[_INSiriAuthorizationManager _rawSiriAuthorizationStatusForAppID:] : 740 -> 712
~ -[_INDataImage initWithCoder:] : 172 -> 328
~ ___68+[_INSiriAuthorizationManager _requestSiriAuthorization:auditToken:]_block_invoke : 316 -> 288
+ +[_INSiriAuthorizationManager _rawSiriAccessAuthorizationStatusForAppID:]
+ _INImageDataHasSupportedImageSignature
~ -[INImageFilePersistence retrieveImageWithIdentifier:completion:] : 1108 -> 1216
CStrings:
+ "%s Dropping decoded _INDataImage payload with unsupported/invalid image signature (length: %tu)"
+ "%s Refusing to load persisted image %@: contents do not match a supported image signature"
+ "%s Siri is not enabled on this device, therefore Siri access cannot be authorized for %@"
+ "+[_INSiriAuthorizationManager _rawSiriAccessAuthorizationStatusForAppID:]"
+ "-[_INDataImage initWithCoder:]"
+ "heic"
+ "heim"
+ "heis"
+ "heix"
+ "hevc"
+ "hevm"
+ "hevs"
+ "hevx"
+ "mif1"
+ "msf1"
- "AppExclusions"
- "IntelligenceFlow"
```
