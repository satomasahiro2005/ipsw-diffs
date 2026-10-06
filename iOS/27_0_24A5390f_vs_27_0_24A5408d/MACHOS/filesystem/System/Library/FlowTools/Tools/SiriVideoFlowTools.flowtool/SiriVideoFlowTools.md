## SiriVideoFlowTools

> `/System/Library/FlowTools/Tools/SiriVideoFlowTools.flowtool/SiriVideoFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19048` | `0x1a29c` | **`+0x1254`** |
| `__TEXT.__cstring` | `0xe65` | `0x15d5` | **`+0x770`** |
| `__DATA.__bss` | `0x2420` | `0x2720` | **`+0x300`** |
| `__TEXT.__const` | `0x1fd8` | `0x2198` | **`+0x1c0`** |
| `__DATA_CONST.__auth_ptr` | `0xa18` | `0xad0` | **`+0xb8`** |
| `__TEXT.__auth_stubs` | `0xe80` | `0xf00` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x708` | `0x778` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x75d` | `0x7af` | **`+0x52`** |
| `__TEXT.__oslogstring` | `0x5a0` | `0x5f0` | **`+0x50`** |
| `__DATA.__data` | `0x7f8` | `0x838` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x748` | `0x788` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x3a8` | `0x3e0` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0x968` | `0x9a0` | **`+0x38`** |
| `__TEXT.__swift5_assocty` | `0x150` | `0x180` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x6fe` | `0x72e` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xee9` | `0xf11` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x298` | `0x2b8` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x3c0` | `0x3e0` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x7e8` | `0x804` | **`+0x1c`** |
| `__TEXT.__swift5_proto` | `0x128` | `0x140` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__TEXT.__objc_methname` | `0x5ef` | `0x5ff` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x60` | `0x64` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.28.6.0.0
+3600.28.7.0.0

+  - /System/Library/PrivateFrameworks/LinkServices.framework/LinkServices

-  Functions: 667
-  Symbols:   150
-  CStrings:  180
+  Functions: 701
+  Symbols:   157
+  CStrings:  191
Symbols:
+ _LNPerformActionErrorKindInterventionRequired
+ _LNPerformActionErrorKindKey
+ _NSUnderlyingErrorKey
+ _OBJC_CLASS_$_NSError
+ _objc_release_x27
+ _swift_dynamicCast
+ _swift_getForeignTypeMetadata
CStrings:
+ "Intents.Error.ContentRestricted"
+ "Intents.Error.PlayFailureContentUnavailable"
+ "Intents.Error.PlayFailureFederatedUnavailable"
+ "PlayVideoContentToolErrorProvider: received error from TV app — %s"
+ "Playback requires the user to take an action in the app. Stop and inform the user they need to take that action in the app before this content can play. Do not retry this or any other play request for this content."
+ "The app did not respond in time when launched for playback. Stop and inform the user the app didn't respond. Do not retry this or any other play request for this content."
+ "The app failed to open for playback. Stop and inform the user the app couldn't be launched. Do not retry this or any other play request for this content."
+ "The app has already shown the user a screen asking them to connect the app to the Apple TV app, which requires agreeing to share their viewing activity with Apple under their Apple Account. Stop and inform the user they need to tap Connect on that screen before this content can play. Do not retry this or any other play request for this content."
+ "The app required to play this content is not installed on this device. The app has already shown the user a prompt with the app icon, name, and a message that the content will play once it's installed. Stop and inform the user they need to install the app before this content can play. Do not retry this or any other play request for this content."
+ "The app requires the user to accept a GDPR consent agreement before playing content. Stop and inform the user they need to open the app and accept the agreement. Do not retry this or any other play request for this content."
+ "The app requires the user to sign in with their iCloud account before this content can play. Stop and inform the user they need to sign in to the app with their iCloud account before this content can play. Do not retry this or any other play request for this content."
+ "This content could not be automatically launched in the app. Stop and inform the user to open the app directly to continue. This is not a sign-in or subscription issue Do not suggest sign-in or purchase, and do not retry this or any other play request for this content."
+ "This content exceeds the content restrictions (parental controls) configured on this device. Stop and inform the user this content is blocked by their content restrictions settings. This is not a sign-in or subscription issue — do not suggest sign-in or purchase, and do not retry this or any other play request for this content."
+ "This content is unavailable, for example due to region or licensing restrictions. Stop and inform the user this content isn't available. This is not a sign-in or subscription issue Do not suggest sign-in or purchase, and do not retry this or any other play request for this content."
+ "This content requires a subscription or purchase the user doesn't have. The app has already shown the user a page with options to buy, rent, or subscribe for this content. Stop and inform the user they need to complete a purchase or subscription in the app before this content can play. Do not retry this or any other play request for this content."
+ "Video playback is not supported while CarPlay is in background mode. Stop and inform the user video can't play here while CarPlay is in the background. Do not retry this or any other play request for this content."
+ "playVideoContentTool.error.contentRestricted"
+ "playVideoContentTool.error.playFailureContentUnavailable"
+ "playVideoContentTool.error.playFailureFederatedUnavailable"
+ "userInfo"
- "No app on this device can play this content — the user likely needs to install a provider app first. This cannot be resolved by Siri. Do not retry searching or playing this content."
- "Playback requires the user to take an action in the provider app that Siri cannot complete. This cannot be resolved by Siri. Do not retry searching or playing this content."
- "The content requires a subscription or purchase the user doesn't have. Siri cannot subscribe or purchase content on their behalf. Do not retry searching or playing this content."
- "The provider app did not respond in time when Siri tried to launch it for playback. This cannot be resolved by Siri. Do not retry searching or playing this content."
- "The provider app failed to open when Siri tried to launch it for playback. This cannot be resolved by Siri. Do not retry searching or playing this content."
- "The provider app requires the user to accept a GDPR consent agreement before playing content. Siri cannot complete consent flows. Do not retry searching or playing this content."
- "The provider app requires the user to accept a video privacy agreement (VPPA) before playing content. Siri cannot complete consent flows. Do not retry searching or playing this content."
- "The provider app requires the user to be signed in, and they currently are not. Siri cannot sign in on their behalf. Do not retry searching or playing this content."
- "Video playback is not supported in CarPlay background mode. This is a platform limitation. This cannot be resolved by Siri. Do not retry searching or playing this content."
```
