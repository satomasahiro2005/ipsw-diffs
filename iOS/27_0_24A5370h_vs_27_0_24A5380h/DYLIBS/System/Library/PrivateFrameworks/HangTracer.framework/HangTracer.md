## HangTracer

> `/System/Library/PrivateFrameworks/HangTracer.framework/HangTracer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16cfc` | `0x174f0` | **`+0x7f4`** |
| `__TEXT.__cstring` | `0x43cf` | `0x4534` | **`+0x165`** |
| `__AUTH_CONST.__cfstring` | `0x5a40` | `0x5b80` | **`+0x140`** |
| `__AUTH.__objc_data` | `0xa0` | `0x140` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x4a0` | `0x540` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0xf0` | `0x50` | **`-0xa0`** |
| `__DATA.__bss` | `0x88` | `0xe0` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x1768` | `0x17b8` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xa20` | `0xa58` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x1a68` | `0x1a98` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x2bc8` | `0x2bf4` | **`+0x2c`** |
| `__AUTH_CONST.__auth_got` | `0x5c8` | `0x5f0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x5a8` | `0x5c8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1d8` | `0x1f0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x9f0` | `0x9fc` | **`+0xc`** |
| `__DATA.__data` | `0x218` | `0x220` | **`+0x8`** |
| `__TEXT.__const` | `0x260` | `0x268` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1f0` | `0x1f4` | **`+0x4`** |

### Other Changes

```diff

-415.0.0.0.0
+421.0.0.0.0

+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

-  Functions: 571
-  Symbols:   1269
-  CStrings:  979
+  Functions: 588
+  Symbols:   1306
+  CStrings:  994
Symbols:
+ -[HTPrefs shouldMonitorCPURoleForAppExtensions]
+ _CC_SHA256_Final
+ _CC_SHA256_Init
+ _CC_SHA256_Update
+ _HTAnalyticsShouldReportBundleID.sDeviceIdentifier
+ _HTAnalyticsShouldReportBundleID.sDeviceIdentifierOnce
+ _HTCPURoleMonitoringDenylist.denylist
+ _HTCPURoleMonitoringDenylist.onceToken
+ _HTReportSignpostStateForBundleID
+ _HTSamplingQueue.once
+ _HTSamplingQueue.q
+ _OBJC_CLASS_$_LSApplicationExtensionRecord
+ _OBJC_CLASS_$_LSApplicationWorkspace
+ _OBJC_CLASS_$_NSSet
+ _OBJC_IVAR_$_HTPrefs._shouldMonitorCPURoleForAppExtensions
+ ___HTAnalyticsShouldReportBundleID_block_invoke
+ ___HTCPURoleMonitoringDenylist_block_invoke
+ ___HTReportSignpostStateForBundleID_block_invoke
+ ___HTReportSignpostStateForBundleID_block_invoke_2
+ ___HTSamplingQueue_block_invoke
+ ___block_descriptor_41_e8_32s_e19_"NSDictionary"8?0ls32l8
+ ___block_descriptor_41_e8_32s_e5_v8?0ls32l8
+ ___tailspinBoostingSignpost_block_invoke
+ ___tailspinProcessingSignpost_block_invoke
+ __block_invoke.sLastReportedState
+ _disableProcess
+ _gettimeofday
+ _kHTCoreAnalyticsHangSignpostsEnabled
+ _kHTDoneProcessingTailspinNotification
+ _kHTExtendedAttributeIsBoosted
+ _kHTExtendedAttributeTailspinPath
+ _kHTPrefsShouldMonitorCPURoleForAppExtensions
+ _kHTServiceMessageNameBoostTask
+ _localtime_r
+ _shouldMonitorCPURoleForProcessBundleID
+ _tailspinBoostingSignpost
+ _tailspinBoostingSignpost.onceToken
+ _tailspinBoostingSignpost.signpostLog
+ _tailspinProcessingSignpost
+ _tailspinProcessingSignpost.onceToken
+ _tailspinProcessingSignpost.signpostLog
- ___block_descriptor_40_e8_32s_e19_"NSDictionary"8?0ls32l8
- ___signpostHangInterval_block_invoke
- ___signpostHangInterval_block_invoke_2
- _signpostHangInterval.onceToken
CStrings:
+ "PosterBoard"
+ "Should sample bundleID:%@ for telemetry: %@"
+ "ShouldMonitorCPURoleForAppExtensions"
+ "WidgetRenderer-Default"
+ "Yes"
+ "boost-task"
+ "com.apple.chrono.WidgetRenderer-Default"
+ "com.apple.hangreporter.doneProcessingTailspin"
+ "com.apple.hangtracer.sampling-helper"
+ "com.apple.posterkit.provider"
+ "enabled"
+ "hangreporter_tailspin_boosting"
+ "hangreporter_tailspin_processing"
+ "hangtracer.isBoosted"
+ "hangtracer.tailspin_path"
```
