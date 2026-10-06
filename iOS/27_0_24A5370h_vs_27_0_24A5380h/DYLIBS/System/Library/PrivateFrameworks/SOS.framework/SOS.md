## SOS

> `/System/Library/PrivateFrameworks/SOS.framework/SOS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x355fc` | `0x3609c` | **`+0xaa0`** |
| `__TEXT.__oslogstring` | `0x63b8` | `0x6670` | **`+0x2b8`** |
| `__AUTH_CONST.__cfstring` | `0x4180` | `0x4240` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x4b02` | `0x4bb8` | **`+0xb6`** |
| `__TEXT.__objc_methlist` | `0x394c` | `0x39d4` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x2778` | `0x27e0` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0x4d58` | `0x4db8` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x1150` | `0x1178` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x370` | `0x380` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xff8` | `0x1008` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2fc` | `0x304` | **`+0x8`** |

### Other Changes

```diff

-668.100.1.0.0
+669.100.1.0.0

-  Functions: 1455
-  Symbols:   2416
-  CStrings:  1157
+  Functions: 1468
+  Symbols:   2441
+  CStrings:  1174
Symbols:
+ -[SOSContactsManager isMessagesHandlingSMS]
+ -[SOSCoordinator _sendUrgentMessageToPairedDevice:retries:identifier:]
+ -[SOSCoordinator handleSOSMessageTypeMessagesHandlingSMS:]
+ -[SOSCoordinator handleSOSMessageTypeMessagesHandlingSMSReq:]
+ -[SOSCoordinator messagesHandlingSMSRequestTimers]
+ -[SOSCoordinator pendingMessagesHandlingSMSRequests]
+ -[SOSCoordinator requestMessagesHandlingSMSFromCompanionWithCompletion:]
+ -[SOSCoordinator sendUrgentMessageToPairedDevice:identifier:]
+ -[SOSCoordinator setMessagesHandlingSMSRequestTimers:]
+ -[SOSCoordinator setPendingMessagesHandlingSMSRequests:]
+ -[SOSCoordinator startMessagesHandlingSMSRequestTimerWithIdentifier:]
+ -[SOSEngine refreshMessagesHandlingSMS]
+ GCC_except_table105
+ GCC_except_table35
+ GCC_except_table41
+ GCC_except_table50
+ GCC_except_table90
+ GCC_except_table96
+ _OBJC_CLASS_$_NSError
+ _OBJC_IVAR_$_SOSCoordinator._messagesHandlingSMSRequestTimers
+ _OBJC_IVAR_$_SOSCoordinator._pendingMessagesHandlingSMSRequests
+ ___58-[SOSCoordinator handleSOSMessageTypeMessagesHandlingSMS:]_block_invoke
+ ___69-[SOSCoordinator startMessagesHandlingSMSRequestTimerWithIdentifier:]_block_invoke
+ ___70-[SOSCoordinator _sendUrgentMessageToPairedDevice:retries:identifier:]_block_invoke
+ ___block_descriptor_41_e8_32s_e42_v32?0"NSString"8?<v?B"NSError">16^B24ls32l8
+ __dispatch_source_type_timer
+ _dispatch_resume
+ _dispatch_source_cancel
+ _dispatch_source_create
+ _dispatch_source_set_event_handler
+ _dispatch_source_set_timer
- -[SOSCoordinator _sendUrgentMessageToPairedDevice:retries:]
- GCC_except_table102
- GCC_except_table34
- GCC_except_table89
- GCC_except_table95
- ___59-[SOSCoordinator _sendUrgentMessageToPairedDevice:retries:]_block_invoke
CStrings:
+ "NO"
+ "SOSContactsManager, refreshIsMessagesHandlingSMS no-op"
+ "SOSCoordinationMessagesHandlingSMS"
+ "SOSCoordinator, IDS didSendWithSuccess identifier=%@ Success!"
+ "SOSCoordinator, IDS didSendWithSuccess identifier=%@ error=%@"
+ "SOSCoordinator, cancelling timeout timer for messagesHandlingSMS"
+ "SOSCoordinator, handleSOSMessageTypeMessagesHandlingSMS"
+ "SOSCoordinator, handleSOSMessageTypeMessagesHandlingSMSReq"
+ "SOSCoordinator, messagesHandlingSMS: %@, clearing out pending messages handling SMS requests, count: %lu"
+ "SOSCoordinator, no paired device nearby, not asking companion for messages handling SMS"
+ "SOSCoordinator, requestMessagesHandlingSMSFromCompanionWithCompletion"
+ "SOSCoordinator, sendUrgentMessageToPairedDevice"
+ "SOSCoordinator, waiting for response from phone for messages handling SMS"
+ "SOSCoordinatorErrorDomain"
+ "SOSMessageTypeMessagesHandlingSMS"
+ "SOSMessageTypeMessagesHandlingSMSReq"
+ "Timed out waiting for reply to message (%@)"
+ "YES"
+ "v32@?0@\"NSString\"8@?<v@?B@\"NSError\">16^B24"
- "IDS didSendWithSuccess identifier=%@ Success!"
- "IDS didSendWithSuccess identifier=%@ error=%@"
```
