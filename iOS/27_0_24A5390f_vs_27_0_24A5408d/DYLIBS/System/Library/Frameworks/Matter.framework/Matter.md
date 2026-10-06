## Matter

> `/System/Library/Frameworks/Matter.framework/Matter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x835010` | `0x8579cc` | **`+0x229bc`** |
| `__TEXT.__gcc_except_tab` | `0xc030c` | `0xc4460` | **`+0x4154`** |
| `__AUTH_CONST.__objc_const` | `0x73328` | `0x76178` | **`+0x2e50`** |
| `__TEXT.__objc_methlist` | `0x5c054` | `0x5e054` | **`+0x2000`** |
| `__TEXT.__unwind_info` | `0x50200` | `0x515a0` | **`+0x13a0`** |
| `__TEXT.__const` | `0x63239` | `0x64189` | **`+0xf50`** |
| `__AUTH.__objc_data` | `0x1db50` | `0x1e640` | **`+0xaf0`** |
| `__AUTH_CONST.__cfstring` | `0x17ae0` | `0x183c0` | **`+0x8e0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c008` | `0x1c7e8` | **`+0x7e0`** |
| `__TEXT.__cstring` | `0x2fa0c` | `0x301aa` | **`+0x79e`** |
| `__AUTH_CONST.__const` | `0x1c420` | `0x1c820` | **`+0x400`** |
| `__DATA.__objc_ivar` | `0x3e64` | `0x4038` | **`+0x1d4`** |
| `__DATA_CONST.__const` | `0x12a88` | `0x12c40` | **`+0x1b8`** |
| `__TEXT.__oslogstring` | `0x1b1c6` | `0x1b37e` | **`+0x1b8`** |
| `__DATA_CONST.__objc_classlist` | `0x2f88` | `0x30a0` | **`+0x118`** |
| `__DATA_CONST.__got` | `0x22c8` | `0x23b0` | **`+0xe8`** |
| `__DATA_CONST.__objc_superrefs` | `0x2160` | `0x2248` | **`+0xe8`** |
| `__AUTH_CONST.__objc_intobj` | `0x6990` | `0x6a68` | **`+0xd8`** |

### Other Changes

