## MobileInstallation

> `/System/Library/PrivateFrameworks/MobileInstallation.framework/MobileInstallation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28c00` | `0x296f0` | **`+0xaf0`** |
| `__AUTH.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x2d0` | `0x320` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xdc0` | `0xe08` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0xce4` | `0xd1c` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x1424` | `0x1454` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x1a20` | `0x1a30` | **`+0x10`** |
| `__DATA.__bss` | `0x60` | `0x70` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xdc0` | `0xdd0` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x20` | `0x10` | **`-0x10`** |

### Other Changes

```diff

-1680.40.8.0.1
+1680.40.14.0.0

-  Functions: 875
-  Symbols:   1418
+  Functions: 889
+  Symbols:   1434
Symbols:
+ -[MIInstallerClient endAppReplacementWithStatus:forApp:completion:]
+ -[MIInstallerClient pushReplacementInfoForApp:replacingApp:withCompletion:]
+ GCC_except_table331
+ GCC_except_table336
+ GCC_except_table339
+ GCC_except_table342
+ GCC_except_table345
+ GCC_except_table348
+ GCC_except_table351
+ GCC_except_table371
+ GCC_except_table378
+ GCC_except_table380
+ GCC_except_table392
+ GCC_except_table394
+ GCC_except_table396
+ GCC_except_table400
+ GCC_except_table417
+ GCC_except_table419
+ GCC_except_table421
+ GCC_except_table423
+ GCC_except_table425
+ GCC_except_table444
+ GCC_except_table446
+ GCC_except_table448
+ GCC_except_table450
+ GCC_except_table455
+ GCC_except_table478
+ GCC_except_table486
+ GCC_except_table490
+ GCC_except_table492
+ GCC_except_table494
+ GCC_except_table499
+ GCC_except_table532
+ GCC_except_table534
+ GCC_except_table536
+ GCC_except_table538
+ GCC_except_table540
+ GCC_except_table542
+ GCC_except_table544
+ _MobileInstallationEndAppReplacement
+ _MobileInstallationPushReplacementInfo
+ ___67-[MIInstallerClient endAppReplacementWithStatus:forApp:completion:]_block_invoke
+ ___67-[MIInstallerClient endAppReplacementWithStatus:forApp:completion:]_block_invoke_2
+ ___67-[MIInstallerClient endAppReplacementWithStatus:forApp:completion:]_block_invoke_3
+ ___67-[MIInstallerClient endAppReplacementWithStatus:forApp:completion:]_block_invoke_4
+ ___75-[MIInstallerClient pushReplacementInfoForApp:replacingApp:withCompletion:]_block_invoke
+ ___75-[MIInstallerClient pushReplacementInfoForApp:replacingApp:withCompletion:]_block_invoke_2
+ ___75-[MIInstallerClient pushReplacementInfoForApp:replacingApp:withCompletion:]_block_invoke_3
+ ___75-[MIInstallerClient pushReplacementInfoForApp:replacingApp:withCompletion:]_block_invoke_4
+ ___MobileInstallationEndAppReplacement_block_invoke
+ ___MobileInstallationPushReplacementInfo_block_invoke
- GCC_except_table316
- GCC_except_table321
- GCC_except_table329
- GCC_except_table332
- GCC_except_table335
- GCC_except_table338
- GCC_except_table341
- GCC_except_table361
- GCC_except_table368
- GCC_except_table370
- GCC_except_table376
- GCC_except_table382
- GCC_except_table384
- GCC_except_table390
- GCC_except_table397
- GCC_except_table401
- GCC_except_table403
- GCC_except_table405
- GCC_except_table409
- GCC_except_table418
- GCC_except_table420
- GCC_except_table422
- GCC_except_table424
- GCC_except_table426
- GCC_except_table445
- GCC_except_table458
- GCC_except_table464
- GCC_except_table466
- GCC_except_table480
- GCC_except_table489
- GCC_except_table500
- GCC_except_table502
- GCC_except_table504
- GCC_except_table506
- GCC_except_table508
```
