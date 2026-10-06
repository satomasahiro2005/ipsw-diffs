## com.apple.driver.DiskImages.UDIFDiskImage

> `com.apple.driver.DiskImages.UDIFDiskImage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x240` | **`+0x240`** |
| `__TEXT_EXEC.__text` | `0xb4c0` | `0xb494` | **`-0x2c`** |

### Other Changes

```diff

-691.0.0.0.0
+696.0.0.0.0
Functions:
~ sub_fffffff00a00c430 -> sub_fffffff00a08e430 : 588 -> 584
~ sub_fffffff00a00c67c -> sub_fffffff00a08e678 : 844 -> 876
~ sub_fffffff00a00cd90 -> sub_fffffff00a08edac : 384 -> 372
~ sub_fffffff00a00cf7c -> sub_fffffff00a08ef8c : 232 -> 224
~ sub_fffffff00a00d1a0 -> sub_fffffff00a08f1a8 : 200 -> 196
~ __ZN18KDIUDIFCacheObject18displayCacheStatusEv : 200 -> 196
~ __ZN18KDIUDIFCacheObject14commitHariKariEv : 212 -> 204
~ sub_fffffff00a00f2fc -> sub_fffffff00a0912f4 : 1412 -> 1420
~ sub_fffffff00a010650 -> sub_fffffff00a092650 : 2292 -> 2300
~ sub_fffffff00a0110d8 -> sub_fffffff00a0930e0 : 1752 -> 1776
~ sub_fffffff00a0117dc -> sub_fffffff00a0937fc : 2096 -> 2120
~ sub_fffffff00a012038 -> sub_fffffff00a094070 : 1204 -> 1224
~ sub_fffffff00a0124ec -> sub_fffffff00a094538 : 500 -> 488
~ sub_fffffff00a012fe4 -> sub_fffffff00a095024 : 460 -> 480
~ sub_fffffff00a0131b0 -> sub_fffffff00a095204 : 444 -> 432
~ sub_fffffff00a013378 -> sub_fffffff00a0953c0 : 3508 -> 3460
~ sub_fffffff00a01412c -> sub_fffffff00a096144 : 508 -> 520
~ sub_fffffff00a014548 -> sub_fffffff00a09656c : 5472 -> 5432
~ sub_fffffff00a016164 -> sub_fffffff00a098160 : 300 -> 288
~ sub_fffffff00a016448 -> sub_fffffff00a098438 : 756 -> 760
~ sub_fffffff00a01674c -> sub_fffffff00a098740 : 564 -> 532
```
