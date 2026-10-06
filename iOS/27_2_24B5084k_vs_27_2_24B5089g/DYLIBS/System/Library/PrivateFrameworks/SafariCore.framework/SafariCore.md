## SafariCore

> `/System/Library/PrivateFrameworks/SafariCore.framework/SafariCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x23a8` | `0x748` | **`-0x1c60`** |
| `__DATA_DIRTY.__objc_data` | `0x2980` | `0x45e0` | **`+0x1c60`** |
| `__DATA_DIRTY.__data` | `0xdc8` | `0x1bb8` | **`+0xdf0`** |
| `__AUTH.__data` | `0x1080` | `0x2c8` | **`-0xdb8`** |
| `__TEXT.__text` | `0x1f46a0` | `0x1f4b08` | **`+0x468`** |
| `__AUTH_CONST.__const` | `0xb328` | `0xb3b8` | **`+0x90`** |
| `__TEXT.__const` | `0x7d24` | `0x7d74` | **`+0x50`** |
| `__TEXT.__cstring` | `0x170e7` | `0x17137` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x26ba` | `0x2706` | **`+0x4c`** |
| `__TEXT.__constg_swiftt` | `0x2340` | `0x2380` | **`+0x40`** |
| `__TEXT.__swift5_builtin` | `0x154` | `0x17c` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1af00` | `0x1af20` | **`+0x20`** |
| `__DATA.__bss` | `0xa730` | `0xa710` | **`-0x20`** |
| `__DATA.__data` | `0x36a0` | `0x3680` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x690` | `0x6b0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xd2ec` | `0xd304` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x9cf0` | `0x9d08` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x1538` | `0x154c` | **`+0x14`** |
| `__AUTH_CONST.__objc_const` | `0x165e0` | `0x165f0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x76d0` | `0x76e0` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x5ad8` | `0x5ae0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x21c` | `0x224` | **`+0x8`** |

### Other Changes

```diff

-625.2.4.1.0
+625.2.5.10.1

-  Functions: 11385
-  Symbols:   12090
-  CStrings:  5283
+  Functions: 11398
+  Symbols:   12097
+  CStrings:  5285
Symbols:
+ +[WBSFeatureAvailability isNotifyMeWhenJitterEnabled]
+ _WBSDebugNotifyMeWhenJitterEnabledKey
+ __OBJC_$_INSTANCE_METHODS_WBSAnalyticsLogger(ForegroundReturnAnalyticsLogger)
+ _symbolic SS_So8NSObjectCt
+ _symbolic _____ So35WBSAnalyticsForegroundReturnOutcomeV
+ _symbolic _____ So43WBSAnalyticsForegroundReturnAwayDurationBinV
+ _symbolic _____ySSSo8NSObjectCG s18_DictionaryStorageC
+ _symbolic _____ySS_So8NSObjectCtG s23_ContiguousArrayStorageC
- __OBJC_$_INSTANCE_METHODS_WBSAnalyticsLogger
CStrings:
+ "WBSDebugNotifyMeWhenJitterEnabled"
+ "com.apple.Safari.Foreground.DidResolveOutcome"
```
