## TelephonyUtilities

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/TelephonyUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b7a9c` | `0x1bd710` | **`+0x5c74`** |
| `__TEXT.__eh_frame` | `0x2a78` | `0x31d8` | **`+0x760`** |
| `__TEXT.__oslogstring` | `0x14877` | `0x14bea` | **`+0x373`** |
| `__TEXT.__unwind_info` | `0x7248` | `0x7408` | **`+0x1c0`** |
| `__AUTH_CONST.__const` | `0x4dd8` | `0x4ee0` | **`+0x108`** |
| `__DATA.__bss` | `0x85d0` | `0x84d0` | **`-0x100`** |
| `__TEXT.__cstring` | `0x14616` | `0x14716` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0x12820` | `0x12900` | **`+0xe0`** |
| `__TEXT.__swift5_capture` | `0x2b8` | `0x38c` | **`+0xd4`** |
| `__TEXT.__objc_methlist` | `0x1ba80` | `0x1bb30` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x13a1` | `0x1443` | **`+0xa2`** |
| `__TEXT.__const` | `0x4adc` | `0x4b6c` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x2b648` | `0x2b6d0` | **`+0x88`** |
| `__TEXT.__swift_as_cont` | `0x194` | `0x1e4` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xb8c0` | `0xb900` | **`+0x40`** |
| `__TEXT.__swift_as_entry` | `0xb4` | `0xec` | **`+0x38`** |
| `__TEXT.__swift_as_ret` | `0xcc` | `0x104` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x1354` | `0x1320` | **`-0x34`** |
| `__AUTH.__data` | `0xde0` | `0xe00` | **`+0x20`** |
| `__DATA.__data` | `0x3f20` | `0x3f40` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1690` | `0x1678` | **`-0x18`** |
| `__TEXT.__constg_swiftt` | `0xeb0` | `0xec4` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0x194c` | `0x1954` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x3910` | `0x3918` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x10b0` | `0x10a8` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x3e0` | `0x3d8` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x150` | `0x14c` | **`-0x4`** |

### Other Changes

```diff

-1626.200.65.0.0
+1626.200.84.0.0

-  Functions: 11979
-  Symbols:   16252
-  CStrings:  4673
+  Functions: 12076
+  Symbols:   16279
+  CStrings:  4687
Symbols:
+ +[NSPredicate(TUManagedConversationLinkDescriptor) tu_predicateForConversationLinkDescriptorsIsAccessibilityLink:]
+ +[NSPredicate(TUManagedConversationLinkDescriptor) tu_predicateForConversationLinkDescriptorsWithPseudonyms:]
+ -[TUContinuityConversationLink groupUUID]
+ -[TUContinuityConversationLink initWithTUConversationLink:displayName:date:uniqueId:groupUUID:]
+ -[TUConversationLink isAccessibilityLink]
+ -[TUConversationManager accessibilityLinkPseudonymsAmongPseudonyms:completionHandler:]
+ -[TUConversationManager interpreterRequestWithID:debugSendLink:toHandle:]
+ -[TUConversationManagerXPCClient accessibilityLinkPseudonymsAmongPseudonyms:completionHandler:]
+ -[TUConversationManagerXPCClient interpreterRequestWithID:debugSendLink:toHandle:]
+ -[TUJoinConversationRequest handlesToAddAfterHandoff]
+ -[TUJoinConversationRequest setHandlesToAddAfterHandoff:]
+ GCC_except_table151
+ GCC_except_table177
+ GCC_except_table88
+ GCC_except_table91
+ _OBJC_IVAR_$_TUContinuityConversationLink._groupUUID
+ _OBJC_IVAR_$_TUJoinConversationRequest._handlesToAddAfterHandoff
+ _TUSimulatedModeEnabledKey
+ ___73-[TUConversationManager interpreterRequestWithID:debugSendLink:toHandle:]_block_invoke
+ ___73-[TUConversationManager interpreterRequestWithID:debugSendLink:toHandle:]_block_invoke_2
+ ___82-[TUConversationManagerXPCClient interpreterRequestWithID:debugSendLink:toHandle:]_block_invoke
+ ___95-[TUConversationManagerXPCClient accessibilityLinkPseudonymsAmongPseudonyms:completionHandler:]_block_invoke
+ _swift_deletedAsyncMethodErrorTu
+ _symbolic Scgyyt______pG s5ErrorP
+ _symbolic ShySSG
+ _symbolic ShySSGIeAgHr_
+ _symbolic _____ySSSaySo8TUHandleCGG s18_DictionaryStorageC
+ _symbolic _____yShySSGG 2os21OSAllocatedUnfairLockV
+ _symbolic _____yShySSG_G ScG8IteratorV
+ _symbolic _____yShySSG_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic _____ySo8TUHandleCSbG s18_DictionaryStorageC
+ _symbolic _____y_____y_____GG 2os21OSAllocatedUnfairLockV 18TelephonyUtilities23CancellableContinuationO AD15ResponseWrapperV
+ _symbolic yt______pIeghHrzo_ s5ErrorP
- -[TUContinuityConversationLink initWithTUConversationLink:displayName:date:uniqueId:]
- GCC_except_table149
- GCC_except_table175
- GCC_except_table87
- _associated conformance 18TelephonyUtilities17TUCallContextCardV4ItemO8BirthdayV15TUBirthdayStateOSHAASQ
- _symbolic _____ 18TelephonyUtilities17TUCallContextCardV4ItemO8BirthdayV15TUBirthdayStateO
CStrings:
+ " handlesToAddAfterHandoff=%@"
+ "Asked which of %lu pseudonym(s) are accessibility links"
+ "Companion Lockdown Mode Enabled"
+ "Error in retrieving accessibility link pseudonyms: %@"
+ "FaceTimeServiceAvailabilityHelper: Cannot generate IDS destination for handle, reporting false for handle: %@"
+ "FaceTimeServiceAvailabilityHelper: Every destination is FaceTime available, no need to wait for the remaining services"
+ "FaceTimeServiceAvailabilityHelper: Got %{public}s back for availability of service %s: %@"
+ "FaceTimeServiceAvailabilityHelper: Querying availability of FaceTime services for %ld handles across %ld destinations with timeout: %s"
+ "FaceTimeServiceAvailabilityHelper: The ID status cache reported every destination valid for service %s, skipping the network lookup"
+ "FaceTimeServiceAvailabilityHelper: Timeout reached querying batch availability of FaceTime, returning the results gathered so far"
+ "SimulatedModeEnabled"
+ "The companion device could not complete the operation because it has Lockdown Mode enabled."
+ "accessibilityReqUUID != NULL"
+ "accessibilityReqUUID == NULL"
+ "idStatus(for:service:fromNetwork:)"
+ "pseudonym IN %@"
- "requiredIDStatus(for:service:)"
- "simulatedMode"
```
