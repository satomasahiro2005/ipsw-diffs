## DocumentManagerCore

> `/System/Library/PrivateFrameworks/DocumentManagerCore.framework/DocumentManagerCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x71554` | `0x72588` | **`+0x1034`** |
| `__TEXT.__cstring` | `0x4fda` | `0x518a` | **`+0x1b0`** |
| `__AUTH_CONST.__objc_const` | `0x6dc8` | `0x6f50` | **`+0x188`** |
| `__AUTH_CONST.__cfstring` | `0x30a0` | `0x3200` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x4872` | `0x4992` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x4478` | `0x4540` | **`+0xc8`** |
| `__DATA_CONST.__objc_selrefs` | `0x29b8` | `0x2a38` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x438` | `0x4a8` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x1e38` | `0x1e88` | **`+0x50`** |
| `__DATA.__data` | `0x1118` | `0x1158` | **`+0x40`** |
| `__AUTH.__data` | `—` | `0x28` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x1960` | `0x1968` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x740` | `0x748` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1a0` | `0x1a8` | **`+0x8`** |

### Other Changes

```diff

-401.0.0.0.0
+401.1.5.0.0

-  Functions: 2926
-  Symbols:   3052
-  CStrings:  897
+  Functions: 2951
+  Symbols:   3069
+  CStrings:  914
Symbols:
+ +[DOCAXIdentifier galleryPickerStatusLabel]
+ +[DOCAXIdentifier galleryPickerWindowWidthLabel]
+ +[DOCAXIdentifier inlineRenameOverlay]
+ +[DOCAXIdentifier navigationBarActionForActionIdentifier:]
+ +[DOCAXIdentifier pickerDismissButton]
+ +[DOCAXIdentifier saveToFilesLoadingView]
+ +[_DOCNavigationButtonAXIdentifier dismiss]
+ _DOCUserDefaultsStateRestorationFailedLaunchCount
+ _OBJC_CLASS_$_DOCStateRestorationCrashGuard
+ _OBJC_METACLASS_$_DOCStateRestorationCrashGuard
+ __CLASS_METHODS_DOCStateRestorationCrashGuard
+ __CLASS_PROPERTIES_DOCStateRestorationCrashGuard
+ __DATA_DOCStateRestorationCrashGuard
+ __INSTANCE_METHODS_DOCStateRestorationCrashGuard
+ __IVARS_DOCStateRestorationCrashGuard
+ __METACLASS_DATA_DOCStateRestorationCrashGuard
+ __PROPERTIES_DOCStateRestorationCrashGuard
CStrings:
+ "%{public}s: %ld launches in a row crashed before %{public}s was usable. Suppressing state restoration for this launch."
+ "%{public}s: launch attempt %ld of %ld for %{public}s. Restoring state."
+ "%{public}s: launch is healthy. Clearing the failed launch count."
+ "DOCUserDefaultsStateRestorationFailedLaunchCount"
+ "DocumentManagerCore_Private.DOCStateRestorationCrashGuard"
+ "FilesUIGallery"
+ "Should not be requesting favorite rank for SMB node"
+ "Should not be setting favorite rank for SMB node"
+ "beginLaunchAttempt(forHostIdentifier:)"
+ "dismiss"
+ "dismissButton"
+ "finishLaunchAttempt()"
+ "inlineRenameOverlay"
+ "navBarAction"
+ "pickerStatusLabel"
+ "pickerWindowWidthLabel"
+ "saveToFilesLoadingView"
```
