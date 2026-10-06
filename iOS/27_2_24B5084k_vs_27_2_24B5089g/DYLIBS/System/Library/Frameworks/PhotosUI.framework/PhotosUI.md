## PhotosUI

> `/System/Library/Frameworks/PhotosUI.framework/PhotosUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43358` | `0x45040` | **`+0x1ce8`** |
| `__TEXT.__eh_frame` | `0x70c` | `0x884` | **`+0x178`** |
| `__AUTH_CONST.__const` | `0x2180` | `0x2298` | **`+0x118`** |
| `__DATA_DIRTY.__objc_data` | `0xf0` | `0x1e0` | **`+0xf0`** |
| `__AUTH.__objc_data` | `0x20a8` | `0x1fc8` | **`-0xe0`** |
| `__TEXT.__swift5_typeref` | `0xc28` | `0xcd0` | **`+0xa8`** |
| `__AUTH_CONST.__auth_got` | `0xa38` | `0xac0` | **`+0x88`** |
| `__TEXT.__unwind_info` | `0x1980` | `0x1a08` | **`+0x88`** |
| `__TEXT.__const` | `0x3018` | `0x3088` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x4c0` | `0x528` | **`+0x68`** |
| `__TEXT.__cstring` | `0x4cc4` | `0x4d24` | **`+0x60`** |
| `__DATA.__data` | `0x1bf8` | `0x1c48` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0xb71` | `0xbc1` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x6fc8` | `0x7008` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x628` | `0x668` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x2170` | `0x2198` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0xc40` | `0xc58` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x28` | `0x3c` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x2c` | `0x34` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x4` | `0xc` | **`+0x8`** |

### Other Changes

```diff

-916.40.110.0.0
+916.45.110.0.0

+  - /System/Library/Frameworks/SwiftUI.framework/SwiftUI

-  Functions: 3008
-  Symbols:   2946
-  CStrings:  559
+  Functions: 3045
+  Symbols:   2955
+  CStrings:  560
Symbols:
+ _OBJC_CLASS_$_PHAssetCollection
+ _swift_release_x9
+ _swift_retain_x24
+ _symbolic Ig_
+ _symbolic ScTyyt_____GSg s5NeverO
+ _symbolic _____XDXMT 8PhotosUI23PVSClientViewControllerC
+ _symbolic _____yAAy_____y_____ACG_____G_____y_____GG 7SwiftUI15ModifiedContentV AA12ProgressViewV AA05EmptyF0V AA16_FlexFrameLayoutV AA24_BackgroundStyleModifierV AA5ColorV
+ _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
+ _symbolic _____y_____yABy_____y_____ADG_____G_____y_____GGG 7SwiftUI19UIHostingControllerC AA15ModifiedContentV AA12ProgressViewV AA05EmptyH0V AA16_FlexFrameLayoutV AA24_BackgroundStyleModifierV AA5ColorV
+ _symbolic _____y_____y_____ACG_____G 7SwiftUI15ModifiedContentV AA12ProgressViewV AA05EmptyF0V AA16_FlexFrameLayoutV
- _OUTLINED_FUNCTION_91
CStrings:
+ "User does not have permission to add content to the shared album with identifier: "
```
