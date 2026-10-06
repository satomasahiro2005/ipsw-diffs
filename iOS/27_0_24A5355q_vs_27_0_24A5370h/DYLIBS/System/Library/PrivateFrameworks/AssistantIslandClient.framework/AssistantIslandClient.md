## AssistantIslandClient

> `/System/Library/PrivateFrameworks/AssistantIslandClient.framework/AssistantIslandClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4fac0` | `0x50d80` | **`+0x12c0`** |
| `__TEXT.__oslogstring` | `0x57e` | `0x85e` | **`+0x2e0`** |
| `__DATA_CONST.__objc_selrefs` | `0xaa8` | `0xaf0` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x26cc` | `0x2684` | **`-0x48`** |
| `__TEXT.__eh_frame` | `0x1ae8` | `0x1b28` | **`+0x40`** |
| `__AUTH.__data` | `0x1488` | `0x1450` | **`-0x38`** |
| `__TEXT.__const` | `0x8514` | `0x8544` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x50a8` | `0x50d0` | **`+0x28`** |
| `__DATA.__data` | `0x2298` | `0x22c0` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0xca0` | `0xcc0` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x2ed8` | `0x2ef0` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x249a` | `0x24b0` | **`+0x16`** |
| `__TEXT.__swift5_capture` | `0x84c` | `0x860` | **`+0x14`** |
| `__TEXT.__cstring` | `0x1076` | `0x1066` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x18a8` | `0x1898` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x25c0` | `0x25d0` | **`+0x10`** |
| `__AUTH.__objc_data` | `0x2cd8` | `0x2ce0` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x3b8` | `0x3b0` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x19b0` | `0x19a8` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x18` | `0x14` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-60.105.0.0.0
+67.4.100.0.0

+  - /System/Library/PrivateFrameworks/SearchUI.framework/SearchUI

-  Functions: 3976
-  Symbols:   1707
-  CStrings:  113
+  Functions: 3985
+  Symbols:   1714
+  CStrings:  122
Symbols:
+ _OBJC_CLASS_$_SFButtonItem
+ _OBJC_CLASS_$_SearchUICommandEnvironment
+ _OBJC_CLASS_$_SearchUICommandHandler
+ _OBJC_CLASS_$_SearchUIRowModel
+ _associated conformance 21AssistantIslandClient22VoiceScenePresentation33_8898E8EEB6BFE17E5EE08E064017BD33LLV0A6UICore25PlatformViewRepresentableAA7SwiftUI06UIViewQ0
+ _associated conformance 21AssistantIslandClient23PromptScenePresentation33_2A59C839311F9EE9B0074627F29398A5LLV0A6UICore25PlatformViewRepresentableAA7SwiftUI06UIViewQ0
+ _objc_release_x9
+ _swift_retain_x27
+ _symbolic $s15AssistantUICore25PlatformViewRepresentableP
+ _symbolic So24SPUISearchViewControllerC
- __IVARS__TtC21AssistantIslandClient34CommonUILatencyStringUpdatedAction
- _symbolic $s21AssistantIslandClient25PlatformViewRepresentableP
- _symbolic 8ViewType_____Qz 21AssistantIslandClient25PlatformViewRepresentableP
CStrings:
+ "#islandAction inbound CommonUIDismissalRequestedAction"
+ "#islandAction inbound PromptPendingAction"
+ "#islandAction inbound TransientCanvasReadyAction hasCompletion=%{bool,public}d"
+ "#islandAction inbound VoicePendingAction requestInitiatedBringup=%{bool,public}d"
+ "#islandAction inbound VoiceStopAction"
+ "#islandAction outbound RequestDismissalAction reason=%{public}s"
+ "#islandAction outbound RequestPunchoutAction"
+ "#islandAction outbound RequestTransientCanvasAction hasCompletion=%{bool,public}d"
+ "#islandAction pendingResponsePromptAction orphan-timer expired (%{public}fs) — invalidating"
+ "#islandAction pendingResponseVoiceAction orphan-timer expired (%{public}fs) — invalidating"
- "slat"
```
