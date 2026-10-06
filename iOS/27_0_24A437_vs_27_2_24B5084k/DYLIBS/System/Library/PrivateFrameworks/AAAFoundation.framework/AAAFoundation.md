## AAAFoundation

> `/System/Library/PrivateFrameworks/AAAFoundation.framework/AAAFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11df0` | `0x12138` | **`+0x348`** |
| `__AUTH_CONST.__objc_const` | `0x3e88` | `0x3f78` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x1b4c` | `0x1bd4` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x1280` | `0x12c8` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x1080` | `0x10a0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x1a4` | `0x1b8` | **`+0x14`** |
| `__TEXT.__cstring` | `0xfd8` | `0xfe5` | **`+0xd`** |
| `__DATA_CONST.__const` | `0xa70` | `0xa78` | **`+0x8`** |

### Other Changes

```diff

-117.0.0.0.0
+117.125.3.0.0

-  Functions: 682
-  Symbols:   1434
-  CStrings:  269
+  Functions: 693
+  Symbols:   1451
+  CStrings:  270
Symbols:
+ -[AAFTapToRadarHelper _ttrURLForRequest:]
+ -[AAFTapToRadarRequest attachmentURLs]
+ -[AAFTapToRadarRequest autoDiagnostics]
+ -[AAFTapToRadarRequest classification]
+ -[AAFTapToRadarRequest reproducibility]
+ -[AAFTapToRadarRequest setAttachmentURLs:]
+ -[AAFTapToRadarRequest setAutoDiagnostics:]
+ -[AAFTapToRadarRequest setClassification:]
+ -[AAFTapToRadarRequest setReproducibility:]
+ -[AAFTapToRadarRequest setSkipsConfirmationAlert:]
+ -[AAFTapToRadarRequest skipsConfirmationAlert]
+ GCC_except_table13
+ _OBJC_IVAR_$_AAFTapToRadarRequest._attachmentURLs
+ _OBJC_IVAR_$_AAFTapToRadarRequest._autoDiagnostics
+ _OBJC_IVAR_$_AAFTapToRadarRequest._classification
+ _OBJC_IVAR_$_AAFTapToRadarRequest._reproducibility
+ _OBJC_IVAR_$_AAFTapToRadarRequest._skipsConfirmationAlert
+ __AFTTRAttachmentsKey
- GCC_except_table11
CStrings:
+ "Attachments"
```
