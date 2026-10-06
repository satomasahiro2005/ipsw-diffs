## MarkupUI

> `/System/Library/PrivateFrameworks/MarkupUI.framework/MarkupUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x29c4` | `0x2a78` | **`+0xb4`** |
| `__TEXT.__text` | `0x28ca8` | `0x28cf8` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x2620` | `0x2660` | **`+0x40`** |

### Other Changes

```diff

-581.0.0.0.0
+582.0.0.0.0

-  CStrings:  396
+  CStrings:  398
Functions:
~ -[MUPayloadEncryption decryptData:] : 392 -> 472
CStrings:
+ "MUPayloadEncryption: %lu bytes is not a valid encrypted payload length. Returning nil."
+ "MUPayloadEncryption: decrypted %lu bytes, too few to contain the salt prefix. Returning nil."
```
