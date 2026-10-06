## SendLaterProvider

> `/System/Library/Messages/iMessageBalloons/SendLaterProvider.bundle/SendLaterProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6688` | `0x5c04` | **`-0xa84`** |
| `__TEXT.__objc_stubs` | `0x600` | `0x520` | **`-0xe0`** |
| `__TEXT.__auth_stubs` | `0x8b0` | `0x7e0` | **`-0xd0`** |
| `__TEXT.__oslogstring` | `0x1c3` | `0x133` | **`-0x90`** |
| `__TEXT.__objc_methname` | `0x214d` | `0x20cd` | **`-0x80`** |
| `__DATA_CONST.__auth_got` | `0x460` | `0x3f8` | **`-0x68`** |
| `__DATA_CONST.__const` | `0x268` | `0x218` | **`-0x50`** |
| `__DATA.__objc_selrefs` | `0x730` | `0x6f0` | **`-0x40`** |
| `__TEXT.__cstring` | `0x1e1` | `0x1a1` | **`-0x40`** |
| `__TEXT.__swift5_typeref` | `0x253` | `0x219` | **`-0x3a`** |
| `__DATA_CONST.__got` | `0x130` | `0xf8` | **`-0x38`** |
| `__DATA.__data` | `0x4d8` | `0x4b0` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x1e0` | `0x1c8` | **`-0x18`** |
| `__TEXT.__swift5_capture` | `0x50` | `0x40` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x98` | `0x90` | **`-0x8`** |
| `__TEXT.__const` | `0x258` | `0x250` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0xa9c` | `0xa94` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1486.100.5.2.1
+1487.100.6.2.2

-  - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

-  - /System/Library/PrivateFrameworks/IMSharedUtilities.framework/IMSharedUtilities

-  Functions: 142
-  Symbols:   151
-  CStrings:  422
+  Functions: 135
+  Symbols:   145
+  CStrings:  410
Symbols:
- _CGRectGetHeight
- _OBJC_CLASS_$_IMMetricsCollector
- _OBJC_CLASS_$_OS_dispatch_queue
- _OBJC_CLASS_$_UIScreen
- _OBJC_CLASS_$_UISheetPresentationControllerDetent
- _objc_retain_x26
CStrings:
- "Detected full-screen presentation of time picker. Dismissing. Detents: %s"
- "Dismissing programmatically due to a full-screen presentation."
- "FullScreenPresentation"
- "SendLaterTimePickerPresentation"
- "detents"
- "forceAutoBugCaptureWithSubType:errorPayload:type:context:"
- "frame"
- "mainScreen"
- "sharedInstance"
- "sheetPresentationController"
- "viewDidLayoutSubviews"
- "window"
```
