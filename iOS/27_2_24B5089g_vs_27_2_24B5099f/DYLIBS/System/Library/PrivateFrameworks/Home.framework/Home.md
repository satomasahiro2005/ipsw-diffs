## Home

> `/System/Library/PrivateFrameworks/Home.framework/Home`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c8a44` | `0x3c9240` | **`+0x7fc`** |
| `__TEXT.__oslogstring` | `0x1da48` | `0x1db38` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x34f66` | `0x35011` | **`+0xab`** |
| `__AUTH_CONST.__cfstring` | `0x275a0` | `0x27620` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x2cb7c` | `0x2cbe4` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x13130` | `0x13170` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x7458` | `0x7490` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x4c650` | `0x4c660` | **`+0x10`** |
| `__DATA.__bss` | `0x3bd0` | `0x3be0` | **`+0x10`** |
| `__DATA.__data` | `0x7970` | `0x7980` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x112b0` | `0x112c0` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0xf20` | `0xf30` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xeb70` | `0xeb80` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x1e40` | `0x1e38` | **`-0x8`** |
| `__TEXT.__const` | `0x5970` | `0x5978` | **`+0x8`** |

### Other Changes

```diff

-1265.0.0.1.1
+1269.2.3.0.1

-  Functions: 21297
-  Symbols:   30349
-  CStrings:  8570
+  Functions: 21306
+  Symbols:   30361
+  CStrings:  8577
Symbols:
+ +[HFHomeKitDispatcher isProxPairingLaunch]
+ +[HFHomeKitDispatcher setIsProxPairingLaunch:]
+ +[HFSetupPairingControllerUtilities factoryResetRequiredDescriptionForCategory:]
+ +[HFSetupPairingControllerUtilities factoryResetRequiredTitleForCategory:]
+ -[HFHomeKitDispatcher _allowsLocationSensing]
+ -[HFSetupAccessoryResult _allZerosSetupCodeError]
+ -[HFSoftwareUpdateManager isSoftwareUpdateOnAssetServer:]
+ -[HMAccessory(HFSoftwareUpdateAdditions) hf_isSoftwareUpdateOnAssetServer]
+ GCC_except_table171
+ GCC_except_table201
+ GCC_except_table202
+ GCC_except_table205
+ GCC_except_table39
+ GCC_except_table45
+ GCC_except_table59
+ GCC_except_table77
+ GCC_except_table79
+ _HFPreferencesCameraClipsDebugMenuKey
+ ___isProxPairingLaunch
- GCC_except_table168
- GCC_except_table199
- GCC_except_table200
- GCC_except_table203
- GCC_except_table57
- GCC_except_table70
- GCC_except_table78
CStrings:
+ "HFSetupPairingControllerStatusDescriptionFailureFactoryResetRequired"
+ "HFSetupPairingControllerStatusTitleFailureFactoryResetRequired"
+ "No software update to check: %@"
+ "OnAssetServer"
+ "Update State: %@; On Asset Server: %{BOOL}d; %@"
+ "_allowsLocationSensing -> %{bool}d (hostProcess: %ld, isAllowedProcess: %{bool}d, isProxPairingLaunchInHomeUIService: %{bool}d, isRunningOnAccessory: %{bool}d)"
+ "cameraClipsShowDebugMenu"
```
