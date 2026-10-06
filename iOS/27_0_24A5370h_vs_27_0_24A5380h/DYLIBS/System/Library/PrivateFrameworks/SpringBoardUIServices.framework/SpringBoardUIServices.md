## SpringBoardUIServices

> `/System/Library/PrivateFrameworks/SpringBoardUIServices.framework/SpringBoardUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x5320` | `0x50a0` | **`-0x280`** |
| `__DATA_DIRTY.__objc_data` | `0xc80` | `0xeb0` | **`+0x230`** |
| `__TEXT.__text` | `0xa215c` | `0xa22f8` | **`+0x19c`** |
| `__AUTH_CONST.__objc_const` | `0x2d9f0` | `0x2d960` | **`-0x90`** |
| `__TEXT.__oslogstring` | `0x4771` | `0x47c5` | **`+0x54`** |
| `__AUTH_CONST.__cfstring` | `0xa280` | `0xa240` | **`-0x40`** |
| `__TEXT.__cstring` | `0xac2f` | `0xabf2` | **`-0x3d`** |
| `__TEXT.__const` | `0xae0` | `0xac8` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0xe67c` | `0xe68c` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x2be8` | `0x2be0` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x990` | `0x988` | **`-0x8`** |

### Other Changes

```diff

-4621.0.0.0.0
+4626.103.0.0.0

-  Functions: 4761
-  Symbols:   9381
-  CStrings:  1819
+  Functions: 4762
+  Symbols:   9376
+  CStrings:  1818
Symbols:
+ -[SBSUIApplicationResizeConstraintHelper _settingsForDisplayBounds:baseSettings:]
+ -[SBSUIApplicationResizeConstraintHelper initWithDisplayBounds:]
+ -[SBUIProudLockContainerViewController pendingStateTransitionCompletion]
+ -[SBUIProudLockContainerViewController setPendingStateTransitionCompletion:]
+ -[_SBSUICFUserNotificationContentRemoteContainerViewController dealloc]
+ _OBJC_IVAR_$_SBUIProudLockContainerViewController._pendingStateTransitionCompletion
+ __UIClamp
+ ___76-[SBUIProudLockContainerViewController setPendingStateTransitionCompletion:]_block_invoke
- -[SBSUIApplicationResizeConstraintHelper _settingsForWindowScene:baseSettings:]
- -[SBSUIApplicationResizeConstraintHelper initWithWindowScene:]
- -[SBUIProudLockContainerViewController setUnlockCompletion:]
- -[SBUIProudLockContainerViewController unlockCompletion]
- _OBJC_CLASS_$_SBUIAppHostingContinuitySceneSpecification
- _OBJC_IVAR_$_SBUIProudLockContainerViewController._unlockCompletion
- _OBJC_METACLASS_$_SBUIAppHostingContinuitySceneSpecification
- _SBUISceneLevelAppHostingContinuity
- _SBUISceneLevelResizableAppHosting
- _SBUIWindowSceneSessionRoleAppHostingContinuity
- __OBJC_CLASS_RO_$_SBUIAppHostingContinuitySceneSpecification
- __OBJC_METACLASS_RO_$_SBUIAppHostingContinuitySceneSpecification
- ___60-[SBUIProudLockContainerViewController setUnlockCompletion:]_block_invoke
CStrings:
+ "<%p> Remote container view controller deallocating (extension view controller: %p)."
- "SBUIWindowSceneSessionRoleAppHostingContinuity"
- "UIWindowScene"
```
