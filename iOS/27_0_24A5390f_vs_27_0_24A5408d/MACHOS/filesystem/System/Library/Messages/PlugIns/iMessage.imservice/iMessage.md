## iMessage

> `/System/Library/Messages/PlugIns/iMessage.imservice/iMessage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10a50c` | `0x10b510` | **`+0x1004`** |
| `__TEXT.__objc_methname` | `0x14e7e` | `0x1548e` | **`+0x610`** |
| `__DATA.__objc_const` | `0x3878` | `0x3db0` | **`+0x538`** |
| `__TEXT.__objc_stubs` | `0xeb20` | `0xee00` | **`+0x2e0`** |
| `__TEXT.__objc_methtype` | `0x32a9` | `0x355e` | **`+0x2b5`** |
| `__TEXT.__objc_methlist` | `0x3074` | `0x32a4` | **`+0x230`** |
| `__TEXT.__gcc_except_tab` | `0x9a84` | `0x9918` | **`-0x16c`** |
| `__DATA.__objc_data` | `0xc88` | `0xdc8` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x1c51b` | `0x1c65b` | **`+0x140`** |
| `__DATA.__data` | `0xdd8` | `0xe98` | **`+0xc0`** |
| `__DATA.__objc_selrefs` | `0x4188` | `0x4248` | **`+0xc0`** |
| `__TEXT.__objc_classname` | `0x72f` | `0x7ef` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x3e7d` | `0x3ebd` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x2bd8` | `0x2c08` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x248` | `0x270` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x5458` | `0x5480` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x108` | `0x128` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x4e3` | `0x503` | **`+0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0x98` | `0xb0` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x9b8` | `0x9d0` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x78` | `0x88` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x570` | `0x57c` | **`+0xc`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1487.100.6.2.2
+1491.100.1.2.11

-  Functions: 2417
+  Functions: 2455

