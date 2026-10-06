## callservicesd

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/callservicesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53ddac` | `0x53f778` | **`+0x19cc`** |
| `__TEXT.__objc_methname` | `0x70c67` | `0x70f37` | **`+0x2d0`** |
| `__TEXT.__objc_methtype` | `0x133a2` | `0x134a2` | **`+0x100`** |
| `__TEXT.__objc_stubs` | `0x3d920` | `0x3d9e0` | **`+0xc0`** |
| `__DATA.__objc_const` | `0x407b8` | `0x40868` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x1c39c` | `0x1c44c` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x53f93` | `0x54033` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x29ba0` | `0x29c30` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x28a40` | `0x28ac0` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0xbf00` | `0xbf60` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x13a48` | `0x13a98` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x9a6c` | `0x9a90` | **`+0x24`** |
| `__TEXT.__swift5_reflstr` | `0x8c40` | `0x8c50` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xf360` | `0xf370` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2088` | `0x2094` | **`+0xc`** |
| `__TEXT.__swift5_fieldmd` | `0x720c` | `0x7218` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
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

-1626.200.53.0.0
+1626.200.65.0.0

-  Functions: 29147
+  Functions: 29165

-  CStrings:  24608
+  CStrings:  24628
CStrings:
+ "@\"NSDictionary\"48@0:8@\"NSArray\"16@\"NSString\"24@\"IDSURI\"32@\"NSString\"40"
+ "B64@0:8@\"NSArray\"16@\"NSString\"24@\"IDSURI\"32@\"NSString\"40@\"OS_dispatch_queue\"48@?<v@?@\"NSDictionary\"@\"NSError\">56"
+ "Current remote device results: %@ for destinationIDs: %@, service: %@, fromIDURI: %@, error: %@"
+ "FaceTimeInviteDemuxer: an IDS query failed and no destinations were found via the others"
+ "None of the managing provider delegates implement a handler for action %@. Marking as failed"
+ "TB,N,V_hostCallEligibleToBeScreened"
+ "TB,N,V_relayHostProviderSupportsScreening"
+ "The IDS query failed, destination availability could not be determined for %@"
+ "Tq,N,V_relayHostCallScreeningEligibility"
+ "_currentCachedRemoteDevicesForDestinations:service:preferredFromID:listenerID:"
+ "_hostCallEligibleToBeScreened"
+ "_relayHostCallScreeningEligibility"
+ "_relayHostProviderSupportsScreening"
+ "_reportQueryFailedForCallUUID:providerErrorCode:actionDescription:"
+ "currentRemoteDevicesForDestinations:service:preferredFromID:listenerID:queue:completionBlockWithError:"
+ "hasHostCallEligibleToBeScreened"
+ "hasRelayHostProviderSupportsScreening"
+ "hostCallEligibleToBeScreened"
+ "join call action"
+ "relayHostCallScreeningEligibility"
+ "relayHostProviderSupportsScreening"
+ "setHasHostCallEligibleToBeScreened:"
+ "setHasRelayHostProviderSupportsScreening:"
+ "setHostCallEligibleToBeScreened:"
+ "setRelayHostCallScreeningEligibility:"
+ "setRelayHostProviderSupportsScreening:"
+ "start call action"
+ "tuRelayHostCallScreeningEligibility"
+ "{?=\"hostCallCreationTime\"b1\"messageSendTime\"b1\"hardPauseState\"b1\"protoDisconnectedReason\"b1\"protoOriginatingUIType\"b1\"protoPriority\"b1\"protoProtocolVersion\"b1\"protoService\"b1\"protoSoundRegion\"b1\"protoTTYType\"b1\"protoVerificationStatus\"b1\"receivedMessageType\"b1\"receptionistState\"b1\"requestActionType\"b1\"systemVolume\"b1\"type\"b1\"announcementHasFinished\"b1\"automaticCallActivationDisabled\"b1\"hostCallEligibleToBeScreened\"b1\"isLocalUserInHomeCountry\"b1\"isReceptionistCapable\"b1\"isScreening\"b1\"protoCallerIDBlocked\"b1\"protoCannotBeAnswered\"b1\"protoCannotRelayAudioOrVideoOnPairedDevice\"b1\"protoEmergency\"b1\"protoExpectedEndpointOnMessagingDevice\"b1\"protoFailureExpected\"b1\"protoNeedsManualInCallSounds\"b1\"protoRemoteUplinkMuted\"b1\"protoSOS\"b1\"protoShouldSuppressRingtone\"b1\"protoSupportsDTMFUpdates\"b1\"protoSupportsEmergencyFallback\"b1\"protoSupportsTTYWithVoice\"b1\"protoUplinkMuted\"b1\"protoVideo\"b1\"protoVoicemail\"b1\"protoWantsHoldMusic\"b1\"relayHostProviderSupportsScreening\"b1}"
+ "\xf0A"
+ "\xf0\x82\xf1"
- "Current remote device results: %@ for destinationIDs: %@, service: %@, fromIDURI: %@"
- "TB,N,V_relayHostCanScreen"
- "TB,R,N,V_relayHostCanScreen"
- "_relayHostCanScreen"
- "hasRelayHostCanScreen"
- "relayHostCanScreen"
- "setHasRelayHostCanScreen:"
- "setRelayHostCanScreen:"
- "{?=\"hostCallCreationTime\"b1\"messageSendTime\"b1\"hardPauseState\"b1\"protoDisconnectedReason\"b1\"protoOriginatingUIType\"b1\"protoPriority\"b1\"protoProtocolVersion\"b1\"protoService\"b1\"protoSoundRegion\"b1\"protoTTYType\"b1\"protoVerificationStatus\"b1\"receivedMessageType\"b1\"receptionistState\"b1\"requestActionType\"b1\"systemVolume\"b1\"type\"b1\"announcementHasFinished\"b1\"automaticCallActivationDisabled\"b1\"isLocalUserInHomeCountry\"b1\"isReceptionistCapable\"b1\"isScreening\"b1\"protoCallerIDBlocked\"b1\"protoCannotBeAnswered\"b1\"protoCannotRelayAudioOrVideoOnPairedDevice\"b1\"protoEmergency\"b1\"protoExpectedEndpointOnMessagingDevice\"b1\"protoFailureExpected\"b1\"protoNeedsManualInCallSounds\"b1\"protoRemoteUplinkMuted\"b1\"protoSOS\"b1\"protoShouldSuppressRingtone\"b1\"protoSupportsDTMFUpdates\"b1\"protoSupportsEmergencyFallback\"b1\"protoSupportsTTYWithVoice\"b1\"protoUplinkMuted\"b1\"protoVideo\"b1\"protoVoicemail\"b1\"protoWantsHoldMusic\"b1\"relayHostCanScreen\"b1}"
- "\xf01"
- "\xf0r\xf1"
```
