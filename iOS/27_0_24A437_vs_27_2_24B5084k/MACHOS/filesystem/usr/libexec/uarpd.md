## uarpd

> `/usr/libexec/uarpd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa42ac` | `0xa6600` | **`+0x2354`** |
| `__TEXT.__cstring` | `0xb112` | `0xb685` | **`+0x573`** |
| `__TEXT.__objc_stubs` | `0xa7a0` | `0xac40` | **`+0x4a0`** |
| `__TEXT.__objc_methname` | `0xf56a` | `0xf9fa` | **`+0x490`** |
| `__TEXT.__oslogstring` | `0x9566` | `0x987e` | **`+0x318`** |
| `__TEXT.__objc_methlist` | `0x8820` | `0x89c0` | **`+0x1a0`** |
| `__DATA.__objc_selrefs` | `0x3218` | `0x3340` | **`+0x128`** |
| `__DATA.__objc_const` | `0x10910` | `0x10a18` | **`+0x108`** |
| `__TEXT.__objc_methtype` | `0x2ad1` | `0x2b3a` | **`+0x69`** |
| `__TEXT.__unwind_info` | `0x2410` | `0x2470` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x10e0` | `0x1108` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x56a0` | `0x56c0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0xb74` | `0xb84` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x658` | `0x668` | **`+0x10`** |
| `__DATA_CONST.__objc_catlist` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__const` | `0x140` | `0x138` | **`-0x8`** |
| `__TEXT.__objc_classname` | `0x1d20` | `0x1d25` | **`+0x5`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1587.2.3.0.0
+1587.40.26.502.1

