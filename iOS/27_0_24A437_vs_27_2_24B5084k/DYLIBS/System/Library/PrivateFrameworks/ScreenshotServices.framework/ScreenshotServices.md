## ScreenshotServices

> `/System/Library/PrivateFrameworks/ScreenshotServices.framework/ScreenshotServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e764` | `0x1e880` | **`+0x11c`** |
| `__TEXT.__oslogstring` | `0x1802` | `0x1813` | **`+0x11`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c98` | `0x1ca0` | **`+0x8`** |

### Other Changes

```diff

-447.100.0.0.0
+451.0.0.0.0
Functions:
~ ___113-[SSScreenCapturer _takeScreenshotWithOptionsCollection:serviceOptions:presentationOptions:appleInternalOptions:]_block_invoke : 548 -> 628
~ -[SSEnvironmentElement isAppLauncher] : 152 -> 176
~ -[SSEnvironmentDescription currentApplicationBundleID] : 120 -> 284
~ -[SSScreenCapturer _captureAndSendMetadataAndDocumentForEnvironmentDescription:metadataCaptureCompletion:] : 1196 -> 1212
CStrings:
+ "Sending env description for session %@: waitedMs=%.1f elementCount=%lu bundleID=%@ layoutDisplay=%@"
- "Sending env description for session %@: waitedMs=%.1f elementCount=%lu bundleID=%@"
```
