## Intents

> `/System/Library/Frameworks/Intents.framework/Intents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x15ae0` | `0x17430` | **`+0x1950`** |
| `__DATA_DIRTY.__objc_data` | `0x4100` | `0x27b0` | **`-0x1950`** |
| `__TEXT.__text` | `0x45fbf8` | `0x45fddc` | **`+0x1e4`** |
| `__TEXT.__oslogstring` | `0x600d` | `0x606c` | **`+0x5f`** |
| `__TEXT.__unwind_info` | `0x11a40` | `0x11a88` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x2164` | `0x2190` | **`+0x2c`** |
| `__AUTH_CONST.__auth_got` | `0x838` | `0x858` | **`+0x20`** |
| `__AUTH_CONST.__cfstring` | `0x429a0` | `0x42980` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x28a8` | `0x28c8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x479cd` | `0x479e1` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x154a8` | `0x154b8` | **`+0x10`** |

### Other Changes

```diff

-4016.0.42.4.0
+4016.0.43.5.0

-  Functions: 30704
-  Symbols:   51835
-  CStrings:  9685
+  Functions: 30705
+  Symbols:   51839
+  CStrings:  9687
Symbols:
+ GCC_except_table10139
+ GCC_except_table10149
+ GCC_except_table10151
+ GCC_except_table10156
+ GCC_except_table10221
+ GCC_except_table10227
+ GCC_except_table10780
+ GCC_except_table10905
+ GCC_except_table10909
+ GCC_except_table11022
+ GCC_except_table11135
+ GCC_except_table11163
+ GCC_except_table11385
+ GCC_except_table11827
+ GCC_except_table12117
+ GCC_except_table1219
+ GCC_except_table12560
+ GCC_except_table12567
+ GCC_except_table12570
+ GCC_except_table12578
+ GCC_except_table12599
+ GCC_except_table1269
+ GCC_except_table13204
+ GCC_except_table1325
+ GCC_except_table1344
+ GCC_except_table1354
+ GCC_except_table13738
+ GCC_except_table13777
+ GCC_except_table13781
+ GCC_except_table14026
+ GCC_except_table14553
+ GCC_except_table15233
+ GCC_except_table15237
+ GCC_except_table1620
+ GCC_except_table16377
+ GCC_except_table16480
+ GCC_except_table16489
+ GCC_except_table16791
+ GCC_except_table18437
+ GCC_except_table19092
+ GCC_except_table19262
+ GCC_except_table19289
+ GCC_except_table19854
+ GCC_except_table19856
+ GCC_except_table19859
+ GCC_except_table19937
+ GCC_except_table20937
+ GCC_except_table21032
+ GCC_except_table21254
+ GCC_except_table22322
+ GCC_except_table22325
+ GCC_except_table22328
+ GCC_except_table22943
+ GCC_except_table22960
+ GCC_except_table23676
+ GCC_except_table2511
+ GCC_except_table25150
+ GCC_except_table25162
+ GCC_except_table2545
+ GCC_except_table27033
+ GCC_except_table27039
+ GCC_except_table2806
+ GCC_except_table28731
+ GCC_except_table28733
+ GCC_except_table28735
+ GCC_except_table28743
+ GCC_except_table28745
+ GCC_except_table28754
+ GCC_except_table2888
+ GCC_except_table2924
+ GCC_except_table2956
+ GCC_except_table29802
+ GCC_except_table29811
+ GCC_except_table29818
+ GCC_except_table29820
+ GCC_except_table29824
+ GCC_except_table29829
+ GCC_except_table29831
+ GCC_except_table30020
+ GCC_except_table3176
+ GCC_except_table3179
+ GCC_except_table3187
+ GCC_except_table3200
+ GCC_except_table4081
+ GCC_except_table4083
+ GCC_except_table4180
+ GCC_except_table4184
+ GCC_except_table4191
+ GCC_except_table4193
+ GCC_except_table4206
+ GCC_except_table4419
+ GCC_except_table5394
+ GCC_except_table5451
+ GCC_except_table5611
+ GCC_except_table5614
+ GCC_except_table5618
+ GCC_except_table5620
+ GCC_except_table5857
+ GCC_except_table5866
+ GCC_except_table6414
+ GCC_except_table6416
+ GCC_except_table6451
+ GCC_except_table6485
+ GCC_except_table7046
+ GCC_except_table7132
+ GCC_except_table7853
+ GCC_except_table8119
+ GCC_except_table8464
+ GCC_except_table8468
+ GCC_except_table8716
+ GCC_except_table8718
+ GCC_except_table9395
+ GCC_except_table9951
+ ___strlcpy_chk
+ _close
+ _fpathconf
+ _open
- GCC_except_table10138
- GCC_except_table10148
- GCC_except_table10150
- GCC_except_table10155
- GCC_except_table10220
- GCC_except_table10226
- GCC_except_table10779
- GCC_except_table10904
- GCC_except_table10908
- GCC_except_table11021
- GCC_except_table11134
- GCC_except_table11161
- GCC_except_table11384
- GCC_except_table11826
- GCC_except_table12116
- GCC_except_table1218
- GCC_except_table12559
- GCC_except_table12566
- GCC_except_table12569
- GCC_except_table12577
- GCC_except_table12598
- GCC_except_table1268
- GCC_except_table13203
- GCC_except_table1324
- GCC_except_table1343
- GCC_except_table1353
- GCC_except_table13737
- GCC_except_table13776
- GCC_except_table13780
- GCC_except_table14025
- GCC_except_table14552
- GCC_except_table15232
- GCC_except_table15236
- GCC_except_table1619
- GCC_except_table16376
- GCC_except_table16479
- GCC_except_table16487
- GCC_except_table16790
- GCC_except_table18436
- GCC_except_table19091
- GCC_except_table19261
- GCC_except_table19288
- GCC_except_table19853
- GCC_except_table19855
- GCC_except_table19858
- GCC_except_table19936
- GCC_except_table20936
- GCC_except_table21031
- GCC_except_table21253
- GCC_except_table22321
- GCC_except_table22324
- GCC_except_table22327
- GCC_except_table22942
- GCC_except_table22959
- GCC_except_table23675
- GCC_except_table2510
- GCC_except_table25149
- GCC_except_table25161
- GCC_except_table2544
- GCC_except_table27032
- GCC_except_table27035
- GCC_except_table2804
- GCC_except_table28730
- GCC_except_table28732
- GCC_except_table28734
- GCC_except_table28742
- GCC_except_table28744
- GCC_except_table28753
- GCC_except_table2887
- GCC_except_table2923
- GCC_except_table2955
- GCC_except_table29801
- GCC_except_table29809
- GCC_except_table29814
- GCC_except_table29819
- GCC_except_table29823
- GCC_except_table29825
- GCC_except_table29830
- GCC_except_table30019
- GCC_except_table3175
- GCC_except_table3178
- GCC_except_table3186
- GCC_except_table3199
- GCC_except_table4080
- GCC_except_table4082
- GCC_except_table4179
- GCC_except_table4183
- GCC_except_table4190
- GCC_except_table4192
- GCC_except_table4205
- GCC_except_table4418
- GCC_except_table5392
- GCC_except_table5450
- GCC_except_table5610
- GCC_except_table5613
- GCC_except_table5617
- GCC_except_table5619
- GCC_except_table5856
- GCC_except_table5865
- GCC_except_table6413
- GCC_except_table6415
- GCC_except_table6447
- GCC_except_table6484
- GCC_except_table7045
- GCC_except_table7130
- GCC_except_table7852
- GCC_except_table8118
- GCC_except_table8463
- GCC_except_table8467
- GCC_except_table8715
- GCC_except_table8717
- GCC_except_table9394
- GCC_except_table9950
CStrings:
+ "%s Security scope path check failed: F_GETPATH failed for %{public}s: %{public}s"
+ "%s Security scope path check failed: realpath and open both failed for %{public}s: %{public}s"
+ "AppExclusions"
+ "IntelligenceFlow"
- "%s Security scope path check failed: realpath failed for %{public}s: %{public}s"
- "/.nofollow"
```
