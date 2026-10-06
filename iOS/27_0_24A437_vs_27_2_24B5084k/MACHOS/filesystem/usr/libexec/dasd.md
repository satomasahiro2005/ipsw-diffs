## dasd

> `/usr/libexec/dasd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x178204` | `0x17b1fc` | **`+0x2ff8`** |
| `__TEXT.__objc_methname` | `0x2e5bd` | `0x2ebb5` | **`+0x5f8`** |
| `__TEXT.__oslogstring` | `0x16c79` | `0x171a9` | **`+0x530`** |
| `__TEXT.__objc_stubs` | `0x1b040` | `0x1b380` | **`+0x340`** |
| `__DATA_CONST.__cfstring` | `0x11940` | `0x11ae0` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x10586` | `0x10706` | **`+0x180`** |
| `__TEXT.__objc_methlist` | `0x131f4` | `0x1334c` | **`+0x158`** |
| `__DATA.__objc_selrefs` | `0x9cf0` | `0x9e20` | **`+0x130`** |
| `__DATA.__objc_const` | `0x33ed8` | `0x33fc8` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x5068` | `0x5130` | **`+0xc8`** |
| `__TEXT.__gcc_except_tab` | `0x4f78` | `0x502c` | **`+0xb4`** |
| `__DATA_CONST.__const` | `0x4f00` | `0x4fa8` | **`+0xa8`** |
| `__DATA_CONST.__objc_arraydata` | `0x470` | `0x4a0` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x4201` | `0x4231` | **`+0x30`** |
| `__DATA_CONST.__objc_dictobj` | `0x208` | `0x230` | **`+0x28`** |
| `__DATA_CONST.__got` | `0xe38` | `0xe58` | **`+0x20`** |
| `__DATA_CONST.__objc_arrayobj` | `0x1b0` | `0x1c8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1630` | `0x1644` | **`+0x14`** |
| `__DATA.__data` | `0x2190` | `0x21a0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2230` | `0x2240` | **`+0x10`** |
| `__TEXT.__const` | `0x1568` | `0x1578` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1128` | `0x1130` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2467.2.2.0.0
+2467.40.37.0.0

