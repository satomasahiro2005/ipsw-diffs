## AskToMessages

> `/System/Library/Messages/iMessageApps/AskToMessages.bundle/AskToMessages`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17f28` | `0x17704` | **`-0x824`** |
| `__TEXT.__cstring` | `0x6b9` | `0x5b9` | **`-0x100`** |
| `__TEXT.__auth_stubs` | `0x1500` | `0x1430` | **`-0xd0`** |
| `__TEXT.__objc_stubs` | `0x720` | `0x680` | **`-0xa0`** |
| `__TEXT.__objc_methname` | `0x801` | `0x771` | **`-0x90`** |
| `__TEXT.__oslogstring` | `0xa5a` | `0xad9` | **`+0x7f`** |
| `__DATA_CONST.__auth_got` | `0xa88` | `0xa20` | **`-0x68`** |
| `__TEXT.__swift5_typeref` | `0x4a6` | `0x44c` | **`-0x5a`** |
| `__TEXT.__const` | `0x884` | `0x854` | **`-0x30`** |
| `__DATA.__objc_selrefs` | `0x238` | `0x210` | **`-0x28`** |
| `__DATA.__data` | `0x830` | `0x810` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x30d` | `0x32d` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x258` | `0x240` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x3f0` | `0x3e0` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x29c` | `0x2a8` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x200` | `0x1f8` | **`-0x8`** |
| `__TEXT.__swift5_capture` | `0x120` | `0x124` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-93.0.0.0.0
-  - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics
+96.0.0.0.0
+  - /System/Library/Frameworks/Contacts.framework/Contacts

-  - /System/Library/Frameworks/QuartzCore.framework/QuartzCore

+  - /System/Library/PrivateFrameworks/AskToPeopleBridge.framework/AskToPeopleBridge

-  Functions: 293
-  Symbols:   188
-  CStrings:  198
+  Functions: 288
+  Symbols:   178
+  CStrings:  188
Symbols:
+ _OBJC_CLASS_$_CNMutableContact
+ _swift_retain_x27
+ _swift_retain_x28
- _CGBitmapContextCreate
- _CGBitmapContextCreateImage
- _CGColorSpaceCreateDeviceRGB
- _CGImageGetColorSpace
- _CGImageGetHeight
- _CGImageGetWidth
- _OBJC_CLASS_$_CALayer
- _kCACornerCurveContinuous
- _kCAGravityResize
- _swift_release_x27
- _swift_retain_x22
- _swift_retain_x23
- _swift_retain_x24
CStrings:
+ "Failed to make mutable copy of contact for resizing; preserving original"
+ "Legacy people message using long form bubble"
+ "imageData"
+ "mutableCopy"
+ "setImageData:"
+ "showContent(for:isLegacyPeopleMessage:conversationContext:messageContext:presentationStyle:)"
- "AskToBuyActionApprove"
- "AskToBuyActionDecline"
- "AskToBuyRequestTitle"
- "com.apple.AskPermission.AskToBuy"
- "com.apple.askpermission.AskToResponseExtension"
- "com.apple.askpermissiond"
- "plus.arrow.trianglehead.clockwise"
- "renderInContext:"
- "setContents:"
- "setContentsGravity:"
- "setCornerCurve:"
- "setCornerRadius:"
- "setFrame:"
- "setGeometryFlipped:"
- "setMasksToBounds:"
- "showContent(for:conversationContext:messageContext:presentationStyle:)"
```
