## PlatformSSO

> `/System/Library/PrivateFrameworks/PlatformSSO.framework/PlatformSSO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5ac90` | `0x5adf0` | **`+0x160`** |
| `__TEXT.__gcc_except_tab` | `0x126c` | `0x13a8` | **`+0x13c`** |

### Other Changes

```diff

-643.0.12.0.0
+643.0.21.0.0
Functions:
~ -[PORegistrationManager completeLegacyUserRegistration] : 556 -> 564
~ -[PORegistrationManager finishRegistrationWithStatus:message:] : 712 -> 720
~ ___139-[POAgentProcess performOpenIDLogin:loginUserName:callbackResponse:passwordContext:updateLocalAccountPassword:additionalScopes:completion:]_block_invoke.106 : 2092 -> 2104
~ -[POAgentAuthenticationProcess _handleConfigurationChanged:startup:] : 2492 -> 2692
~ sub_291a6d8ac -> sub_296354990 : 3780 -> 3904
```