-  CStrings:  5302
+  CStrings:  5373
CStrings:
+ "@\"<IMDChorosFringeDetecting>\"16@0:8"
+ "@\"<IMDMessageStoring>\"16@0:8"
+ "@\"<IMPowerLogging>\"16@0:8"
+ "@\"<MessageSendControllerDelegate>\""
+ "@\"<MessageSendControllerDependencyProviding>\""
+ "@\"IMDAppleServiceSession\""
+ "@28@0:8B16@?20"
+ "@32@0:8B16I20B24B28"
+ "Failed sending message withGUID: %@  to people: %@   error: %d"
+ "Finished sending message: (guid: %@) people: %@ error: %d is chat: %{bool}d from me - to me: %{bool}d"
+ "Got error %@ while replicating, suppressing"
+ "Ignoring stale transcript background %llu < current %llu for chat %s."
+ "Incoming background version: %llu is lower than current chat background version: %llu."
+ "MessageSendCompletionHandler"
+ "MessageSendController"
+ "MessageSendControllerDelegate"
+ "MessageSendControllerDependencyProvider"
+ "MessageSendControllerDependencyProviding"
+ "MessageSendNotificationContext"
+ "PrepareMessage %s: %s failure, failing message"
+ "Setting needsDeliveryReceipt to %{BOOL}d since allExistingTransfersAreGradients = %{BOOL}d for transfers on message guid %@"
+ "T@\"<IMDChorosFringeDetecting>\",R,N"
+ "T@\"<IMDMessageStoring>\",R,N"
+ "T@\"<IMPowerLogging>\",R,N"
+ "T@\"<MessageSendControllerDelegate>\",R,N,V_delegate"
+ "T@\"<MessageSendControllerDependencyProviding>\",R,N,V_dependencies"
+ "T@\"IMDAppleServiceSession\",R,N,V_serviceSession"
+ "T@\"NSMutableDictionary\",&,N,V_transcriptBackgroundInFlightVersionByChatGUID"
+ "T@?,R,N,V_notificationHandler"
+ "TB,R,N,GisLastCall,V_lastCall"
+ "TB,R,N,V_replicating"
+ "TB,R,N,V_sendSuccess"
+ "TI,R,N,V_errorType"
+ "Unrecoverable acquisition"
+ "Unrecoverable acquisition failure for message %@; failing send."
+ "_dependencies"
+ "_errorType"
+ "_handleDelayedSendFailureForMessage:withContext:"
+ "_lastCall"
+ "_notificationHandler"
+ "_postPopulateFileTransferUpdates:message:indexForTransferGUID:"
+ "_prePopulateFileTransferUpdates:message:reason:indexForTransferGUID:"
+ "_replicating"
+ "_sendSuccess"
+ "_transcriptBackgroundInFlightVersionByChatGUID"
+ "areMySelectedAliases:forService:"
+ "dependencies"
+ "errorType"
+ "fringeMessageDetector"
+ "handleDeliveryCompletion:withSendContext:message:"
+ "handleIDSCompletionCall error: %d hasNotifiedClient: %{bool}d lastCall: %{bool}d"
+ "handleIDSCompletionCallWithError:isLastCall:"
+ "hasNotifiedClient: %{bool}d sendSuccess: %{bool}d "
+ "initWithDelegate:"
+ "initWithDelegate:dependencies:"
+ "initWithReplicating:notificationHandler:"
+ "initWithSendSuccess:errorType:hasNotifiedClient:lastCall:"
+ "isOneOfMySelectedAliases:forService:"
+ "lastCall"
+ "normalizeUpdateUserInfoOrder:"
+ "notificationHandler"
+ "powerLog"
+ "replicating"
+ "sendController:FTAWDLogForMessage:withContext:"
+ "sendController:deactivateAccountDueToInvalidState:imdAccount:"
+ "sendController:didHandleDeliveryFailureForMessageNeedingRelay:"
+ "sendController:didSendMessage:withContext:forceDate:fromStorage:"
+ "sendController:handleScheduledMessageSendFailure:"
+ "sendController:trackFinishedSentMessage:"
+ "sendController:trackIDSTokenURI:forChatIdentifier:chatStyle:messageGUID:"
+ "sendControllerDidStopTimingMessageSend:"
+ "sendSuccess"
+ "setTranscriptBackgroundInFlightVersionByChatGUID:"
+ "transcriptBackgroundInFlightVersionByChatGUID"
+ "v16@?0@\"MessageSendNotificationContext\"8"
+ "v24@0:8@\"MessageSendController\"16"
+ "v24@0:8I16B20"
+ "v32@0:8@\"MessageSendController\"16@\"IMMessageItem\"24"
+ "v40@0:8@\"MessageSendController\"16@\"IDSAccount\"24@\"IMDAccount\"32"
+ "v40@0:8@\"MessageSendController\"16@\"IMMessageItem\"24@\"SendMessageContext\"32"
+ "v48@0:8@16@24q32@40"
+ "v52@0:8@\"MessageSendController\"16@\"IMMessageItem\"24@\"SendMessageContext\"32@\"NSDate\"40B48"
+ "v52@0:8@\"MessageSendController\"16@\"NSString\"24@\"NSString\"32C40@\"NSString\"44"
+ "v52@0:8@16@24@32@40B48"
- "Finished sending message: (guid: %@) %@ to people: %@ error: %d is chat: %@ from me - to me: %@"
- "Got error %@ while replicating %@, suppressing"
- "Incoming background version: %llu is lower than current chat background version: %@."
- "PrepareMessage %s: Comm safety failure, failing message"
- "T@\"MessageServiceSession\",R,N,V_serviceSession"
- "_postPopulateFileTransferUpdates:message:"
- "_prePopulateFileTransferUpdates:message:reason:"
- "areMyAliases:forService:"
- "hasNotifiedClient: %@ sendSuccess: %@ "
- "idsCompletionBlock returned with error: %d guid: %@ hasNotifiedClient: %@ block: %@"
- "isOneOfMyAliases:forService:"
- "subarrayWithRange:"
- "v40@0:8@16@24q32"
```
