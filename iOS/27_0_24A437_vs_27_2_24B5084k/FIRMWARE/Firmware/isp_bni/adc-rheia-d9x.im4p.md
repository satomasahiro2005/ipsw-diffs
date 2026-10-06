## adc-rheia-d9x.im4p

> `Firmware/isp_bni/adc-rheia-d9x.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaa8320` | `0xaa872c` | **`+0x40c`** |
| `__TEXT.__cstring` | `0xaab08` | `0xaab6a` | **`+0x62`** |
| `__TEXT.__const` | `0x9cbb00` | `0x9cbb18` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__data_copy`
- `__DATA._rtk_mtab`
- `__DATA._rtk_smp_main`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-  CStrings:  18553
+  CStrings:  18555
Functions:
~ sub_2fd30 : 11204 -> 11208
~ sub_39500 -> sub_39504 : 22036 -> 22040
~ sub_402a68 -> sub_402a70 : 2264 -> 2932
~ sub_4ba4e8 -> sub_4ba78c : 6284 -> 6388
~ sub_8f4d78 -> sub_8f5084 : 6516 -> 6604
~ sub_913cf8 -> sub_91405c : 3500 -> 3524
~ sub_9186c0 -> sub_918a3c : 4372 -> 4376
~ sub_9197d4 -> sub_919b54 : 21900 -> 21916
~ sub_940d60 -> sub_9410f0 : 1532 -> 1652
~ sub_a9785c -> sub_a97c64 : 328 -> 332
~ sub_aa81e8 -> sub_aa85f4 : 312 -> 320
CStrings:
+ "21:38:29"
+ "IC[%zu] frameSkip set to 1 at ic stopping\n"
+ "ch %zu: forced ProcessStopped() after %u SIF errors in IC_STOPPING"
+ "ch%zu wasPaused %d now %f RVsync %f FVsync %f\n"
- "20:39:44"
- "ch %zu FC: %d Full Res Host Meta Data buffer not available"
```
