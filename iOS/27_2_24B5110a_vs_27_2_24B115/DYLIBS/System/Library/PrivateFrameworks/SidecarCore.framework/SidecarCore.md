## SidecarCore

> `/System/Library/PrivateFrameworks/SidecarCore.framework/SidecarCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13c0c` | `0x13c70` | **`+0x64`** |
| `__AUTH_CONST.__objc_const` | `0x2a70` | `0x2aa0` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x1500` | `0x1520` | **`+0x20`** |
| `__TEXT.__cstring` | `0x113a` | `0x1157` | **`+0x1d`** |
| `__TEXT.__objc_methlist` | `0x1760` | `0x1778` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xc48` | `0xc58` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x198` | `0x19c` | **`+0x4`** |

### Other Changes

```diff

-  Functions: 615
-  Symbols:   1257
-  CStrings:  243
+  Functions: 617
+  Symbols:   1260
+  CStrings:  244
Symbols:
+ -[SidecarDisplayConfig setSupportsSystemGestureRouting:]
+ -[SidecarDisplayConfig supportsSystemGestureRouting]
+ _OBJC_IVAR_$_SidecarDisplayConfig._supportsSystemGestureRouting
CStrings:
+ "supportsSystemGestureRouting"
```
