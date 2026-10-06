## Bridge

> `/private/var/staged_system_apps/Bridge.app/Bridge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x246484` | `0x247438` | **`+0xfb4`** |
| `__TEXT.__objc_methname` | `0x3da45` | `0x3df45` | **`+0x500`** |
| `__TEXT.__objc_stubs` | `0x22a60` | `0x22c20` | **`+0x1c0`** |
| `__TEXT.__oslogstring` | `0x15f9a` | `0x1611a` | **`+0x180`** |
| `__DATA.__objc_const` | `0x24008` | `0x24120` | **`+0x118`** |
| `__TEXT.__objc_methlist` | `0x16ba4` | `0x16c74` | **`+0xd0`** |
| `__DATA.__objc_selrefs` | `0xd510` | `0xd5c8` | **`+0xb8`** |
| `__TEXT.__gcc_except_tab` | `0x2a74` | `0x2af8` | **`+0x84`** |
| `__TEXT.__unwind_info` | `0x85a8` | `0x85e0` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x2c98` | `0x2cc8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xc050` | `0xc078` | **`+0x28`** |
| `__TEXT.__const` | `0x29216` | `0x29236` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1831e` | `0x1833e` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x8a49` | `0x8a29` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0x160c` | `0x1624` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_nlclslist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1372.0.0.0.0
+1377.1.0.0.0

-  Functions: 12634
-  Symbols:   3323
-  CStrings:  15647
+  Functions: 12656
+  Symbols:   3329
+  CStrings:  15688
Symbols:
+ _AVCaptureSessionInterruptionEndedNotification
+ _AVCaptureSessionInterruptionReasonKey
+ _AVCaptureSessionWasInterruptedNotification
+ _OBJC_CLASS_$_UILayoutGuide
+ _OBJC_CLASS_$_UITraitHorizontalSizeClass
+ _OBJC_CLASS_$_UITraitVerticalSizeClass
CStrings:
+ "@\"UILayoutGuide\""
+ "App Store auto-update follow-up changed, reloading root settings specifiers"
+ "COSAppStoreAutoUpdateFollowUpChangedNotification"
+ "COSCameraInterruptedByMultitasking"
+ "Camera interrupted because Bridge is not the sole foreground app; falling back to manual pairing"
+ "Capture session interrupted (reason %ld)"
+ "Capture session interruption ended"
+ "Enabled multitasking camera access: preview stays live when Bridge is not the sole foreground app"
+ "Multitasking camera access not supported: preview will be interrupted when Bridge is not the sole foreground app"
+ "T@\"NSLayoutConstraint\",&,N,V_contentLayoutGuideTopConstraint"
+ "T@\"NSLayoutConstraint\",&,N,V_contentLayoutGuideTopSafeAreaConstraint"
+ "T@\"NSLayoutConstraint\",&,N,V_preferredScannerSuperviewHeightConstraint"
+ "T@\"NSLayoutConstraint\",&,N,V_preferredScannerSuperviewWidthConstraint"
+ "T@\"UILayoutGuide\",&,N,V_contentLayoutGuide"
+ "T@\"UIWebView\",W,N,V_styledReleaseNotesWebView"
+ "_contentLayoutGuide"
+ "_contentLayoutGuideTopConstraint"
+ "_contentLayoutGuideTopSafeAreaConstraint"
+ "_preferredScannerSuperviewHeightConstraint"
+ "_preferredScannerSuperviewWidthConstraint"
+ "_sizeClassDidChange"
+ "_styledReleaseNotesWebView"
+ "addLayoutGuide:"
+ "appStoreAutoUpdateFollowUpChanged:"
+ "contentLayoutGuide"
+ "contentLayoutGuideTopConstraint"
+ "contentLayoutGuideTopSafeAreaConstraint"
+ "handleCameraInterruptedByMultitasking"
+ "handleSessionInterrupted:"
+ "handleSessionInterruptionEnded:"
+ "html { -webkit-text-size-adjust: 100%%; }\nbody {color: #FFFFFF !important;}\na:link {color: %@;}\n"
+ "isMultitaskingCameraAccessEnabled"
+ "isMultitaskingCameraAccessSupported"
+ "preferredScannerSuperviewHeightConstraint"
+ "preferredScannerSuperviewWidthConstraint"
+ "registerForTraitChanges:withAction:"
+ "setBounces:"
+ "setContentLayoutGuide:"
+ "setContentLayoutGuideTopConstraint:"
+ "setContentLayoutGuideTopSafeAreaConstraint:"
+ "setMultitaskingCameraAccessEnabled:"
+ "setPreferredScannerSuperviewHeightConstraint:"
+ "setPreferredScannerSuperviewWidthConstraint:"
+ "setStyledReleaseNotesWebView:"
+ "styledReleaseNotesWebView"
+ "updateViewConstraints"
+ "viewSafeAreaInsetsDidChange"
+ "\xb1"
- "App Store auto-update follow-up cleared, reloading root settings specifiers"
- "COSAppStoreAutoUpdateFollowUpClearedNotification"
- "Q32@0:8@\"RUIObjectModel\"16@\"RUIPage\"24"
- "appStoreAutoUpdateFollowUpCleared:"
- "document.body.style.color='#FFFFFF';"
- "html { -webkit-text-size-adjust: 100%%; }\na:link {color: %@;}\n"
- "supportedInterfaceOrientationsForObjectModel:page:"
```
