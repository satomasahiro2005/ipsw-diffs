## MagnifierAngel

> `/Applications/MagnifierAngel.app/MagnifierAngel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x81990` | `0x84260` | **`+0x28d0`** |
| `__DATA.__data` | `0x2ae8` | `0x2be8` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x16fd` | `0x17fd` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x3dbd` | `0x3e9d` | **`+0xe0`** |
| `__DATA.__objc_const` | `0x23f0` | `0x24c0` | **`+0xd0`** |
| `__TEXT.__eh_frame` | `0x47d4` | `0x489c` | **`+0xc8`** |
| `__TEXT.__auth_stubs` | `0x3300` | `0x33a0` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0x16c0` | `0x1760` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x18fe` | `0x197e` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x1a59` | `0x1ac9` | **`+0x70`** |
| `__TEXT.__objc_classname` | `0x65e` | `0x6be` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1d50` | `0x1da8` | **`+0x58`** |
| `__DATA_CONST.__auth_got` | `0x1988` | `0x19d8` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x1100` | `0x1140` | **`+0x40`** |
| `__DATA.__objc_data` | `0x13c8` | `0x1400` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x1460` | `0x1490` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0xba0` | `0xbc8` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x2c60` | `0x2c38` | **`-0x28`** |
| `__TEXT.__swift5_typeref` | `0x70a0` | `0x70c6` | **`+0x26`** |
| `__TEXT.__swift_as_ret` | `0x174` | `0x184` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xc40` | `0xc34` | **`-0xc`** |
| `__DATA_CONST.__got` | `0xb00` | `0xb08` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xa8` | `0xb0` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xf4` | `0xf8` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x190` | `0x18c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-281.0.0.0.0
+283.0.0.0.0

-  Functions: 2123
-  Symbols:   1429
-  CStrings:  970
+  Functions: 2142
+  Symbols:   1440
+  CStrings:  987
Symbols:
+ _$s10Foundation11JSONDecoderC6decode_4fromxxm_AA4DataVtKSeRzlFTj
+ _$s10Foundation11JSONDecoderCACycfc
+ _$s10Foundation11JSONDecoderCMa
+ _$s16MagnifierSupport12MAGARServiceC18isARSessionStartedSbvgTj
+ _$s16MagnifierSupport19TranscriptViewModelC19activeRecaptureTaskScTyyts5NeverOGSgvgTj
+ _$s16MagnifierSupport19TranscriptViewModelC19activeRecaptureTaskScTyyts5NeverOGSgvsTj
+ _$s16MagnifierSupport19TranscriptViewModelC19cancelInflightTasksyyFTj
+ _$s16MagnifierSupport26MAGVQAOnboardingControllerC13dismissAction9tintColorACyyc_So7UIColorCtcfc
+ _$s16MagnifierSupport26MAGVQAOnboardingControllerCMa
+ _$sSS10FoundationE4data5using20allowLossyConversionAA4DataVSgSSAAE8EncodingV_SbtF
+ _$sSbSEsWP
+ _$sSbSesWP
+ _AXDeviceHasGreyMatterEnabled
+ _OBJC_CLASS_$_NSUserDefaults
- _$s16MagnifierSupport12MAGARServiceC9arSessionSo9ARSessionCSgvsTj
- _$s16MagnifierSupport21MAGOutputAnnouncementO22automaticFlashlightOffyA2CmFWC
- _$s16MagnifierSupport21MAGOutputAnnouncementO28tooDarkAutomaticFlashlightOnyA2CmFWC
CStrings:
+ "Cannot present VQA onboarding: no active angel window scene"
+ "Door announcement skipped: scene unchanged (%ld consecutive)"
+ "People announcement skipped: scene unchanged (%ld consecutive)"
+ "Text detection skipped: scene unchanged (%ld consecutive)"
+ "_TtC14MagnifierAngelP33_5B3A2CD46AE5ECB7CE5FC70846377D6B22MAGFrameChangeDetector"
+ "askMagnifierUsageConfirmed"
+ "com.apple.Accessibility.Magnifier"
+ "consecutiveSkipped"
+ "doorAnnouncementChangeDetector"
+ "imageCaptionChangeDetector"
+ "initWithSuiteName:"
+ "lastFingerprint"
+ "maxConsecutiveSkipped"
+ "peopleAnnouncementChangeDetector"
+ "presentLiveRecognitionAskOnboarding()"
+ "presentedViewController"
+ "setModalInPresentation:"
+ "setValue:forKey:"
+ "stringForKey:"
+ "textDetectionChangeDetector"
+ "tintColor"
- "consecutiveSkippedCaptionFrames"
- "lastCaptionedFrameFingerprint"
- "maxConsecutiveSkippedFrames"
- "torchMode"
```
