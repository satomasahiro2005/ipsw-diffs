## PlatformSSO

> `/System/Library/PrivateFrameworks/PlatformSSO.framework/PlatformSSO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c068` | `0x5c530` | **`+0x4c8`** |
| `__TEXT.__oslogstring` | `0x28f1` | `0x2961` | **`+0x70`** |
| `__TEXT.__cstring` | `0x8296` | `0x82e6` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x3a40` | `0x3a80` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x8640` | `0x8670` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x358c` | `0x35bc` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x2400` | `0x2428` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x440` | `0x458` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x15b8` | `0x15c8` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1448` | `0x1454` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x758` | `0x760` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x390` | `0x394` | **`+0x4`** |

### Other Changes

```diff

-643.0.47.0.0
+643.40.23.0.0

-  Functions: 2146
-  Symbols:   2662
-  CStrings:  1050
+  Functions: 2154
+  Symbols:   2671
+  CStrings:  1053
Symbols:
+ -[POAgentAuthenticationProcess postAuthenticationNotificationForEvaluationError:]
+ -[PODaemonConnection resetTempSessionAccountWithCompletion:]
+ -[POProfile alwaysUseLoginUI]
+ -[POProfile setAlwaysUseLoginUI:]
+ GCC_except_table115
+ GCC_except_table123
+ GCC_except_table130
+ GCC_except_table178
+ GCC_except_table36
+ GCC_except_table89
+ _LAErrorDomain
+ _OBJC_IVAR_$_POProfile._alwaysUseLoginUI
+ _POExtensionNormalizedTeamIdentifier
+ ___60-[PODaemonConnection resetTempSessionAccountWithCompletion:]_block_invoke
+ _krb5_get_init_creds_opt_set_tkt_life
- GCC_except_table114
- GCC_except_table117
- GCC_except_table121
- GCC_except_table128
- GCC_except_table177
- GCC_except_table5
CStrings:
+ "AlwaysUseLoginUI"
+ "Auth rights already checked for this build"
+ "Auth rights check failed, screen unlock may not use Platform SSO: %{public}@"
+ "Auth rights checked successfully"
+ "The federationUserPreauthenticationURL is missing for dynamic OpenID."
- "Rule already checked"
- "Rule successfully checked"
```
