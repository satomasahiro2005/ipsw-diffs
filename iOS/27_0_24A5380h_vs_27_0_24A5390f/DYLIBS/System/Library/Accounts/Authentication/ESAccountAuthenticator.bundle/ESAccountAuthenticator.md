## ESAccountAuthenticator

> `/System/Library/Accounts/Authentication/ESAccountAuthenticator.bundle/ESAccountAuthenticator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6a68` | `0x85c4` | **`+0x1b5c`** |
| `__TEXT.__oslogstring` | `0xd40` | `0x117c` | **`+0x43c`** |
| `__AUTH_CONST.__cfstring` | `0x5a0` | `0x900` | **`+0x360`** |
| `__TEXT.__cstring` | `0x57c` | `0x712` | **`+0x196`** |
| `__DATA_CONST.__const` | `0x300` | `0x370` | **`+0x70`** |
| `__TEXT.__const` | `0x48` | `0xa0` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x598` | `0x5e8` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x110` | `0x138` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x138` | `0x160` | **`+0x28`** |
| `__AUTH_CONST.__const` | `—` | `0x20` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x2c0` | `0x2e0` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `—` | `0x18` | **`+0x18`** |
| `__DATA.__bss` | `0x10` | `0x20` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x8` | `0xc` | **`+0x4`** |

### Other Changes

```diff

-2076.0.0.0.0
+2078.0.0.0.0

-  Functions: 64
-  Symbols:   156
-  CStrings:  107
+  Functions: 79
+  Symbols:   170
+  CStrings:  146
Symbols:
+ _OAuthRefresh4XXIsTerminal
+ _OAuthRefreshErrorNameIsUserActionRequired
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_NSConstantIntegerNumber
+ _OBJC_CLASS_$_NSMutableSet
+ _OBJC_CLASS_$_NSSet
+ __NSConcreteGlobalBlock
+ _kESExchangeOAuthRefresh5XXResetCount
+ _kESExchangeOAuthRefreshFailureCount
+ _kESExchangeOAuthRefreshFirstFailureDate
+ _objc_enumerationMutation
+ _objc_release_x1
+ _objc_sync_enter
+ _objc_sync_exit
CStrings:
+ " "
+ "%lu"
+ "OAuthRefreshGrace: 200-recovery save failed for account %@; stale grace state may persist. err=%@"
+ "OAuthRefreshGrace: 5XX reset status=%ld 5xxResetCount=%lu"
+ "OAuthRefreshGrace: entering grace status=%ld errorName=%{public}@ error_codes=%{public}@ count=1 elapsed=0"
+ "OAuthRefreshGrace: in-grace 4XX status=%ld errorName=%{public}@ error_codes=%{public}@ count=%lu elapsed=%.0f"
+ "OAuthRefreshGrace: in-grace 5XX/429 status=%ld error_codes=%{public}@ count=%lu elapsed=%.0f"
+ "OAuthRefreshGrace: recovered status=200 elapsed=%.0f count=%lu 5xxResetCount=%lu"
+ "OAuthRefreshGrace: short-circuit (backoff) count=%lu elapsed=%.0f"
+ "OAuthRefreshGrace: short-circuit (in-flight) inFlightCount=%lu"
+ "OAuthRefreshGrace: terminal (4XX) status=%ld errorName=%{public}@ error_codes=%{public}@"
+ "OAuthRefreshGrace: terminal (5XX-cap) status=%ld error_codes=%{public}@ elapsed=%.0f 5xxResetCount=%lu"
+ "OAuthRefreshGrace: terminal (final 4XX) status=%ld errorName=%{public}@ error_codes=%{public}@ elapsed=%.0f count=%lu 5xxResetCount=%lu"
+ "Received an error. errorName=%{public}@"
+ "Received an invalid_grant error. errorName=%{public}@"
+ "Refreshing OAuth Token failed (bypass arm). status=%ld errorName=%{public}@ errorDomain=%{public}@ errorCode=%ld"
+ "access_denied"
+ "account_unusable"
+ "authorization_pending"
+ "bad_token"
+ "consent_required"
+ "error_codes"
+ "expired_token"
+ "i"
+ "insufficient_claims"
+ "interaction_required"
+ "invalid_client"
+ "invalid_request"
+ "invalid_resource"
+ "invalid_scope"
+ "invalid_token"
+ "login_required"
+ "malformed"
+ "none"
+ "other"
+ "server_error"
+ "slow_down"
+ "temporarily_unavailable"
+ "unauthorized_client"
+ "unsupported_grant_type"
+ "unsupported_response_type"
+ "unsupported_token_type"
- "Received an Error: refreshing OAuth Token failed with Error %@"
- "Received an error. %@ %@"
- "Received an invalid_grant error. %@ %@"
```
