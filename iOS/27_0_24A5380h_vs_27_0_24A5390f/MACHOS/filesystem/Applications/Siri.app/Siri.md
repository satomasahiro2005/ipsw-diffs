## Siri

> `/Applications/Siri.app/Siri`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xefca8` | `0xf0b5c` | **`+0xeb4`** |
| `__TEXT.__objc_methname` | `0x2b5cf` | `0x2b6bf` | **`+0xf0`** |
| `__DATA_CONST.__const` | `0x4cf8` | `0x4d88` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0xc08` | `0xc88` | **`+0x80`** |
| `__TEXT.__cstring` | `0x24370` | `0x243dd` | **`+0x6d`** |
| `__TEXT.__objc_methtype` | `0xaf31` | `0xaf71` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1b460` | `0x1b4a0` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x12bc` | `0x12fc` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x6ec` | `0x6b8` | **`-0x34`** |
| `__DATA.__objc_const` | `0x10bb8` | `0x10be8` | **`+0x30`** |
| `__TEXT.__const` | `0x30b4` | `0x30e4` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x19c7` | `0x19f1` | **`+0x2a`** |
| `__TEXT.__objc_methlist` | `0xe308` | `0xe330` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x8fa8` | `0x8fc8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x3910` | `0x3930` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x24e8` | `0x2504` | **`+0x1c`** |
| `__DATA.__data` | `0x4768` | `0x4780` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x3020` | `0x3010` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x2616` | `0x2622` | **`+0xc`** |
| `__DATA.__objc_data` | `0x4b10` | `0x4b18` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x1820` | `0x1818` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x118` | `0x11c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
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
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.55.26.0.0
+3600.55.30.0.0

-  Functions: 5192
-  Symbols:   1861
-  CStrings:  9005
+  Functions: 5191
+  Symbols:   1860
+  CStrings:  9014
Symbols:
+ _$s7SwiftUI9UnitPointVN
- _$sBi32_WV
- _swift_retain_x25
CStrings:
+ "@\"<SFCardResourceLoader>\"16@0:8"
+ "Attending window elapsed, but dismissal was paused. Waiting for request end signal"
+ "CalendarUIPlugin"
+ "NotebookUIPlugin"
+ "] SiriDirectedSpeech: resuming and canceling any deferred dismissal."
+ "] Speech detected; pausing auto-dismissal until the turn resolves."
+ "] Turn resolved not-for-Siri; flushing the dismissal deferred while speaking."
+ "] Turn resolved not-for-Siri; re-arming attending window from now."
+ "] Turn resolved not-for-Siri; un-pausing. No window pending."
+ "_showWaveform"
+ "attendingDismissalGate"
+ "cardLoader"
+ "isLinwoodEnabled"
+ "siriSessionSetReplayCaptureRequested:toPath:"
+ "startReplayCaptureToPath:"
+ "stopReplayCapture"
+ "v28@0:8B16@\"NSURL\"20"
+ "v28@0:8B16@20"
- "Cancel any scheduled attending window closure and pending autodismiss due to SiriDirectedSpeech"
- "Cease attending due to speech mitigation"
- "Extending attending window by "
- "Speech detected but attending window already extended once; ignoring"
- "Speech detected with no active attending window; ignoring"
- "_waveFormOpacity"
- "extendAttendingWindowForSpeechDetectedIfEligible()"
- "s due to speech detected (one-time)"
- "speechDetectedExtensionUsed"
```
