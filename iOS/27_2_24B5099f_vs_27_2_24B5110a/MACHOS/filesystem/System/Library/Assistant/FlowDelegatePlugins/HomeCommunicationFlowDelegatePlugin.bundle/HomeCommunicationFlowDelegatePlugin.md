## HomeCommunicationFlowDelegatePlugin

> `/System/Library/Assistant/FlowDelegatePlugins/HomeCommunicationFlowDelegatePlugin.bundle/HomeCommunicationFlowDelegatePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x90ef0` | `0x99d00` | **`+0x8e10`** |
| `__DATA.__bss` | `0x9f80` | `0xb300` | **`+0x1380`** |
| `__TEXT.__const` | `0x73f8` | `0x7dd8` | **`+0x9e0`** |
| `__TEXT.__eh_frame` | `0x5520` | `0x5c70` | **`+0x750`** |
| `__TEXT.__oslogstring` | `0x593e` | `0x605e` | **`+0x720`** |
| `__DATA_CONST.__const` | `0x55b0` | `0x5c10` | **`+0x660`** |
| `__TEXT.__unwind_info` | `0x2b60` | `0x2ed0` | **`+0x370`** |
| `__TEXT.__cstring` | `0x2932` | `0x2be2` | **`+0x2b0`** |
| `__TEXT.__swift5_reflstr` | `0x2178` | `0x2408` | **`+0x290`** |
| `__DATA.__data` | `0x4680` | `0x48c0` | **`+0x240`** |
| `__TEXT.__swift5_typeref` | `0x2680` | `0x28be` | **`+0x23e`** |
| `__TEXT.__swift5_fieldmd` | `0x1f80` | `0x20f4` | **`+0x174`** |
| `__TEXT.__auth_stubs` | `0x2f80` | `0x3090` | **`+0x110`** |
| `__TEXT.__swift5_assocty` | `0x648` | `0x720` | **`+0xd8`** |
| `__TEXT.__constg_swiftt` | `0x2fac` | `0x3064` | **`+0xb8`** |
| `__TEXT.__swift5_capture` | `0x578` | `0x628` | **`+0xb0`** |
| `__TEXT.__swift5_proto` | `0x544` | `0x5e0` | **`+0x9c`** |
| `__DATA_CONST.__auth_got` | `0x17c8` | `0x1850` | **`+0x88`** |
| `__TEXT.__swift_as_cont` | `0x458` | `0x4bc` | **`+0x64`** |
| `__DATA_CONST.__auth_ptr` | `0xe68` | `0xec0` | **`+0x58`** |
| `__TEXT.__swift_as_ret` | `0x364` | `0x3b0` | **`+0x4c`** |
| `__DATA_CONST.__got` | `0x7b0` | `0x7d8` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0xce0` | `0xd00` | **`+0x20`** |
| `__DATA.__common` | `0x340` | `0x358` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x220` | `0x238` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x2c0` | `0x2d4` | **`+0x14`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-  Functions: 3844
-  Symbols:   245
-  CStrings:  974
+  Functions: 4098
+  Symbols:   248
+  CStrings:  1011
Symbols:
+ _OBJC_CLASS_$_SAUIDelayedActionCommand
+ _OBJC_CLASS_$_SAUIPerformAppIntent
+ _swift_getTupleTypeMetadata
CStrings:
+ "#CommandHelper failed to make SAUIPerformAPpIntent for PlayAnnouncementSoundIntent."
+ "#CommandHelper failed to make SAUIPerformAppIntent for DismissIntercomIntent."
+ "#CommandHelper failed to make SAUIPerformAppIntent for DismissIntercomIntent. Error=%@"
+ "#CommandHelper has prompted for announcement: %{bool}d."
+ "#CommandHelper making SAUIPerformAppIntent with wrapped %s."
+ "#CommandHelper wrapping SAUIPerformAppIntent with aceId=%s in SAUIDelayedActionCommand with aceId=%s"
+ "#SendAnnouncementFlow using UnsupportedValueAndCancelIntentFlowProducer (HomeAccessory or CarPlay)"
+ "#SendAnnouncementIntentHandlerStrategy adding PlayAnnouncementSoundAction"
+ "#SendAnnouncementNeedsValueStrategy adding dismissIntercomDelayedAction"
+ "#SendAnnouncementNeedsValueStrategy sending DismissIntercomIntent in delayedAction with aceId=%s"
+ "#SendAnnouncementPreflightGuardFlow - makePreflightFailureResponse: success response code is not a failure"
+ "#SendAnnouncementPreflightGuardFlow CheckTargetSupportIntent returned a non-successful preflight check: %s"
+ "#SendAnnouncementPreflightGuardFlow failed to create CheckTargetSupportIntent"
+ "#SendAnnouncementPreflightGuardFlow failed to get nlIntent from parse. Returning generic error flow"
+ "#SendAnnouncementPreflightGuardFlow failed to perform preflight check: %@"
+ "#SendAnnouncementPreflightGuardFlow makeFailureHandlingIntentResponseAsync"
+ "#SendAnnouncementPreflightGuardFlow preflight check successful. Guard flow passed."
+ "#SendAnnouncementPreflightGuardFlow sending preflight intent"
+ "#SendAnnouncementPreflightGuardFlow skipping preflight check for non-homeAccessory"
+ "#Transformer<HomeCommunicationNLIntent, CheckTargetSupportIntent?> CheckTargetSupportIntent=%s"
+ "#Transformer<HomeCommunicationNLIntent, CheckTargetSupportIntent?> converting %s"
+ "AppIntentDispatcherError("
+ "CheckTargetSupportIntent"
+ "CheckTargetSupportIntent(home="
+ "Error while making AppIntent "
+ "Failed to perform "
+ "Got .success response code from CheckTargetSupportIntent instead of a failure"
+ "HomeCommunicationFlowDelegatePlugin/CommandHelper.swift"
+ "HomeCommunicationFlowDelegatePlugin/SendAnnouncementPreflightGuardFlow.swift"
+ "ShouldNeverBeLogged"
+ "actionName error fileName methodName line "
+ "announcementSent"
+ "cancelled"
+ "completed"
+ "failed to transform input"
+ "failureAnnouncingToSelf"
+ "failureTargetNotFound"
+ "makeSAUIPerformAppIntent(for:performOptions:dialogPhase:)"
- "#SendAnnouncementPreflightGuardFlow bypassing preflight check. Guard flow passed."
```
