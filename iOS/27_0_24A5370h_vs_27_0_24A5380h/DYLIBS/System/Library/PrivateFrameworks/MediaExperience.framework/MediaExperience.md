## MediaExperience

> `/System/Library/PrivateFrameworks/MediaExperience.framework/MediaExperience`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e5e5c` | `0x2e8944` | **`+0x2ae8`** |
| `__AUTH.__objc_data` | `0x14a0` | `0x1d10` | **`+0x870`** |
| `__DATA_DIRTY.__objc_data` | `0x960` | `0x190` | **`-0x7d0`** |
| `__TEXT.__oslogstring` | `0x77b7f` | `0x782da` | **`+0x75b`** |
| `__TEXT.__cstring` | `0x4dfab` | `0x4e3ed` | **`+0x442`** |
| `__AUTH_CONST.__objc_const` | `0xcb60` | `0xce50` | **`+0x2f0`** |
| `__AUTH_CONST.__cfstring` | `0x1c220` | `0x1c360` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x8628` | `0x8748` | **`+0x120`** |
| `__DATA_CONST.__got` | `0xc40` | `0xd08` | **`+0xc8`** |
| `__DATA_CONST.__objc_selrefs` | `0x5328` | `0x53a8` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x72d8` | `0x7330` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x6318` | `0x6370` | **`+0x58`** |
| `__DATA.__objc_ivar` | `0xc40` | `0xc64` | **`+0x24`** |
| `__AUTH_CONST.__const` | `0x48c8` | `0x48e8` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x518c` | `0x51a8` | **`+0x1c`** |
| `__DATA.__bss` | `0x1298` | `0x12b0` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x300` | `0x310` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x2d0` | `0x2e0` | **`+0x10`** |
| `__DATA.__data` | `0x1400` | `0x1408` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0xd98` | `0xd90` | **`-0x8`** |

### Other Changes

