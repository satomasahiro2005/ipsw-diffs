## ScreenSharingKit

> `/System/Library/PrivateFrameworks/ScreenSharingKit.framework/ScreenSharingKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2615ec` | `0x267f64` | **`+0x6978`** |
| `__TEXT.__eh_frame` | `0x18138` | `0x18878` | **`+0x740`** |
| `__TEXT.__cstring` | `0x9145` | `0x96c5` | **`+0x580`** |
| `__TEXT.__swift_as_cont` | `0x1910` | `0x17c4` | **`-0x14c`** |
| `__TEXT.__unwind_info` | `0x8e78` | `0x8f10` | **`+0x98`** |
| `__TEXT.__constg_swiftt` | `0x88f0` | `0x885c` | **`-0x94`** |
| `__AUTH_CONST.__objc_const` | `0xab20` | `0xaba8` | **`+0x88`** |
| `__AUTH.__data` | `0x8c18` | `0x8b98` | **`-0x80`** |
| `__TEXT.__const` | `0x19654` | `0x195f4` | **`-0x60`** |
| `__AUTH.__objc_data` | `0x2b40` | `0x2af0` | **`-0x50`** |
| `__AUTH_CONST.__const` | `0x10a90` | `0x10ae0` | **`+0x50`** |
| `__DATA.__bss` | `0x1d780` | `0x1d730` | **`-0x50`** |
| `__DATA.__data` | `0x57f8` | `0x57b0` | **`-0x48`** |
| `__TEXT.__swift_as_entry` | `0x9d4` | `0xa1c` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x3d30` | `0x3d68` | **`+0x38`** |
| `__TEXT.__swift_as_ret` | `0xa70` | `0xaa4` | **`+0x34`** |
| `__TEXT.__oslogstring` | `0xb9c5` | `0xb9e5` | **`+0x20`** |
| `__DATA.__common` | `0x278` | `0x288` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x7932` | `0x7936` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-114.44.0.0.0
+114.48.0.0.0

-  Functions: 9655
-  Symbols:   3410
-  CStrings:  1552
+  Functions: 9612
+  Symbols:   3408
+  CStrings:  1573
Symbols:
+ ___swift_closure_destructor.125Tm
+ ___swift_closure_destructor.131Tm
+ ___swift_closure_destructor.240Tm
+ _symbolic _______________Xj r0_lSci_px7ElementRts_q_7FailureRtsXPXGMq 16ScreenSharingKit21ControlMessengerStateO s5NeverO
+ _symbolic _____ySDy__________G_____G 7Combine19CurrentValueSubjectC 16ScreenSharingKit15MediaStreamTypeO AD04MockhI0C s5NeverO
+ _symbolic _____ySay_____G_____G 7Combine19CurrentValueSubjectC 10Foundation4DataV s5NeverO
+ _symbolic _____y_____Sg_____G 7Combine19CurrentValueSubjectC 16ScreenSharingKit24MockControlMessageStreamC s5NeverO
+ _symbolic _____y_____Sg_____G 7Combine19CurrentValueSubjectC 16ScreenSharingKit27MockContinuityClientSessionC s5NeverO
- ___swift_closure_destructor.113Tm
- ___swift_closure_destructor.119Tm
- ___swift_closure_destructor.241Tm
- _symbolic SDy__________G 16ScreenSharingKit15MediaStreamTypeO AA04MockdE0C
- _symbolic _____Sg 16ScreenSharingKit24MockControlMessageStreamC
- _symbolic _____Sg 16ScreenSharingKit27MockContinuityClientSessionC
- _symbolic _____ySDy__________GG 7Combine9PublishedV 16ScreenSharingKit15MediaStreamTypeO AD04MockfG0C
- _symbolic _____ySay_____GG 7Combine9PublishedV 10Foundation4DataV
- _symbolic _____y_____SgG 7Combine9PublishedV 16ScreenSharingKit24MockControlMessageStreamC
- _symbolic _____y_____SgG 7Combine9PublishedV 16ScreenSharingKit27MockContinuityClientSessionC
CStrings:
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/ScreenSharingKit/ScreenSharingKit/Mocks/MediaTransport/MockContinuityClientSession.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/ScreenSharingKit/ScreenSharingKit/Mocks/MediaTransport/MockMediaTransportClientSessionVendor.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/ScreenSharingKit/ScreenSharingKit/Playback/PlaybackServer.swift"
+ "Activating underlying ControlMessageSession"
+ "Activation complete"
+ "ControlMessageSession activated, beginning monitoring"
+ "Finished reconfiguring playback primitives"
+ "Finished setting up AccessibilityMessage monitor"
+ "Finished setting up DragAndDropEvent monitor"
+ "Finished setting up DrawEvent monitor"
+ "Finished setting up HIDMessage monitor"
+ "Finished setting up RTIMessage monitor"
+ "Finished setting up SystemGestureEvent monitor"
+ "Finished setting up buffered sender"
+ "Finished setting up client StatusEvent monitor"
+ "PlaybackServer received ControlMessengerSession state %{public}s"
+ "Session is already invalidated. Ignoring"
+ "activateSession()"
+ "createContinuityClientSession(device:telemetry:)"
+ "monitorSession(with:)"
+ "reconfigurePlaybackPrimitives(for:)"
+ "sessionActivated()"
- "Session is already in a terminal state. Ignoring"
```
