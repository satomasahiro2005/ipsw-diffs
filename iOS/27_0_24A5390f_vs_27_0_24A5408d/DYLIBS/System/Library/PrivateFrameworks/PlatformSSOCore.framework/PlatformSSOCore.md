## PlatformSSOCore

> `/System/Library/PrivateFrameworks/PlatformSSOCore.framework/PlatformSSOCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x976dc` | `0x97b0c` | **`+0x430`** |
| `__AUTH_CONST.__objc_const` | `0x14cc8` | `0x14d28` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x6278` | `0x62d8` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x2ce8` | `0x2d10` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x64c` | `0x654` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2170` | `0x2178` | **`+0x8`** |

### Other Changes

```diff

-643.0.33.0.0
+643.0.47.0.0

-  Functions: 3843
-  Symbols:   5826
+  Functions: 3850
+  Symbols:   5836
Symbols:
+ +[POAuthenticationProcess authorizationContextScopes]
+ -[POAuthenticationContext includePlatformSSOAuthorizationScopes]
+ -[POAuthenticationContext setIncludePlatformSSOAuthorizationScopes:]
+ -[POAuthenticationProcess _requestScopeForContext:]
+ -[POAuthenticationProcess _scopeByRemovingAuthorizationContextScopes:]
+ -[POLoginConfiguration includePlatformSSOAuthorizationScopes]
+ -[POLoginConfiguration setIncludePlatformSSOAuthorizationScopes:]
+ _OBJC_IVAR_$_POAuthenticationContext._includePlatformSSOAuthorizationScopes
+ _OBJC_IVAR_$_POLoginConfiguration._includePlatformSSOAuthorizationScopes
+ __OBJC_$_CLASS_METHODS_POAuthenticationProcess
```
