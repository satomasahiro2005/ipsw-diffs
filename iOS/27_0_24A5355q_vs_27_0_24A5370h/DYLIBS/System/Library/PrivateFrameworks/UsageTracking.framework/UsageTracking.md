## UsageTracking

> `/System/Library/PrivateFrameworks/UsageTracking.framework/UsageTracking`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x298d8` | `0x29a90` | **`+0x1b8`** |
| `__AUTH_CONST.__objc_const` | `0x28d0` | `0x2930` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x16cc` | `0x1704` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x13f8` | `0x1420` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0xe60` | `0xe80` | **`+0x20`** |
| `__TEXT.__cstring` | `0x136d` | `0x1385` | **`+0x18`** |
| `__DATA_CONST.__const` | `0xeb8` | `0xec8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x710` | `0x720` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1a0` | `0x1a8` | **`+0x8`** |

### Other Changes

```diff

-401.0.0.0.0
+403.0.0.0.0

-  Functions: 609
-  Symbols:   1174
-  CStrings:  224
+  Functions: 614
+  Symbols:   1183
+  CStrings:  225
Symbols:
+ +[USApplicationUsageMonitor activeApplicationsFromElements:]
+ -[USDeviceActivityEvent initWithApplicationTokens:exemptApplicationTokens:categoryTokens:webDomainTokens:exemptWebDomainTokens:threshold:includesPastActivity:warningTime:warnsOnlyDuringActivity:]
+ -[USDeviceActivityEvent initWithBundleIdentifiers:exemptBundleIdentifiers:categoryIdentifiers:webDomains:exemptWebDomains:threshold:includesPastActivity:warningTime:warnsOnlyDuringActivity:]
+ -[USDeviceActivityEvent warningTime]
+ -[USDeviceActivityEvent warnsOnlyDuringActivity]
+ GCC_except_table18
+ _OBJC_IVAR_$_USDeviceActivityEvent._warningTime
+ _OBJC_IVAR_$_USDeviceActivityEvent._warnsOnlyDuringActivity
+ _USLockScreenIdentifier
+ _USSleepLockScreenBundleIdentifier
- GCC_except_table17
CStrings:
+ "WarnsOnlyDuringActivity"
```
