## SiriVideoFlowTools

> `/System/Library/FlowTools/Tools/SiriVideoFlowTools.flowtool/SiriVideoFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x169d0` | `0x19f58` | **`+0x3588`** |
| `__TEXT.__cstring` | `0x4c5` | `0xe65` | **`+0x9a0`** |
| `__TEXT.__objc_stubs` | `0x100` | `0x3c0` | **`+0x2c0`** |
| `__TEXT.__auth_stubs` | `0xcd0` | `0xef0` | **`+0x220`** |
| `__TEXT.__objc_methname` | `0x3ff` | `0x5ef` | **`+0x1f0`** |
| `__DATA_CONST.__auth_got` | `0x670` | `0x780` | **`+0x110`** |
| `__DATA.__data` | `0x728` | `0x808` | **`+0xe0`** |
| `__DATA.__objc_selrefs` | `0x108` | `0x1b8` | **`+0xb0`** |
| `__TEXT.__const` | `0x1f48` | `0x1ff8` | **`+0xb0`** |
| `__DATA_CONST.__got` | `0x210` | `0x2b8` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0x6a8` | `0x728` | **`+0x80`** |
| `__DATA_CONST.__auth_ptr` | `0x9d8` | `0xa30` | **`+0x58`** |
| `__TEXT.__swift5_reflstr` | `0x6ae` | `0x6fe` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x777` | `0x7b9` | **`+0x42`** |
| `__DATA.__objc_const` | `0x490` | `0x4d0` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x7a8` | `0x7e8` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x380` | `0x3a8` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x5c` | `0x60` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.22.2.0.0
+3600.28.1.0.0

+  - /System/Library/PrivateFrameworks/SiriInstrumentation.framework/SiriInstrumentation

-  Functions: 655
-  Symbols:   131
-  CStrings:  131
+  Functions: 714
+  Symbols:   162
+  CStrings:  180
Symbols:
+ _OBJC_CLASS_$_FTDSchemaFTDClientEvent
+ _OBJC_CLASS_$_FTDSchemaFTDClientEventMetadata
+ _OBJC_CLASS_$_FTDVideoSchemaFTDVideoFindThirdPartyVideoInvoked
+ _OBJC_CLASS_$_FTDVideoSchemaFTDVideoPlayVideoContentInvoked
+ _OBJC_CLASS_$_FTDVideoSchemaFTDVideoSiriKitIntentsLookupContext
+ _OBJC_CLASS_$_FTDVideoSchemaFTDVideoSiriKitIntentsLookupEnded
+ _OBJC_CLASS_$_FTDVideoSchemaFTDVideoSiriKitIntentsLookupStarted
+ _OBJC_CLASS_$_FTDVideoSchemaFTDVideoToolDatabaseQueryContext
+ _OBJC_CLASS_$_FTDVideoSchemaFTDVideoToolDatabaseQueryEnded
+ _OBJC_CLASS_$_FTDVideoSchemaFTDVideoToolDatabaseQueryFailed
+ _OBJC_CLASS_$_FTDVideoSchemaFTDVideoToolDatabaseQueryStarted
+ _OBJC_CLASS_$_FTDVideoSchemaFTDVideoToolInvoked
+ _OBJC_CLASS_$_SISchemaFreeFormText
+ _OBJC_CLASS_$_SISchemaUUID
+ _mach_absolute_time
+ _objc_release
+ _objc_release_x25
+ _objc_release_x26
+ _objc_release_x28
+ _objc_retain
+ _objc_retain_x21
+ _objc_retain_x23
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithTake
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getExistentialTypeMetadata
+ _swift_getObjCClassFromMetadata
+ _swift_getObjCClassMetadata
+ _swift_getSingletonMetadata
+ _swift_release_x22
+ _swift_storeEnumTagSinglePayloadGeneric
CStrings:
+ "Intents.Error.NeedsSignIn"
+ "Intents.Error.PlayFailureAppUninstalled"
+ "Intents.Error.PlayFailureCarPlay"
+ "Intents.Error.PlayFailureGDPR"
+ "Intents.Error.PlayFailurePunchoutError"
+ "Intents.Error.PlayFailurePunchoutTimeout"
+ "Intents.Error.PlayFailureUnentitled"
+ "Intents.Error.PlayFailureVPPA"
+ "No app on this device can play this content — the user likely needs to install a provider app first. This cannot be resolved by Siri. Do not retry searching or playing this content."
+ "PlayVideoContentTool: CDTVC via SiriX — device=%s, id=%s"
+ "Playback requires the user to take an action in the provider app that Siri cannot complete. This cannot be resolved by Siri. Do not retry searching or playing this content."
+ "The content requires a subscription or purchase the user doesn't have. Siri cannot subscribe or purchase content on their behalf. Do not retry searching or playing this content."
+ "The provider app did not respond in time when Siri tried to launch it for playback. This cannot be resolved by Siri. Do not retry searching or playing this content."
+ "The provider app failed to open when Siri tried to launch it for playback. This cannot be resolved by Siri. Do not retry searching or playing this content."
+ "The provider app requires the user to accept a GDPR consent agreement before playing content. Siri cannot complete consent flows. Do not retry searching or playing this content."
+ "The provider app requires the user to accept a video privacy agreement (VPPA) before playing content. Siri cannot complete consent flows. Do not retry searching or playing this content."
+ "The provider app requires the user to be signed in, and they currently are not. Siri cannot sign in on their behalf. Do not retry searching or playing this content."
+ "Video playback is not supported in CarPlay background mode. This is a platform limitation. This cannot be resolved by Siri. Do not retry searching or playing this content."
+ "_instrumentationSender"
+ "initWithNSUUID:"
+ "key"
+ "ln_staticDeferredLocalizedString"
+ "playVideoContentTool.error.interventionRequired"
+ "playVideoContentTool.error.needsSignIn"
+ "playVideoContentTool.error.playFailureAppUninstalled"
+ "playVideoContentTool.error.playFailureCarPlay"
+ "playVideoContentTool.error.playFailureGDPR"
+ "playVideoContentTool.error.playFailurePunchoutError"
+ "playVideoContentTool.error.playFailurePunchoutTimeout"
+ "playVideoContentTool.error.playFailureUnentitled"
+ "playVideoContentTool.error.playFailureVPPA"
+ "setBundleId:"
+ "setContentIdentifier:"
+ "setContentTitle:"
+ "setContentType:"
+ "setContextId:"
+ "setEnded:"
+ "setEventMetadata:"
+ "setFailed:"
+ "setFlowToolClientInteractionId:"
+ "setInvoked:"
+ "setIsExplicitAppMention:"
+ "setIsRoutedToRemoteDevice:"
+ "setSearchTerm:"
+ "setStartedOrChanged:"
+ "setText:"
+ "setVideoFindThirdPartyVideoInvoked:"
+ "setVideoPlayVideoContentInvoked:"
+ "setVideoSiriKitIntentsLookupContext:"
+ "setVideoToolDatabaseQueryContext:"
- "PlayVideoContentTool: CDTVC via SiriX — device=%s, umcId=%s"
```
