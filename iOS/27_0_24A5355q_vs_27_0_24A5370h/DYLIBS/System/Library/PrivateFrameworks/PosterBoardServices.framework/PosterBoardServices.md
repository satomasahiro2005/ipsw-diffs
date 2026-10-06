## PosterBoardServices

> `/System/Library/PrivateFrameworks/PosterBoardServices.framework/PosterBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7da28` | `0x7de1c` | **`+0x3f4`** |
| `__TEXT.__unwind_info` | `0x1b30` | `0x1b90` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x37ae` | `0x37ee` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x10920` | `0x10948` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x52b8` | `0x52e0` | **`+0x28`** |
| `__TEXT.__cstring` | `0x6a9b` | `0x6abb` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xc30` | `0xc18` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2bc8` | `0x2bd8` | **`+0x10`** |

### Other Changes

```diff

-341.0.3.0.0
+344.0.101.0.0

-  Functions: 2688
-  Symbols:   3870
-  CStrings:  1090
+  Functions: 2693
+  Symbols:   3871
+  CStrings:  1092
Symbols:
+ -[PRSServer enterPosterSwitcherForRole:]
+ -[PRSService enterPosterSwitcherForRole:]
+ _OUTLINED_FUNCTION_19
+ _OUTLINED_FUNCTION_20
- _swift_retain_x19
- _swift_retain_x24
- _swift_retain_x28
CStrings:
+ "%{public}@ failed to acquire service interface: %{public}@"
+ "-[PRSServer enterPosterSwitcherForRole:]"
```
