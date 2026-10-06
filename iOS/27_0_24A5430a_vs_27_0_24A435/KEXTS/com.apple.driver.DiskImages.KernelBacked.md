## com.apple.driver.DiskImages.KernelBacked

> `com.apple.driver.DiskImages.KernelBacked`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x4348` | `0x4484` | **`+0x13c`** |

### Other Changes

```text
Functions:
~ sub_fffffff00a0012a0 -> sub_fffffff00a0977b0 : 72 -> 76
~ sub_fffffff00a0012f0 -> sub_fffffff00a097804 : 52 -> 56
~ sub_fffffff00a001324 -> sub_fffffff00a09783c : 52 -> 56
~ sub_fffffff00a001368 -> sub_fffffff00a097884 : 68 -> 72
~ sub_fffffff00a0013d4 -> sub_fffffff00a0978f4 : 72 -> 76
~ sub_fffffff00a00141c -> sub_fffffff00a097940 : 104 -> 108
~ sub_fffffff00a001498 -> sub_fffffff00a0979c0 : 88 -> 92
~ sub_fffffff00a0014f0 -> sub_fffffff00a097a1c : 88 -> 92
~ sub_fffffff00a001548 -> sub_fffffff00a097a78 : 108 -> 112
~ sub_fffffff00a0015bc -> sub_fffffff00a097af0 : 80 -> 84
~ sub_fffffff00a00161c -> sub_fffffff00a097b54 : 72 -> 76
~ sub_fffffff00a00166c -> sub_fffffff00a097ba8 : 52 -> 56
~ sub_fffffff00a0016a0 -> sub_fffffff00a097be0 : 52 -> 56
~ sub_fffffff00a0016e4 -> sub_fffffff00a097c28 : 68 -> 72
~ sub_fffffff00a001750 -> sub_fffffff00a097c98 : 72 -> 76
~ sub_fffffff00a001798 -> sub_fffffff00a097ce4 : 104 -> 108
~ sub_fffffff00a001814 -> sub_fffffff00a097d64 : 88 -> 92
~ sub_fffffff00a00186c -> sub_fffffff00a097dc0 : 88 -> 92
~ sub_fffffff00a0018f0 -> sub_fffffff00a097e48 : 128 -> 132
~ sub_fffffff00a001970 -> sub_fffffff00a097ecc : 164 -> 168
~ sub_fffffff00a001a58 -> sub_fffffff00a097fb8 : 196 -> 200
~ sub_fffffff00a001b1c -> sub_fffffff00a098080 : 180 -> 184
~ sub_fffffff00a001ca8 -> sub_fffffff00a098210 : 144 -> 148
~ sub_fffffff00a001d38 -> sub_fffffff00a0982a4 : 100 -> 104
~ sub_fffffff00a001d9c -> sub_fffffff00a09830c : 104 -> 108
~ sub_fffffff00a001e04 -> sub_fffffff00a098378 : 44 -> 48
~ sub_fffffff00a001e50 -> sub_fffffff00a0983c8 : 304 -> 308
~ __ZN21IOHDIXHDDriveInKernel14kernelIOThreadEPv : 228 -> 232
~ sub_fffffff00a002064 -> sub_fffffff00a0985e4 : 160 -> 164
~ sub_fffffff00a002104 -> sub_fffffff00a098688 : 108 -> 112
~ __ZN21IOHDIXHDDriveInKernel14processCommandER13IOHDIXCommandR12BounceBuffer : 1252 -> 1256
~ __ZN21IOHDIXHDDriveInKernel19processPropertyListEv : 1360 -> 1364
~ sub_fffffff00a002bac -> sub_fffffff00a09913c : 80 -> 84
~ sub_fffffff00a002c0c -> sub_fffffff00a0991a0 : 72 -> 76
~ sub_fffffff00a002c5c -> sub_fffffff00a0991f4 : 52 -> 56
~ sub_fffffff00a002ca8 -> sub_fffffff00a099244 : 72 -> 76
~ sub_fffffff00a002d48 -> sub_fffffff00a0992e8 : 124 -> 128
~ sub_fffffff00a002dc4 -> sub_fffffff00a099368 : 176 -> 180
~ sub_fffffff00a002e74 -> sub_fffffff00a09941c : 120 -> 124
~ sub_fffffff00a002eec -> sub_fffffff00a099498 : 204 -> 208
~ sub_fffffff00a002fb8 -> sub_fffffff00a099568 : 136 -> 140
~ sub_fffffff00a003040 -> sub_fffffff00a0995f4 : 136 -> 140
~ sub_fffffff00a003230 -> sub_fffffff00a0997e8 : 80 -> 84
~ sub_fffffff00a003290 -> sub_fffffff00a09984c : 72 -> 76
~ sub_fffffff00a0032e0 -> sub_fffffff00a0998a0 : 52 -> 56
~ sub_fffffff00a00332c -> sub_fffffff00a0998f0 : 72 -> 76
~ sub_fffffff00a0033d0 -> sub_fffffff00a099998 : 100 -> 104
~ sub_fffffff00a003464 -> sub_fffffff00a099a30 : 336 -> 340
~ __ZN15KDIBackingStore9readBytesExmPmPvb : 40 -> 44
~ __ZN15KDIBackingStore10writeBytesExmPmPKvb : 40 -> 44
~ sub_fffffff00a003668 -> sub_fffffff00a099c40 : 104 -> 108
~ sub_fffffff00a0036f4 -> sub_fffffff00a099cd0 : 80 -> 84
~ sub_fffffff00a003754 -> sub_fffffff00a099d34 : 72 -> 76
~ sub_fffffff00a0037a4 -> sub_fffffff00a099d88 : 52 -> 56
~ sub_fffffff00a0037f0 -> sub_fffffff00a099dd8 : 72 -> 76
~ sub_fffffff00a003870 -> sub_fffffff00a099e5c : 72 -> 76
~ sub_fffffff00a0039b0 -> sub_fffffff00a099fa0 : 80 -> 84
~ sub_fffffff00a003a10 -> sub_fffffff00a09a004 : 72 -> 76
~ sub_fffffff00a003a60 -> sub_fffffff00a09a058 : 52 -> 56
~ sub_fffffff00a003a94 -> sub_fffffff00a09a090 : 52 -> 56
~ sub_fffffff00a003ad8 -> sub_fffffff00a09a0d8 : 68 -> 72
~ sub_fffffff00a003b44 -> sub_fffffff00a09a148 : 72 -> 76
~ sub_fffffff00a003b8c -> sub_fffffff00a09a194 : 104 -> 108
~ sub_fffffff00a003c08 -> sub_fffffff00a09a214 : 88 -> 92
~ sub_fffffff00a003c60 -> sub_fffffff00a09a270 : 88 -> 92
~ sub_fffffff00a003cdc -> sub_fffffff00a09a2f0 : 96 -> 100
~ sub_fffffff00a003d3c -> sub_fffffff00a09a354 : 112 -> 116
~ sub_fffffff00a003dac -> sub_fffffff00a09a3c8 : 108 -> 112
~ __ZN15KDIDiskImageNub5startEP9IOService : 792 -> 796
~ sub_fffffff00a004414 -> sub_fffffff00a09aa38 : 144 -> 148
~ sub_fffffff00a0044ac -> sub_fffffff00a09aad4 : 80 -> 84
~ sub_fffffff00a00450c -> sub_fffffff00a09ab38 : 72 -> 76
~ sub_fffffff00a00455c -> sub_fffffff00a09ab8c : 52 -> 56
~ sub_fffffff00a0045a8 -> sub_fffffff00a09abdc : 72 -> 76
~ sub_fffffff00a004650 -> sub_fffffff00a09ac88 : 272 -> 276
~ __ZN12KDIDiskImage12_handleStartEP9IOService : 1324 -> 1328
~ sub_fffffff00a004ca8 -> sub_fffffff00a09b2e8 : 148 -> 152
~ sub_fffffff00a004de4 -> sub_fffffff00a09b428 : 136 -> 140
~ sub_fffffff00a004f34 -> sub_fffffff00a09b57c : 80 -> 84
```
