## SharedWithYouCore

> `/System/Library/Frameworks/SharedWithYouCore.framework/SharedWithYouCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12824` | `0x129fc` | **`+0x1d8`** |
| `__AUTH_CONST.__objc_const` | `0x3008` | `0x3068` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x1a78` | `0x1aa8` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x800` | `0x820` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xb98` | `0xbb8` | **`+0x20`** |
| `__TEXT.__cstring` | `0xb1f` | `0xb2f` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x148` | `0x150` | **`+0x8`** |

### Other Changes

```diff

-217.100.1.0.0
+217.200.21.0.0

-  Functions: 520
-  Symbols:   1172
-  CStrings:  113
+  Functions: 524
+  Symbols:   1178
+  CStrings:  114
Symbols:
+ -[SWCollaborationOptionsGroup isReadOnly]
+ -[SWCollaborationOptionsGroup setReadOnly:]
+ -[SWCollaborationShareOptions isReadOnly]
+ -[SWCollaborationShareOptions setReadOnly:]
+ _OBJC_IVAR_$_SWCollaborationOptionsGroup._readOnly
+ _OBJC_IVAR_$_SWCollaborationShareOptions._readOnly
CStrings:
+ "readOnly"
```
