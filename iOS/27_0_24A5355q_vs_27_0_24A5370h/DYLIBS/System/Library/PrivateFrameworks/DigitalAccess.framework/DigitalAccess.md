## DigitalAccess

> `/System/Library/PrivateFrameworks/DigitalAccess.framework/DigitalAccess`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x395d4` | `0x39700` | **`+0x12c`** |
| `__DATA_CONST.__const` | `0x1130` | `0x1180` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x2abc` | `0x2adc` | **`+0x20`** |
| `__TEXT.__cstring` | `0x8917` | `0x892d` | **`+0x16`** |
| `__DATA_CONST.__objc_selrefs` | `0x1588` | `0x1598` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xdb8` | `0xdc8` | **`+0x10`** |

### Other Changes

```diff

-70.31.1.0.0
+70.34.0.0.0

-  Functions: 1065
-  Symbols:   1861
-  CStrings:  974
+  Functions: 1067
+  Symbols:   1866
+  CStrings:  975
Symbols:
+ -[DAKeyManagementSession(SwiftBridge) countImmobilizerTokensForKeyWithIdentifier:callbackBridge:]
+ -[DAManager(SwiftBridge) registerFriendSidePasscodeRetryRequestTestHandlerBridge:]
+ -[KmlSettingsManager pendingPairingNotificationSchedulingStrategyOverride]
+ __OBJC_$_CLASS_METHODS_DAManager(HydraKey|PendingPairing|SwiftBridge|AliroKey)
+ __OBJC_$_INSTANCE_METHODS_DAKeyManagementSession(SwiftBridge)
+ __OBJC_$_INSTANCE_METHODS_DAManager(HydraKey|PendingPairing|SwiftBridge|AliroKey)
+ ___82-[DAManager(SwiftBridge) registerFriendSidePasscodeRetryRequestTestHandlerBridge:]_block_invoke
+ ___97-[DAKeyManagementSession(SwiftBridge) countImmobilizerTokensForKeyWithIdentifier:callbackBridge:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e11_v24?0Q8Q16ls32l8
+ ___block_descriptor_40_e8_32bs_e21_v24?0"NSString"8Q16ls32l8
- -[KmlSettingsManager pendingPairingNotificationSchedulingStrategy]
- _OUTLINED_FUNCTION_21
- __OBJC_$_CLASS_METHODS_DAManager(HydraKey|PendingPairing|AliroKey)
- __OBJC_$_INSTANCE_METHODS_DAKeyManagementSession
- __OBJC_$_INSTANCE_METHODS_DAManager(HydraKey|PendingPairing|AliroKey)
CStrings:
+ "v24@?0@\"NSString\"8Q16"
```
