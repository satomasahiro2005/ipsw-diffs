## mediaremoted

> `/System/Library/PrivateFrameworks/MediaRemote.framework/Support/mediaremoted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x44acb8` | `0x44c138` | **`+0x1480`** |
| `__TEXT.__objc_methname` | `0x41fa5` | `0x42185` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0x2a419` | `0x2a569` | **`+0x150`** |
| `__DATA.__objc_const` | `0x28310` | `0x28430` | **`+0x120`** |
| `__TEXT.__objc_stubs` | `0x28280` | `0x28380` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x15b8c` | `0x15c6c` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x1a44b` | `0x1a4db` | **`+0x90`** |
| `__DATA_CONST.__cfstring` | `0xed60` | `0xede0` | **`+0x80`** |
| `__TEXT.__objc_methtype` | `0x81c8` | `0x8248` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0xca78` | `0xcaf8` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x1cb28` | `0x1cba0` | **`+0x78`** |
| `__DATA.__data` | `0xc250` | `0xc2c0` | **`+0x70`** |
| `__TEXT.__auth_stubs` | `0x6c80` | `0x6cf0` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x5b5c` | `0x5bb0` | **`+0x54`** |
| `__DATA.__objc_data` | `0xa418` | `0xa468` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0xc420` | `0xc468` | **`+0x48`** |
| `__TEXT.__eh_frame` | `0x6cdc` | `0x6d24` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x587d` | `0x58bd` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x3650` | `0x3688` | **`+0x38`** |
| `__TEXT.__objc_classname` | `0x4a56` | `0x4a86` | **`+0x30`** |
| `__TEXT.__const` | `0x10780` | `0x107a0` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x46c4` | `0x46dc` | **`+0x18`** |
| `__DATA.__bss` | `0x129c0` | `0x129d0` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x4e93` | `0x4ea3` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x3008` | `0x3010` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xb20` | `0xb28` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x650` | `0x658` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x5c8` | `0x5d0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1778` | `0x177c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4026.200.15.0.0
+4026.200.23.0.0

+  - /System/Library/Frameworks/SystemConfiguration.framework/SystemConfiguration

-  Functions: 18000
-  Symbols:   3594
-  CStrings:  15602
+  Functions: 18020
+  Symbols:   3602
+  CStrings:  15628
Symbols:
+ _$s12MediaControl11PreferencesC29sessionMinimumContentDurationSdvgZ
+ _$s12MediaControl14RoutingSessionV14NowPlayingInfoV08PlaybackG0V0H4TypeO08DurationG0V8durationSdvg
+ _CFArrayCreate
+ _MGGetBoolAnswer
+ _SCDynamicStoreCopyComputerName
+ _SCDynamicStoreCreate
+ _SCDynamicStoreKeyCreateComputerName
+ _SCDynamicStoreSetDispatchQueue
+ _SCDynamicStoreSetNotificationKeys
+ _kCFTypeArrayCallBacks
- _MGCancelNotifications
- _MGRegisterForUpdates
CStrings:
+ "1%"
+ "@\"<MRLockScreenUIControllable><MRNowPlayingActivityUIControllable>\""
+ "AIRPLAY_CLUSTER_ATV_ALERT_6GSTEERNOCANDIDATE_WIFI_MESSAGE"
+ "AIRPLAY_CLUSTER_ATV_ALERT_6GSTEERNOCANDIDATE_WLAN_MESSAGE"
+ "Installing Multiple forwarders for destinationOrigin"
+ "MRDOriginForwarderManager"
+ "MRNowPlayingActivityUIControllable"
+ "Multiple forwarders for destinationOrigin"
+ "OriginForwarder"
+ "T@\"<MRLockScreenUIControllable><MRNowPlayingActivityUIControllable>\",&,N,V_uiController"
+ "T@\"NSString\",&,N,V_computerName"
+ "[MRDOriginForwarder] %@"
+ "[MRDOriginForwarder] %@ Installing destinationOrigin callbacks"
+ "[MRDOriginForwarder] Registering %{public}@ while %{public}@ is already forwarding to the same destinationOrigin"
+ "[MRDOriginForwarder] Unregistering %{public}@ while %{public}@ is still forwarding to the same destinationOrigin - repointing callbacks"
+ "^{__SCDynamicStore=}"
+ "_computerName"
+ "_dynamicStore"
+ "_forwarders"
+ "_locked_forwarderForDestinationOrigin:excluding:"
+ "_nameDidChange"
+ "acquireNowPlayingActivityAssertionForRouteIdentifier:withDuration:preferredState:"
+ "allForwarders"
+ "com.apple.mediaremoted.MRDDeviceInfoDataSource"
+ "hasForwarderForDestinationOrigin:"
+ "registerForwarder:"
+ "setPreferredState:"
+ "setPreferredState:forBundleIdentifier:"
+ "setSpeakerGroupCount:"
+ "setTvAndSpeakerCount:"
+ "suppressPresentationOverBundleIdentifiers:"
+ "unregisterForwarder:"
+ "v32@0:8q16@\"NSString\"24"
+ "v40@0:8@\"NSString\"16q24q32"
+ "v40@0:8@16q24q32"
+ "wapi"
- "1$"
- "AIRPLAY_CLUSTER_ATV_ALERT_6GSTEERNOCANDIDATE_MESSAGE"
- "ComputerName"
- "UserAssignedDeviceName"
- "^{MGNotificationTokenStruct=}"
- "_gestaltNotificationToken"
- "_hasForwarderForOrigin:"
- "registerOriginForwarder:"
- "unregisterOriginForwarder:"
- "v24@?0^{__CFString=}8^{__CFDictionary=}16"
```
