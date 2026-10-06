## OSAnalytics

> `/System/Library/PrivateFrameworks/OSAnalytics.framework/OSAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4b024` | `0x4b1a0` | **`+0x17c`** |
| `__AUTH_CONST.__objc_const` | `0x3900` | `0x3930` | **`+0x30`** |
| `__TEXT.__cstring` | `0x92fa` | `0x932a` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xa220` | `0xa240` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xe78` | `0xe90` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1cb8` | `0x1cd0` | **`+0x18`** |
| `__DATA.__bss` | `0x358` | `0x360` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x16b8` | `0x16c0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2cc` | `0x2d0` | **`+0x4`** |

### Other Changes

```diff

-1056.0.17.0.0
+1056.0.22.0.0

-  Functions: 1253
-  Symbols:   2111
-  CStrings:  1861
+  Functions: 1256
+  Symbols:   2119
+  CStrings:  1863
Symbols:
+ -[OSAProxyConfiguration panicReportSubmissionDisabled]
+ -[OSASystemConfiguration panicReportSubmissionDisabled]
+ GCC_except_table103
+ GCC_except_table107
+ GCC_except_table135
+ OBJC_IVAR_$_OSAProxyConfiguration._panicReportSubmissionDisabled
+ _CFDataGetTypeID
+ _IORegistryEntryCreateCFProperty
+ _IORegistryEntryFromPath
+ ___55-[OSASystemConfiguration panicReportSubmissionDisabled]_block_invoke
+ _getmntinfo_r_np
+ _panicReportSubmissionDisabled.onceToken
- GCC_except_table102
- GCC_except_table105
- GCC_except_table132
- _getmntinfo
CStrings:
+ "IODeviceTree:/product"
+ "disable-panic-report-submission"
```
