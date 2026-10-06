## SetupKit

> `/System/Library/PrivateFrameworks/SetupKit.framework/SetupKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `—` | `0xcb0` | **`+0xcb0`** |
| `__DATA.__data` | `0xc90` | `—` | **`-0xc90`** |
| `__TEXT.__text` | `0x28f7c` | `0x2901c` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x762e` | `0x7688` | **`+0x5a`** |
| `__AUTH.__data` | `0x20` | `—` | **`-0x20`** |
| `__AUTH_CONST.__const` | `0x7d8` | `0x7f8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xa18` | `0xa20` | **`+0x8`** |

### Other Changes

```diff

-910.21.0.0.0
+910.24.0.0.0

-  Functions: 954
-  Symbols:   1840
-  CStrings:  882
+  Functions: 955
+  Symbols:   1842
+  CStrings:  884
Symbols:
+ GCC_except_table292
+ GCC_except_table296
+ GCC_except_table316
+ GCC_except_table318
+ GCC_except_table324
+ GCC_except_table330
+ GCC_except_table335
+ GCC_except_table348
+ GCC_except_table356
+ GCC_except_table385
+ GCC_except_table408
+ GCC_except_table414
+ GCC_except_table420
+ GCC_except_table458
+ GCC_except_table548
+ GCC_except_table753
+ GCC_except_table760
+ GCC_except_table767
+ GCC_except_table770
+ GCC_except_table804
+ GCC_except_table810
+ GCC_except_table814
+ GCC_except_table877
+ _CNUserInteractionIsRequired
+ ___79-[SKSetupCaptiveNetworkJoinServer _captiveNetworkLoginRequest:responseHandler:]_block_invoke_2
- GCC_except_table291
- GCC_except_table295
- GCC_except_table315
- GCC_except_table317
- GCC_except_table323
- GCC_except_table329
- GCC_except_table334
- GCC_except_table347
- GCC_except_table355
- GCC_except_table384
- GCC_except_table407
- GCC_except_table413
- GCC_except_table419
- GCC_except_table457
- GCC_except_table547
- GCC_except_table752
- GCC_except_table759
- GCC_except_table766
- GCC_except_table769
- GCC_except_table803
- GCC_except_table809
- GCC_except_table813
- GCC_except_table876
Functions:
~ -[SKSetupCaptiveNetworkJoinServer _captiveNetworkLoginRequest:responseHandler:] : 424 -> 580
+ ___79-[SKSetupCaptiveNetworkJoinServer _captiveNetworkLoginRequest:responseHandler:]_block_invoke
CStrings:
+ "### CaptiveNetworkLogin failed: captive UI not required"
+ "CNUserInteractionIsRequired false"
```
