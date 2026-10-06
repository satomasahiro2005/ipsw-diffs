## AppleIDAuthentication

> `/System/Library/Accounts/Authentication/AppleIDAuthentication.bundle/AppleIDAuthentication`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9cf8` | `0x9d88` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x2542` | `0x25a3` | **`+0x61`** |
| `__DATA_CONST.__objc_selrefs` | `0x6d8` | `0x6e0` | **`+0x8`** |

### Other Changes

```diff

-1069.125.4.0.0
+1069.125.7.0.0

-  Functions: 111
+  Functions: 112

-  CStrings:  191
+  CStrings:  192
CStrings:
+ "AppleIDAuthenticationPlugin: server backoff suppressed the login request, keeping the credential"
```
