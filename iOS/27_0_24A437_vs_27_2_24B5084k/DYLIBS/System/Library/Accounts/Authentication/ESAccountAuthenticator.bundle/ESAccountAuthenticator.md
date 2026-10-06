## ESAccountAuthenticator

> `/System/Library/Accounts/Authentication/ESAccountAuthenticator.bundle/ESAccountAuthenticator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x900` | `0x980` | **`+0x80`** |
| `__TEXT.__cstring` | `0x712` | `0x76f` | **`+0x5d`** |
| `__TEXT.__text` | `0x85c4` | `0x85fc` | **`+0x38`** |
| `__TEXT.__oslogstring` | `0x117c` | `0x117a` | **`-0x2`** |

### Other Changes

```diff

-2079.0.1.0.0
+2079.200.31.0.0

-  CStrings:  146
+  CStrings:  150
Functions:
~ sub_242e7d844 -> sub_2467e3844 : 676 -> 732
CStrings:
+ "EXCHANGE_OAUTH_SIGNIN_TITLE"
+ "HOTMAIL_OAUTH_SIGNIN_TITLE"
+ "OAUTH_SIGNIN_BODY"
+ "OAUTH_SIGNIN_BUTTON"
+ "User cancelled out of OAuth authentication alert"
- "User cancelled out of Hotmail authentication alert"
```
