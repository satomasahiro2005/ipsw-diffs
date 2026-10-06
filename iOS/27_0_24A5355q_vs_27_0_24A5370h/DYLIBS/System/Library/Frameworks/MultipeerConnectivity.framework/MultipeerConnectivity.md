## MultipeerConnectivity

> `/System/Library/Frameworks/MultipeerConnectivity.framework/MultipeerConnectivity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e680` | `0x2e6f0` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x2dc` | `0x2e0` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ __Z20AGPTransportCallbackPvPjiPhiiS1_ihhhi : 1208 -> 1180
~ _TracePrintNodes : 712 -> 692
~ -[NSArray(MCSession_copyDeep_MC) copyDeep_MC] : 236 -> 240
~ -[MCSessionPeerConnectionData parseConnectionDataBlob:] : 376 -> 380
~ -[MCSession syncCloseStreamsForPeer:] : 720 -> 712
~ -[MCSession syncDetailedDescription] : 736 -> 732
~ -[MCSession syncConnectedPeersCount] : 260 -> 256
~ -[MCSession syncHandleNetworkEvent:pid:freeEventWhenDone:] : 7836 -> 7828
~ -[MCSession dealloc] : 424 -> 420
~ -[MCSession syncSendData:toPeers:withDataMode:] : 560 -> 556
~ ___45-[MCSession sendData:toPeers:withMode:error:]_block_invoke : 300 -> 296
~ ___27-[MCSession connectedPeers]_block_invoke : 288 -> 284
~ -[MCNearbyDiscoveryPeerConnection syncAcceptedConnection] : 532 -> 528
~ -[MCNearbyDiscoveryPeerConnection syncProcessMessage:data:sequenceNumber:] : 2432 -> 2436
~ -[MCBrowserViewController handleViewWillAppear] : 384 -> 380
~ _gckSessionUpdateRoutingTable : 908 -> 900
~ _gckSessionDisposeAllConnections : 500 -> 512
~ _GCKSessionPrepareConnection : 3888 -> 3856
~ _gckSessionChangeStateCList : 3080 -> 3156
~ _GCKSessionSendTo : 1332 -> 1312
~ _gckSessionFindNextHop : 120 -> 136
~ ___SendUDPPacketCList_block_invoke : 624 -> 632
~ _gckSessionUpdateNode : 204 -> 212
~ _gckSessionCheckPendingConnections : 368 -> 384
~ _gckSessionRecvMessage : 4504 -> 4468
~ _gckSessionProcessDD : 2048 -> 2060
~ _gckSessionProcessLSA : 2548 -> 2692
~ _gckIsNewInformationAvailableForParticipant : 184 -> 196
~ _gckPreemptivelyClearFlagsForTransientNodes : 252 -> 260
~ _gckSessionHandleRemainingDisconnectedNodes : 320 -> 328
~ _gckSessionDisconnectParticipant : 316 -> 312
~ _gckSessionHandleDeletedNode : 340 -> 356
~ -[MCNearbyServiceAdvertiser makeTXTRecordDataWithDiscoveryInfo:] : 400 -> 396
~ -[MCNearbyServiceAdvertiser txtRecordDataWithDiscoveryInfo:] : 344 -> 340
~ -[MCNearbyServiceAdvertiser syncStartAdvertisingPeer] : 588 -> 584
~ -[MCNearbyServiceBrowser dealloc] : 556 -> 552
~ -[MCNearbyServiceBrowser syncStartBrowsingForPeers] : 1000 -> 988
~ -[MCNearbyServiceBrowser syncHandleDeclinedInviteWithInfo:] : 428 -> 424
~ ___72-[MCNearbyServiceBrowser netServiceBrowser:didRemoveService:moreComing:]_block_invoke : 524 -> 520
~ -[MCNearbyServiceBrowser rebuildUserDiscoveryInfoFromTXTRecordDictionary:] : 488 -> 484
~ -[MCNearbyDiscoveryPeer flushDataBuffer] : 780 -> 772
~ __ZN20AGPSendingSetElement6searchEj : 120 -> 116
~ __ZN20AGPSendingSetElement6removeEh : 444 -> 448
~ __Z15checkSendingSetPKvPv : 516 -> 508
~ __ZN12AGPDataQueue10disconnectEPji : 240 -> 232
~ _AGPSessionSendTo : 1220 -> 1204
~ __Z18AGPSessionRecvFromP4CAGPjP15GCKSessionEventi : 3672 -> 3648
~ __ZN24AGPAssociationSetElementC2EP4CAGP : 328 -> 336
~ __ZN24AGPAssociationSetElementD2Ev : 148 -> 168
~ _OSPFMakeDD : 616 -> 632
~ _OSPFMakeLSA : 752 -> 760
~ _OSPFMakeData : 424 -> 440
~ _ospfVerifyOptions : 828 -> 832
~ _OSPFParse : 3052 -> 3044
CStrings:
+ "19:17:20"
+ "19:17:32"
+ "Jun  9 2026"
- "10:08:00"
- "10:08:08"
- "May 21 2026"
```
