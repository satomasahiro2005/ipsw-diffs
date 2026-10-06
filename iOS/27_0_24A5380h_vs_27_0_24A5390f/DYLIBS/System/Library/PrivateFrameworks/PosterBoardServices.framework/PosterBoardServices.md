## PosterBoardServices

> `/System/Library/PrivateFrameworks/PosterBoardServices.framework/PosterBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7df94` | `0x7eb44` | **`+0xbb0`** |
| `__AUTH_CONST.__cfstring` | `0x4a20` | `0x4ca0` | **`+0x280`** |
| `__TEXT.__cstring` | `0x6abb` | `0x6c8b` | **`+0x1d0`** |
| `__TEXT.__oslogstring` | `0x392e` | `0x39ee` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x1c70` | `0x1ce8` | **`+0x78`** |
| `__AUTH_CONST.__objc_const` | `0x10948` | `0x10998` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x2bd8` | `0x2c20` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0xc18` | `0xc40` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x52e0` | `0x5308` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0xfe0` | `0x1000` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1b98` | `0x1bb8` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x5c0` | `0x5c8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x720` | `0x728` | **`+0x8`** |

### Other Changes

```diff

-347.102.0.0.0
+350.1.100.0.0

-  Functions: 2694
-  Symbols:   3873
-  CStrings:  1094
+  Functions: 2702
+  Symbols:   3890
+  CStrings:  1118
Symbols:
+ -[PRSLockScreenColorConfigurationCache _stateCaptureDescription]
+ -[PRSLockScreenColorConfigurationCache dealloc]
+ -[PRSPosterGalleryItemOptions initWithModularComplications:modularLandscapeComplications:inlineComplication:allowsSystemSuggestedComplications:allowsSystemSuggestedComplicationsInLandscape:featuredConfidenceLevel:displayNameLocalizationKey:spokenNameLocalizationKey:descriptiveTextLocalizationKey:sectionSubtitle:hero:shouldShowAsShuffleStack:photoSubtype:focus:onlyEligibleForMadeForFocusSection:isOffloaded:]
+ -[PRSPosterGalleryItemOptions sectionSubtitle]
+ -[PRSPosterIconConfiguration briefStateCaptureLine]
+ GCC_except_table3
+ _BSLogAddStateCaptureBlockWithTitle
+ _NSSelectorFromString
+ _OBJC_IVAR_$_PRSLockScreenColorConfigurationCache._stateCaptureHandle
+ _OBJC_IVAR_$_PRSPosterGalleryItemOptions._sectionSubtitle
+ _PRSLockScreenColorConfigurationCacheErrorDomain
+ ___39-[PRSPosterGalleryItemOptions isEqual:]_block_invoke_16
+ ___58-[PRSLockScreenColorConfigurationCache initWithCachePath:]_block_invoke
+ ___block_descriptor_40_e8_32w_e5_8?0lw32l8
+ __dispatch_main_q
+ _close
+ _fgetxattr
+ _open
- -[PRSPosterGalleryItemOptions initWithModularComplications:modularLandscapeComplications:inlineComplication:allowsSystemSuggestedComplications:allowsSystemSuggestedComplicationsInLandscape:featuredConfidenceLevel:displayNameLocalizationKey:spokenNameLocalizationKey:descriptiveTextLocalizationKey:hero:shouldShowAsShuffleStack:photoSubtype:focus:onlyEligibleForMadeForFocusSection:isOffloaded:]
CStrings:
+ "  %@\n"
+ "%llu-%llu"
+ "-"
+ "<none>"
+ "?-?"
+ "@8@?0"
+ "Accent"
+ "Auto"
+ "Cache file missing"
+ "Clear"
+ "Color"
+ "N"
+ "OS version xattr missing or stale"
+ "PRSLockScreenColorConfigurationCache: file read failed: %{public}@"
+ "PRSLockScreenColorConfigurationCacheErrorDomain"
+ "PRSPosterIconConfiguration: %{public}@ type with non-nil accentColor — dropping color to preserve tint-set invariant"
+ "Unarchive returned unexpected root type (expected NSArray)"
+ "Y"
+ "file missing"
+ "in-memory-cache epoch=%llu configs=%lu\n"
+ "in-memory-cache=not-yet-loaded (read skipped to avoid main-thread I/O; on-disk cache above is canonical)\n"
+ "path=%@ exists=%@ size=%llu mtime=%@ epoch=%llu\n"
+ "sectionSubtitle"
+ "setSectionSubtitle:"
+ "uuid=%@ ver=%@ type=%@ variant=%@ tint=%@"
- "OS version mismatch or file missing"
```