```diff

-360.63.1.11.2
+360.66.1.11.1

-  Functions: 11510
-  Symbols:   13648
-  CStrings:  14129
+  Functions: 11549
+  Symbols:   13712
+  CStrings:  14173
Symbols:
+ +[MXCustomRoutingSessionController sharedInstance]
+ +[MXSystemController(InternalUse) copyPayloadToPost:notificationPayload:systemController:]
+ -[AVSystemController associateProcessesForPIDInheritance:processToInheritStateFrom:]
+ -[MXCustomRoutingSession bundleID]
+ -[MXCustomRoutingSession dealloc]
+ -[MXCustomRoutingSession description]
+ -[MXCustomRoutingSession initWithPID:bundleID:]
+ -[MXCustomRoutingSession isPlaying]
+ -[MXCustomRoutingSession pid]
+ -[MXCustomRoutingSession setPlaying:]
+ -[MXCustomRoutingSessionController currentSession]
+ -[MXCustomRoutingSessionController dealloc]
+ -[MXCustomRoutingSessionController setCurrentSession:]
+ -[MXResolvedEndpoint ipv4Strings]
+ -[MXResolvedEndpoint ipv6Strings]
+ -[MXResolvedEndpoint setIpv4Strings:]
+ -[MXResolvedEndpoint setIpv6Strings:]
+ -[MXSystemCastingControllerServer_ClientInformation currentSession]
+ -[MXSystemCastingControllerServer_ClientInformation mBundleID]
+ -[MXSystemCastingControllerServer_ClientInformation mPID]
+ -[MXSystemCastingControllerServer_ClientInformation setCurrentSession:]
+ -[MXSystemController applyProcessAssociation:]
+ -[MXSystemController clientWantsLegacyRingtoneVolumeScaling]
+ -[MXSystemController pidToInheritAppState]
+ -[MXSystemController setClientWantsLegacyRingtoneVolumeScaling:]
+ -[MXSystemController setPidToInheritAppState:]
+ GCC_except_table121
+ GCC_except_table123
+ _MXCustomRoutingSessionPlayingDidChangeNotification
+ _MXResolvedEndpointIPArraysOverlap
+ _MXResolvedEndpointMergeIPArrays
+ _OBJC_CLASS_$_MXCustomRoutingSession
+ _OBJC_CLASS_$_MXCustomRoutingSessionController
+ _OBJC_CLASS_$_NSKeyedArchiver
+ _OBJC_CLASS_$_UTTypeCodingBox
+ _OBJC_IVAR_$_MXCustomRoutingSession._bundleID
+ _OBJC_IVAR_$_MXCustomRoutingSession._pid
+ _OBJC_IVAR_$_MXCustomRoutingSession._playing
+ _OBJC_IVAR_$_MXCustomRoutingSessionController._currentSession
+ _OBJC_IVAR_$_MXResolvedEndpoint._ipv4Strings
+ _OBJC_IVAR_$_MXResolvedEndpoint._ipv6Strings
+ _OBJC_IVAR_$_MXSystemCastingControllerServer_ClientInformation._currentSession
+ _OBJC_IVAR_$_MXSystemCastingControllerServer_ClientInformation._mBundleID
+ _OBJC_IVAR_$_MXSystemCastingControllerServer_ClientInformation._mPID
+ _OBJC_IVAR_$_MXSystemController._clientWantsLegacyRingtoneVolumeScaling
+ _OBJC_IVAR_$_MXSystemController._pidToInheritAppState
+ _OBJC_METACLASS_$_MXCustomRoutingSession
+ _OBJC_METACLASS_$_MXCustomRoutingSessionController
+ _PVMCalculateVolumeAlignedToSliderPosition
+ __OBJC_$_CLASS_METHODS_MXCustomRoutingSessionController
+ __OBJC_$_INSTANCE_METHODS_MXCustomRoutingSession
+ __OBJC_$_INSTANCE_METHODS_MXCustomRoutingSessionController
+ __OBJC_$_INSTANCE_VARIABLES_MXCustomRoutingSession
+ __OBJC_$_INSTANCE_VARIABLES_MXCustomRoutingSessionController
+ __OBJC_$_PROP_LIST_MXCustomRoutingSession
+ __OBJC_$_PROP_LIST_MXCustomRoutingSessionController
+ __OBJC_CLASS_RO_$_MXCustomRoutingSession
+ __OBJC_CLASS_RO_$_MXCustomRoutingSessionController
+ __OBJC_METACLASS_RO_$_MXCustomRoutingSession
+ __OBJC_METACLASS_RO_$_MXCustomRoutingSessionController
+ ___50+[MXCustomRoutingSessionController sharedInstance]_block_invoke
+ ___block_descriptor_56_e8_32o40o48r_e22_v16?0"NSDictionary"8lr48l8s32l8s40l8
+ _fsm_requestResourceModeChangeUnborrowWithoutBorrowID
+ _gActiveClient
+ _kFigEndpointDescriptorKey_ProtocolTypeArchive
+ _kFigSystemControllerProperty_ProcessesToAssociateForInheritance
+ _kMXSystemControllerProperty_ProcessesToAssociateForInheritance
+ _kMXSystemController_ProcessesToAssociateForInheritanceKey_ProcessToInheritState
+ _kMXSystemController_ProcessesToAssociateForInheritanceKey_ProcessToInheritStateFrom
+ _mxsc_fetchCanInheritApplicationStateFromOtherProcesses
+ _mxsmccs_ClearActiveClientIfMatches
+ _mxsmccs_UpdateActiveClientPlaying
- -[MXResolvedEndpoint ipv4String]
- -[MXResolvedEndpoint ipv6String]
- -[MXResolvedEndpoint setIpv4String:]
- -[MXResolvedEndpoint setIpv6String:]
- GCC_except_table102
- GCC_except_table44
- _OBJC_IVAR_$_MXResolvedEndpoint._ipv4String
- _OBJC_IVAR_$_MXResolvedEndpoint._ipv6String
CStrings:
+ "-AVSystemController- %s: Associating %d with %d"
+ "-CMSMUtilities- %s: NOTICE: PIDToInheritAppStateFrom changed from %d to %d."
+ "-FigEndpointDescriptorUtility- %s: Failed to archive UTTypeCodingBox for %{public}@: %{public}@"
+ "-FigRoutingManager- %s:   SubEndpoint[%ld]: name=%{public}@, routeUID=%{private}@"
+ "-MDENetworkPolicyEngine- %s: Building per-endpoint LAN policy. UUID=%{public}@ hostname=%{public}@ ipv4=%{public}@ ipv6=%{public}@ port=%u"
+ "-MDENetworkPolicyEngine- %s: Failed to allocate policy for IPv4 %{public}@"
+ "-MDENetworkPolicyEngine- %s: Failed to allocate policy for IPv6 %{public}@"
+ "-MDENetworkPolicyEngine- %s: Failed to get NWAddressEndpoint for IPv4 %{public}@"
+ "-MDENetworkPolicyEngine- %s: Failed to get NWAddressEndpoint for IPv6 %{public}@"
+ "-MDENetworkPolicyEngine- %s: Failed to get condition for IPv4 %{public}@"
+ "-MDENetworkPolicyEngine- %s: Failed to get condition for IPv6 %{public}@"
+ "-MXCustomRoutingSession- %s: playing changed from: %{BOOL}u to: %{BOOL}u for: %{public}@"
+ "-MXCustomRoutingSessionController- %s: currentSession changed. previousSession: %{public}@. currentSession: %{public}@."
+ "-MXDeviceResolver- %s: MXDeviceResolver: _resolveEndpoint — deviceID: %{public}@, protocolType: %{public}@, bonjourName: %{public}@, bonjourServiceType: %{public}@, bonjourDomain: %{public}@, bonjourFullName: %{public}@, bonjourHostname: %{public}@, hostname: %{public}@, ipv4Strings: %{public}@, ipv6Strings: %{public}@, port: %u"
+ "-MXDeviceResolver- %s: MXDeviceResolver: _resolveEndpoint — promoted literal IPv4 hostname to ipv4Strings=%{public}@ port=%u"
+ "-MXSystemController- %s: Applying process association: prevPidToInheritState = %d, prevPidToInheritStateFrom = %d, pidToInheritAppState = %d, pidToInheritAppStateFrom = %d"
+ "-MXSystemMediaCastingController_Server- %s: Cleared active client because it disposed."
+ "-MXSystemMediaCastingController_Server- %s: Cleared active client because it stopped its application."
+ "-MXSystemMediaCastingRTCReportingAgent- %s: Reporting activationErrorCode: %ld (%{public}@)"
+ "-MXSystemMediaCastingRTCReportingAgent- %s: Reporting discoveryErrorCode: %ld (%{public}@)"
+ "-MXSystemMediaCastingRTCReportingAgent- %s: Reporting playbackErrorCode: %ld (%{public}@)"
+ "-MXSystemMediaCastingRTCReportingAgent- %s: Reporting playbackRealtimeErrorCode: %ld (%{public}@)"
+ "-[AVSystemController associateProcessesForPIDInheritance:processToInheritStateFrom:]"
+ "-[MXCustomRoutingSession setPlaying:]"
+ "-[MXCustomRoutingSessionController setCurrentSession:]"
+ "-[MXSystemCastingRTCReportingAgent recordActivated]_block_invoke"
+ "-[MXSystemCastingRTCReportingAgent recordDiscoveryEnded]_block_invoke"
+ "-[MXSystemCastingRTCReportingAgent recordPlaybackEnded]_block_invoke"
+ "-[MXSystemCastingRTCReportingAgent recordPlaybackRealtimeEnded]_block_invoke"
+ "-[MXSystemController applyProcessAssociation:]"
+ "-stark mode- %s: We did not find borrower matching borrowID %{public}@ in the array list, unborrow last borrowed resource by requestor"
+ "21:27:17"
+ ":"
+ "<MXCustomRoutingSession: %p> pid: %d bundleID: %@ playing: %@"
+ "Attribute is not of type NSDictionary"
+ "Endpoint[%ld]: %@ (%@) "
+ "Failed to set ProcessesToAssociateForInheritance"
+ "Jun 29 2026"
+ "MXCustomRoutingSessionControllerCurrentSessionDidChangeNotification"
+ "MXCustomRoutingSessionPlayingDidChangeNotification"
+ "Nil attribute value"
+ "ProcessToInheritState"
+ "ProcessToInheritState must have a valid value"
+ "ProcessToInheritStateFrom"
+ "ProcessToInheritStateFrom must have a valid value"
+ "ProcessesToAssociateForInheritance"
+ "ProtocolTypeArchive"
+ "[%@] Updating from old route descriptors: "
+ "entitlement missing to associate processes"
+ "isPlaying"
+ "pidToInheritState is not NSNumber"
+ "pidToInheritStateFrom is not NSNumber"
+ "to new route descriptors: "
- " to new route descriptors: "
- "-CMSMUtilities- %s: NOTICE: PIDToInheritAppStateFrom changed from %d to %d without stopping previous monitoring."
- "-MXDeviceResolver- %s: MXDeviceResolver: _resolveEndpoint — deviceID: %{public}@, protocolType: %{public}@, bonjourName: %{public}@, bonjourServiceType: %{public}@, bonjourDomain: %{public}@, bonjourFullName: %{public}@, bonjourHostname: %{public}@, hostname: %{public}@, ipv4String: %{public}@, ipv6String: %{public}@, port: %u"
- "-stark mode- %s: We did not find borrower matching borrowID %{public}@ in the array list, treating as no-op"
- "21:51:30"
- "Endpoint[%ld]: %@"
- "Failed to get an NWAddressEndpoint back"
- "Jun 16 2026"
- "Updating from old route descriptors: "
```
