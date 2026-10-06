## ESDaemonSupport

> `/System/Library/PrivateFrameworks/ExchangeSync.framework/Frameworks/ESDaemonSupport.framework/ESDaemonSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20f5c` | `0x212c4` | **`+0x368`** |
| `__TEXT.__oslogstring` | `0x339b` | `0x34c8` | **`+0x12d`** |
| `__AUTH_CONST.__objc_const` | `0x2a70` | `0x2a90` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x750` | `0x758` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1270` | `0x1278` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x14e4` | `0x14ec` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x698` | `0x6a0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x160` | `0x164` | **`+0x4`** |
| `__TEXT.__cstring` | `0x10fe` | `0x10ff` | **`+0x1`** |

### Other Changes

```diff

-2078.0.0.0.0
+2079.0.1.0.0

-  Functions: 582
-  Symbols:   1301
-  CStrings:  335
+  Functions: 583
+  Symbols:   1303
+  CStrings:  338
Symbols:
+ +[ESDAgentManager wirelessPolicy:isMorePermissiveThanPolicy:]
+ GCC_except_table46
+ GCC_except_table69
+ _OBJC_IVAR_$_ESDAgentManager._wirelessPolicies
+ _kCTCellularDataUsagePolicyDeny
- GCC_except_table45
- GCC_except_table68
- _CFDictionaryGetValue
CStrings:
+ "Received cellular data usage changed notification. Checking if a refresh is required."
+ "Refreshing account %@ because wireless data use is now allowed for %{public}@ and might not have been before."
+ "User allowed cellular or wifi data for BundleID %{public}@"
+ "Wireless data usage policy changes do not affect any existing agents; no refreshes will be done."
- "User allowed cellular-data for BundleID %{public}@"
```
