## LocalAuthenticationCredentialServices

> `/System/Library/PrivateFrameworks/LocalAuthenticationCredentialServices.framework/LocalAuthenticationCredentialServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18bec` | `0x18c08` | **`+0x1c`** |
| `__DATA.__bss` | `0x98` | `0x88` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `—` | `0x10` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x150` | `0x158` | **`+0x8`** |

### Other Changes

```diff

-2319.0.16.502.1
+2319.0.33.0.1

-  Functions: 674
+  Functions: 675
Functions:
+ _OUTLINED_FUNCTION_57
~ _OUTLINED_FUNCTION_59 : 20 -> 12
~ _LibCall_ACMContextVerifyPolicyAndCopyRequirementEx : 704 -> 716
~ _LibCall_ACMKernDoubleClickNotify : 172 -> 180
~ _LibCall_ACMContextVerifyPolicyEx : 196 -> 192
~ _LibCall_ACMSecContextVerifyPolicyAndCopyRequirementEx : 200 -> 196
~ _LibCall_ACMContextLoadFromImage : 464 -> 460
~ _LibCall_ACMSecSetBuiltinBiometry : 164 -> 172
```
