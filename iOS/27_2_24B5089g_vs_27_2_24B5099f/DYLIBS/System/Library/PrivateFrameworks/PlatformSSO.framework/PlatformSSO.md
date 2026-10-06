## PlatformSSO

> `/System/Library/PrivateFrameworks/PlatformSSO.framework/PlatformSSO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5d028` | `0x5dd74` | **`+0xd4c`** |
| `__TEXT.__oslogstring` | `0x2a41` | `0x2c81` | **`+0x240`** |
| `__AUTH_CONST.__objc_const` | `0x8828` | `0x8948` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x36bc` | `0x37cc` | **`+0x110`** |
| `__TEXT.__gcc_except_tab` | `0x1464` | `0x1554` | **`+0xf0`** |
| `__DATA_CONST.__objc_selrefs` | `0x2460` | `0x2538` | **`+0xd8`** |
| `__TEXT.__cstring` | `0x8376` | `0x83e6` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x15e8` | `0x1640` | **`+0x58`** |
| `__AUTH_CONST.__cfstring` | `0x3aa0` | `0x3ae0` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x3a4` | `0x3bc` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x458` | `0x468` | **`+0x10`** |

### Other Changes

```diff

-643.40.27.0.0
+643.40.34.0.0

-  Functions: 2179
-  Symbols:   2703
-  CStrings:  1058
+  Functions: 2206
+  Symbols:   2741
+  CStrings:  1067
Symbols:
+ -[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:error:]
+ -[POAgentAuthenticationProcess requestUserRegistrationRepairIfNeeded]
+ -[POAgentAuthenticationProcess setUserRegistrationRepairLock:]
+ -[POAgentAuthenticationProcess setUserRegistrationRepairRequested:]
+ -[POAgentAuthenticationProcess shouldRunConfigurationChangeOnUnlock]
+ -[POAgentAuthenticationProcess userRegistrationRepairLock]
+ -[POAgentAuthenticationProcess userRegistrationRepairRequested]
+ -[PODaemonConnection verifyOwnSecureTokenPasswordForUser:passwordContext:completion:]
+ -[POProfile additionalHTTPHeaders]
+ -[PORegistrationManager claimDeviceRegistrationStart]
+ -[PORegistrationManager claimRegistrationStartResumingUnfinishedDeviceRegistration:]
+ -[PORegistrationManager claimUserRegistrationStart]
+ -[PORegistrationManager publishRegistrationContext:claim:]
+ -[PORegistrationManager publishRegistrationContextWithState:claim:]
+ -[PORegistrationManager registrationContextLock]
+ -[PORegistrationManager registrationGeneration]
+ -[PORegistrationManager registrationIsInProgress]
+ -[PORegistrationManager registrationStarting]
+ -[PORegistrationManager releaseRegistrationStart:]
+ -[PORegistrationManager setRegistrationContextLock:]
+ -[PORegistrationManager setRegistrationGeneration:]
+ -[PORegistrationManager setRegistrationStarting:]
+ GCC_except_table104
+ GCC_except_table126
+ GCC_except_table127
+ GCC_except_table128
+ GCC_except_table133
+ GCC_except_table134
+ GCC_except_table16
+ GCC_except_table185
+ GCC_except_table68
+ GCC_except_table69
+ GCC_except_table70
+ GCC_except_table71
+ GCC_except_table93
+ GCC_except_table95
+ GCC_except_table98
+ _NSLocalizedDescriptionKey
+ _OBJC_IVAR_$_POAgentAuthenticationProcess._userRegistrationRepairLock
+ _OBJC_IVAR_$_POAgentAuthenticationProcess._userRegistrationRepairRequested
+ _OBJC_IVAR_$_POProfile._additionalHTTPHeaders
+ _OBJC_IVAR_$_PORegistrationManager._registrationContextLock
+ _OBJC_IVAR_$_PORegistrationManager._registrationGeneration
+ _OBJC_IVAR_$_PORegistrationManager._registrationStarting
+ ___69-[POAgentAuthenticationProcess requestUserRegistrationRepairIfNeeded]_block_invoke
+ ___80-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:error:]_block_invoke
+ ___80-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:error:]_block_invoke_2
+ ___85-[PODaemonConnection verifyOwnSecureTokenPasswordForUser:passwordContext:completion:]_block_invoke
+ ___block_descriptor_57_e8_32s40s48bs_e20_v24?0Q8"NSError"16ls32l8s40l8s48l8
+ _kPOErrorDomain
- GCC_except_table101
- GCC_except_table112
- GCC_except_table116
- GCC_except_table122
- GCC_except_table124
- GCC_except_table130
- GCC_except_table180
- GCC_except_table89
- _OUTLINED_FUNCTION_13
- ___74-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:]_block_invoke
- ___74-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:]_block_invoke_2
- ___block_descriptor_56_e8_32s40s48bs_e20_v24?0Q8"NSError"16ls32l8s40l8s48l8
CStrings:
+ ")#Z"
+ "-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:error:]"
+ "A registration check was already requested for this user"
+ "A registration is already in progress (state = %{public}@), not asking for a registration check"
+ "A registration is already running for this new user; not running the registration checks on unlock"
+ "AdditionalHTTPHeaders"
+ "Keybag rekey failed at login; falling back to the password-authorized local account password change"
+ "Registration has failed, not asking for a registration check"
+ "The configuration changed while this registration was starting; not publishing it"
+ "User registration is not usable (state = %{public}@), running the registration checks"
+ "User registration needs to be repaired before the user can authenticate."
+ "User registration no longer needs repair (state = %{public}@)"
+ "another registration is already starting"
+ "\xf0\xe1"
- ")#Y"
- "-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:]"
- "Falling back to password-authorized local account password change"
- "User registration already in progress: %{public}@"
- "\xf0\xd1"
```
