## AudioFlowDelegatePlugin

> `/System/Library/Assistant/FlowDelegatePlugins/AudioFlowDelegatePlugin.bundle/AudioFlowDelegatePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d0718` | `0x2d7518` | **`+0x6e00`** |
| `__TEXT.__oslogstring` | `0x247bc` | `0x24d2c` | **`+0x570`** |
| `__DATA.__bss` | `0xc710` | `0xc890` | **`+0x180`** |
| `__TEXT.__swift5_reflstr` | `0x424b` | `0x436b` | **`+0x120`** |
| `__TEXT.__swift5_fieldmd` | `0x3688` | `0x377c` | **`+0xf4`** |
| `__TEXT.__const` | `0xc11a` | `0xc1fa` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0xfe08` | `0xfec8` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x5b98` | `0x5c38` | **`+0xa0`** |
| `__DATA.__data` | `0xc330` | `0xc3c0` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0x6f10` | `0x6f70` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x47a4` | `0x47fc` | **`+0x58`** |
| `__TEXT.__cstring` | `0x4a9c` | `0x4adc` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3898` | `0x38d8` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x1ea8` | `0x1ee0` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x3790` | `0x37c0` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x3f9d` | `0x3fcd` | **`+0x30`** |
| `__DATA.__objc_const` | `0x9e10` | `0x9e30` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2ec0` | `0x2ee0` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x1ac0` | `0x1ad0` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x708` | `0x714` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0xdb0` | `0xdb8` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x70` | `0x74` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3605.23.1.0.0
+3605.24.1.0.0

+  - /System/Library/PrivateFrameworks/IntelligenceFlowShared.framework/IntelligenceFlowShared

-  Functions: 6047
+  Functions: 6072

-  CStrings:  2977
+  CStrings:  2992
CStrings:
+ "ContinueInAppPunchOutStrategy#homeAccessoryContinuation cannot continue on the accessory, handling locally. hasAppIdentifier: %{bool,public}d, handledBySiriForAirPlay: %{bool,public}d, hasAssistantID: %{bool,public}d"
+ "ContinueInAppPunchOutStrategy#homeAccessoryContinuation originIsHomeAccessory: %{bool,public}d, isPumpkin: %{bool,public}d"
+ "ContinueInAppPunchOutStrategy#makeContinueInAppAutoPunchOutResponse launchAppCommand %@, appBundleId %s"
+ "ContinueInAppPunchOutStrategy#makeContinueInAppAutoPunchOutResponse remote assistantId %s, eor %@"
+ "ContinueInAppPunchOutStrategy#requireUnlock requireUnlock: %{bool}d"
+ "ExecuteMusicOnRemoteFlow#execute isFollowUpTurn: %{bool}d"
+ "ExecuteMusicOnRemoteFlow#execute remote request completed with topicSwitchDetected. Will return .unhandled(reason: .needsExecutionRerun)"
+ "ExecuteMusicOnRemoteFlow#execute remote request is waiting on user input. Will return .ongoing(requireInput: true)"
+ "FallbackSpeakerIDProviding#speakerIDInfo attaching sharedUserID: %{private}s, classification: %{public}s, speakerIDConfidence: %{public}ld %{public}s"
+ "FallbackSpeakerIDProviding#speakerIDInfo no sharedUserID to attach; SiriKit fallback intent will carry no speaker identity %{public}s"
+ "INAddMediaIntent#from(payload) reattaching forwarded SFA signals: %s"
+ "INPlayMediaIntent#from(payload) reattaching forwarded SFA signals: %s"
+ "UpdateMediaAffinityFlowStrategy#makeIntentFromParse reattaching forwarded SFA signals: %s"
+ "internalSignalsFromSiriAudio"
+ "originalPlayMediaIntent"
+ "topicSwitchDetected"
- "ExecuteMusicOnRemoteFlow#execute remote request is waiting on user input. But follow ups are not currently supported by this flow. Returning .complete()"
```
