## CoreCDPInternal

> `/System/Library/PrivateFrameworks/CoreCDPInternal.framework/CoreCDPInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8dbdc` | `0x8dda4` | **`+0x1c8`** |
| `__TEXT.__cstring` | `0xe055` | `0xe0c5` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x94c0` | `0x9520` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x14a5e` | `0x14a9e` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x10b8` | `0x10f0` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0xb94` | `0xb68` | **`-0x2c`** |
| `__TEXT.__unwind_info` | `0x1df8` | `0x1e10` | **`+0x18`** |

### Other Changes

```diff

-445.0.0.0.0
+447.0.0.0.0

-  Functions: 3158
-  Symbols:   4146
-  CStrings:  2806
+  Functions: 3159
+  Symbols:   4153
+  CStrings:  2809
Symbols:
+ _kAAAnalyticsEventRCOwnerCustodianCountMatch
+ _kAAAnalyticsEventRCOwnerEscapeOfferTapped
+ _kAAAnalyticsEventRCOwnerFlowOutcome
+ _kAAAnalyticsEventRCOwnerGetCodeLanding
+ _kAAAnalyticsEventRCOwnerPrivateChannelCreated
+ _kAAAnalyticsEventRCOwnerRecoveryLanding
+ _kSecureBackupDBRKey
Functions:
~ _OUTLINED_FUNCTION_4 : 12 -> 20
~ _OUTLINED_FUNCTION_4 : 28 -> 12
+ _OUTLINED_FUNCTION_4
~ ___46+[CDPDAnalyticsTransport getAllowedDIDCEvents]_block_invoke : 488 -> 520
~ +[CDPDAnalyticsTransport approvedRecoveryContactEventsForDIDCAndDNU] : 1824 -> 1996
~ -[CDPInternalWalrusStateController _fetchiCDPAccountInfoDictionaryWithContext:error:] : 436 -> 500
~ -[CDPWalrusDaemonService combinedWalrusStatusWithContext:completion:].cold.2 : 136 -> 124
~ ___77-[CDPWalrusDaemonService updateWalrusStatus:authenticatedContext:completion:]_block_invoke.cold.1 : 52 -> 120
~ -[CDPWalrusDaemonService _checkWalrusBeforeFetchingPCSKeysForServices:pcsController:completion:].cold.2 : 52 -> 64
~ ___71-[CDPWalrusDaemonService _pcsKeysForServices:pcsController:completion:]_block_invoke.cold.2 : 52 -> 64
~ ___87-[CDPInternalWalrusStateController _retryWalrusStateUpdate:context:account:completion:]_block_invoke.cold.1 : 52 -> 140
CStrings:
+ "Failed to update walrus status with error: domain=%{public}@ code=%{public}ld"
+ "Silent re-authentication prior to Walrus re-try failed with error: domain=%{public}@ code=%{public}ld"
+ "com.apple.authkit.pac.signature"
+ "com.apple.authkit.pac.subscriptionInfo"
+ "com.apple.authkit.pac.subscriptionSource"
- "Failed to update walrus status with error: %@"
- "Silent re-authentication prior to Walrus re-try failed with error: %@"
```
