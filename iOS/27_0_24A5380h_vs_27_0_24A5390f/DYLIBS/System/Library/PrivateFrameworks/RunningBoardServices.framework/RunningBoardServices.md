## RunningBoardServices

> `/System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41b00` | `0x41bf4` | **`+0xf4`** |
| `__TEXT.__objc_methlist` | `0x5b98` | `0x5ba8` | **`+0x10`** |
| `__DATA_CONST.__const` | `0xcb8` | `0xcc0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d60` | `0x1d68` | **`+0x8`** |

### Other Changes

```diff

-1072.0.0.0.0
+1078.0.0.0.0

-  Functions: 2328
-  Symbols:   4000
+  Functions: 2329
+  Symbols:   4001
Symbols:
+ +[RBSExtensionProcessIdentity _extensionIdentityFromDataRepresentation:correctedToInstanceUUID:]
Functions:
~ -[RBSExtensionProcessIdentity _copyWithCorrectedInstanceUUID:] : 372 -> 196
+ +[RBSExtensionProcessIdentity _extensionIdentityFromDataRepresentation:correctedToInstanceUUID:]
~ -[RBSExtensionProcessIdentity initWithDecodeFromJob:uuid:] : 456 -> 600
```
