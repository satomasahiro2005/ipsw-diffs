## SafariFoundation

> `/System/Library/PrivateFrameworks/SafariFoundation.framework/SafariFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x1ee0` | `0x1ec0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x2a67` | `0x2a57` | **`-0x10`** |
| `__TEXT.__text` | `0x35d5c` | `0x35d54` | **`-0x8`** |

### Other Changes

```diff

-625.1.22.10.3
+625.1.24.10.1

-  CStrings:  439
+  CStrings:  438
Symbols:
+ -[SFCredentialIdentity compareForAutoFill:]
- -[SFCredentialIdentity compareForQuickTypeBar:]
Functions:
~ +[SFSafariCredentialStore _applicationIDsForAppsToOfferToSaveEvenIfEnabledAsCredentialProvider] : 80 -> 72
CStrings:
- "com.apple.sfapp"
```
