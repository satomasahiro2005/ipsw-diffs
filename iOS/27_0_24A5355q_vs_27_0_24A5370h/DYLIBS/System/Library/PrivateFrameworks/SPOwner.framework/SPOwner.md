## SPOwner

> `/System/Library/PrivateFrameworks/SPOwner.framework/SPOwner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7549c` | `0x754f4` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x14018` | `0x14048` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x5e60` | `0x5e80` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xb9fc` | `0xba14` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3ce0` | `0x3cf0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x6a09` | `0x6a19` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xee0` | `0xee4` | **`+0x4`** |

### Other Changes

```diff

-446.30.5.17.5
+448.30.6.7.2

-  Functions: 4357
-  Symbols:   7276
-  CStrings:  1542
+  Functions: 4359
+  Symbols:   7279
+  CStrings:  1543
Symbols:
+ -[SPUnknownProductMetadata initWithTitle:description:percentageX:percentageY:image:image2x:image3x:video:]
+ -[SPUnknownProductMetadata setVideo:]
+ -[SPUnknownProductMetadata video]
+ _OBJC_IVAR_$_SPUnknownProductMetadata._video
- -[SPUnknownProductMetadata initWithTitle:description:percentageX:percentageY:image:image2x:image3x:]
CStrings:
+ "video"
```
