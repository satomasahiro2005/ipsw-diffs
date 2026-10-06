## PlatformSSOCore

> `/System/Library/PrivateFrameworks/PlatformSSOCore.framework/PlatformSSOCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x967c4` | `0x96e70` | **`+0x6ac`** |
| `__TEXT.__cstring` | `0xaa1d` | `0xac4c` | **`+0x22f`** |
| `__AUTH_CONST.__cfstring` | `0x78e0` | `0x7a40` | **`+0x160`** |
| `__DATA_CONST.__const` | `0x2580` | `0x25d8` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c90` | `0x2cb0` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x1e47` | `0x1e67` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2140` | `0x2158` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x6250` | `0x6260` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x9a8` | `0x9b0` | **`+0x8`** |

### Other Changes

```diff

-635.0.0.0.0
+643.0.12.0.0

-  Functions: 3829
-  Symbols:   5778
-  CStrings:  1736
+  Functions: 3832
+  Symbols:   5790
+  CStrings:  1750
Symbols:
+ -[POAgentCoreProcess _verifyLogin:passwordContext:smartCardContext:tokenId:callbackResponse:deviceConfiguration:loginConfiguration:forAuthorization:authorizationContextScope:completion:]
+ -[POAuthenticationProcess _mergedScopes:withScopes:]
+ -[POAuthenticationProcess createSignedOpenIDAuthorizationRequestWithURL:authorizationRequestValues:scope:deviceConfiguration:error:]
+ _OBJC_CLASS_$_NSMutableOrderedSet
+ ___132-[POAuthenticationProcess createSignedOpenIDAuthorizationRequestWithURL:authorizationRequestValues:scope:deviceConfiguration:error:]_block_invoke
+ ___186-[POAgentCoreProcess _verifyLogin:passwordContext:smartCardContext:tokenId:callbackResponse:deviceConfiguration:loginConfiguration:forAuthorization:authorizationContextScope:completion:]_block_invoke
+ _kPOAuthorizationScopeAuthPrompt
+ _kPOAuthorizationScopeCreateUser
+ _kPOAuthorizationScopeElevation
+ _kPOAuthorizationScopeFVUnlock
+ _kPOAuthorizationScopeFallback
+ _kPOAuthorizationScopeLogin
+ _kPOAuthorizationScopePasswordChange
+ _kPOAuthorizationScopeRefresh
+ _kPOAuthorizationScopeSetupAssistant
+ _kPOAuthorizationScopeTemporarySession
+ _kPOAuthorizationScopeUnlock
- -[POAgentCoreProcess _verifyLogin:passwordContext:smartCardContext:tokenId:callbackResponse:deviceConfiguration:loginConfiguration:forAuthorization:completion:]
- -[POAuthenticationProcess createSignedOpenIDAuthorizationRequestWithURL:authorizationRequestValues:deviceConfiguration:error:]
- _OUTLINED_FUNCTION_101
- ___126-[POAuthenticationProcess createSignedOpenIDAuthorizationRequestWithURL:authorizationRequestValues:deviceConfiguration:error:]_block_invoke
- ___160-[POAgentCoreProcess _verifyLogin:passwordContext:smartCardContext:tokenId:callbackResponse:deviceConfiguration:loginConfiguration:forAuthorization:completion:]_block_invoke
CStrings:
+ "%s:%spid:%d,%s:%s%s%s%s%s%u:%s cccurve25519 failed: small-order point used%s\n"
+ "-[POAgentCoreProcess _verifyLogin:passwordContext:smartCardContext:tokenId:callbackResponse:deviceConfiguration:loginConfiguration:forAuthorization:authorizationContextScope:completion:]"
+ "Mailbox sequence is empty"
+ "generate_wrapping_key_curve25519"
+ "urn:apple:platformsso:auth:auth-prompt"
+ "urn:apple:platformsso:auth:create-user"
+ "urn:apple:platformsso:auth:elevation"
+ "urn:apple:platformsso:auth:fallback"
+ "urn:apple:platformsso:auth:fvunlock"
+ "urn:apple:platformsso:auth:login"
+ "urn:apple:platformsso:auth:password-change"
+ "urn:apple:platformsso:auth:refresh"
+ "urn:apple:platformsso:auth:setup-assistant"
+ "urn:apple:platformsso:auth:temporary-session"
+ "urn:apple:platformsso:auth:unlock"
- "-[POAgentCoreProcess _verifyLogin:passwordContext:smartCardContext:tokenId:callbackResponse:deviceConfiguration:loginConfiguration:forAuthorization:completion:]"
```