-  Functions: 8351
-  Symbols:   1014
-  CStrings:  12452
+  Functions: 8411
+  Symbols:   1019
+  CStrings:  12534
Symbols:
+ _BMCarPlayConnectedIdentifier
+ _BMDeviceActivityPredictionIdentifier
+ _BMDeviceWirelessNFCTagIdentifier
+ _BMMediaNowPlayingIdentifier
+ _dispatch_assert_queue_not$V2
CStrings:
+ "%@ is %d"
+ "%{public}@: Process %d requested host-managed UI without the %{public}@ vouch"
+ "/carplay/connected"
+ "/device/activityPrediction"
+ "/device/nfcTagRead"
+ "/media/nowPlayingPlaybackState"
+ "@36@0:8@16i24d28"
+ "@52@0:8@16@24B32@36^@44"
+ "Adding %@ as stream for dasdDataCollection"
+ "App is not permitted to suppress system-vended progress UI."
+ "BAR re-enabled for %@"
+ "BARSchedulingDisabled"
+ "Convert stream: %@ : Failed to save %lu events: %@"
+ "Convert stream: %@ : Failed to save %lu final events: %@"
+ "Convert stream: %@ : Timed out waiting for conversion to complete"
+ "ERROR Submitting Activity: %@ due to configuration limits. Please contact us to prevent this activity from getting rejected. Configuration: %@"
+ "HostManagedProgressUI"
+ "Loaded trial parameter MLFreezerAllowListSpotlightEnabled: %d"
+ "MLFreezerAllowListSpotlightEnabled"
+ "Missing Tag"
+ "No bundleIdentifier was associated with the process handle, ignoring suspension update"
+ "Override status: %@"
+ "Remote Notification: %@ - BAR Scheduling Disabled by Trial"
+ "Siri AI"
+ "T@\"NSMutableSet\",&,N,V_suspendedBundleIDs"
+ "T@\"RBSProcessMonitor\",&,N,V_suspensionMonitor"
+ "TB,N,V_barSchedulingDisabledByTrial"
+ "TB,N,V_siriAIAllowListEnabled"
+ "TB,N,V_spotlightAllowListEnabled"
+ "TB,N,V_suspensionSendPending"
+ "Trial parameter MLFreezerAllowListSpotlightEnabled not found, using default: %d"
+ "Unable to resolve the client process handle; treating host-managed UI as unvouched"
+ "[%{public}@] Host manages its own UI; suppressing system-vended progress for %{public}@"
+ "[%{public}@] Not posting %@; host manages its own UI"
+ "_barSchedulingDisabledByTrial"
+ "_siriAIAllowListEnabled"
+ "_spotlightAllowListEnabled"
+ "_suspendedBundleIDs"
+ "_suspensionMonitor"
+ "_suspensionSendPending"
+ "activityPredictionEventForStream:eventBody:atTimestamp:"
+ "barSchedulingDisabledByTrial"
+ "confidenceLevel"
+ "currentStateMatchingDescriptor:"
+ "defaultPathIsInexpensive"
+ "defaultPathIsUnconstrained"
+ "directBiomeWriterStreamNames"
+ "handleSuspensionStateTransitionForProcess:withUpdate:"
+ "hasHostManagedProgressUIVouch"
+ "hostManagedProgressUI"
+ "initWithDKStreamIdentifier:"
+ "intervalEventForStream:openIntervalStartDate:starting:atTimestamp:newOpenIntervalStartDate:"
+ "isConstrained"
+ "isExpensive"
+ "isMindPalaceAmbientActivity"
+ "isMindPalaceUserInitiatedActivity"
+ "mindPalaceAmbient == 1"
+ "nfcTagEventForStream:atTimestamp:"
+ "nowPlayingEventForStream:playbackState:atTimestamp:"
+ "outputReason"
+ "playbackState"
+ "registerSuspensionMonitor"
+ "scheduleSuspensionSend"
+ "sendCachedFreezerRecommendationsOnSuspension"
+ "setBarSchedulingDisabledByTrial:"
+ "setSiriAIAllowListEnabled:"
+ "setSpotlightAllowListEnabled:"
+ "setSuspendedBundleIDs:"
+ "setSuspensionMonitor:"
+ "setSuspensionSendPending:"
+ "shouldPresentUIForActivity:"
+ "siriAIAllowListEnabled"
+ "spotlightAllowListEnabled"
+ "suspendedBundleIDs"
+ "suspensionMonitor"
+ "suspensionSendPending"
+ "tags"
+ "tagsVouchForHostManagedProgressUI:"
+ "v16@?0@\"_DKEvent\"8"
+ "v24@?0@?<v@?@\"_DKEvent\">8@?<v@?>16"
+ "writeActivityPredictionStream:toFileHandle:withEventPredicate:"
+ "writeCarPlayConnectedStream:toFileHandle:withEventPredicate:"
+ "writeDirectStreamName: %@ : Processed events are not valid JSON objects, skipping with error %@"
+ "writeDirectStreamName: %@ : Timed out waiting for write to complete, numberOfWrittenEvents may be an undercount"
+ "writeDirectStreamName: %@ : written %lu events, total written so far: %lu"
+ "writeDirectStreamName:toFileHandle:withEventPredicate:withEventProvider:"
+ "writeExperiment: %@ : stream %@ is in directBiomeWriterStreamNames but has no direct writer wired up"
+ "writeKeybagLockedStream:toFileHandle:withEventPredicate:"
+ "writeNFCTagStream:toFileHandle:withEventPredicate:"
+ "writeNowPlayingStream:toFileHandle:withEventPredicate:"
+ "writeStream: %@ : Timed out waiting for read to complete, numberOfWrittenEvents may be an undercount"
- "Campo"
- "ERROR Submitting Activity: %@ due to configuration limits. Please contact das-core@group.apple.com to prevent this activity from getting rejected. Configuration: %@"
- "TB,N,V_campoAllowListEnabled"
- "_campoAllowListEnabled"
- "campoAllowListEnabled"
- "convertKeybagLockedStream:toKnowledgeStoreStream:"
- "inexpensivePathAvailable"
- "initWithDKStreamIdentifier:contentProtection:"
- "setCampoAllowListEnabled:"
```
