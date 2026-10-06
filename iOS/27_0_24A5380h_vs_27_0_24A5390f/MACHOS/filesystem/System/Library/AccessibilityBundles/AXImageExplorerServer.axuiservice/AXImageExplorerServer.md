## AXImageExplorerServer

> `/System/Library/AccessibilityBundles/AXImageExplorerServer.axuiservice/AXImageExplorerServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4fc7c` | `0x53fe8` | **`+0x436c`** |
| `__TEXT.__objc_stubs` | `0x7c0` | `0xb40` | **`+0x380`** |
| `__DATA_CONST.__const` | `0xfb0` | `0x12b0` | **`+0x300`** |
| `__DATA.__bss` | `0x1888` | `0x1b78` | **`+0x2f0`** |
| `__TEXT.__swift5_typeref` | `0x6fec` | `0x72da` | **`+0x2ee`** |
| `__TEXT.__objc_methname` | `0x1151` | `0x13c1` | **`+0x270`** |
| `__TEXT.__cstring` | `0xeab` | `0x110b` | **`+0x260`** |
| `__TEXT.__const` | `0x2744` | `0x2974` | **`+0x230`** |
| `__TEXT.__oslogstring` | `0x1039` | `0x1249` | **`+0x210`** |
| `__TEXT.__eh_frame` | `0x2464` | `0x2654` | **`+0x1f0`** |
| `__TEXT.__auth_stubs` | `0x27d0` | `0x2950` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x1160` | `0x1258` | **`+0xf8`** |
| `__DATA.__objc_selrefs` | `0x3e0` | `0x4d0` | **`+0xf0`** |
| `__TEXT.__swift5_capture` | `0x394` | `0x460` | **`+0xcc`** |
| `__DATA_CONST.__auth_got` | `0x13f0` | `0x14b0` | **`+0xc0`** |
| `__DATA.__objc_data` | `0x278` | `0x328` | **`+0xb0`** |
| `__TEXT.__objc_classname` | `0x1d5` | `0x225` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x634` | `0x681` | **`+0x4d`** |
| `__DATA.__objc_const` | `0x978` | `0x9c0` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x8d4` | `0x90c` | **`+0x38`** |
| `__TEXT.__swift5_assocty` | `0x238` | `0x270` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x3fc` | `0x41c` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x617` | `0x637` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x1b8` | `0x1d4` | **`+0x1c`** |
| `__DATA_CONST.__auth_ptr` | `0x7c0` | `0x7d8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x980` | `0x998` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0xb8` | `0xd0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x50` | `0x64` | **`+0x14`** |
| `__DATA.__data` | `0x1eb0` | `0x1ea0` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x598` | `0x5a8` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0xc0` | `0xcc` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x74` | `0x7c` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x8c` | `0x94` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-3234.5.0.0.0
+3237.1.0.0.0

+  - /System/Library/Frameworks/Photos.framework/Photos

-  Functions: 1248
-  Symbols:   245
-  CStrings:  394
+  Functions: 1342
+  Symbols:   260
+  CStrings:  451
Symbols:
+ _AXImageExplorerGetSilentMode
+ _NSUnderlyingErrorKey
+ _OBJC_CLASS_$_NSAttributedString
+ _OBJC_CLASS_$_PHAsset
+ _OBJC_CLASS_$_PHAssetChangeRequest
+ _OBJC_CLASS_$_PHAssetCreationRequest
+ _OBJC_CLASS_$_PHPhotoLibrary
+ _OBJC_CLASS_$_UITextView
+ _OBJC_METACLASS_$_UITextView
+ _UIAccessibilityAnnouncementNotification
+ _UIAccessibilityPostNotification
+ _UIEdgeInsetsZero
+ _swift_continuation_throwingResume
+ _swift_continuation_throwingResumeWithError
+ _swift_getObjCClassFromMetadata
+ _swift_retain_x22
- _pow
CStrings:
+ "@24@0:8@16"
+ "@56@0:8{CGRect={CGPoint=dd}{CGSize=dd}}16@48"
+ "AXImageExplorerServer/AXImageExplorerReadOnlyText.swift"
+ "Attempting to save Image Description into asset."
+ "Could not find photo asset to save description into."
+ "Failed to generate image description. %@"
+ "Failed to generate image description: empty result."
+ "Failed to save photo: %s."
+ "Failed to write description into photo asset. domain=%s code=%ld userInfo=%s underlying=%s."
+ "Fatal error"
+ "IMAGE_EXPLORER_COPY_IMAGE"
+ "IMAGE_EXPLORER_SAVE_DESCRIPTION_FAILED"
+ "IMAGE_EXPLORER_SAVE_TO_PHOTOS"
+ "IMAGE_EXPLORER_SAVE_TO_PHOTOS_FAILED"
+ "IMAGE_EXPLORER_SAVE_TO_PHOTOS_SUCCESS"
+ "IMAGE_EXPLORER_TRANSCRIPT_DESCRIPTION"
+ "PHAssetChangeRequest accessibilityDescription SPI unavailable; cannot save description."
+ "Photo library access denied for Save to Photos."
+ "Photo library write access denied for Save Image Description. status=%ld."
+ "Save Image Description requires a locally available photo asset."
+ "Will not proceed with ask about image. Guardrail evaluation failed: %@"
+ "Will not proceed with presenting Image Explorer. Guardrail evaluation failed: %@"
+ "Will not proceed with speak description. Guardrail evaluation failed: %@"
+ "Will not proceed with user prompt. Guardrail evaluation failed: %@"
+ "_TtCV21AXImageExplorerServer27AXImageExplorerReadOnlyText16ReadOnlyTextView"
+ "accessibilityDescription"
+ "addResourceWithType:data:options:"
+ "auxiliarySession"
+ "changeRequestForAsset:"
+ "clearColor"
+ "code"
+ "creationRequestForAsset"
+ "domain"
+ "embedDescription(_:intoAssetWithLocalIdentifier:)"
+ "fetchAssetsWithLocalIdentifiers:options:"
+ "firstObject"
+ "imageExplorerDescription"
+ "init(coder:) has not been implemented"
+ "initWithCoder:"
+ "initWithFrame:textContainer:"
+ "initWithString:attributes:"
+ "instancesRespondToSelector:"
+ "invalidateIntrinsicContentSize"
+ "performChanges:completionHandler:"
+ "photo.on.rectangle"
+ "requestAuthorizationForAccessLevel:handler:"
+ "setAccessibilityDescription:"
+ "setAttributedText:"
+ "setBackgroundColor:"
+ "setData:forPasteboardType:"
+ "setEditable:"
+ "setLineFragmentPadding:"
+ "setScrollEnabled:"
+ "setSelectable:"
+ "setTextContainerInset:"
+ "setUserInteractionEnabled:"
+ "setValue:forKey:"
+ "sharedPhotoLibrary"
+ "sizeThatFits:"
+ "square.and.arrow.down"
+ "textContainer"
+ "userInfo"
+ "v16@?0q8"
+ "v20@?0B8@\"NSError\"12"
- "Attempting to speak Image Description."
- "Error generating image description. %@"
- "Failed to generate image description."
- "Will not proceed with ask about image. Image contains sensitive content."
- "Will not proceed with presenting Image Explorer. Image contains sensitive content."
- "Will not proceed with speak description. Image contains sensitive content."
- "Will not proceed with user prompt. Image contains sensitive content."
```
