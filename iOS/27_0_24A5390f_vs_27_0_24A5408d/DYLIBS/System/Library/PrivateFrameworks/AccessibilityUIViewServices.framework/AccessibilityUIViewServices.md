## AccessibilityUIViewServices

> `/System/Library/PrivateFrameworks/AccessibilityUIViewServices.framework/AccessibilityUIViewServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x720` | `0x7cc` | **`+0xac`** |
| `__AUTH_CONST.__cfstring` | `0x120` | `0x140` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x28` | `0x48` | **`+0x20`** |
| `__TEXT.__cstring` | `0x142` | `0x162` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x18` | `0x28` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x20` | `0x28` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x194` | `0x19c` | **`+0x8`** |

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

+  - /System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices

-  Functions: 25
-  Symbols:   95
-  CStrings:  10
+  Functions: 26
+  Symbols:   100
+  CStrings:  11
Symbols:
+ -[AXVSBaseService sb_usesSceneBasedRemoteAlert]
+ _AXVSRemoteAlertServiceClassNameKey
+ _OBJC_CLASS_$_LSApplicationIdentity
+ _OBJC_CLASS_$_RBSProcessIdentity
+ _objc_release_x23
CStrings:
+ "AXVSRemoteAlertServiceClassName"
```