-  Functions: 3979
-  Symbols:   239
-  CStrings:  5013
+  Functions: 4025
+  Symbols:   241
+  CStrings:  5101
Symbols:
+ _OBJC_CLASS_$_NSHashTable
+ _OBJC_CLASS_$_UARPHostEndpointProperties
CStrings:
+ "%s: %@, %lu endpoint(s) with transport plumbed"
+ "%s: Cancelling inactivity timer for %@"
+ "%s: Created power assertion for %@"
+ "%s: Do not offer asset %@ to %@; reported no firmware available"
+ "%s: EndpointUUID %@; available firmware %@ is greater than active firmware %@"
+ "%s: EndpointUUID %@; available firmware %@, not greater than active firmware %@"
+ "%s: Failed to create power assertion for %@; error %d"
+ "%s: Failed to release power assertion for %@; error %d"
+ "%s: No Firmware Asset for endpoint %@"
+ "%s: No available firmware for endpointUUID is %@"
+ "%s: No power assertion to release for %@"
+ "%s: Not starting pruning timer, paused"
+ "%s: Pausing pruning timer"
+ "%s: Power assertion disabled for %@"
+ "%s: Previous power assertion created for %@"
+ "%s: Released power assertion for %@"
+ "%s: Releasing power assertion for %@"
+ "%s: Request to plumb transport for %@"
+ "%s: Resuming pruning timer"
+ "%s: Taking power assertion for %@"
+ "%s: Transport set to staging only for %@; checking version before requesting to plumb transport"
+ "%s: endpointUUID is %@, transportForStagingOnly is not set"
+ "%s: inactivity timer expired for %@"
+ "%s: no firmware available"
+ "-[UARPEndpointLayer3 noFirmwareAvailable]_block_invoke"
+ "-[UARPEndpointLayer3 notifyEndpointRemoteNotResponding]"
+ "-[UARPHostEndpoint activityTimerExpireForSource:]"
+ "-[UARPHostEndpoint hostEndpointAvailable:endpointProperties:]"
+ "-[UARPHostEndpoint hostEndpointNoFirmwareUpdateAvailable]"
+ "-[UARPHostEndpoint hostEndpointTransportAvailable:]"
+ "-[UARPHostEndpoint hostEntryDeviceCheckAvailableFirmware]"
+ "-[UARPHostEndpoint hostEntryDeviceInactivityTimeout]_block_invoke"
+ "-[UARPHostEndpoint hostEntryDeviceNoFirmwareUpdateAvailable]_block_invoke"
+ "-[UARPHostEndpoint layer3EndpointPersonalizationNeeded:asset:]_block_invoke"
+ "-[UARPHostEndpoint layer3EndpointRemoteNotResponding:]"
+ "-[UARPHostEndpoint powerAssertionCreate]"
+ "-[UARPHostEndpoint powerAssertionRelease]"
+ "-[UARPHostManager(HostEndpointNotifications) hostEndpointInactive:]"
+ "-[UARPHostManager(HostEndpointNotifications) hostEndpointTransportPlumbed:]"
+ "-[UARPHostManager(HostEndpointNotifications) hostEndpointTransportPlumbed:]_block_invoke"
+ "-[UARPHostManager(HostEndpointNotifications) hostEndpointTransportUnplumbed:]"
+ "-[UARPHostManager(HostEndpointNotifications) hostEndpointTransportUnplumbed:]_block_invoke"
+ "-[UARPHostManager(HostEndpointNotifications) hostEndpointUnresponsive:]"
+ "-[UARPHostManagerService(UARPEndpointControllerDelegate) uarpHostManagerServiceEndpointInactive:]"
+ "-[UARPHostManagerService(UARPEndpointControllerDelegate) uarpHostManagerServiceEndpointUnresponsive:]"
+ "-[UARPPrunerManager pausePruning]_block_invoke"
+ "-[UARPPrunerManager resumePruning]_block_invoke"
+ "-[UARPPrunerManager startPruningInternal]"
+ "@\"NSHashTable\""
+ "Endpoint %@: Remote Not Responding"
+ "PreventUserIdleSystemSleep"
+ "TB,R,V_blockFirmwareUpdate"
+ "UARP"
+ "^{uarpPlatformEndpoint={uarpPlatformOptionsObj=IIISCSSSiSSCSCC}^v{uarpPlatformEndpointCallbacks=^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?}C^viI^^{uarpPlatformRemoteEndpoint}^{uarpPlatformAsset}iCi^?S^{uarpLayer2EndpointIDInfo}S^{uarpDownstreamEndpointObj}I^{uarpMemoryTracker}}"
+ "_activityTimer"
+ "_blockFirmwareUpdate"
+ "_kQueueKey"
+ "_paused"
+ "_transportPlumbedEndpoints"
+ "activeFirmwareVersionInternal"
+ "activityTimerCancel"
+ "activityTimerCancelOnQueue"
+ "activityTimerExpireForSource:"
+ "activityTimerReset"
+ "blockFirmwareUpdate"
+ "endpointControllerDelegateEndpointInactive:"
+ "endpointControllerDelegateEndpointUnresponsive:"
+ "hashTableWithOptions:"
+ "hostEndpointAvailable:endpointProperties:"
+ "hostEndpointDelegateInactivityTimeout:"
+ "hostEndpointDelegateNoFirmwareUpdateAvailable:"
+ "hostEndpointInactive:"
+ "hostEndpointNoFirmwareUpdateAvailable"
+ "hostEndpointTransportAvailable:"
+ "hostEndpointTransportPlumbed:"
+ "hostEndpointTransportUnplumbed:"
+ "hostEndpointUnresponsive:"
+ "hostEntryDeviceCheckAvailableFirmware"
+ "hostEntryDeviceInactivityTimeout"
+ "hostEntryDeviceNoFirmwareUpdateAvailable"
+ "isMatchingUUID:"
+ "layer2CallbackRemoteNotResponding:length:"
+ "layer3EndpointRemoteNotResponding:"
+ "noFirmwareAvailable"
+ "noSleepWhileStaging"
+ "notifyEndpointRemoteNotResponding"
+ "numPacketRetries"
+ "pausePruning"
+ "resumePruning"
+ "setTransportForStagingOnly:"
+ "startPruningInternal"
+ "timeoutActivity"
+ "timeoutPacketRetry"
+ "transportForStagingOnly"
+ "uarpHostManagerServiceEndpointInactive:"
+ "uarpHostManagerServiceEndpointUnresponsive:"
+ "v28@0:8*16I24"
+ "v32@0:8@\"NSUUID\"16@\"UARPHostEndpointProperties\"24"
+ "{uarpPlatformEndpointCallbacks=\"fRequestBuffer\"^?\"fReturnBuffer\"^?\"fRequestAssetBuffer\"^?\"fReturnAssetBuffer\"^?\"fRequestTransmitMsgBuffer\"^?\"fReturnTransmitMsgBuffer\"^?\"fSendMessage\"^?\"fDataTransferPause\"^?\"fDataTransferPauseAck\"^?\"fDataTransferResume\"^?\"fDataTransferResumeAck\"^?\"fSuperBinaryOffered\"^?\"fDynamicAssetOffered\"^?\"fApplyStagedAssets\"^?\"fApplyStagedAssetsResponse\"^?\"fManufacturerName\"^?\"fManufacturerNameResponse\"^?\"fModelName\"^?\"fModelNameResponse\"^?\"fSerialNumber\"^?\"fSerialNumberResponse\"^?\"fHardwareVersion\"^?\"fHardwareVersionResponse\"^?\"fActiveFirmwareVersion2\"^?\"fActiveFirmwareVersionResponse\"^?\"fStagedFirmwareVersion2\"^?\"fStagedFirmwareVersionResponse\"^?\"fLastError\"^?\"fLastErrorResponse\"^?\"fStatisticsResponse\"^?\"fAssetSolicitation\"^?\"fRescindAllAssets\"^?\"fRescindAllAssetsAck\"^?\"fLayer2WatchdogSet\"^?\"fLayer2WatchdogCancel\"^?\"fRemoteNotResponding\"^?\"fMonotonicClockTime\"^?\"fProtocolVersion\"^?\"fFriendlyName\"^?\"fFriendlyNameResponse\"^?\"fDiscoveredEndpointID\"^?\"fDiscoveredComponent\"^?\"fBulkInfoQuery\"^?\"fBulkInfoResponse\"^?\"fDecompressBuffer\"^?\"fCompressBuffer\"^?\"fHashInfo\"^?\"fHashInit\"^?\"fHashUpdate\"^?\"fHashFinal\"^?\"fHashLog\"^?\"fLogPacket\"^?\"fLogError\"^?\"fLogInfo\"^?\"fLogDebug\"^?\"fLogFault\"^?\"fDownstreamDiscovery\"^?\"fDownstreamReachable3\"^?\"fDownstreamUnreachable2\"^?\"fDownstreamReleased2\"^?\"fDownstreamRecvMessage\"^?\"fNoFirmwareUpdateAvailable\"^?\"fVendorSpecificRecvMsg\"^?\"fVendorSpecificCheckExpectedResponse\"^?\"fVendorSpecificCheckValidToSend\"^?\"fVendorSpecificExceededRetries\"^?\"fActiveFirmwareVersion\"^?\"fStagedFirmwareVersion\"^?\"fTxWatchdogSet\"^?\"fTxWatchdogCancel\"^?\"fDownstreamReachable\"^?\"fDownstreamReachable2\"^?\"fDownstreamUnreachable\"^?\"fDownstreamReleased\"^?}"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xc31"
- "%s: Request to plumb transport for %@, based on transport policy of %ld"
- "%s: Starting TapToRadar flow if upstream endpoint is in process for %@"
- "%s: Transport Release Policy is Immediate for %@; checking version before requesting to plumb transport"
- "%s: endpointUUID is %@, release transport immediately"
- "%s: endpointUUID is %@, transport release policy is %ld"
- "-[UARPHostEndpoint hostEndpointAvailable:releasePolicy:endpointProperties:]"
- "-[UARPHostEndpoint hostEndpointTransportAvailable:releasePolicy:]"
- "-[UARPPrunerManager startPruning]_block_invoke"
- "^{uarpPlatformEndpoint={uarpPlatformOptionsObj=IIISCSSSiSSCSCC}^v{uarpPlatformEndpointCallbacks=^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?^?}C^viI^^{uarpPlatformRemoteEndpoint}^{uarpPlatformAsset}iCi^?S^{uarpLayer2EndpointIDInfo}S^{uarpDownstreamEndpointObj}I^{uarpMemoryTracker}}"
- "_transportReleasePolicy"
- "{uarpPlatformEndpointCallbacks=\"fRequestBuffer\"^?\"fReturnBuffer\"^?\"fRequestAssetBuffer\"^?\"fReturnAssetBuffer\"^?\"fRequestTransmitMsgBuffer\"^?\"fReturnTransmitMsgBuffer\"^?\"fSendMessage\"^?\"fDataTransferPause\"^?\"fDataTransferPauseAck\"^?\"fDataTransferResume\"^?\"fDataTransferResumeAck\"^?\"fSuperBinaryOffered\"^?\"fDynamicAssetOffered\"^?\"fApplyStagedAssets\"^?\"fApplyStagedAssetsResponse\"^?\"fManufacturerName\"^?\"fManufacturerNameResponse\"^?\"fModelName\"^?\"fModelNameResponse\"^?\"fSerialNumber\"^?\"fSerialNumberResponse\"^?\"fHardwareVersion\"^?\"fHardwareVersionResponse\"^?\"fActiveFirmwareVersion2\"^?\"fActiveFirmwareVersionResponse\"^?\"fStagedFirmwareVersion2\"^?\"fStagedFirmwareVersionResponse\"^?\"fLastError\"^?\"fLastErrorResponse\"^?\"fStatisticsResponse\"^?\"fAssetSolicitation\"^?\"fRescindAllAssets\"^?\"fRescindAllAssetsAck\"^?\"fLayer2WatchdogSet\"^?\"fLayer2WatchdogCancel\"^?\"fMonotonicClockTime\"^?\"fProtocolVersion\"^?\"fFriendlyName\"^?\"fFriendlyNameResponse\"^?\"fDiscoveredEndpointID\"^?\"fDiscoveredComponent\"^?\"fBulkInfoQuery\"^?\"fBulkInfoResponse\"^?\"fDecompressBuffer\"^?\"fCompressBuffer\"^?\"fHashInfo\"^?\"fHashInit\"^?\"fHashUpdate\"^?\"fHashFinal\"^?\"fHashLog\"^?\"fLogPacket\"^?\"fLogError\"^?\"fLogInfo\"^?\"fLogDebug\"^?\"fLogFault\"^?\"fDownstreamDiscovery\"^?\"fDownstreamReachable3\"^?\"fDownstreamUnreachable2\"^?\"fDownstreamReleased2\"^?\"fDownstreamRecvMessage\"^?\"fNoFirmwareUpdateAvailable\"^?\"fVendorSpecificRecvMsg\"^?\"fVendorSpecificCheckExpectedResponse\"^?\"fVendorSpecificCheckValidToSend\"^?\"fVendorSpecificExceededRetries\"^?\"fActiveFirmwareVersion\"^?\"fStagedFirmwareVersion\"^?\"fTxWatchdogSet\"^?\"fTxWatchdogCancel\"^?\"fDownstreamReachable\"^?\"fDownstreamReachable2\"^?\"fDownstreamUnreachable\"^?\"fDownstreamReleased\"^?}"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xb31"
```
