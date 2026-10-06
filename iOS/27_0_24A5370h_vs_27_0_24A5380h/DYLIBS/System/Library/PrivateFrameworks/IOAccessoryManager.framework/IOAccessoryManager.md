## IOAccessoryManager

> `/System/Library/PrivateFrameworks/IOAccessoryManager.framework/IOAccessoryManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23ce8` | `0x22d9c` | **`-0xf4c`** |
| `__TEXT.__oslogstring` | `0x596b` | `0x560c` | **`-0x35f`** |
| `__TEXT.__cstring` | `0x4a58` | `0x4828` | **`-0x230`** |
| `__AUTH_CONST.__cfstring` | `0x31a0` | `0x3020` | **`-0x180`** |
| `__DATA.__data` | `0x248` | `0x1e8` | **`-0x60`** |
| `__TEXT.__gcc_except_tab` | `0x40` | `—` | **`-0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1ce8` | `0x1cb0` | **`-0x38`** |
| `__DATA_CONST.__const` | `0x460` | `0x440` | **`-0x20`** |
| `__TEXT.__const` | `0x8d8` | `0x8b8` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x300` | `0x2f0` | **`-0x10`** |
| `__DATA_DIRTY.__common` | `0x170` | `0x160` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x3284` | `0x3294` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x588` | `0x578` | **`-0x10`** |
| `__DATA.__common` | `0x58` | `0x50` | **`-0x8`** |

### Other Changes

```diff

-1064.0.0.0.1
+1068.0.0.0.0

-  Functions: 1413
-  Symbols:   2223
-  CStrings:  967
+  Functions: 1407
+  Symbols:   2193
+  CStrings:  916
Symbols:
+ -[IOPortLDCMManagerV4 setForcePortWet:]
- GCC_except_table171
- _OBJC_CLASS_$_ASAssetQuery
- _OBJC_EHTYPE_$_NSException
- _OUTLINED_FUNCTION_62
- _OUTLINED_FUNCTION_63
- __Unwind_Resume
- ___block_descriptor_36_e5_v8?0l
- ___objc_personality_v0
- _gAssetContext
- _gLdcmBehaviorPlist
- _kIOAMLDCMBehaviorDryThresholdDictionarykey
- _kIOAMLDCMBehaviorPlistBehaviorBitmaskKey
- _kIOAMLDCMBehaviorPlistConsecutiveDetectedInterval
- _kIOAMLDCMBehaviorPlistConsecutiveDetectedThresh
- _kIOAMLDCMBehaviorPlistConsecutiveNotDetectedInterval
- _kIOAMLDCMBehaviorPlistConsecutiveNotDetectedThresh
- _kIOAMLDCMBehaviorPlistDeviceGen1SubKey
- _kIOAMLDCMBehaviorPlistFdpBitmaskKey
- _kIOAMLDCMBehaviorPlistLegacySubKey
- _kIOAMLDCMBehaviorPlistVersionKey
- _kIOAMLDCMBehaviorThresholdDefaultKey
- _kIOAMLDCMBehaviorWetThresholdDictionaryKey
- _kMaximumErrorAssetQueryExtraSec
- _kMaximumRegularAssetQueryExtraSec
- _kMinimumErrorAssetQueryIntervalSec
- _kMinimumRegularAssetQueryIntervalSec
- _kSupportedLdcmBehaviorPlistVersion
- _objc_begin_catch
- _objc_end_catch
- _performAssetQuery
- _processLdcmBehaviorPlist
CStrings:
+ "LDCM - Setting ForcePortWet in kernel: %d"
+ "com.apple.accessoryd.plugin"
- "%s\n"
- "%s finished local asset query\n"
- "%s finished remote asset query\n"
- "%s starting local asset query\n"
- "%s starting remote asset query\n"
- "%s: Asset not yet downloaded, fetching: %s"
- "%s: Asset on disk, found at: %s\n"
- "%s: LDCM behavior plist version: %u, supported %d\n"
- "%s: MobileAsset query results: %s\n"
- "%s: Skipping download for uninstalled asset. Error in asset %s: %s\n"
- "%s: commitPersistentConfigDictParams: success=%s"
- "%s: consecutive detected interval : %u\n"
- "%s: consecutive detected thresh : %u\n"
- "%s: consecutive not detected interval : %u\n"
- "%s: consecutive not detected thresh : %u\n"
- "%s: dictionaryWithContentsOfURL failed\n"
- "%s: dictionaryWithContentsOfURL succeeded\n"
- "%s: encountered error: %s\n"
- "%s: exception\n"
- "%s: failed\n"
- "%s: fdpBehaviorMask : %#x\n"
- "%s: getOrDownloadAsset: %s\n"
- "%s: load_dict failed\n"
- "%s: no persistent dictionary"
- "%s: success=%s\n"
- "%s: userBehaviorMask : %#x\n"
- "%s: wet threshold: %f dry threshold: %f\n"
- "BehaviorBitmask"
- "ConsecutiveDetectedInterval"
- "ConsecutiveDetectedThresh"
- "ConsecutiveNotDetectedInterval"
- "ConsecutiveNotDetectedThresh"
- "DeviceGen1"
- "DeviceLegacy"
- "DryThresholds"
- "FalsePreventionBitmask"
- "IOAccessoryHandleAttach_block_invoke"
- "IOAccessoryManagerLdcmBehavior.plist"
- "IOAccessoryServiceMatchingCallback_block_invoke"
- "Version"
- "WetThresholds"
- "commitPersistentConfigDictParams"
- "configDictionary"
- "downloadAssetWithError"
- "false"
- "getAsset"
- "load_dict"
- "performAssetQuery"
- "processLdcmBehaviorPlist"
- "processLdcmBehaviorPlistForVersion1"
- "processLdcmBehaviorPlistForVersion2"
- "retrievePersistentConfigDictParams"
- "true"
```
