## VoiceMemos

> `/private/var/staged_system_apps/VoiceMemos.app/VoiceMemos`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f3700` | `0x1f4028` | **`+0x928`** |
| `__DATA.__data` | `0xe610` | `0xe770` | **`+0x160`** |
| `__DATA.__objc_data` | `0xa060` | `0x9f70` | **`-0xf0`** |
| `__DATA_CONST.__got` | `0x1c30` | `0x1d10` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x336b9` | `0x33779` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0xa874` | `0xa7ec` | **`-0x88`** |
| `__DATA_CONST.__const` | `0xd3c8` | `0xd350` | **`-0x78`** |
| `__TEXT.__objc_methlist` | `0x11d6c` | `0x11cf4` | **`-0x78`** |
| `__TEXT.__constg_swiftt` | `0xa8fc` | `0xa95c` | **`+0x60`** |
| `__TEXT.__cstring` | `0xbb69` | `0xbb09` | **`-0x60`** |
| `__TEXT.__objc_stubs` | `0x22040` | `0x220a0` | **`+0x60`** |
| `__DATA.__objc_const` | `0x1dd58` | `0x1dd98` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x4802` | `0x47c2` | **`-0x40`** |
| `__TEXT.__swift5_reflstr` | `0x6630` | `0x6670` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x1b94` | `0x1b58` | **`-0x3c`** |
| `__TEXT.__unwind_info` | `0x9648` | `0x9620` | **`-0x28`** |
| `__TEXT.__swift5_typeref` | `0x9e34` | `0x9e0e` | **`-0x26`** |
| `__TEXT.__auth_stubs` | `0x5bd0` | `0x5bf0` | **`+0x20`** |
| `__TEXT.__const` | `0x15a84` | `0x15aa4` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x5938` | `0x5950` | **`+0x18`** |
| `__DATA.__bss` | `0x155e0` | `0x155f0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2e00` | `0x2e10` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x38aa` | `0x38ba` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x808a` | `0x809a` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xa9b8` | `0xa9b0` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x21b0` | `0x21b8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x7d4` | `0x7cc` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x3d0` | `0x3cc` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x3e8` | `0x3e4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1431.0.0.0.0
+1433.0.0.0.0

-  Functions: 13353
-  Symbols:   3014
-  CStrings:  10265
+  Functions: 13341
+  Symbols:   3016
+  CStrings:  10263
Symbols:
+ _UIContentSizeCategoryCompareToCategory
+ _UIFontTextStyleFootnote
+ __UIUnlerp
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "@40@0:8@16@24d32"
+ "@72@0:8q16@24@32@40@48@56@64"
+ "CornobbleScrollAllRecordings"
+ "More Actions title"
+ "_currentLocationBasedName"
+ "_overviewWaveformHasBeginEndTimeLabels"
+ "_platterTimeLabelFontWithTextStyle:traitCollection:weight:"
+ "currentTraitCollection"
+ "init(with:composition:recordingID:)"
+ "initWithStyle:uiModelContainer:dependencyContainer:controlsActionHandler:renameRecordingHandler:presentationHelper:timeController:"
+ "preferredFontForTextStyle:weight:maximumContentSizeCategory:"
+ "preferredMonospacedDigitFontForTextStyle:weight:maximumContentSizeCategory:"
+ "rc_traitCollectionWithMaximumContentSizeCategory:"
+ "traitCollectionWithPreferredContentSizeCategory:"
- "%s -- No locations of interest discovered near current location."
- "-[RCApplicationModel insertRecordingWithAudioFile:duration:date:customTitleBase:uniqueID:error:]"
- "@64@0:8@16d24@32@40@48^@56"
- "More actions AX label"
- "ScrollAllRecordings"
- "VoiceMemos.RCLiveTranscription"
- "_platterTimeLabelFontWithTextStyle:traitCollection:"
- "bottomAccessoryMainContainerStackViewHeight"
- "bottomControlsContainerHeight"
- "currentLocationBasedName"
- "finalizeAndReturnTranscriptionDataWithCompletionHandler:"
- "hasBeginAndEndTimeLabelAtOverviewWaveform"
- "init(with:recordingID:)"
- "initWith:recordingID:"
- "recordingControlSectionHeight"
- "refreshWithComposition:"
```
