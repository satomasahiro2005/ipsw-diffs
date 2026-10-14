## NearbyInteraction

> `/System/Library/Frameworks/NearbyInteraction.framework/NearbyInteraction`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x371f0` | `0x37744` | **`+0x554`** |
| `__TEXT.__gcc_except_tab` | `0x5a54` | `0x5af0` | **`+0x9c`** |
| `__TEXT.__oslogstring` | `0x142b` | `0x14c3` | **`+0x98`** |
| `__AUTH_CONST.__objc_const` | `0x7ff8` | `0x8070` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x2200` | `0x2260` | **`+0x60`** |
| `__TEXT.__cstring` | `0x51fa` | `0x5259` | **`+0x5f`** |
| `__TEXT.__objc_methlist` | `0x44c0` | `0x4518` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x2050` | `0x2088` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x5b20` | `0x5b40` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xd40` | `0xd58` | **`+0x18`** |

### Other Changes

```diff

-575.0.8.0.0
+575.0.10.0.0

-  Functions: 1588
-  Symbols:   3003
-  CStrings:  948
+  Functions: 1593
+  Symbols:   3015
+  CStrings:  953
Symbols:
+ +[NIPlatformInfo supportsDeviceCVPerception]
+ -[NISession didUpdateDeviceAssociationStatus:]
+ -[NISession object:didUpdateCVDistance:]
+ -[NISession object:didUpdateCVRegion:previousRegion:]
+ GCC_except_table155
+ GCC_except_table156
+ GCC_except_table157
+ GCC_except_table158
+ GCC_except_table159
+ GCC_except_table160
+ GCC_except_table175
+ GCC_except_table183
+ GCC_except_table198
+ GCC_except_table211
+ GCC_except_table212
+ GCC_except_table214
+ GCC_except_table216
+ GCC_except_table219
+ GCC_except_table221
+ GCC_except_table236
+ GCC_except_table237
+ GCC_except_table238
+ GCC_except_table239
+ GCC_except_table240
+ GCC_except_table252
+ GCC_except_table253
+ GCC_except_table256
+ GCC_except_table269
+ GCC_except_table272
+ GCC_except_table285
+ GCC_except_table289
+ GCC_except_table292
+ GCC_except_table293
+ GCC_except_table302
+ GCC_except_table303
+ GCC_except_table310
+ GCC_except_table317
+ GCC_except_table319
+ GCC_except_table324
+ GCC_except_table329
+ GCC_except_table338
+ GCC_except_table348
+ GCC_except_table351
+ GCC_except_table352
+ GCC_except_table362
+ GCC_except_table367
+ GCC_except_table370
+ GCC_except_table374
+ GCC_except_table375
+ GCC_except_table377
+ GCC_except_table378
+ GCC_except_table382
+ GCC_except_table386
+ GCC_except_table92
+ ___40-[NISession object:didUpdateCVDistance:]_block_invoke
+ ___46-[NISession didUpdateDeviceAssociationStatus:]_block_invoke
+ ___53-[NISession object:didUpdateCVRegion:previousRegion:]_block_invoke
- GCC_except_table169
- GCC_except_table171
- GCC_except_table172
- GCC_except_table173
- GCC_except_table174
- GCC_except_table176
- GCC_except_table181
- GCC_except_table195
- GCC_except_table210
- GCC_except_table228
- GCC_except_table230
- GCC_except_table231
- GCC_except_table232
- GCC_except_table233
- GCC_except_table241
- GCC_except_table242
- GCC_except_table243
- GCC_except_table244
- GCC_except_table245
- GCC_except_table246
- GCC_except_table258
- GCC_except_table265
- GCC_except_table268
- GCC_except_table287
- GCC_except_table296
- GCC_except_table297
- GCC_except_table301
- GCC_except_table304
- GCC_except_table308
- GCC_except_table311
- GCC_except_table316
- GCC_except_table323
- GCC_except_table325
- GCC_except_table327
- GCC_except_table336
- GCC_except_table350
- GCC_except_table354
- GCC_except_table363
- GCC_except_table364
- GCC_except_table365
- GCC_except_table368
- GCC_except_table376
- GCC_except_table380
- GCC_except_table97
- GCC_except_table98
CStrings:
+ "DelegateProxy: updated cv distance: %.3f. Object: %{private}@"
+ "DelegateProxy: updated cv region %{private}@ (previous: %{private}@). Object: %{private}@"
+ "HomeKit Accessory Control Devices"
+ "HomeKit Accessory Control Devices | Known Devices"
+ "Perception"
```