```diff

-322.0.0.0.0
+324.0.0.0.0

-  Functions: 51797
-  Symbols:   3387
-  CStrings:  8855
+  Functions: 52652
+  Symbols:   3455
+  CStrings:  8934
Symbols:
+ _OBJC_CLASS_$_MTRAppleAccessoryErrorsClusterAppleAccessoryErrorEventEvent
+ _OBJC_CLASS_$_MTRAppleAccessoryErrorsClusterAppleAccessoryPersistentErrorStruct
+ _OBJC_CLASS_$_MTRAudioControlClusterDecreaseVolumeParams
+ _OBJC_CLASS_$_MTRAudioControlClusterIncreaseVolumeParams
+ _OBJC_CLASS_$_MTRAudioControlClusterMuteParams
+ _OBJC_CLASS_$_MTRAudioControlClusterSetVolumeParams
+ _OBJC_CLASS_$_MTRAudioControlClusterToggleMutedParams
+ _OBJC_CLASS_$_MTRAudioControlClusterUnmuteParams
+ _OBJC_CLASS_$_MTRBaseClusterAudioControl
+ _OBJC_CLASS_$_MTRBaseClusterMediaFileManagement
+ _OBJC_CLASS_$_MTRClosureControlClusterGroupedMoveToParams
+ _OBJC_CLASS_$_MTRClosureDimensionClusterGroupedSetTargetParams
+ _OBJC_CLASS_$_MTRClosureDimensionClusterGroupedStepParams
+ _OBJC_CLASS_$_MTRClusterAppleAccessoryErrors
+ _OBJC_CLASS_$_MTRClusterAudioControl
+ _OBJC_CLASS_$_MTRClusterMediaFileManagement
+ _OBJC_CLASS_$_MTRContentLauncherClusterContentAppInfo
+ _OBJC_CLASS_$_MTRContentLauncherClusterContentPresetStruct
+ _OBJC_CLASS_$_MTRContentLauncherClusterContentReplicationEvent
+ _OBJC_CLASS_$_MTRContentLauncherClusterContentReplicationRequestParams
+ _OBJC_CLASS_$_MTRContentLauncherClusterContentReplicationResponseParams
+ _OBJC_CLASS_$_MTRContentLauncherClusterLaunchUrlInfo
+ _OBJC_CLASS_$_MTRContentLauncherClusterPlayPresetParams
+ _OBJC_CLASS_$_MTRContentLauncherClusterReplicationInfo
+ _OBJC_CLASS_$_MTRMediaFileManagementClusterAddFileParams
+ _OBJC_CLASS_$_MTRMediaFileManagementClusterAddFileResponseParams
+ _OBJC_CLASS_$_MTRMediaFileManagementClusterDeleteFileParams
+ _OBJC_CLASS_$_MTRMediaFileManagementClusterFileDescriptionStruct
+ _OBJC_CLASS_$_MTRMediaFileManagementClusterGetSharedFileParams
+ _OBJC_CLASS_$_MTRMediaFileManagementClusterGetSharedFileResponseParams
+ _OBJC_CLASS_$_MTRMediaFileManagementClusterOfferFileParams
+ _OBJC_CLASS_$_MTRMediaFileManagementClusterRequestSharedFilesParams
+ _OBJC_CLASS_$_MTRMediaFileManagementClusterSharedFilesAddedEvent
+ _OBJC_CLASS_$_MTRMediaPlaybackClusterContentInfoStruct
+ _OBJC_METACLASS_$_MTRAppleAccessoryErrorsClusterAppleAccessoryErrorEventEvent
+ _OBJC_METACLASS_$_MTRAppleAccessoryErrorsClusterAppleAccessoryPersistentErrorStruct
+ _OBJC_METACLASS_$_MTRAudioControlClusterDecreaseVolumeParams
+ _OBJC_METACLASS_$_MTRAudioControlClusterIncreaseVolumeParams
+ _OBJC_METACLASS_$_MTRAudioControlClusterMuteParams
+ _OBJC_METACLASS_$_MTRAudioControlClusterSetVolumeParams
+ _OBJC_METACLASS_$_MTRAudioControlClusterToggleMutedParams
+ _OBJC_METACLASS_$_MTRAudioControlClusterUnmuteParams
+ _OBJC_METACLASS_$_MTRBaseClusterAudioControl
+ _OBJC_METACLASS_$_MTRBaseClusterMediaFileManagement
+ _OBJC_METACLASS_$_MTRClosureControlClusterGroupedMoveToParams
+ _OBJC_METACLASS_$_MTRClosureDimensionClusterGroupedSetTargetParams
+ _OBJC_METACLASS_$_MTRClosureDimensionClusterGroupedStepParams
+ _OBJC_METACLASS_$_MTRClusterAppleAccessoryErrors
+ _OBJC_METACLASS_$_MTRClusterAudioControl
+ _OBJC_METACLASS_$_MTRClusterMediaFileManagement
+ _OBJC_METACLASS_$_MTRContentLauncherClusterContentAppInfo
+ _OBJC_METACLASS_$_MTRContentLauncherClusterContentPresetStruct
+ _OBJC_METACLASS_$_MTRContentLauncherClusterContentReplicationEvent
+ _OBJC_METACLASS_$_MTRContentLauncherClusterContentReplicationRequestParams
+ _OBJC_METACLASS_$_MTRContentLauncherClusterContentReplicationResponseParams
+ _OBJC_METACLASS_$_MTRContentLauncherClusterLaunchUrlInfo
+ _OBJC_METACLASS_$_MTRContentLauncherClusterPlayPresetParams
+ _OBJC_METACLASS_$_MTRContentLauncherClusterReplicationInfo
+ _OBJC_METACLASS_$_MTRMediaFileManagementClusterAddFileParams
+ _OBJC_METACLASS_$_MTRMediaFileManagementClusterAddFileResponseParams
+ _OBJC_METACLASS_$_MTRMediaFileManagementClusterDeleteFileParams
+ _OBJC_METACLASS_$_MTRMediaFileManagementClusterFileDescriptionStruct
+ _OBJC_METACLASS_$_MTRMediaFileManagementClusterGetSharedFileParams
+ _OBJC_METACLASS_$_MTRMediaFileManagementClusterGetSharedFileResponseParams
+ _OBJC_METACLASS_$_MTRMediaFileManagementClusterOfferFileParams
+ _OBJC_METACLASS_$_MTRMediaFileManagementClusterRequestSharedFilesParams
+ _OBJC_METACLASS_$_MTRMediaFileManagementClusterSharedFilesAddedEvent
+ _OBJC_METACLASS_$_MTRMediaPlaybackClusterContentInfoStruct
CStrings:
+ "<%@: clientName:%@; name:%@; size:%@; mimeType:%@; imageUri:%@; >"
+ "<%@: clientName:%@; requestID:%@; supportedMimeTypes:%@; >"
+ "<%@: contentAppVendorID:%@; contentAppProductID:%@; data:%@; >"
+ "<%@: contentType:%@; title:%@; show:%@; season:%@; episode:%@; provider:%@; artist:%@; album:%@; track:%@; >"
+ "<%@: contentURL:%@; displayString:%@; brandingInformation:%@; playbackPreferences:%@; contentType:%@; contentHeaders:%@; offsetMillisecs:%@; queueType:%@; nextUrl:%@; >"
+ "<%@: errorCode:%@; category:%@; severity:%@; moreInfoMetadata:%@; >"
+ "<%@: fileID:%@; >"
+ "<%@: fileID:%@; name:%@; size:%@; mimeType:%@; imageUri:%@; >"
+ "<%@: languageCode:%@; characteristics:%@; displayName:%@; >"
+ "<%@: launchUrlInfo:%@; contentAppInfo:%@; >"
+ "<%@: name:%@; size:%@; mimeType:%@; imageUri:%@; >"
+ "<%@: newVolume:%@; unmutePolicy:%@; >"
+ "<%@: presetID:%@; presetName:%@; >"
+ "<%@: requestID:%@; responseID:%@; >"
+ "<%@: responseID:%@; >"
+ "<%@: search:%@; autoPlay:%@; data:%@; playbackPreferences:%@; useCurrentContext:%@; contentAppVendorID:%@; contentAppProductID:%@; >"
+ "<%@: status:%@; fileDescription:%@; >"
+ "<%@: status:%@; fileID:%@; >"
+ "<%@: status:%@; replicationInfo:%@; >"
+ "<%@: stepSize:%@; unmutePolicy:%@; >"
+ "<%@: stepSize:%@; unmutePolicy:%@; unmuteVolume:%@; >"
+ "<%@: url:%@; data:%@; contentType:%@; contentHeaders:%@; offsetMillisecs:%@; queueType:%@; nextUrl:%@; >"
+ "AddFile"
+ "AddFileResponse"
+ "AppleAccessoryErrorEvent"
+ "AppleAccessoryErrors"
+ "AppleAccessoryPersistentErrors"
+ "AudioControl"
+ "AvailableCommands"
+ "AvailableFiles"
+ "AvailableStorage"
+ "Bass"
+ "ContentInfo"
+ "ContentReplication"
+ "ContentReplicationRequest"
+ "ContentReplicationResponse"
+ "DecreaseVolume"
+ "DecreaseVolumeUnmutePolicy"
+ "DefaultStepSize"
+ "DeleteFile"
+ "GetSharedFile"
+ "GetSharedFileResponse"
+ "GroupedMoveTo"
+ "GroupedSetTarget"
+ "GroupedStep"
+ "IncreaseVolume"
+ "IncreaseVolumeUnmutePolicy"
+ "IncreaseVolumeUnmuteVolume"
+ "MaxCorrection"
+ "MaxDeviceVolume"
+ "MaxDeviceVolumeDB"
+ "MaxUserVolume"
+ "MediaFileManagement"
+ "Mid"
+ "MinCorrection"
+ "MinDeviceVolume"
+ "Movable"
+ "Mute"
+ "OfferFile"
+ "PhysicallyMuted"
+ "PlayPreset"
+ "RegisterClientResponse received in incorrect stage '%s'"
+ "RegisterClientResponse received while no device is being commissioned"
+ "RegisterClientResponse received with null context"
+ "RequestSharedFiles"
+ "Response suppressed, skipping status: 0x%02x (%s)"
+ "SetVolume"
+ "SetVolumeUnmutePolicy"
+ "SharedFilesAdded"
+ "SoftMuted"
+ "StartUpMuted"
+ "StartUpVolume"
+ "StayActiveResponse received in incorrect stage '%s'"
+ "StayActiveResponse received while no device is being commissioned"
+ "StayActiveResponse received with null context"
+ "SupportedMimeTypes"
+ "TimedRequest cannot be sent with SuppressResponse"
+ "ToggleMuted"
+ "TotalStorage"
+ "Treble"
+ "Unmute"
+ "Volume"
- "<%@: contentURL:%@; displayString:%@; brandingInformation:%@; >"
- "<%@: languageCode:%@; displayName:%@; >"
- "<%@: search:%@; autoPlay:%@; data:%@; playbackPreferences:%@; useCurrentContext:%@; >"
```
