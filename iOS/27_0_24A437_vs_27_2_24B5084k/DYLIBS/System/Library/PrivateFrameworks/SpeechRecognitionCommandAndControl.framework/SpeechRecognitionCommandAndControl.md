## SpeechRecognitionCommandAndControl

> `/System/Library/PrivateFrameworks/SpeechRecognitionCommandAndControl.framework/SpeechRecognitionCommandAndControl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12315c` | `0x123748` | **`+0x5ec`** |
| `__TEXT.__cstring` | `0x9667` | `0x9787` | **`+0x120`** |
| `__AUTH_CONST.__cfstring` | `0x9960` | `0x9a00` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x1220` | `0x11c0` | **`-0x60`** |
| `__TEXT.__gcc_except_tab` | `0x252c` | `0x2578` | **`+0x4c`** |
| `__AUTH_CONST.__const` | `0x4e20` | `0x4dd8` | **`-0x48`** |
| `__AUTH.__objc_data` | `0x47f8` | `0x4828` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x20e8` | `0x2110` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x11a88` | `0x11aa8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x7f50` | `0x7f70` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xc0b4` | `0xc0cc` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1f18` | `0x1f28` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xaa8` | `0xab8` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0xdb8` | `0xdc8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1014` | `0x1020` | **`+0xc`** |
| `__DATA.__data` | `0x32f8` | `0x3300` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x43e0` | `0x43e8` | **`+0x8`** |

### Other Changes

```diff

-188.1.0.0.0
+191.2.0.0.0

-  Functions: 7366
-  Symbols:   14844
-  CStrings:  1862
+  Functions: 7368
+  Symbols:   14854
+  CStrings:  1869
Symbols:
+ -[CACDisplayManager _sceneManagerForModalAlerts]
+ -[CACUtilityToolServer disambiguationLabelDetails]
+ _$s12VoiceControl10VCSettingsC27vciScreenshotStorageEnabledSbvg
+ _$s14VoiceControlUI20VCScrollElementModelC5frame5state16scrollDirections6number15layoutDirection12screenBounds0N11CornerRadiiACSo6CGRectV_AC5StateOShyAA0D0V0M0OGSi05SwiftC006LayoutM0OAlT09RectanglepQ0VSgtcfc
+ _$s34SpeechRecognitionCommandAndControl30CACLabeledScrollOverlayManagerC021startDelayedDimmingOfgH033_E0ABF0E32BFDEA5F715ABE5D1599EC8ALLyyFyyXEfU_yyScMYccfU_yyXEfU_
+ _$s34SpeechRecognitionCommandAndControl30CACLabeledScrollOverlayManagerC021startDelayedDimmingOfgH033_E0ABF0E32BFDEA5F715ABE5D1599EC8ALLyyFyyXEfU_yyScMYccfU_yyXEfU_TA
+ _$s34SpeechRecognitionCommandAndControl30CACLabeledScrollOverlayManagerC04showgH0yyFSo17CACViewController_So06UIViewL0CXcycfU_TA
+ _$s34SpeechRecognitionCommandAndControl37CACLabeledScrollOverlayViewControllerC11windowScene33_133984795F26B76EAEB42E1349C7DCDFLLSo08UIWindowL0CvpWvd
+ _$s34SpeechRecognitionCommandAndControl37CACLabeledScrollOverlayViewControllerC11windowSceneACSo08UIWindowL0C_tcfC
+ _$s34SpeechRecognitionCommandAndControl37CACLabeledScrollOverlayViewControllerC11windowSceneACSo08UIWindowL0C_tcfCTj
+ _$s34SpeechRecognitionCommandAndControl37CACLabeledScrollOverlayViewControllerC11windowSceneACSo08UIWindowL0C_tcfCTq
+ _$s34SpeechRecognitionCommandAndControl37CACLabeledScrollOverlayViewControllerC11windowSceneACSo08UIWindowL0C_tcfc
+ _$s34SpeechRecognitionCommandAndControl37CACLabeledScrollOverlayViewControllerC11windowSceneACSo08UIWindowL0C_tcfcTo
+ _$s34SpeechRecognitionCommandAndControl37CACLabeledScrollOverlayViewControllerC22overlayCoordinateSpace33_133984795F26B76EAEB42E1349C7DCDFLLSo012UICoordinateM0_pvg
+ _$s34SpeechRecognitionCommandAndControl37CACLabeledScrollOverlayViewControllerC24overlayScreenCornerRadii33_133984795F26B76EAEB42E1349C7DCDFLL7SwiftUI09RectanglemN0VSgvg
+ _$s7SwiftUI20RectangleCornerRadiiV7topLeft0F5Right06bottomH00iG0AC12CoreGraphics7CGFloatV_A3JtcfC
+ _NSStringFromRect
- -[CACDisplayManager _sceneForModalAlerts]
- _$s12VoiceControl10VCSettingsC05voiceB31IntelligenceScreenshotDebuggingSbvg
- _$s14VoiceControlUI20VCScrollElementModelC5frame5state16scrollDirections6number15layoutDirectionACSo6CGRectV_AC5StateOShyAA0D0V0M0OGSi05SwiftC006LayoutM0Otcfc
- _$s34SpeechRecognitionCommandAndControl30CACLabeledScrollOverlayManagerC021startDelayedDimmingOfgH033_E0ABF0E32BFDEA5F715ABE5D1599EC8ALLyyFyyXEfU_yyScMYccfU_yycfU_
- _$s34SpeechRecognitionCommandAndControl30CACLabeledScrollOverlayManagerC021startDelayedDimmingOfgH033_E0ABF0E32BFDEA5F715ABE5D1599EC8ALLyyFyyXEfU_yyScMYccfU_yycfU_TA
- _$s34SpeechRecognitionCommandAndControl37CACLabeledScrollOverlayViewControllerC011setNumberedgI8ElementsyySayAA011CACNumberedgI7ElementCGF05VoiceE2UI08VCScrollO5ModelCAFXEfU_
- _$s34SpeechRecognitionCommandAndControl37CACLabeledScrollOverlayViewControllerC18screenOrientedRect33_133984795F26B76EAEB42E1349C7DCDFLL4fromSo6CGRectVAH_tF
CStrings:
+ "DisambiguationLabels"
+ "ElementFrame"
+ "LabelFrame"
+ "SpeechRecognitionCommandAndControl.CACLabeledScrollOverlayViewController"
+ "SpeechRecognitionCommandAndControl/CACLabeledScrollOverlayViewController.swift"
+ "UserNotification.VCIScreenshotStorage.Body"
+ "UserNotification.VCISensitiveLogging.Body"
```
