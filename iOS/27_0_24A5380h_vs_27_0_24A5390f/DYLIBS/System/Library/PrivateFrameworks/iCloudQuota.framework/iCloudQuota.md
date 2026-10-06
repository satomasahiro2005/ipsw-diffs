## iCloudQuota

> `/System/Library/PrivateFrameworks/iCloudQuota.framework/iCloudQuota`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x75d4c` | `0x77298` | **`+0x154c`** |
| `__TEXT.__oslogstring` | `0x85f9` | `0x8799` | **`+0x1a0`** |
| `__AUTH.__objc_data` | `0x1500` | `0x15b0` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x4f80` | `0x4ff0` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x590c` | `0x597c` | **`+0x70`** |
| `__TEXT.__const` | `0x1138` | `0x1198` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1d10` | `0x1d70` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x1248` | `0x1298` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0xb340` | `0xb388` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0xbe0` | `0xc20` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x6e0` | `0x71c` | **`+0x3c`** |
| `__AUTH.__data` | `0x460` | `0x490` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x64c` | `0x678` | **`+0x2c`** |
| `__AUTH_CONST.__objc_dictobj` | `0x190` | `0x1b8` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x1e20` | `0x1e48` | **`+0x28`** |
| `__DATA.__bss` | `0x1130` | `0x1150` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x710` | `0x730` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3040` | `0x3060` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x318` | `0x32c` | **`+0x14`** |
| `__DATA.__data` | `0x548` | `0x558` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x800` | `0x810` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x310` | `0x320` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x398` | `0x3a0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x48` | `0x4c` | **`+0x4`** |

### Other Changes

```diff

-301.24.0.23.0
+301.24.0.25.0

+  - /System/Library/PrivateFrameworks/ACSEFoundation.framework/ACSEFoundation

+  - /usr/lib/swift/libswiftCoreLocation.dylib

-  Functions: 2907
-  Symbols:   4288
-  CStrings:  1626
+  Functions: 2941
+  Symbols:   4304
+  CStrings:  1634
Symbols:
+ +[ICQDaemonOfferManager logDailyQuotaUsageAnalyticsIgnoringThrottle:]
+ +[ICQDaemonOfferManager logDailyQuotaUsageAnalytics]
+ +[ICQDaemonOfferManager persistedOfferStubs]
+ +[ICQDaemonOfferManager persistedOffer]
+ GCC_except_table112
+ GCC_except_table117
+ GCC_except_table31
+ GCC_except_table32
+ GCC_except_table54
+ GCC_except_table62
+ GCC_except_table72
+ GCC_except_table80
+ GCC_except_table97
+ _OBJC_CLASS_$_QuotaAnalytics
+ _OBJC_METACLASS_$_QuotaAnalytics
+ __CLASS_METHODS_QuotaAnalytics
+ __DATA_QuotaAnalytics
+ __INSTANCE_METHODS_QuotaAnalytics
+ __METACLASS_DATA_QuotaAnalytics
+ __swift_FORCE_LOAD_$_swiftCoreLocation
+ __swift_FORCE_LOAD_$_swiftCoreLocation_$_iCloudQuota
+ _symbolic SDy_____ypG s11AnyHashableV
+ _symbolic Sd10totalQuota_Sd11usedStoraget
+ _symbolic _____ 11iCloudQuota0B9AnalyticsC
+ _symbolic _____XMT 11iCloudQuota0B9AnalyticsC
- GCC_except_table108
- GCC_except_table113
- GCC_except_table27
- GCC_except_table28
- GCC_except_table50
- GCC_except_table58
- GCC_except_table68
- GCC_except_table76
- GCC_except_table93
CStrings:
+ "Cached offer has no quota info dictionary; skipping logging daily quota usage event."
+ "Daily quota usage event already logged today; skipping."
+ "Logging daily quota usage event"
+ "No cached offer available; skipping logging daily quota usage event."
+ "Quota info missing totalQuota/totalUsed; skipping logging daily quota usage event."
+ "Successfully logged daily quota usage event"
+ "com.apple.iCloudNotification.quotaUsageLastLoggedDate"
+ "com.apple.massStorage.iCloudInfo.quotaUsage"
```
