## PosterBoardUIServices

> `/System/Library/PrivateFrameworks/PosterBoardUIServices.framework/PosterBoardUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x15018` | `0x15080` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x65c0` | `0x6600` | **`+0x40`** |
| `__TEXT.__text` | `0x89244` | `0x89284` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0x3060` | `0x3080` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3b89` | `0x3ba9` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3ab8` | `0x3ac8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x77c` | `0x780` | **`+0x4`** |

### Other Changes

```diff

-355.0.5.0.0
+355.0.8.0.0

-  Functions: 3553
-  Symbols:   5062
-  CStrings:  836
+  Functions: 3555
+  Symbols:   5065
+  CStrings:  837
Symbols:
+ -[_PRUISPosterStagedSceneSettings pui_renderSessionTimeoutInterval]
+ -[_PRUISPosterStagedSceneSettings pui_setRenderSessionTimeoutInterval:]
+ _OBJC_IVAR_$__PRUISPosterStagedSceneSettings._renderSessionTimeoutInterval
CStrings:
+ "pui_renderSessionTimeoutInterval"
```
