## ChronoCore

> `/System/Library/PrivateFrameworks/ChronoCore.framework/ChronoCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42417c` | `0x424350` | **`+0x1d4`** |
| `__TEXT.__oslogstring` | `0x15b47` | `0x15c47` | **`+0x100`** |
| `__TEXT.__swift5_typeref` | `0xc457` | `0xc393` | **`-0xc4`** |
| `__TEXT.__eh_frame` | `0xc640` | `0xc6a8` | **`+0x68`** |
| `__AUTH_CONST.__const` | `0x138c8` | `0x13868` | **`-0x60`** |
| `__TEXT.__const` | `0x14908` | `0x148d8` | **`-0x30`** |
| `__TEXT.__swift5_capture` | `0x558c` | `0x556c` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x1dd8` | `0x1df0` | **`+0x18`** |
| `__TEXT.__cstring` | `0x6e4b` | `0x6e5b` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1f10` | `0x1f20` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x7f68` | `0x7f58` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0xa9f3` | `0xaa03` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x4540` | `0x4548` | **`+0x8`** |
| `__AUTH_CONST.__objc_const` | `0x187c0` | `0x187c8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1960` | `0x1968` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x7750` | `0x7758` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0xbc94` | `0xbc98` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x684` | `0x680` | **`-0x4`** |

### Other Changes

```diff

-740.0.0.0.0
+749.0.1.0.0

-  Functions: 11046
-  Symbols:   4498
-  CStrings:  1989
+  Functions: 11048
+  Symbols:   4493
+  CStrings:  1990
Symbols:
+ ___swift_closure_destructor.220Tm
+ ___swift_memcpy33_8
+ ___swift_project_boxed_opaque_existential_0Tm
+ _symbolic ___________p 9ChronoKit15ExtensionHidingP AA0C8ManagingP
- ___swift_closure_destructor.216Tm
- ___swift_closure_destructor.35Tm
- _symbolic _____ 10ChronoCore21MobileTimelineServiceC19ReloadBehaviorState33_FA00F2730F9D79EF75DE399C5A05AFB0LLV23ResolvedRefreshStrategyV
- _symbolic _____Sg 10ChronoCore21MobileTimelineServiceC19ReloadBehaviorState33_FA00F2730F9D79EF75DE399C5A05AFB0LLV23ResolvedRefreshStrategyV
- _symbolic ______p 10ChronoCore25TimelineRendererServicingP
- _symbolic _____y______y__________GG 7Combine10PublishersO6FilterV AA12AnyPublisherV 9ChronoKit28WidgetDescriptorsChangeEventV s5NeverO
- _symbolic _____y______y______y__________GG_____ySo19CHSWidgetDescriptorCGG 7Combine10PublishersO3MapV AC6FilterV AA12AnyPublisherV 9ChronoKit28WidgetDescriptorsChangeEventV s5NeverO AJ20DescriptorCollectionC
- _symbolic _____y______y______y______y__________GG_____ySo19CHSWidgetDescriptorCGGSo17OS_dispatch_queueCG 7Combine10PublishersO9ReceiveOnV AC3MapV AC6FilterV AA12AnyPublisherV 9ChronoKit28WidgetDescriptorsChangeEventV s5NeverO AL20DescriptorCollectionC
- _type_layout_string 10ChronoCore21MobileTimelineServiceC19ReloadBehaviorState33_FA00F2730F9D79EF75DE399C5A05AFB0LLV23ResolvedRefreshStrategyV
CStrings:
+ "Asked to reload placeholder widget: %{public}s for reason: %{public}s, but that's not currently supported."
+ "Setting extension hidden: %{bool,public}d for extensions: %{public}s"
+ "[%{public}@] Reload widget for reason: %{public}s, contentType: %{public}s"
+ "[%{public}@] Reload widget ignored because content type %{public}s is unhandled."
+ "[%{public}s] Received message to reload %{public}@ for reason: %{public}s, contentType: %{public}s"
+ "[%{public}s] Received message to reload if failed %{public}@ for reason: %{public}s, contentType: %{public}s"
+ "going from not disabled -> disabled"
+ "going from once/disabled -> not disabled/once"
+ "setExtensionHidden: Empty extension bundle identifiers array"
- "Failed to reload relevances for %{public}@: %{public}@"
- "Got updated descriptor collection with identities %{public}s"
- "Reloaded relevances for %{public}@"
- "[%{public}@] Reload widget for reason: %{public}s"
- "[%{public}@] Reload widget ignored because service doesn't support reloading."
- "[%{public}s] Received message to reload %{public}@ for reason: %{public}s"
- "once/disabled refresh strategy suppression"
- "refreshStrategySuppression"
```
