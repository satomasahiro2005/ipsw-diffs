## GuidedAccess

> `/System/Library/AccessibilityBundles/GuidedAccess.axuiservice/GuidedAccess`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f1b0` | `0x2f6fc` | **`+0x54c`** |
| `__TEXT.__oslogstring` | `0xec3` | `0x1244` | **`+0x381`** |
| `__TEXT.__objc_methname` | `0xc4fc` | `0xc5f6` | **`+0xfa`** |
| `__TEXT.__objc_stubs` | `0x8e20` | `0x8ee0` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x3e06` | `0x3e48` | **`+0x42`** |
| `__DATA.__objc_selrefs` | `0x2a68` | `0x2a98` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1b08` | `0x1b38` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x4f0` | `0x520` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x29e0` | `0x2a00` | **`+0x20`** |
| `__TEXT.__const` | `0x1a0` | `0x1b0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x36bc` | `0x36cc` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x24ee` | `0x24f1` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1061.0.0.0.0
+1064.0.0.0.0

+  - /System/Library/PrivateFrameworks/AACCore.framework/AACCore

-  Functions: 1176
-  Symbols:   662
-  CStrings:  2553
+  Functions: 1178
+  Symbols:   669
+  CStrings:  2569
Symbols:
+ _GAXUIMessageKeyShouldDriveSiriAssessmentRestriction
+ _MCFeatureControlCenterAllowed
+ _MCFeatureEmojiKeyboardAllowed
+ _MCFeatureKeyboardPeriodShortcutAllowed
+ _MCFeatureLiveVoicemailAllowed
+ _OBJC_CLASS_$_AEAssessmentModeRestrictionEnforcerProxy
+ _OBJC_CLASS_$_NSThread
CStrings:
+ "GAXUIServer dealloc starting (this is not expected to happen while the service is registered with AXUIServer, since GAXUIServer has no way to remove its scene for identifier %@ outside of this teardown path)"
+ "GAXUIServer init starting. Caller: %@"
+ "Received CompleteHidingWorkspaceAndEnterSession, clearing activeContentViewController %@. Note: this only removes the content view controller, it does not release the scene requested for identifier %@."
+ "Received CompleteHidingWorkspaceAndReturnToApplication, clearing activeContentViewController %@. Note: this only removes the content view controller, it does not release the scene requested for identifier %@."
+ "Siri assessment-mode restriction %{public}s failed: %{public}@"
+ "Siri assessment-mode restriction %{public}s succeeded"
+ "Unmanaged ASAM restriction state changed: enabled=%d shouldDriveSiri=%d"
+ "_changeUnmanagedASAMRestrictionStateEnabled:style:managedConfigurationSettings:shouldDriveSiriAssessmentRestriction:"
+ "_driveSiriAssessmentModeRestriction:"
+ "activeContentViewController changing from %@ to %@"
+ "callStackSymbols"
+ "com.apple.siri.assessment-mode-restriction"
+ "end"
+ "initWithMachServiceName:queue:"
+ "safeAreaLayoutGuide"
+ "should drive siri assessment restriction"
+ "shouldBeginRestrictingForAssessmentModeWithCompletion:"
+ "shouldEndRestrictingForAssessmentModeWithCompletion:"
+ "v40@0:8B16q20@28B36"
- "_changeUnmanagedASAMRestrictionStateEnabled:style:managedConfigurationSettings:"
- "allowKeyboardPeriodShortcut"
- "v36@0:8B16q20@28"
```
