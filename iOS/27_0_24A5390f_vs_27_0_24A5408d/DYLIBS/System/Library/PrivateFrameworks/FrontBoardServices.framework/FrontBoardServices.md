## FrontBoardServices

> `/System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x987d4` | `0x98a4c` | **`+0x278`** |
| `__AUTH_CONST.__cfstring` | `0xa280` | `0xa2e0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x8638` | `0x8688` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x100b8` | `0x100f8` | **`+0x40`** |
| `__TEXT.__cstring` | `0xc079` | `0xc0b0` | **`+0x37`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d48` | `0x3d68` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x3110` | `0x3128` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2ac8` | `0x2ad8` | **`+0x10`** |

### Other Changes

```diff

-1150.0.0.0.0
+1153.0.0.0.0

-  Functions: 4371
-  Symbols:   6487
-  CStrings:  1935
+  Functions: 4380
+  Symbols:   6495
+  CStrings:  1938
Symbols:
+ -[FBSSceneAction abortForUsageViolation:]
+ -[FBSSceneSettingsCore defaultWatchdogBehavior]
+ -[FBSSceneSettingsCore setDefaultWatchdogBehavior:]
+ -[FBSSceneSnapshotAction abortForUsageViolation:]
+ -[FBSSceneSnapshotRequestAction abortForUsageViolation:]
+ -[_FBSTestExitAction abortForUsageViolation:]
+ _NSStringFromFBSDefaultWatchdogBehavior
+ ___BSSafeCast
CStrings:
+ "FBSSceneActivityModeIsValid(activityMode)"
+ "always"
+ "never"
```
