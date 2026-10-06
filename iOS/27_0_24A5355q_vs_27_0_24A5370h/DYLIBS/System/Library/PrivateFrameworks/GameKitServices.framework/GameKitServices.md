## GameKitServices

> `/System/Library/PrivateFrameworks/GameKitServices.framework/GameKitServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x76e4c` | `0x76e28` | **`-0x24`** |
| `__AUTH_CONST.__auth_got` | `0x9c0` | `0x9b8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xfc0` | `0xfb8` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2235.48.1.0.0
+2235.52.1.11.1

-  Symbols:   2440
+  Symbols:   2439
Symbols:
- _objc_release_x27
Functions:
~ _rijndaelKeySetupEnc : 684 -> 676
~ __ZL9poly_hashP9uhash_ctxPj : 204 -> 208
~ __ZL7ip_longP9uhash_ctxPc : 156 -> 152
~ _uhash : 460 -> 456
~ _umac_new : 692 -> 720
~ __ZL6nh_auxPvS_S_j : 348 -> 336
~ _CDXGetPreblobLength : 68 -> 64
~ __ZN20AGPSendingSetElement6searchEj : 120 -> 116
~ __Z15checkSendingSetPKvPv : 1040 -> 1032
~ __Z20AGPTransportCallbackPvPjiPhiS1_ihhh : 2064 -> 2124
~ __ZN12AGPDataQueue10disconnectEPji : 236 -> 224
~ _AGPSessionSendTo : 1268 -> 1252
~ __Z18AGPSessionRecvFromP4CAGPjP15GCKSessionEvent : 9804 -> 9940
~ _AGPSessionBroadcast : 468 -> 484
~ __ZN24AGPAssociationSetElementC2EP4CAGP : 340 -> 348
~ __ZN24AGPAssociationSetElementD2Ev : 144 -> 164
~ _TracePrintChanStats : 2324 -> 2316
~ _GCKSession_TrimLocalInterfaceList : 1456 -> 1476
~ _GCKSessionRelease : 2168 -> 2152
~ _gckSessionRecvProc : 9012 -> 8924
~ _gckRegisterForNetworkChanges : 2248 -> 2244
~ _GCKSessionConnectToLocalService : 1320 -> 1324
~ _gckSessionAddNode : 340 -> 344
~ _gckSessionLocalClientProc : 5232 -> 5124
~ _gckSessionDeleteNode : 480 -> 516
~ _gckSessionDisconnectNeighbor : 736 -> 752
~ _GCKSessionPrepareConnectionWithRelayInfo : 2168 -> 2152
~ _gckHandleRetryICEReport : 1828 -> 1840
~ _xdr_chanstat_node : 408 -> 424
~ _gckSessionChangeStateCList : 2264 -> 2312
~ _GCKSessionSendTo : 1744 -> 1760
~ _gckSessionFindNextHop : 120 -> 136
~ _GCKSessionSendAudioTo : 904 -> 852
~ _gckSessionUpdateNode : 204 -> 208
~ _gckSessionCheckPendingConnections : 468 -> 484
~ _TracePrintNodesX : 972 -> 932
~ _gckSessionLocalServerProc : 2880 -> 2884
~ _gckSessionRecvMessage : 5892 -> 5880
~ _gckSessionRecvTCPMessage : 2288 -> 2260
~ _gckSessionProcessDD : 3572 -> 3580
~ _gckSessionProcessLSA : 3264 -> 3320
~ _TracePrintNodes : 932 -> 916
~ _isInNeighbor : 392 -> 388
~ _gckSessionCleanupNodes : 1764 -> 1768
~ _gckNetworkMonitorCallback : 4776 -> 4796
~ _gckDisplayNetworkState : 1420 -> 1416
~ -[GKConnectionInternal dealloc] : 788 -> 784
~ -[GKConnectionInternal connectParticipantsWithConnectionData:withSessionInfo:] : 2756 -> 2752
~ -[GKConnectionInternal setEventDelegate:] : 948 -> 944
~ -[GKConnectionInternal setParticipantID:forPeerID:] : 808 -> 804
~ -[GKConnectionInternal networkStatistics] : 764 -> 760
~ -[GKConnectionInternal getLocalConnectionDataForLocalGaming] : 788 -> 808
~ -[GKList hasID:] : 108 -> 116
~ -[GKList addID:] : 408 -> 416
~ -[GKList copyItemsInto:] : 116 -> 112
~ -[GKList removeID:] : 128 -> 124
~ -[GKList allMatchingObjectsFromTable:] : 156 -> 152
~ -[GKList print] : 196 -> 192
~ -[GKTable allObjects] : 156 -> 148
~ -[GKTable setObject:forKey:] : 968 -> 952
~ -[GKTable touchObject:] : 148 -> 140
~ -[GKTable touchObjectForKey:] : 140 -> 132
~ -[GKTable removeObjectForKey:] : 460 -> 456
~ -[GKTable removeAllObjects] : 168 -> 160
~ -[GKTable makeObjectsPerformSelector:] : 148 -> 140
~ -[GKTable makeObjectsPerformSelector:withObject:] : 164 -> 148
~ -[GKTable print] : 304 -> 296
~ -[GKSessionInternal(_private) serviceName] : 200 -> 196
~ -[GKSessionInternal(callback) sendCallbacksToDelegate:remotePeer:] : 9712 -> 9700
~ _NSStringCreateTruncatedStringWithMaxBytesInUTF8Encoding : 160 -> 164
~ -[GKSessionInternal initWithSessionID:displayName:session:sessionMode:] : 2136 -> 2128
~ -[GKSessionInternal setAvailable:] : 1932 -> 1940
~ -[GKSessionInternal tryConnectToPeer:] : 1820 -> 1808
~ +[GKPeerInternal freeLookupList:andAddrList:andInterfaceList:count:] : 132 -> 136
~ -[GKPeerInternal containsLookupService:] : 316 -> 324
~ -[GKPeerInternal setAddr:interface:forLookupService:] : 1080 -> 1072
~ -[GKPeerInternal usableAddrs] : 64 -> 72
~ -[GKPeerInternal stopResolving] : 1168 -> 1160
~ -[GKSessionGlobals hasActivePID:] : 52 -> 60
~ +[GKVoiceChatDictionary validateInvite:] : 280 -> 276
~ +[GKVoiceChatDictionary validateReply:] : 280 -> 276
~ +[GKVoiceChatDictionary validateCancel:] : 280 -> 276
~ +[GKVoiceChatDictionary validateFocus:] : 280 -> 276
~ -[GKVoiceChatServiceFocus dictionaryForNonce:participantID:isIncomingDictonary:] : 384 -> 380
~ -[GKVoiceChatServiceFocus dictionaryForParticipantID:isIncomingDictonary:] : 364 -> 360
~ -[GKVoiceChatServiceFocus dictionaryForCallID:isIncomingDictonary:] : 348 -> 344
~ -[GKVoiceChatServiceFocus openOutgoingDictionaryForParticipantID:] : 416 -> 412
~ -[GKVoiceChatServiceFocus incomingDictionaryMatchingOriginalCallID:participantID:] : 348 -> 344
~ -[GKVoiceChatServiceFocus sendFocusChange:] : 568 -> 564
~ -[GKVoiceChatSessionInternal stopSessionInternal] : 524 -> 516
~ -[GKVoiceChatSessionInternal updatedSubscribedBeaconList:] : 1020 -> 1008
~ -[GKVoiceChatSessionInternal updatedMutedPeers:forPeer:] : 340 -> 336
~ -[GKVoiceChatSessionInternal pauseAll] : 256 -> 252
~ -[GKVoiceChatSessionInternal unPauseAll] : 296 -> 292
~ -[GKVoiceChatSessionInternal pruneBadLinks] : 448 -> 444
~ -[GKVoiceChatSessionInternal updatedFocusPeers:] : 720 -> 708
~ -[GKVoiceChatSessionInternal updatedConnectedPeers:] : 372 -> 368
~ -[GKVoiceChatSessionInternal(VideoConferenceChannelQualityDelegate) calculateChannelQualities] : 316 -> 312
~ -[VoiceChatSessionRoster startBeacon] : 456 -> 452
~ -[VoiceChatSessionRoster updateBeacon] : 376 -> 372
~ -[VoiceChatSessionRoster stopBeacon] : 320 -> 316
~ -[VoiceChatSessionRoster calculateFocus:] : 712 -> 708
~ -[VoiceChatSessionRoster subscribedPeers] : 316 -> 312
~ -[GKVoiceChatSessionListener receivedNewVoiceChatOOBMessage:fromPeerID:] : 320 -> 316
~ -[GKVoiceChatSessionListener session:peer:didChangeState:] : 280 -> 276
~ _OSPFMakeDD : 620 -> 636
~ _OSPFMakeLSA : 652 -> 668
~ _OSPFMakeData : 424 -> 440
~ _OSPFMakeAudio : 244 -> 256
~ _OSPFGetLength : 1416 -> 1420
~ _OSPFParse_ParsePacketHeader : 572 -> 564
~ __OSPFParse_ParseExtractOptions : 2508 -> 2512
~ __OSPFParse_ParsePacketHello : 304 -> 312
~ _OSPFAddDynamicOptions : 4528 -> 4496
~ ___OSPFAddDynamicOptions_block_invoke : 48 -> 56
~ __OSPFParse_ParseNodes : 504 -> 516
~ _UpdateRxEstimate : 1548 -> 1556
~ _GCK_BWE_CalcRxEstimate : 4796 -> 4836
~ -[GKDiscoveryPeer nextInterfaceIndex] : 584 -> 580
~ -[GKDiscoveryPeer flushDataBuffer] : 1028 -> 1020
~ -[GKDiscoveryManager generateDeviceID] : 260 -> 268
~ ___43-[GKDiscoveryManager cleanUpPeersForBrowse]_block_invoke : 580 -> 576
~ -[GKDiscoveryManager peersList] : 308 -> 304
~ -[GKDiscoveryBonjourResolveContainer dealloc] : 292 -> 288
~ -[GKDiscoveryBonjour closeListeningSockets] : 272 -> 268
~ -[GKDiscoveryBonjour sendBonjourRegistrationEvent:discoveryInfo:] : 1136 -> 1132
~ -[GKDiscoveryPeerConnection syncAcceptedConnection] : 736 -> 732
~ +[GKInterfacePrioritizer bsdNameToInterfaceTypeMap] : 844 -> 840
~ +[GKInterfacePrioritizer prioritizeLocalInterfaces:] : 1176 -> 1172
~ -[CDXClientSession sendData:toParticipants:] : 1300 -> 1296
~ -[CDXClientSession recvRaw:ticket:] : 1504 -> 1524
~ -[GKConnectionInternal connectPendingConnectionsFromList:sessionInfo:] : 1960 -> 1956
CStrings:
+ "22:09:21"
+ "Jun 18 2026"
- "00:07:16"
- "Jun  4 2026"
```
