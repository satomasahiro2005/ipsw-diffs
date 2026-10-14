## corespeechd

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/corespeechd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1833e0` | `0x183f5c` | **`+0xb7c`** |
| `__TEXT.__oslogstring` | `0x280c5` | `0x283f6` | **`+0x331`** |
| `__TEXT.__objc_methname` | `0x49237` | `0x49432` | **`+0x1fb`** |
| `__TEXT.__cstring` | `0x3116b` | `0x312c0` | **`+0x155`** |
| `__DATA.__objc_const` | `0x2c900` | `0x2ca28` | **`+0x128`** |
| `__DATA_CONST.__const` | `0x5e80` | `0x5f50` | **`+0xd0`** |
| `__TEXT.__objc_methlist` | `0x1c3a0` | `0x1c430` | **`+0x90`** |
| `__DATA_CONST.__cfstring` | `0x9180` | `0x91e0` | **`+0x60`** |
| `__DATA.__objc_data` | `0x6540` | `0x6590` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0xd210` | `0xd258` | **`+0x48`** |
| `__TEXT.__objc_stubs` | `0x22660` | `0x226a0` | **`+0x40`** |
| `__TEXT.__const` | `0x3d0` | `0x400` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x3a7f` | `0x3aa5` | **`+0x26`** |
| `__DATA_CONST.__objc_intobj` | `0xd50` | `0xd68` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x97e8` | `0x97ff` | **`+0x17`** |
| `__DATA_CONST.__got` | `0x1550` | `0x1560` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1610` | `0x1620` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x22a8` | `0x22b4` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0xb20` | `0xb28` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xa20` | `0xa28` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x848` | `0x850` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3605.31.3.0.0
+3605.32.1.0.0

-  Functions: 10623
-  Symbols:   1037
-  CStrings:  17449
+  Functions: 10639
+  Symbols:   1039
+  CStrings:  17480
Symbols:
+ _CSIsJ265
+ _OBJC_CLASS_$_CSPickableRouteChangeMonitor
CStrings:
+ "%s #stream CSAudioStreamProviderServiceHandler DROP already emitted for streamId=%@ (useHostTime=%llu)"
+ "%s #stream CSAudioStreamProviderServiceHandler DROP legacy USE, no current stream to attribute it to"
+ "%s #stream CSAudioStreamProviderServiceHandler DROP nil streamId (useHostTime=%llu)"
+ "%s #stream CSAudioStreamProviderServiceHandler DROP no mhId for streamId=%@ (useHostTime=%llu)"
+ "%s #stream CSAudioStreamProviderServiceHandler DROP unknown streamId=%@ (current=%@, previous=%@)"
+ "%s #stream CSAudioStreamProviderServiceHandler EMITTED MHSchemaMHUserSpeakingEnded mhId=%@ useHostTime=%llu streamId=%@"
+ "%s #stream CSAudioStreamProviderServiceHandler EMITTING mhId=%@ useHostTime=%llu (mach_continuous=%llu) streamId=%@ stream=%{public}@"
+ "%s #stream CSAudioStreamProviderServiceHandler SKIP SELF emit — requestMHUUID=%@ is not a valid UUID"
+ "%s #stream CSAudioStreamProviderServiceHandler XPC RECEIVED (legacy, no streamId) useHostTime=%llu"
+ "%s #stream CSAudioStreamProviderServiceHandler XPC RECEIVED useHostTime=%llu streamId=%@"
+ "%s VoiceTrigger cannot be turned on since Hearst is routed and owned with A2DP"
+ "%s VoiceTrigger cannot be turned on since Siri locale is not FarField VT supported"
+ "%s VoiceTrigger cannot be turned on since other non-eligible App is recording and we are not in a connected or outgoing call"
+ "-[CSAudioStreamProviderServiceHandler _forwardUserSpeakingEndAtHostTime:forStreamId:]"
+ "-[CSAudioStreamProviderServiceHandler forwardUserSpeakingEndAtHostTime:forStreamId:]"
+ "-[CSAudioStreamProviderServiceHandler forwardUserSpeakingEndAtHostTime:forStreamId:]_block_invoke"
+ "-[CSVoiceTriggerEnabledPolicyATVExclave _addVoiceTriggerEnabledConditions]_block_invoke"
+ "CSVoiceTriggerEnabledPolicyATVExclave"
+ "T@\"NSString\",C,N,V_previousRequestMHUUID"
+ "T@\"NSUUID\",C,N,V_previousStreamId"
+ "TB,N,V_previousDidEmitForwardedUserSpeakingEnd"
+ "Vv32@0:8Q16@\"NSUUID\"24"
+ "_forwardUserSpeakingEndAtHostTime:forStreamId:"
+ "_previousDidEmitForwardedUserSpeakingEnd"
+ "_previousRequestMHUUID"
+ "_previousStreamId"
+ "current"
+ "forwardUserSpeakingEndAtHostTime:forStreamId:"
+ "isATVFarFieldVoiceTriggerSupportedLanguageCode:"
+ "isOdeonProxyVoiceTriggered"
+ "previous"
+ "previousDidEmitForwardedUserSpeakingEnd"
+ "previousRequestMHUUID"
+ "previousStreamId"
+ "setPreviousDidEmitForwardedUserSpeakingEnd:"
+ "setPreviousRequestMHUUID:"
+ "setPreviousStreamId:"
+ "trailingSilenceDurationThresholdMsPebble"
- "%s #stream CSAudioStreamProviderServiceHandler DROP already emitted (useHostTime=%llu)"
- "%s #stream CSAudioStreamProviderServiceHandler EMITTED MHSchemaMHUserSpeakingEnded mhId=%@ useHostTime=%llu"
- "%s #stream CSAudioStreamProviderServiceHandler EMITTING mhId=%@ useHostTime=%llu (mach_continuous=%llu)"
- "%s #stream CSAudioStreamProviderServiceHandler SKIP SELF emit — no requestMHUUID on _option (MH emission requires it)"
- "%s #stream CSAudioStreamProviderServiceHandler XPC RECEIVED useHostTime=%llu"
- "-[CSAudioStreamProviderServiceHandler _forwardUserSpeakingEndAtHostTime:]"
- "_forwardUserSpeakingEndAtHostTime:"
```
