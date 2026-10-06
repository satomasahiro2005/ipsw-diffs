## MechanismBase

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/MechanismBase.framework/MechanismBase`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__objc_selrefs` | `0x1190` | `0x1198` | **`+0x8`** |
| `__TEXT.__text` | `0x19f24` | `0x19f28` | **`+0x4`** |

### Other Changes

```diff

-2305.0.0.0.1
+2319.0.16.502.1

-  Symbols:   1356
+  Symbols:   1357
Symbols:
+ _LACAnalyticsTCCResultFromAuthorizationStatus
Functions:
~ -[MechanismBase description] : 412 -> 408
~ -[MechanismUI _invalidateListeners] : 272 -> 268
~ -[MechanismBaseComposite initWithEventIdentifier:remoteViewController:k:ofSubmechanisms:request:] : 456 -> 452
~ -[MechanismBaseComposite isAvailableForPurpose:error:] : 452 -> 444
~ -[MechanismBaseComposite canRecoverFromAvailabilityError:request:] : 684 -> 676
~ -[MechanismBase isTCCAllowedWithAuditTokenData:optionAuditTokenData:forcePrompt:auditTokenUsage:error:] : 600 -> 704
~ -[MechanismBase availabilityEventsForPurpose:] : 600 -> 596
~ -[MechanismBase handleEvaluationEvent:value:timeout:reply:] : 740 -> 736
~ -[MechanismBase event:params:reply:] : 976 -> 972
~ -[MechanismBase _acquireAssertionsWithReason:error:] : 368 -> 364
~ -[MechanismBase _dropAssertionsWithReason:] : 264 -> 260
~ -[MechanismKofNReorganizer reorganizeMechanisms:k:error:] : 888 -> 884
~ +[MechanismKofN mechanismWithK:ofSubmechanisms:serial:request:preserveStandaloneReorganizers:] : 1140 -> 1136
~ -[MechanismKofN mechanismPruningMechanismsWithEventIdentifier:] : 592 -> 588
~ -[MechanismKofN finishRunWithResult:error:] : 456 -> 452
~ -[MechanismKofN bestEffortAvailableMechanismForRequest:error:] : 584 -> 580
~ -[MechanismKofN availabilityEventsForPurpose:] : 324 -> 320
~ -[MechanismKofN findMechanismWithEventIdentifier:] : 296 -> 292
~ -[MechanismKofN mechanismTreeDescription] : 404 -> 400
~ -[MechanismKofN pause:forEvent:error:] : 396 -> 392
~ -[MechanismKofN requiresUiWithEventProcessing:] : 280 -> 276
~ -[MechanismKofN requiresHostingControllerUiWithEventProcessing:] : 280 -> 276
~ -[MechanismKofN additionalControllerInternalInfoForPolicy:] : 608 -> 604
~ -[MechanismKofN setParent:] : 296 -> 292
```
