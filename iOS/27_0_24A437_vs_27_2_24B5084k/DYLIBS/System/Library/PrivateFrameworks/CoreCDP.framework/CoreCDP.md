## CoreCDP

> `/System/Library/PrivateFrameworks/CoreCDP.framework/CoreCDP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f6a8` | `0x4f994` | **`+0x2ec`** |
| `__TEXT.__cstring` | `0x65c2` | `0x66aa` | **`+0xe8`** |
| `__AUTH_CONST.__cfstring` | `0x3e80` | `0x3f40` | **`+0xc0`** |
| `__TEXT.__const` | `0x147c` | `0x14d4` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x3a74` | `0x3aac` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x8838` | `0x8868` | **`+0x30`** |
| `__DATA.__data` | `0x1178` | `0x11a0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x21b8` | `0x21d8` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x2fd0` | `0x2fe8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1660` | `0x1668` | **`+0x8`** |

### Other Changes

```diff

-447.0.0.0.0
+448.125.5.1.0

-  Functions: 2401
-  Symbols:   3885
-  CStrings:  1639
+  Functions: 2404
+  Symbols:   3903
+  CStrings:  1647
Symbols:
+ +[CDPUtilities isDBRHealingEnabled]
+ +[CDPUtilities isDBRInlineSignInHealEnabled]
+ +[CDPUtilities isEntitlementEnforcementEnabled]
+ -[AAFAnalyticsEvent(CDP) populateDBRDetectionDetailWithRemainingAttempts:detectionError:]
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_AAFAnalyticsEvent_$_CDP
+ ___der_key_state_abs_last_mesa_auth
+ ___der_key_state_abs_last_mesa_unlock
+ ___der_key_state_abs_last_passcode_auth
+ ___der_key_state_abs_last_passcode_unlock
+ ___der_key_state_abs_lock_time
+ _der_key_state_abs_last_mesa_auth
+ _der_key_state_abs_last_mesa_unlock
+ _der_key_state_abs_last_passcode_auth
+ _der_key_state_abs_last_passcode_unlock
+ _der_key_state_abs_lock_time
+ _kCDPAnalyticsPDPRecordGenerationAheadEvent
+ _kCDPAnalyticsPDPRecordGenerationCheckSkippedEvent
+ _kCDPAnalyticsPDPWrappingKeyRepairEvent
CStrings:
+ "DBRHealing"
+ "DBRHealingEnabled"
+ "DBRInlineSignInHeal"
+ "DBRInlineSignInHealEnabled"
+ "EnforceCDPDEntitlements"
+ "com.apple.corecdp.pdpRecordGenerationAhead"
+ "com.apple.corecdp.pdpRecordGenerationCheckSkipped"
+ "com.apple.corecdp.pdpWrappingKeyRepair"
```
