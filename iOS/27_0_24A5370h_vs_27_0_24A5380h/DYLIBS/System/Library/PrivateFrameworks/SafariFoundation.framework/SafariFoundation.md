## SafariFoundation

> `/System/Library/PrivateFrameworks/SafariFoundation.framework/SafariFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `—` | `0x5f0` | **`+0x5f0`** |
| `__AUTH.__data` | `0x598` | `—` | **`-0x598`** |
| `__AUTH.__objc_data` | `0x308` | `0xd8` | **`-0x230`** |
| `__DATA_DIRTY.__objc_data` | `0x960` | `0xb90` | **`+0x230`** |
| `__DATA.__bss` | `0x230` | `0x1d0` | **`-0x60`** |
| `__DATA_DIRTY.__bss` | `0xb0` | `0x110` | **`+0x60`** |
| `__DATA.__data` | `0x598` | `0x550` | **`-0x48`** |
| `__AUTH_CONST.__cfstring` | `0x1ec0` | `0x1ee0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2a47` | `0x2a67` | **`+0x20`** |
| `__TEXT.__text` | `0x35d44` | `0x35d5c` | **`+0x18`** |

### Other Changes

```diff

-625.1.20.10.3
+625.1.22.10.3

-  CStrings:  438
+  CStrings:  439
Functions:
~ +[SFSafariCredentialStore _applicationIDsForAppsToOfferToSaveEvenIfEnabledAsCredentialProvider] : 72 -> 80
~ ___153+[SFSafariCredentialStore getOneTimeCodeCredentialsForAppWithAppID:externallyVerifiedAndApprovedSharedWebCredentialDomains:websiteURL:completionHandler:]_block_invoke : 628 -> 644
CStrings:
+ "0000000000.com.apple.ASApp-Catalyst"
```
