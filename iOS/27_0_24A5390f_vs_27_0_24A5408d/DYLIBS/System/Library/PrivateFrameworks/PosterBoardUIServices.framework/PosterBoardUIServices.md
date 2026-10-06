## PosterBoardUIServices

> `/System/Library/PrivateFrameworks/PosterBoardUIServices.framework/PosterBoardUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x88c90` | `0x89244` | **`+0x5b4`** |
| `__TEXT.__oslogstring` | `0x44bf` | `0x454f` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x3080` | `0x3060` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xdc8` | `0xde0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1298` | `0x12a8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x3b99` | `0x3b89` | **`-0x10`** |

### Other Changes

```diff

-350.1.100.0.0
+355.0.5.0.0

-  Functions: 3554
-  Symbols:   5060
+  Functions: 3553
+  Symbols:   5062
Symbols:
+ _OBJC_CLASS_$_FBSOrientationObserver
+ _PRUISAmbientOrientationForCurrentDevice
+ _PRUISResolveInterfaceOrientation
- _PRUISPosterSceneSettingsApplyIdealizedDateComponents
CStrings:
+ "PRUISResolveInterfaceOrientation: no resolvable orientation; flooring to the per-role device default to avoid AlwaysAll scene-update fault"
- "contentsURLIsReachable"
```
