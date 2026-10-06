## MailServices

> `/System/Library/PrivateFrameworks/MailServices.framework/MailServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdffc` | `0xe06c` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x1bd0` | `0x1c00` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x1f00` | `0x1f20` | **`+0x20`** |
| `__TEXT.__cstring` | `0x19e4` | `0x1a02` | **`+0x1e`** |
| `__TEXT.__objc_methlist` | `0xf54` | `0xf6c` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x908` | `0x918` | **`+0x10`** |
| `__DATA_CONST.__const` | `0xb98` | `0xba0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xfc` | `0x100` | **`+0x4`** |

### Other Changes

```diff

-3897.100.8.2.5
+3901.100.1.2.7

-  Functions: 323
-  Symbols:   1077
-  CStrings:  307
+  Functions: 325
+  Symbols:   1081
+  CStrings:  308
Symbols:
+ -[MSEmailModel quotedContentHTML]
+ -[MSEmailModel setQuotedContentHTML:]
+ _MSCodingKeyQuotedContentHTML
+ _OBJC_IVAR_$_MSEmailModel._quotedContentHTML
CStrings:
+ "MSCodingKeyQuotedContentHTML"
```
