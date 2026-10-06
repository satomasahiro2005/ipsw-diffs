## AXRuntime

> `/System/Library/PrivateFrameworks/AXRuntime.framework/AXRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4dd7c` | `0x4dd28` | **`-0x54`** |
| `__DATA.__data` | `0x878` | `0x8b8` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0x90` | `0x50` | **`-0x40`** |
| `__AUTH_CONST.__objc_const` | `0x39d8` | `0x3a08` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x23d0` | `0x23f8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x38dc` | `0x38f4` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xa80` | `0xa90` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2d8` | `0x2e8` | **`+0x10`** |
| `__DATA.__bss` | `0x2f8` | `0x300` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1348` | `0x1350` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x238` | `0x23c` | **`+0x4`** |

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0

-  Functions: 1633
-  Symbols:   3225
+  Functions: 1637
+  Symbols:   3235
Symbols:
+ -[AXSimpleRuntimeManager dedicatedServerThread]
+ -[AXSimpleRuntimeManager setDedicatedServerThread:]
+ GCC_except_table1168
+ GCC_except_table1320
+ GCC_except_table1323
+ GCC_except_table1352
+ GCC_except_table1367
+ GCC_except_table1381
+ GCC_except_table1459
+ GCC_except_table1487
+ GCC_except_table1534
+ GCC_except_table1592
+ GCC_except_table1600
+ GCC_except_table163
+ GCC_except_table166
+ GCC_except_table180
+ GCC_except_table182
+ GCC_except_table237
+ GCC_except_table238
+ GCC_except_table256
+ GCC_except_table265
+ GCC_except_table274
+ GCC_except_table30
+ GCC_except_table343
+ GCC_except_table345
+ GCC_except_table357
+ GCC_except_table39
+ GCC_except_table445
+ GCC_except_table451
+ GCC_except_table516
+ GCC_except_table537
+ GCC_except_table59
+ GCC_except_table664
+ GCC_except_table670
+ GCC_except_table765
+ GCC_except_table775
+ GCC_except_table776
+ GCC_except_table777
+ GCC_except_table778
+ GCC_except_table821
+ GCC_except_table829
+ GCC_except_table835
+ GCC_except_table910
+ GCC_except_table921
+ GCC_except_table923
+ GCC_except_table947
+ GCC_except_table983
+ _NSDefaultRunLoopMode
+ _OBJC_CLASS_$_NSRunLoop
+ _OBJC_IVAR_$_AXSimpleRuntimeManager._dedicatedServerThread
+ __AXSetSystemWideServerUsesDedicatedThread
+ __AXStartSystemWideServerThread
+ _gSystemWideServerUsesDedicatedThread
+ _pthread_create
+ _pthread_set_qos_class_self_np
- GCC_except_table1164
- GCC_except_table1316
- GCC_except_table1319
- GCC_except_table1348
- GCC_except_table1363
- GCC_except_table1377
- GCC_except_table1455
- GCC_except_table1483
- GCC_except_table1530
- GCC_except_table1588
- GCC_except_table159
- GCC_except_table1596
- GCC_except_table162
- GCC_except_table168
- GCC_except_table170
- GCC_except_table233
- GCC_except_table234
- GCC_except_table252
- GCC_except_table253
- GCC_except_table27
- GCC_except_table270
- GCC_except_table339
- GCC_except_table341
- GCC_except_table353
- GCC_except_table36
- GCC_except_table441
- GCC_except_table447
- GCC_except_table512
- GCC_except_table533
- GCC_except_table56
- GCC_except_table660
- GCC_except_table666
- GCC_except_table753
- GCC_except_table771
- GCC_except_table772
- GCC_except_table773
- GCC_except_table774
- GCC_except_table817
- GCC_except_table825
- GCC_except_table831
- GCC_except_table906
- GCC_except_table909
- GCC_except_table919
- GCC_except_table943
- GCC_except_table979
```
