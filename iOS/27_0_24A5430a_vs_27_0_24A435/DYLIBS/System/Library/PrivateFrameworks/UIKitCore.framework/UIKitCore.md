## UIKitCore

> `/System/Library/PrivateFrameworks/UIKitCore.framework/UIKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bcb540` | `0x1bca50c` | **`-0x1034`** |
| `__TEXT.__oslogstring` | `0x54c60` | `0x54bbf` | **`-0xa1`** |
| `__DATA.__bss` | `0x3ddd8` | `0x3dd38` | **`-0xa0`** |
| `__AUTH_CONST.__cfstring` | `0xb3760` | `0xb3700` | **`-0x60`** |
| `__TEXT.__cstring` | `0x101b2a` | `0x101adc` | **`-0x4e`** |
| `__DATA_CONST.__const` | `0x3ebf8` | `0x3ec20` | **`+0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0x41f8` | `0x41d0` | **`-0x28`** |
| `__AUTH_CONST.__const` | `0x5bd58` | `0x5bd78` | **`+0x20`** |
| `__TEXT.__const` | `0x4c6a8` | `0x4c6c8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x8648` | `0x8630` | **`-0x18`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x2e20` | `0x2e08` | **`-0x18`** |
| `__DATA_DIRTY.__bss` | `0x15d50` | `0x15d60` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x71f90` | `0x71f80` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x8f98` | `0x8fa0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x95c30` | `0x95c38` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 181272
-  Symbols:   228739
-  CStrings:  33774
+  Functions: 181273
+  Symbols:   228722
+  CStrings:  33769
Symbols:
+ _OBJC_CLASS_$_FBSDeviceEmulationConfiguration
+ ___67-[_UIScreenComplexBoundingPathUtilities _loadBitmapForScreen:type:]_block_invoke
+ ____alwaysIgnoreHIDEdgeFlags_block_invoke
+ ___block_descriptor_56_e8_32s_e28_B24?0{_UIIntegralPoint=qq}8ls32l8
+ _activeKeyboard
- __UIKBHTVerifyFrameworkDepth
- __verifyClient.didReport
- _acceptAutocorrection._UIKBHT_hit
- _activeKeyboardSceneDelegate._UIKBHT_hit
- _addSubview:._UIKBHT_hit
- _autocorrectionController._UIKBHT_hit
- _candidateController._UIKBHT_hit
- _candidateViewController._UIKBHT_hit
- _compatibilityViewController._UIKBHT_hit
- _hitTest:withEvent:.onceToken
- _inlineTextCompletionController._UIKBHT_hit
- _inputManager._UIKBHT_hit
- _predictionViewController._UIKBHT_hit
- _predictiveViewController._UIKBHT_hit
- _remoteKeyboardWindowForScene:create:._UIKBHT_hit
- _remoteTextInputPartner._UIKBHT_hit
- _rootViewController._UIKBHT_hit
- _sharedInstance._UIKBHT_hit
- _strncmp
- _swift_retain_x12
- _thread_stack_pcs
- _window._UIKBHT_hit
CStrings:
+ "B24@?0{_UIIntegralPoint=qq}8"
+ "FeedbackFCSBehavior"
- "%{public}@ Called into an unapproved SPI."
- "/System/Library/"
- "Unknown UIKeyboardViewController client (bundleID=%@)"
- "Verify UIKeyboardViewController client (bundleID=%@, isKnown=%s)"
- "com.apple.ContactsUI.MonogramPosterExtension"
- "com.apple.QuickboardViewService"
- "keyboard_spi_caller_verification"
```
