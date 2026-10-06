## DAEASOAuthFramework

> `/System/Library/PrivateFrameworks/DAEASOAuthFramework.framework/DAEASOAuthFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcb70` | `0xcca8` | **`+0x138`** |
| `__TEXT.__oslogstring` | `0x167d` | `0x16f7` | **`+0x7a`** |
| `__TEXT.__objc_methlist` | `0xc40` | `0xc50` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2a4` | `0x298` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0x280` | `0x288` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xb30` | `0xb38` | **`+0x8`** |
| `__TEXT.__const` | `0x98` | `0xa0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x290` | `0x298` | **`+0x8`** |

### Other Changes

```diff

-2075.0.0.0.0
+2076.0.0.0.0

-  Functions: 243
-  Symbols:   654
-  CStrings:  281
+  Functions: 244
+  Symbols:   656
+  CStrings:  282
Symbols:
+ +[DAEASOAuthWebViewController _resolvedAccountDescriptionWithAccount:providedDescription:]
+ _objc_retainAutoreleaseReturnValue
Functions:
~ +[DAEASOAuthTokenRequest claimsValueWithClaimsChallenge:] : 756 -> 752
~ +[DAEASOAuthTokenRequest _urlRequestForTokenRequestURI:params:clientID:] : 684 -> 680
~ -[ESExchangeEmptyBearerResponse initWithData:urlResponse:error:] : 792 -> 788
~ +[DAEASOAuthClient clientIDForOAuthType:] : 424 -> 436
~ +[DAEASOAuthClient defaultScopeForOAuthType:withResourceIdentifier:forToken:isOnPrem:] : 624 -> 620
~ -[DAEASOAuthJWTValidator _signatureValid:] : 1636 -> 1632
~ -[DAEASOAuthMigrationActivity _migrateExchangeAccountToOAuthDecision:disallowedDomains:disallowedHosts:] : 1556 -> 1548
~ ___55-[DAEASOAuthMigrationActivity _triggerAccountMigration]_block_invoke : 1300 -> 1296
~ -[DAEASOAuthWebViewController _commonInitializationWithAccount:accountStore:username:accountDescription:presentationBlock:] : 1704 -> 1636
+ +[DAEASOAuthWebViewController _resolvedAccountDescriptionWithAccount:providedDescription:]
~ +[DAEASOAuthRequest authCodeFromRequest:] : 492 -> 488
~ +[DAEASOAuthRequest stateFromRequest:] : 492 -> 488
~ +[DAEASOAuthRequest errorDomainFromRequest:] : 544 -> 540
~ +[DAEASOAuthRequest errorDescriptionFromRequest:] : 544 -> 540
CStrings:
+ "DAEASOAuthWebViewController accountDescription nil; falling back. accountId=%{private}@ usernamePresent=%d descPresent=%d"
```
