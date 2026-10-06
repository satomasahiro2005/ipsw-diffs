## SafariFoundation

> `/System/Library/PrivateFrameworks/SafariFoundation.framework/SafariFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35d54` | `0x35dec` | **`+0x98`** |
| `__AUTH_CONST.__cfstring` | `0x1ec0` | `0x1ee0` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x3a58` | `0x3a68` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x19a8` | `0x19b8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x2a57` | `0x2a67` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x21d0` | `0x21e0` | **`+0x10`** |

### Other Changes

```diff

-625.1.24.10.1
+625.1.29.10.3

-  Functions: 1411
-  Symbols:   2080
-  CStrings:  438
+  Functions: 1412
+  Symbols:   2082
+  CStrings:  439
Symbols:
+ -[NSExtension(SafariFoundationExtras) sf_extensionAppID]
+ GCC_except_table3
Functions:
+ -[NSExtension(SafariFoundationExtras) sf_extensionAppID]
~ +[SFSafariCredentialStore _applicationIDsForAppsToNotOfferToSavePasswords] : 92 -> 100
CStrings:
+ "com.apple.DocumentsApp"
```
