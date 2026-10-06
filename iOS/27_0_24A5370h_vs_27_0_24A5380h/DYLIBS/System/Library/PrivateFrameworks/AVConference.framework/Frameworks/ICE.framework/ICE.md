## ICE

> `/System/Library/PrivateFrameworks/AVConference.framework/Frameworks/ICE.framework/ICE`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__got` | `0x0` | `0x78` | **`+0x78`** |
| `__TEXT.__text` | `0x2d3dc` | `0x2d420` | **`+0x44`** |

### Other Changes

```diff

-2235.52.1.11.1
+2235.55.1.0.0
Functions:
~ _RemoveOneCandidateFromList : 460 -> 468
~ _ICEStartConnectivityCheckN : 5404 -> 5400
~ _ICEGetRemoteCIDForDstIPPort : 480 -> 488
~ _GetNextBestCandidate : 1404 -> 1392
~ _AppendInterfaceNameToRemoteCandidates : 264 -> 268
~ _ProcessEvent : 5868 -> 5912
~ _ConnectivityCheckProc : 9212 -> 9220
~ _ProcessNewCandidates : 3916 -> 3924
~ ___FlushEventsForSelectedCandidatePair_block_invoke : 284 -> 288
```
