## VisionKitCore

> `/System/Library/PrivateFrameworks/VisionKitCore.framework/VisionKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe70bc` | `0xe7604` | **`+0x548`** |
| `__TEXT.__oslogstring` | `0x41a7` | `0x42a7` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0x19c0` | `0x1980` | **`-0x40`** |
| `__AUTH_CONST.__objc_const` | `0x311d0` | `0x31200` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x3c70` | `0x3c98` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x26e8` | `0x2708` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x9890` | `0x98a8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x10624` | `0x1063c` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x4380` | `0x4398` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1088` | `0x1090` | **`+0x8`** |

### Other Changes

```diff

-342.0.0.0.0
+344.0.0.0.0

-  Functions: 6776
-  Symbols:   10673
-  CStrings:  1620
+  Functions: 6780
+  Symbols:   10680
+  CStrings:  1625
Symbols:
+ -[VKAVCapture attachSessionToPreviewLayer:completion:]
+ -[VKAVCaptureFrameProvider _sessionAttachedToPreviewLayer]
+ ___54-[VKAVCapture attachSessionToPreviewLayer:completion:]_block_invoke
+ ___54-[VKAVCapture attachSessionToPreviewLayer:completion:]_block_invoke_2
+ ___58-[VKAVCaptureFrameProvider _sessionAttachedToPreviewLayer]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e21_v16?0"VKAVCapture"8ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
+ _dyld_program_sdk_at_least
- ___block_descriptor_56_e8_32s40bs_e5_v8?0ls32l8s40l8
CStrings:
+ "%@ preparation complete, attaching session to preview layer"
+ "%@ preparation complete2, startWhenReady=%d"
+ "%@ session attached to preview layer, now connecting sample buffer delegate"
+ "Prewarming with preheat"
+ "Prewarming with preheatFor:environmentBundleIdentifier:"
```
