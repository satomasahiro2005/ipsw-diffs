## AppleServiceToolkit

> `/System/Library/PrivateFrameworks/AppleServiceToolkit.framework/AppleServiceToolkit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c9c0` | `0x2c928` | **`-0x98`** |

### Other Changes

```diff

-231.0.0.0.0
+232.0.0.0.0
Functions:
~ -[ASTSuiteResult initWithDictionary:error:] : 672 -> 668
~ -[ASTControlCommand requestWithData:session:queue:] : 1420 -> 1412
~ -[ASTControlCommand performActionsWithSession:queue:] : 588 -> 584
~ -[ASTControlCommand requestData] : 460 -> 456
~ -[ASTControlCommand allActionsFinished] : 352 -> 348
~ -[ASTControlCommand completionArray] : 456 -> 452
~ +[ASTSession sessionExistsForSerialNumbers:ticketNumber:timeout:completionHandler:] : 412 -> 408
~ -[ASTProfileResult generatePayload] : 820 -> 816
~ -[NSDictionary(NSNull) dictionaryDroppingNSNullValues] : 508 -> 504
~ -[ASTIdentity initWithIdentityAliases:] : 716 -> 712
~ -[ASTIdentity _dictionariesFromIdentityAliases:] : 332 -> 328
~ ___42-[ASTNetworking cancelConnectionsOfClass:]_block_invoke : 336 -> 332
~ +[ASTUploadClientFactory uploadClientWithASTSession:andFileMap:andUrlFactory:andDelegate:] : 476 -> 472
~ -[ASTSuiteResultComponent initWithDictionary:error:] : 876 -> 872
~ -[ASTConnectionPrepareDevice initWithIdentities:] : 636 -> 632
~ -[ASTUploadFilesResult generatePayload] : 1460 -> 1448
~ -[NSSet(NSNull) setDroppingNSNullValues] : 488 -> 484
~ -[NSArray(NSNull) arrayDroppingNSNullValues] : 488 -> 484
~ -[NSError(ASTSerialization) jsonSerializableDictionary] : 828 -> 824
~ -[ASTRepairSessionProvider listener:shouldAcceptNewConnection:] : 1200 -> 1196
~ -[RepairToolURLFactory urlRequest] : 672 -> 668
~ +[ASTAutomatedSession sessionExistsForSerialNumbers:ticketNumber:completionHandler:] : 392 -> 388
~ -[ASTSuiteResultSection initWithDictionary:error:] : 684 -> 680
~ -[ASTTestResult sealWithFileSigner:error:] : 332 -> 328
~ ___33+[ASTResponse stringFromCommand:]_block_invoke : 360 -> 356
~ -[ASTResponse validateData:command:] : 1756 -> 1752
~ -[ASTConfigurableUploadClient uploadStatus] : 356 -> 352
~ -[ASTConfigurableUploadClient uploadTaskDidComplete:withResponse:andError:] : 1632 -> 1628
~ -[ASTConfigurableUploadClient cancelAll] : 372 -> 368
~ -[ASTRemoteServerSession _sendTestResults:] : 1328 -> 1316
~ -[ASTRemoteServerSession _cancelRunningTests] : 632 -> 628
~ -[ASTRemoteServerSession _cancelSendingTestResults] : 328 -> 324
~ -[ASTRemoteServerSession _shouldAllowCellularForSealedTestResult:] : 764 -> 760
```
