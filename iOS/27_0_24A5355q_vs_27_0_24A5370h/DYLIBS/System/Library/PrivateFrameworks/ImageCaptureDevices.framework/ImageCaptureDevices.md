## ImageCaptureDevices

> `/System/Library/PrivateFrameworks/ImageCaptureDevices.framework/ImageCaptureDevices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a430` | `0x1a380` | **`-0xb0`** |

### Other Changes

```diff

-2112.0.0.0.0
+2113.0.0.0.0
Functions:
~ -[ICSessionManager sessionWithConnection:] : 348 -> 344
~ -[ICSessionManager removeSessionsWithProcessIdentifier:] : 348 -> 344
~ -[ICSessionManager removeAllSessions] : 276 -> 272
~ -[ICSessionManager connectionsMonitoringNotification:] : 628 -> 624
~ -[ICSessionManager connectionsMonitoringObjectID:] : 692 -> 688
~ -[ICSessionManager connections] : 320 -> 316
~ -[ICOrderedMediaSet initWithTypes:] : 376 -> 372
~ -[ICOrderedMediaSet mediaItemCount] : 312 -> 308
~ -[ICOrderedMediaSet removeMediaItemsFromIndex:] : 268 -> 264
~ -[ICOrderedMediaSet removeAllItems] : 292 -> 288
~ -[ICOrderedMediaSet mediaItemWithHandle:inTypes:] : 492 -> 488
~ -[ICOrderedMediaSet performSelector:onTypes:] : 504 -> 500
~ -[ICRemoteCameraDevice sendNotification:toConnections:selector:] : 752 -> 748
~ -[ICRemoteCameraDeviceManager remoteDeviceForUUID:] : 344 -> 340
~ -[ICRemoteCameraDeviceManager remoteDeviceForPrimaryIdentifier:] : 344 -> 340
~ -[ICRemoteCameraDeviceManager notifyClientDeviceAdded:uuidString:deviceName:] : 508 -> 504
~ -[ICRemoteCameraDeviceManager notifyClientDeviceRemoved:] : 492 -> 488
~ ___66-[ICRemoteCameraDeviceManager requestDeviceListWithOptions:reply:]_block_invoke : 612 -> 608
~ -[ICRemoteCameraDeviceManager removeRemoteManagerConnectionWithProcessIdentifier:] : 1276 -> 1260
~ -[ICRemoteCameraDeviceManager updateRemoteManagerConnectionWithProcessIdentifier:authorized:] : 400 -> 396
~ -[ICRemoteCameraDeviceManager remoteManagerConnectionWithProcessIdentifierAuthorized:] : 392 -> 388
~ -[PTPEventPacket initWithTCPBuffer:] : 220 -> 216
~ -[PTPEventPacket initWithUSBBuffer:] : 224 -> 220
~ -[PTPEventPacket contentForTCP] : 232 -> 228
~ -[PTPEventPacket contentForUSB] : 232 -> 228
~ -[PTPEventPacket contentForUSBUsingBuffer:capacity:] : 244 -> 240
~ -[PTPEventPacket description] : 224 -> 220
~ -[PTPOperationResponsePacket initWithResponseCode:transactionID:numParameters:parameters:] : 132 -> 140
~ -[PTPOperationResponsePacket initWithTCPBuffer:] : 220 -> 216
~ -[PTPOperationResponsePacket initWithUSBBuffer:] : 224 -> 220
~ -[PTPOperationResponsePacket contentForTCP] : 232 -> 228
~ -[PTPOperationResponsePacket contentForUSB] : 232 -> 228
~ -[PTPOperationResponsePacket contentForUSBUsingBuffer:capacity:] : 244 -> 240
~ _CopyUnicodeStringFromBuffer : 240 -> 232
~ -[ICDeviceAccessManager bundleIdentifiersAccessingExternalCameras] : 968 -> 964
~ -[ICDeviceAccessManager bundleIdentifiersAccessingExternalCamerasWithStatus] : 2896 -> 2888
~ _ICAcessQuery : 412 -> 416
~ _ICAcessStatusQuery : 420 -> 412
~ -[ICDeviceAccessManager bundleIdentifier:stateForAccessType:] : 808 -> 804
~ -[ICDeviceAccessManager validateBundleIdentifierInstalled:] : 1012 -> 1008
~ -[PTPOperationRequestPacket initWithOperationCode:transactionID:dataPhaseInfo:numParameters:parameters:] : 144 -> 152
~ -[PTPOperationRequestPacket initWithTCPBuffer:] : 232 -> 228
~ -[PTPOperationRequestPacket initWithUSBBuffer:] : 228 -> 224
~ -[PTPOperationRequestPacket contentForTCP] : 244 -> 240
~ -[PTPOperationRequestPacket contentForUSB] : 232 -> 228
~ -[PTPOperationRequestPacket contentForUSBUsingBuffer:capacity:] : 244 -> 240
```
