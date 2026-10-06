## libAccessibility.dylib

> `/usr/lib/libAccessibility.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37464` | `0x37a20` | **`+0x5bc`** |
| `__TEXT.__oslogstring` | `0x1611` | `0x182f` | **`+0x21e`** |
| `__AUTH_CONST.__cfstring` | `0x6f20` | `0x7000` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x97c0` | `0x9836` | **`+0x76`** |
| `__DATA_CONST.__objc_selrefs` | `0x598` | `0x5b8` | **`+0x20`** |
| `__DATA.__bss` | `0x1600` | `0x1608` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x148` | `0x150` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x368` | `0x360` | **`-0x8`** |
| `__TEXT.__const` | `0x208` | `0x210` | **`+0x8`** |

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  Functions: 1492
-  Symbols:   3253
-  CStrings:  1262
+  Functions: 1490
+  Symbols:   3252
+  CStrings:  1277
Symbols:
+ GCC_except_table1371
+ GCC_except_table1403
+ GCC_except_table1408
+ GCC_except_table1409
+ GCC_except_table1474
+ GCC_except_table1484
+ GCC_except_table1485
+ _OBJC_CLASS_$_NSDate
- GCC_except_table1373
- GCC_except_table1405
- GCC_except_table1410
- GCC_except_table1411
- GCC_except_table1478
- GCC_except_table1486
- GCC_except_table1487
- __AXSSetAppleTVRemoteForceLiveTVButtons
- __AXSSetAppleTVRemoteUsesSimpleGestures
Functions:
~ __AXSTripleClickCopyOptions : 1568 -> 2312
~ __AXSAssistiveTouchSetEnabled : 440 -> 1348
~ __AXSSetTripleClickOptions : 892 -> 796
~ __AXSLiveTranscriptionSetFontFamily : 24 -> 84
~ __AXSLiveTranscriptionSetTextColorData : 24 -> 28
~ __AXSLiveTranscriptionSetBackgroundColorData : 24 -> 28
- __AXSSetAppleTVRemoteUsesSimpleGestures
- __AXSSetAppleTVRemoteForceLiveTVButtons
~ _AXRuntimeCheck_SoundRecognitionMedinaKShotEnrollmentEnabled : 72 -> 116
CStrings:
+ "AssistiveTouchSettingsEvents"
+ "Removing AccessibilityReader triple click option, feature disabled: %@"
+ "Removing HoverText triple click option, feature disabled: %@"
+ "Removing LiveTranscription triple click option, feature disabled: %@"
+ "Removing NearbyDeviceControl triple click option, feature disabled: %@"
+ "Removing OnDeviceEyeTracking triple click option, feature disabled: %@"
+ "Removing TwiceRemoteScreen triple click option, feature disabled: %@"
+ "Setting AssistiveTouchEnabled to %{bool}d, requested by %{public}@ [%d], caller frames: %{public}@"
+ "Setting triple click options: previous: %@, new: %@, caller: %@"
+ "SoundDetection_Medina_KShotEnrollment"
+ "callerFrames"
+ "enabled"
+ "pid"
+ "process"
+ "timestamp"
+ "unknown"
- "Setting triple click options: %@"
```
