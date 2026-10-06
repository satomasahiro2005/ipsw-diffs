## SpringBoardServices

> `/System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7a258` | `0x7a5ec` | **`+0x394`** |
| `__TEXT.__oslogstring` | `0x4719` | `0x4787` | **`+0x6e`** |
| `__TEXT.__objc_methlist` | `0x8a08` | `0x8a68` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x2968` | `0x29c0` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x25b30` | `0x25b70` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x3410` | `0x3448` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x3900` | `0x3928` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x28e8` | `0x2908` | **`+0x20`** |
| `__TEXT.__cstring` | `0xdc31` | `0xdc48` | **`+0x17`** |
| `__DATA.__bss` | `0x8f0` | `0x900` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x860` | `0x864` | **`+0x4`** |

### Other Changes

```diff

-4615.3.107.0.0
+4621.0.0.0.0

-  Functions: 4262
-  Symbols:   7874
-  CStrings:  2101
+  Functions: 4274
+  Symbols:   7887
+  CStrings:  2104
Symbols:
+ -[SBSHomeScreenService redo]
+ -[SBSHomeScreenService undo]
+ -[SBSWallpaperService displayContext]
+ -[SBSWallpaperService fetchAllLockScreenContentCutoutBoundsForType:orientation:displayContext:completionHandler:]
+ -[SBSWallpaperService fetchLockScreenContentCutoutBoundsForType:orientation:displayContext:completionHandler:]
+ -[SBSWallpaperService setDisplayContext:]
+ _OBJC_IVAR_$_SBSWallpaperService._displayContext
+ _SBLogAppRestrictionsOverlay
+ _SBLogAppRestrictionsOverlay.__logObj
+ _SBLogAppRestrictionsOverlay.onceToken
+ ___113-[SBSWallpaperService fetchAllLockScreenContentCutoutBoundsForType:orientation:displayContext:completionHandler:]_block_invoke
+ ___SBLogAppRestrictionsOverlay_block_invoke
+ ___block_descriptor_40_e8_32bs_e39_v40?0{CGRect={CGPoint=dd}{CGSize=dd}}8ls32l8
CStrings:
+ "AppRestrictionsOverlay"
+ "SBSHomeScreenService: failed redo request (no target)."
+ "SBSHomeScreenService: failed undo request (no target)."
```
