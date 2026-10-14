## PosterBoard

> `/System/Library/PrivateFrameworks/PosterBoard.framework/PosterBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x278034` | `0x279794` | **`+0x1760`** |
| `__TEXT.__oslogstring` | `0x1efaa` | `0x1f2ca` | **`+0x320`** |
| `__DATA.__data` | `0x6340` | `0x6460` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x6d78` | `0x6db8` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x9d48` | `0x9d78` | **`+0x30`** |
| `__TEXT.__cstring` | `0x14795` | `0x147c5` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xf02c` | `0xf05c` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x52d0` | `0x52a8` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0xc4e0` | `0xc500` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0xc0` | `0xd8` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x160` | `0x178` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x3e3e8` | `0x3e3f8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1dc0` | `0x1dd0` | **`+0x10`** |

### Other Changes

```diff

-355.2.10.100.0
+355.2.12.101.0

-  - /usr/lib/swift/libswiftAppleArchive.dylib

-  - /usr/lib/swift/libswiftGLKit.dylib

-  - /usr/lib/swift/libswiftMetalKit.dylib
-  - /usr/lib/swift/libswiftModelIO.dylib

-  - /usr/lib/swift/libswiftSceneKit.dylib

-  Functions: 10974
-  Symbols:   11137
-  CStrings:  4026
+  Functions: 11000
+  Symbols:   11132
+  CStrings:  4035
Symbols:
+ +[NSUserDefaults(PBFUtilities) pbf_ambientRepairHasOccurred]
+ +[NSUserDefaults(PBFUtilities) pbf_setAmbientRepairHasOccurred:]
+ -[PBFAmbientRoleCoordinator _ambientPublishedDescriptorsForLegacyDominoProvider:]
+ -[PBFAmbientRoleCoordinator _restoreMissingLegacyDominoAmbientPostersWithChangeHandler:outEvents:]
+ GCC_except_table118
+ ___81-[PBFAmbientRoleCoordinator _ambientPublishedDescriptorsForLegacyDominoProvider:]_block_invoke
- GCC_except_table116
- __swift_FORCE_LOAD_$_swiftAppleArchive
- __swift_FORCE_LOAD_$_swiftAppleArchive_$_PosterBoard
- __swift_FORCE_LOAD_$_swiftGLKit
- __swift_FORCE_LOAD_$_swiftGLKit_$_PosterBoard
- __swift_FORCE_LOAD_$_swiftMetalKit
- __swift_FORCE_LOAD_$_swiftMetalKit_$_PosterBoard
- __swift_FORCE_LOAD_$_swiftModelIO
- __swift_FORCE_LOAD_$_swiftModelIO_$_PosterBoard
- __swift_FORCE_LOAD_$_swiftSceneKit
- __swift_FORCE_LOAD_$_swiftSceneKit_$_PosterBoard
CStrings:
+ "AmbientStandByDowngradeRepairHasOccurred"
+ "[%{public}@] All legacy Domino posters confirmed present;"
+ "[%{public}@] Corrected editingBehavior on existing Clock poster against live descriptor"
+ "[%{public}@] Failed to build restored legacy Domino poster for provider %{public}@ (descriptor %{public}@): %{public}@"
+ "[%{public}@] Failed to correct editingBehavior on existing Clock poster: %{public}@"
+ "[%{public}@] Failed to reorder ambient posters after restoring legacy Domino posters: %{public}@"
+ "[%{public}@] Failed to restore missing legacy Domino poster for provider %{public}@ (descriptor %{public}@): %{public}@"
+ "[%{public}@] No extension store coordinator yet for legacy Domino provider %{public}@; will retry on a later finalize: %{public}@"
+ "[%{public}@] Restored missing legacy Domino poster for provider %{public}@ (descriptor %{public}@)"
```
