## DistributedSensing

> `/System/Library/PrivateFrameworks/DistributedSensing.framework/DistributedSensing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16994` | `0x16920` | **`-0x74`** |

### Other Changes

```text
Functions:
~ -[DSXPCServer _invalidate] : 408 -> 404
~ -[DSXPCServer removeXPCConnection:] : 464 -> 460
~ -[DSXPCServer updateScanner] : 372 -> 368
~ -[DSProvider _receivedDataRequest:options:responseHandler:] : 2284 -> 2280
~ ___30-[DSProvider _sendMotionData:]_block_invoke : 472 -> 468
~ ___36-[DSProvider _heartBeatWithListener]_block_invoke : 476 -> 472
~ -[DSMotionStateListenerProxy requestMotionState] : 548 -> 544
~ -[DSMotionStateListenerProxy stoppedListener] : 960 -> 956
~ -[DSMotionStateListenerProxy failedToStartListenerWithError:] : 568 -> 564
~ -[DSMotionStateListenerProxy startedListener] : 632 -> 628
~ -[DSMotionStateListenerProxy receivedData:fromProvider:] : 416 -> 412
~ -[DSMotionStateListenerProxy updateProviders:] : 368 -> 364
~ -[DSDeviceContext updateWithCBDevice:] : 1464 -> 1456
~ ___34-[DSRapportDevice sendNextRequest]_block_invoke : 1092 -> 1088
~ ___56-[DSRapportDevice _activateSessionClientWithForceL2CAP:]_block_invoke : 568 -> 564
~ ___52-[DSRapportDevice _forceBLEDiscoverytoSendRequestID]_block_invoke.55 : 392 -> 388
~ ___43-[DSRapportDevice _startDiscoveryExitTimer]_block_invoke : 664 -> 660
~ -[DSConsensusDataManager printConsensusData] : 240 -> 236
~ -[DSConsensusDataManager printConsensusDataFromWindowStart:ToWindowEnd:] : 640 -> 636
~ -[DSXPCConnection _activateMotionSessionMessage:] : 912 -> 908
~ ___36-[DSListener _subscribeToMotionData]_block_invoke : 880 -> 876
~ ___38-[DSListener _unsubscribeToMotionData]_block_invoke : 440 -> 436
~ -[DSListener _startCASessionMetricCollection] : 772 -> 768
~ ___49-[DSMotionSession updateVehicleState:confidence:]_block_invoke : 768 -> 760
~ -[DSCohortManager _deviceFound:] : 1612 -> 1604
~ -[DSCohortManager _deviceLost:] : 584 -> 580
```
