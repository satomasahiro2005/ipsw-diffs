## SetupAssistant

> `/System/Library/PrivateFrameworks/SetupAssistant.framework/SetupAssistant`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x44824` | `0x44ac4` | **`+0x2a0`** |
| `__TEXT.__objc_methlist` | `0x41b4` | `0x420c` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x59f4` | `0x5a31` | **`+0x3d`** |
| `__AUTH_CONST.__objc_const` | `0x62d0` | `0x6308` | **`+0x38`** |
| `__TEXT.__cstring` | `0x34e3` | `0x3511` | **`+0x2e`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c88` | `0x2cb0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x3ae0` | `0x3b00` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0xaa0` | `0xac0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1778` | `0x1780` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1360` | `0x1368` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3d0` | `0x3d4` | **`+0x4`** |

### Other Changes

```diff

-5409.0.0.0.0
+5411.0.0.0.0

-  Functions: 1801
-  Symbols:   3110
-  CStrings:  1138
+  Functions: 1807
+  Symbols:   3118
+  CStrings:  1140
Symbols:
+ +[BYChronicleEntry osVersionIsAorERelease:]
+ -[BYBuddyDaemonGeneralClient beginServicesTermsRequirementCheck]
+ -[BYChronicleEntry hasCrossedAOrEBoundary]
+ -[BYManagedAppleIDBootstrap cachedManagedAccountAltDSID]
+ -[BYManagedAppleIDBootstrap setCachedManagedAccountAltDSID:]
+ _BYSetupAssistantDidCompleteAppleAccountNotification
+ _OBJC_IVAR_$_BYManagedAppleIDBootstrap._cachedManagedAccountAltDSID
+ __OBJC_$_CLASS_METHODS_BYChronicleEntry
+ ___64-[BYBuddyDaemonGeneralClient beginServicesTermsRequirementCheck]_block_invoke
- GCC_except_table53
CStrings:
+ "Failed to begin services terms requirement check: %{public}@"
+ "com.apple.purplebuddy.didcompleteappleaccount"
```
