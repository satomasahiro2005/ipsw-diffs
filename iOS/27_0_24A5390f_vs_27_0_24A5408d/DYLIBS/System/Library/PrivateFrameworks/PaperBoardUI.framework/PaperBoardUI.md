## PaperBoardUI

> `/System/Library/PrivateFrameworks/PaperBoardUI.framework/PaperBoardUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77b54` | `0x78af4` | **`+0xfa0`** |
| `__TEXT.__oslogstring` | `0x4363` | `0x47a0` | **`+0x43d`** |
| `__AUTH_CONST.__cfstring` | `0x5f00` | `0x6000` | **`+0x100`** |
| `__TEXT.__cstring` | `0x7a98` | `0x7b16` | **`+0x7e`** |
| `__AUTH_CONST.__objc_const` | `0x19378` | `0x193b8` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x5140` | `0x5160` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x970c` | `0x972c` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2898` | `0x28b8` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xc30` | `0xc4c` | **`+0x1c`** |
| `__TEXT.__const` | `0x828` | `0x838` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x9b4` | `0x9bc` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x890` | `0x898` | **`+0x8`** |

### Other Changes

```diff

-350.1.100.0.0
+355.0.5.0.0

-  Functions: 3751
-  Symbols:   6090
-  CStrings:  1406
+  Functions: 3760
+  Symbols:   6098
+  CStrings:  1425
Symbols:
+ -[PBUIPosterVariantViewController _addStateCaptureHandlers]
+ -[PBUIPosterVariantViewController _completePendingProminentColorFetchesAfterFailedSnapshot]
+ -[PBUIPosterWallpaperViewController _activeStylesDescription]
+ GCC_except_table112
+ GCC_except_table127
+ GCC_except_table36
+ GCC_except_table66
+ GCC_except_table96
+ _OBJC_CLASS_$_FBSOrientationObserver
+ _OBJC_IVAR_$_PBUIPosterVariantViewController._stateCaptureHandles
+ _OBJC_IVAR_$_PBUIPosterViewController._homeWallpaperStyle
+ _PBUIInitialOrientationForCurrentDevice
+ ___59-[PBUIPosterVariantViewController _addStateCaptureHandlers]_block_invoke
- GCC_except_table109
- GCC_except_table56
- GCC_except_table58
- GCC_except_table60
- GCC_except_table93
CStrings:
+ "%@[%@]=%@ "
+ "(none)"
+ "Aug  4 2026 09:38:10"
+ "A\xf0q"
+ "Could not read snapshot: %{public}@ (url=%{public}@)"
+ "PBUIPosterVariant[%@] - %p"
+ "[%{public}@] WIPE cache (orientation rotate -> %ld)"
+ "[%{public}@] WIPE cache (pathProvider rotate): old=%{public}@ new=%{public}@"
+ "[%{public}@] WIPE cache + on-disk RuntimeSnapshots (CLEAR_ALL notification); sender=%{public}@"
+ "[%{public}@] cacheIdentifier ROTATED (new empty cache checked out): %{public}@ -> %{public}@"
+ "[%{public}@] setActiveStyle: %{public}@ -> %{public}@ (contentHidden=%{BOOL}d)"
+ "[%{public}@] snapshot failed; completing %lu pending prominent color fetch(es) with %{public}@"
+ "[home] BLACK-SNAPSHOT-RISK: showsSnapshot=YES but snapshotSourceValid=NO (empty snapshot -> black); reflectsLock=%{BOOL}d portalProvider=%{public}@"
+ "[home] NEAR-BLACK snapshot committed valid (avgColor=%{public}@) -> showing black; please file a radar to SpringBoard"
+ "[home] _updateRotationForOrientation: orientation was Unknown; flooring to Portrait to avoid AlwaysAll scene-update fault"
+ "activeStyles"
+ "contentHidden"
+ "loaded snapshot %{public}@ (%.0f x %.0f)"
+ "setActiveStyle:%{public}@ forVariant:%{public}@ (lockShadow=%{public}@ homeShadow=%{public}@ parentActiveStyle=%{public}@ activeVariant=%{public}@)"
+ "snapshotSource"
+ "snapshotSourceValid"
+ "snapshotViewHidden"
+ "\xf0\xf0a"
- "A\xf0a"
- "Could not read snapshot: %{public}@"
- "Jul 13 2026 21:41:04"
- "\xf0\xf0Q"
```
