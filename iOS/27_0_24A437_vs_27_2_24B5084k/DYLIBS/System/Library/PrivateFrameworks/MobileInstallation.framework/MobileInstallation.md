## MobileInstallation

> `/System/Library/PrivateFrameworks/MobileInstallation.framework/MobileInstallation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x274dc` | `0x28c00` | **`+0x1724`** |
| `__TEXT.__unwind_info` | `0xd30` | `0xdc0` | **`+0x90`** |
| `__TEXT.__gcc_except_tab` | `0xc74` | `0xce4` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x13c4` | `0x1424` | **`+0x60`** |
| `__TEXT.__cstring` | `0x50d6` | `0x5129` | **`+0x53`** |
| `__AUTH_CONST.__cfstring` | `0x2b00` | `0x2b40` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x1a00` | `0x1a20` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xda0` | `0xdc0` | **`+0x20`** |

### Other Changes

```diff

-1674.2.1.0.0
+1680.40.6.502.1

-  Functions: 845
-  Symbols:   1384
-  CStrings:  523
+  Functions: 875
+  Symbols:   1418
+  CStrings:  525
Symbols:
+ -[MIInstallerClient prepareReplacementOfApp:byApp:extensionBundleIDs:withCompletion:]
+ -[MIInstallerClient removeAppReplacementStateForApp:completion:]
+ -[MIInstallerClient setAppReplacementStatus:forApp:replacingApp:completion:]
+ -[MIInstallerClient setLaunchProhibited:forApp:withCompletion:]
+ GCC_except_table316
+ GCC_except_table326
+ GCC_except_table329
+ GCC_except_table332
+ GCC_except_table335
+ GCC_except_table338
+ GCC_except_table361
+ GCC_except_table368
+ GCC_except_table376
+ GCC_except_table382
+ GCC_except_table384
+ GCC_except_table386
+ GCC_except_table390
+ GCC_except_table397
+ GCC_except_table401
+ GCC_except_table403
+ GCC_except_table405
+ GCC_except_table407
+ GCC_except_table409
+ GCC_except_table411
+ GCC_except_table413
+ GCC_except_table415
+ GCC_except_table424
+ GCC_except_table426
+ GCC_except_table428
+ GCC_except_table430
+ GCC_except_table434
+ GCC_except_table436
+ GCC_except_table440
+ GCC_except_table445
+ GCC_except_table458
+ GCC_except_table466
+ GCC_except_table468
+ GCC_except_table472
+ GCC_except_table474
+ GCC_except_table476
+ GCC_except_table489
+ GCC_except_table504
+ GCC_except_table506
+ GCC_except_table508
+ GCC_except_table510
+ GCC_except_table512
+ GCC_except_table514
+ GCC_except_table516
+ GCC_except_table518
+ GCC_except_table520
+ GCC_except_table522
+ GCC_except_table524
+ GCC_except_table526
+ GCC_except_table528
+ GCC_except_table530
+ _MICopySupersededApplicationIdentifiersEntitlement
+ _MIHasHomeKitEntitlement
+ _MobileInstallationPrepareAppReplacement
+ _MobileInstallationRemoveAppReplacementState
+ _MobileInstallationSetAppLaunchProhibited
+ _MobileInstallationSetAppReplacementStatus
+ ___63-[MIInstallerClient setLaunchProhibited:forApp:withCompletion:]_block_invoke
+ ___63-[MIInstallerClient setLaunchProhibited:forApp:withCompletion:]_block_invoke_2
+ ___63-[MIInstallerClient setLaunchProhibited:forApp:withCompletion:]_block_invoke_3
+ ___63-[MIInstallerClient setLaunchProhibited:forApp:withCompletion:]_block_invoke_4
+ ___64-[MIInstallerClient removeAppReplacementStateForApp:completion:]_block_invoke
+ ___64-[MIInstallerClient removeAppReplacementStateForApp:completion:]_block_invoke_2
+ ___64-[MIInstallerClient removeAppReplacementStateForApp:completion:]_block_invoke_3
+ ___64-[MIInstallerClient removeAppReplacementStateForApp:completion:]_block_invoke_4
+ ___76-[MIInstallerClient setAppReplacementStatus:forApp:replacingApp:completion:]_block_invoke
+ ___76-[MIInstallerClient setAppReplacementStatus:forApp:replacingApp:completion:]_block_invoke_2
+ ___76-[MIInstallerClient setAppReplacementStatus:forApp:replacingApp:completion:]_block_invoke_3
+ ___76-[MIInstallerClient setAppReplacementStatus:forApp:replacingApp:completion:]_block_invoke_4
+ ___85-[MIInstallerClient prepareReplacementOfApp:byApp:extensionBundleIDs:withCompletion:]_block_invoke
+ ___85-[MIInstallerClient prepareReplacementOfApp:byApp:extensionBundleIDs:withCompletion:]_block_invoke_2
+ ___85-[MIInstallerClient prepareReplacementOfApp:byApp:extensionBundleIDs:withCompletion:]_block_invoke_3
+ ___85-[MIInstallerClient prepareReplacementOfApp:byApp:extensionBundleIDs:withCompletion:]_block_invoke_4
+ ___MobileInstallationPrepareAppReplacement_block_invoke
+ ___MobileInstallationRemoveAppReplacementState_block_invoke
+ ___MobileInstallationSetAppLaunchProhibited_block_invoke
+ ___MobileInstallationSetAppReplacementStatus_block_invoke
- GCC_except_table296
- GCC_except_table301
- GCC_except_table306
- GCC_except_table309
- GCC_except_table312
- GCC_except_table315
- GCC_except_table318
- GCC_except_table348
- GCC_except_table350
- GCC_except_table356
- GCC_except_table362
- GCC_except_table364
- GCC_except_table366
- GCC_except_table377
- GCC_except_table381
- GCC_except_table383
- GCC_except_table385
- GCC_except_table387
- GCC_except_table389
- GCC_except_table391
- GCC_except_table393
- GCC_except_table395
- GCC_except_table398
- GCC_except_table400
- GCC_except_table402
- GCC_except_table404
- GCC_except_table406
- GCC_except_table408
- GCC_except_table410
- GCC_except_table412
- GCC_except_table414
- GCC_except_table416
- GCC_except_table425
- GCC_except_table444
- GCC_except_table446
- GCC_except_table448
- GCC_except_table454
- GCC_except_table456
- GCC_except_table460
- GCC_except_table469
- GCC_except_table486
- GCC_except_table488
- GCC_except_table490
- GCC_except_table492
- GCC_except_table494
- GCC_except_table496
- GCC_except_table498
CStrings:
+ "com.apple.developer.homekit"
+ "com.apple.developer.superseded-application-identifiers"
```
