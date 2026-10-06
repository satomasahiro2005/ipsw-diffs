## InstallProgress

> `/System/Library/PrivateFrameworks/InstallProgress.framework/InstallProgress`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdf28` | `0xdec8` | **`-0x60`** |

### Other Changes

```text
Functions:
~ -[IPGlobalInstallableStateSource globalStateSourceBehavior:stateSourceAvailableForIdentity:withGenerator:] : 560 -> 556
~ -[IPInstallableProgressData _recalculateCurrentFractionCompleted] : 380 -> 376
~ -[IPInstallableProgressData setTotalUnitCountsForPhases:] : 324 -> 320
~ -[IPInstallableProgressData setInstallPhase:] : 116 -> 112
~ -[IPServerXPCTransport disseminateProgressUpdateForIdentity:currentProgress:] : 296 -> 292
~ -[IPServerXPCTransport disseminateProgressEndForIdenitty:reason:] : 284 -> 280
~ -[IPPublishedIdentityProgress setTotalUnitCountsForPhases:] : 660 -> 656
~ -[IPStateUpdateMessage XPCDictionaryRepresentation] : 412 -> 404
~ ___55-[IPXPCEventStateUpdateStreamSubscriber beginHandshake]_block_invoke : 612 -> 608
~ ___53-[IPXPCEventStateUpdateStreamSink sendUpdateMessage:]_block_invoke : 256 -> 252
~ ___71-[IPGlobalInstallableStateSourceXPCBehavior _queue_connectedConnection]_block_invoke : 424 -> 420
~ -[IPGlobalInstallableStateSourceXPCBehavior _installableStateSourcesForStates:] : 412 -> 408
~ ___100-[IPGlobalInstallableStateSourceXPCBehavior _queue_makeInstallingStateSourcesForGlobalSource:error:]_block_invoke.21 : 492 -> 488
~ ___84-[IPGlobalInstallableStateSourceXPCBehavior installableForIdentity:progressChanged:]_block_invoke : 332 -> 328
~ ___91-[IPGlobalInstallableStateSourceXPCBehavior installableForIdentity:progressEndedForReason:]_block_invoke : 332 -> 328
~ ___80-[IPGlobalInstallableStateSourceXPCBehavior _queue_noteInstallBeganForIdentity:]_block_invoke : 240 -> 236
~ ___88-[IPGlobalInstallableStateSourceXPCBehavior _queue_sendStateSourceAvailableForIdentity:]_block_invoke_2 : 252 -> 248
~ ___90-[IPGlobalInstallableStateSourceXPCBehavior _queue_sendStateSourceUnavailableForIdentity:]_block_invoke : 240 -> 236
~ -[IPProgressServer activeInstallationsForBehavior:] : 556 -> 552
~ -[IPProgressServer serverBehavior:progressForIdentity:error:] : 888 -> 884
~ ___38-[IPLocalStateUpdateStreamSink resume]_block_invoke : 312 -> 308
~ _IPObjectIsKindOfClasses : 280 -> 276
~ _IPLSIdentityFromMIIdentity : 1164 -> 1160
~ -[IPProgressServerDefaultBehavior allInstallableStatesForClient:] : 488 -> 484
~ ___65-[IPProgressServerDefaultBehavior allInstallableStatesForClient:]_block_invoke : 644 -> 640
~ -[IPInstallableProgressData setInstallPhase:].cold.1 : 92 -> 100
```
