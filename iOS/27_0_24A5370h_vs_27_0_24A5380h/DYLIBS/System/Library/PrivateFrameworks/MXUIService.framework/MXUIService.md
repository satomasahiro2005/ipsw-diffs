## MXUIService

> `/System/Library/PrivateFrameworks/MXUIService.framework/MXUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x94c8` | `0xa0f4` | **`+0xc2c`** |
| `__TEXT.__const` | `0x140` | `0xe8` | **`-0x58`** |
| `__AUTH_CONST.__cfstring` | `0x380` | `0x3c0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x1a8` | `0x178` | **`-0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x960` | `0x990` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x17a0` | `0x17c8` | **`+0x28`** |
| `__TEXT.__cstring` | `0x917` | `0x93b` | **`+0x24`** |
| `__TEXT.__objc_methlist` | `0xb04` | `0xb24` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x188` | `0x198` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xa8` | `0xac` | **`+0x4`** |
| `__TEXT.__oslogstring` | `0x87a` | `0x87b` | **`+0x1`** |

### Other Changes

```diff

-360.63.1.11.2
+360.66.1.11.1

+  - /System/Library/Frameworks/UniformTypeIdentifiers.framework/UniformTypeIdentifiers

+  - /System/Library/PrivateFrameworks/IconServices.framework/IconServices

-  Functions: 209
-  Symbols:   464
-  CStrings:  100
+  Functions: 211
+  Symbols:   469
+  CStrings:  102
Symbols:
+ -[MXUIServiceBanner deriveDeviceSymbol]
+ -[MXUIService_BannerUIDelegate showReceiverEnabledBanner:completionHandler:]
+ -[MXUIService_BannerUIDelegate showSpeakerEnabledBanner:completionHandler:]
+ _OBJC_CLASS_$_ISSymbol
+ _OBJC_CLASS_$_UTType
+ _OBJC_IVAR_$_MXUIServiceBanner._bannerStyle
+ _UIFontWeightRegular
- -[MXUIService_BannerUIDelegate showAudioMovedBanner:completionHandler:]
- _UIFontWeightSemibold
CStrings:
+ "-MXUIServiceBanner- %s: Audio moved banner styles require Jindo path — skipping non-Jindo layout"
+ "AUDIO_MOVED_TO_RECEIVER"
+ "iPhone"
+ "speaker.wave.3.fill"
- "-MXUIServiceBanner- %s: MXBannerStyleAudioMoved requires Jindo path — skipping non-Jindo layout"
- "speaker.wave.3"
```
