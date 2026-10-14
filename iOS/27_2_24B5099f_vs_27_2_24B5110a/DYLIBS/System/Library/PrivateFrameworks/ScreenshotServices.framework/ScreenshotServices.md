## ScreenshotServices

> `/System/Library/PrivateFrameworks/ScreenshotServices.framework/ScreenshotServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e884` | `0x1e7e4` | **`-0xa0`** |
| `__TEXT.__oslogstring` | `0x1813` | `0x17fa` | **`-0x19`** |
| `__DATA_CONST.__got` | `0x6e8` | `0x6e0` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1ca0` | `0x1c98` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x265c` | `0x2654` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xb98` | `0xb90` | **`-0x8`** |

### Other Changes

```diff

-452.1.2.0.0
+452.1.3.100.0

-  Functions: 982
-  Symbols:   2123
-  CStrings:  488
+  Functions: 981
+  Symbols:   2122
+  CStrings:  487
Symbols:
- -[SSDittoRemoteConnection preheatDittoProcess]
Functions:
~ -[SSScreenCapturer _preheatAndTakeScreenshotIfPossibleWithOptionsCollection:presentationOptions:appleInternalOptions:] : 848 -> 840
- -[SSDittoRemoteConnection preheatDittoProcess]
CStrings:
- "Preheating Ditto process"
```
