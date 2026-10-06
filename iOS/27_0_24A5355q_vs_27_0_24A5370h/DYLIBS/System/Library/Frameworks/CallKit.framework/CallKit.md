## CallKit

> `/System/Library/Frameworks/CallKit.framework/CallKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x675e8` | `0x67528` | **`-0xc0`** |

### Other Changes

```diff

-1392.100.3.0.0
+1394.100.1.0.0
Functions:
~ -[CXCallObserverXPCClient _addOrUpdateCall:] : 516 -> 512
~ ___40-[CXCallControllerHost addOrUpdateCall:]_block_invoke : 560 -> 556
~ ___52-[CXCallSourceManager commitUncommittedTransactions]_block_invoke : 516 -> 512
~ -[CXTransactionManager addOutstandingTransactionGroup:] : 560 -> 556
~ -[CXTransaction updateCopy:withZone:] : 332 -> 328
~ -[CXTransaction updateSanitizedCopy:withZone:] : 344 -> 340
~ -[CXTransaction isComplete] : 260 -> 256
~ ___49-[CXAbstractProvider provider:commitTransaction:]_block_invoke : 512 -> 508
~ ___49-[CXAbstractProvider provider:commitTransaction:]_block_invoke.7 : 572 -> 568
~ -[CXAbstractProvider _pendingActionWithUUID:] : 544 -> 540
~ -[CXAbstractProvider _updatePendingTransactions] : 628 -> 624
~ -[CXTransactionManager updateWithCompletedAction:] : 836 -> 832
~ -[CXTransactionGroup isComplete] : 260 -> 256
~ -[CXTransactionGroup allActions] : 460 -> 456
~ -[CXTransactionManager failOutstandingActionsForCallWithUUID:] : 656 -> 652
~ ___35-[CXCallControllerHost removeCall:]_block_invoke : 444 -> 440
~ -[CXCallObserverXPCClient _removeCall:] : 500 -> 496
~ ___55-[CXChannelServiceServer commitUncommittedTransactions]_block_invoke : 516 -> 512
~ -[CXCallControllerHost _callsForCallControllerHostConnection:] : 444 -> 440
~ -[CXCallControllerHost callControllerHostConnection:requestTransaction:completion:] : 900 -> 892
~ -[CXTransaction addActionsFromTransaction:] : 252 -> 248
~ ___72-[CXCallDirectoryNSExtensionManager _beginMatchingExtensionsIfNecessary]_block_invoke_2 : 584 -> 580
~ ___55-[CXCallDirectoryNSExtensionManager pluginsDidInstall:]_block_invoke : 680 -> 676
~ -[CXCallDirectoryStore _sqlBindingsForPrioritizedExtensionIdentifiers:withPriorityOffset:] : 372 -> 368
~ -[CXVoicemailObserverXPCClient _addOrUpdateVoicemails:] : 668 -> 660
~ -[CXVoicemailObserverXPCClient _removeVoicemails:] : 652 -> 644
~ ___55-[CXChannelSourceManager commitUncommittedTransactions]_block_invoke : 516 -> 512
~ -[CXTransactionManager failOutstandingActionsForChannelWithUUID:] : 656 -> 652
~ -[CXDatabase closeWithError:] : 504 -> 500
~ ___36-[CXProvider initWithConfiguration:]_block_invoke : 1424 -> 1416
~ -[CXProvider pendingCallActionsOfClass:withCallUUID:] : 580 -> 576
~ -[CXCallObserverXPCClient _markAllCallsAsEnded] : 416 -> 412
~ ___40-[CXCallObserverXPCClient _requestCalls]_block_invoke.10 : 336 -> 332
~ -[CXVoicemailProvider pendingVoicemailActionsOfClass:withVoicemailUUID:] : 580 -> 576
~ -[CXNetworkExtensionMessageControllerHost networkExtensionMessageControllerHostConnection:didReceiveIncomingMessage:forBundleIdentifier:] : 476 -> 472
~ -[CXNetworkExtensionMessageControllerHost networkExtensionMessageControllerHostConnection:didReceiveIncomingPushToTalkMessage:forBundleIdentifier:] : 476 -> 472
~ -[CXTransactionGroup isServiceClientGroupComplete] : 260 -> 256
~ -[CXTransactionGroup serviceClientActions] : 460 -> 456
~ -[CXDatabaseStatement bind:error:] : 920 -> 916
~ ___51-[CXVoicemailControllerHost addOrUpdateVoicemails:]_block_invoke : 464 -> 456
~ ___46-[CXVoicemailControllerHost removeVoicemails:]_block_invoke : 452 -> 444
~ -[CXVoicemailControllerHost _voicemailsForVoicemailControllerHostConnection:] : 448 -> 444
```
