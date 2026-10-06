## ICE

> `/System/Library/PrivateFrameworks/AVConference.framework/Frameworks/ICE.framework/ICE`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d174` | `0x2d3dc` | **`+0x268`** |
| `__TEXT.__unwind_info` | `0x360` | `0x358` | **`-0x8`** |

### Other Changes

```diff

-2235.48.1.0.0
+2235.52.1.11.1
Functions:
~ _CandidateByteOrderNToH : 176 -> 188
~ _CandidateByteOrderHToN : 176 -> 188
~ _RemoveOneCandidateFromList : 432 -> 460
~ _CompressCandidateList : 1084 -> 1100
~ _UncompressCandidateList : 1228 -> 1264
~ _FixFlippedCandidate : 416 -> 420
~ _AddOneCandidate : 904 -> 920
~ _SortCandidate : 456 -> 488
~ _SortCandidatePair : 344 -> 372
~ _PairUpCandidate : 1300 -> 1352
~ _SetUpCandidateList : 152 -> 168
~ _ICEGetCandidates : 6380 -> 6396
~ _ICEGetNewCandidates : 852 -> 844
~ _ICEStartConnectivityCheckN : 5400 -> 5404
~ _ICEGetRemoteCIDForDstIPPort : 456 -> 480
~ _GetNextBestCandidate : 1428 -> 1404
~ _ICEAddRemovedRemoteIPPort : 1912 -> 1904
~ _AppendInterfaceNameToRemoteCandidates : 248 -> 264
~ _ICEGetExtIPPorts : 2812 -> 2844
~ _ICEConnectionDataContainsCallID : 412 -> 428
~ _ICEGetExtIPIndex : 1088 -> 1096
~ _FindMatchCP : 124 -> 128
~ _ProcessEvent : 5872 -> 5868
~ _ConnectivityCheckProc : 9116 -> 9212
~ _ProcessNewCandidates : 3928 -> 3916
~ _ProcessRemovedLocalIPPort : 1948 -> 1956
~ _ICEConnectivityRecheck : 304 -> 316
~ _ProcessRemovedRemoteIPPort : 1876 -> 1884
~ _PromoteSecondaryConnection : 468 -> 472
~ ___FlushEventsForSelectedCandidatePair_block_invoke : 252 -> 284
~ _MakeBindingResponse : 1828 -> 1840
~ _ProcessBindingRequest : 9592 -> 9672
~ _IsNewCandidate : 132 -> 148
~ _IsNewCandidatePair : 224 -> 236
~ _ProcessBindingResponse : 4152 -> 4168
~ _MakeAllocateRequest : 796 -> 804
~ _STUNEncodeAttrXORAddress : 476 -> 468
~ _STUNGetTransID : 160 -> 176
~ _FreeSTUNMessage : 324 -> 300
~ _MakeTransID : 104 -> 116
~ _ParseSTUNXORAddr : 312 -> 304
~ _ParseSTUNMessage : 2692 -> 2716
~ _ParseBinaryData : 144 -> 140
~ _GetSTUNAttr : 48 -> 64
~ _IPToString : 500 -> 492
~ _GetLocalInterfaceListWithOptionsAndCellInterfaceName : 7700 -> 7712
~ _GetLocalIFIndexForDstIPPortFromBuffer : 3448 -> 3424
~ _STUNEncodeMessage : 2500 -> 2492
```
