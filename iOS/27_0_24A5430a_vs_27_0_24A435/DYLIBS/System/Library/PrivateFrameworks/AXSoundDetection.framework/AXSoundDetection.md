## AXSoundDetection

> `/System/Library/PrivateFrameworks/AXSoundDetection.framework/AXSoundDetection`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7cc4` | `0x7e38` | **`+0x174`** |
| `__TEXT.__cstring` | `0x10af` | `0x1173` | **`+0xc4`** |
| `__AUTH_CONST.__cfstring` | `0x17e0` | `0x18a0` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x218` | `0x230` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x880` | `0x898` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x850` | `0x860` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x8c8` | `0x8d8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2b0` | `0x2b8` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 202
-  Symbols:   488
-  CStrings:  238
+  Functions: 205
+  Symbols:   494
+  CStrings:  244
Symbols:
+ -[AXSDSettings allowForwardingSoundRecognitionToSupportedWatch]
+ -[AXSDSettings setAllowForwardingSoundRecognitionToSupportedWatch:]
+ GCC_except_table87
+ GCC_except_table92
+ _AXSDSoundDetectionMessageKeyConfidence
+ _AXSDSoundDetectionMessageKeyType
+ __AXDetectionBodyLocalizedFormatFor
+ _kAXSAllowForwardingSoundRecognitionToSupportedWatch
- GCC_except_table86
- GCC_except_table91
CStrings:
+ "AXSAllowForwardingSoundRecognitionToSupportedWatch"
+ "AXSDSoundDetectionMessageKeyConfidence"
+ "AXSDSoundDetectionMessageKeyType"
+ "DetectionFromPhoneBody"
+ "DetectionFromWatchBody"
+ "SoundDetectionSupport-N237"
```
