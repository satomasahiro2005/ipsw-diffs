## AdID

> `/System/Library/PrivateFrameworks/AdID.framework/AdID`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18c58` | `0x18e98` | **`+0x240`** |
| `__TEXT.__cstring` | `0x69a6` | `0x6a57` | **`+0xb1`** |
| `__AUTH_CONST.__cfstring` | `0x4260` | `0x42c0` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x260` | `0x280` | **`+0x20`** |
| `__DATA.__bss` | `0x1` | `0x11` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xfdc` | `0xfec` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x380` | `0x388` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1310` | `0x1318` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x590` | `0x598` | **`+0x8`** |

### Other Changes

```diff

-638.1.0.0.0
+638.1.3.0.0

-  Functions: 400
-  Symbols:   896
-  CStrings:  573
+  Functions: 404
+  Symbols:   905
+  CStrings:  577
Symbols:
+ -[ADAdTrackingSchedulingManager scrubLegacyCKSubscribedAccountsFromDefaults]
+ GCC_except_table37
+ _ADCoreDefaultsBundleID
+ _CFPreferencesAppSynchronize
+ _CFPreferencesSetAppValue
+ ___76-[ADAdTrackingSchedulingManager scrubLegacyCKSubscribedAccountsFromDefaults]_block_invoke
+ ___76-[ADAdTrackingSchedulingManager scrubLegacyCKSubscribedAccountsFromDefaults]_block_invoke_2
+ _dispatch_set_target_queue
+ _scrubLegacyCKSubscribedAccountsFromDefaults.onceToken
+ _scrubLegacyCKSubscribedAccountsFromDefaults.queue
- GCC_except_table34
CStrings:
+ "CKSubscribedAccounts"
+ "CKSubscribedAccountsScrubbed"
+ "[%@]: Scrubbed legacy CKSubscribedAccounts from com.apple.AdLib defaults"
+ "com.apple.adplatforms.scrubLegacyCKSubscribedAccounts"
```
