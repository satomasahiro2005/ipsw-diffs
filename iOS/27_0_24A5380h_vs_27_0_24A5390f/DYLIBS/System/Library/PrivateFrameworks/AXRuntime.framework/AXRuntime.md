## AXRuntime

> `/System/Library/PrivateFrameworks/AXRuntime.framework/AXRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4df30` | `0x4df88` | **`+0x58`** |
| `__AUTH_CONST.__cfstring` | `0x50a0` | `0x50e0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x5d6e` | `0x5d8e` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1260` | `0x1270` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xa98` | `0xaa0` | **`+0x8`** |

### Other Changes

```diff

-3234.5.0.0.0
+3237.1.0.0.0

-  Functions: 1637
-  Symbols:   3236
-  CStrings:  945
+  Functions: 1638
+  Symbols:   3240
+  CStrings:  947
Symbols:
+ GCC_except_table1169
+ GCC_except_table1321
+ GCC_except_table1324
+ GCC_except_table1353
+ GCC_except_table1368
+ GCC_except_table1382
+ GCC_except_table1460
+ GCC_except_table1488
+ GCC_except_table1535
+ GCC_except_table1593
+ GCC_except_table1601
+ GCC_except_table164
+ GCC_except_table167
+ GCC_except_table173
+ GCC_except_table175
+ GCC_except_table177
+ GCC_except_table179
+ GCC_except_table181
+ GCC_except_table183
+ GCC_except_table239
+ GCC_except_table258
+ GCC_except_table262
+ GCC_except_table266
+ GCC_except_table275
+ GCC_except_table344
+ GCC_except_table346
+ GCC_except_table358
+ GCC_except_table446
+ GCC_except_table452
+ GCC_except_table517
+ GCC_except_table538
+ GCC_except_table665
+ GCC_except_table671
+ GCC_except_table758
+ GCC_except_table762
+ GCC_except_table766
+ GCC_except_table779
+ GCC_except_table822
+ GCC_except_table830
+ GCC_except_table836
+ GCC_except_table911
+ GCC_except_table914
+ GCC_except_table918
+ GCC_except_table922
+ GCC_except_table924
+ GCC_except_table948
+ GCC_except_table984
+ _AXIsInternalInstall
+ _AXUIAccessibilitySpeechAttributeSSML
+ __AXRaiseIfCallingAXRuntimeOffMainThread
+ _kAXSimulatePressAtPointActionKeyDisplayID
- GCC_except_table1168
- GCC_except_table1320
- GCC_except_table1323
- GCC_except_table1352
- GCC_except_table1367
- GCC_except_table1381
- GCC_except_table1459
- GCC_except_table1487
- GCC_except_table1534
- GCC_except_table1592
- GCC_except_table1600
- GCC_except_table163
- GCC_except_table166
- GCC_except_table172
- GCC_except_table174
- GCC_except_table176
- GCC_except_table178
- GCC_except_table180
- GCC_except_table182
- GCC_except_table237
- GCC_except_table256
- GCC_except_table261
- GCC_except_table265
- GCC_except_table274
- GCC_except_table343
- GCC_except_table345
- GCC_except_table357
- GCC_except_table445
- GCC_except_table451
- GCC_except_table516
- GCC_except_table537
- GCC_except_table664
- GCC_except_table670
- GCC_except_table757
- GCC_except_table761
- GCC_except_table765
- GCC_except_table775
- GCC_except_table821
- GCC_except_table829
- GCC_except_table835
- GCC_except_table910
- GCC_except_table913
- GCC_except_table917
- GCC_except_table921
- GCC_except_table923
- GCC_except_table947
- GCC_except_table983
Functions:
~ __AXUIElementCopyElementAtPositionWithParams : 4040 -> 4052
+ __AXRaiseIfCallingAXRuntimeOffMainThread
~ __handleNonMainThreadCallback : 376 -> 232
~ __AXAddToElementCache : 272 -> 276
~ -[AXRemoteElement _getRemoteValuesOffMainThread:] : 476 -> 480
~ ___49-[AXRemoteElement _getRemoteValuesOffMainThread:]_block_invoke_2 : 136 -> 132
CStrings:
+ "AXSpeechAttributeSSML"
+ "displayID"
```
