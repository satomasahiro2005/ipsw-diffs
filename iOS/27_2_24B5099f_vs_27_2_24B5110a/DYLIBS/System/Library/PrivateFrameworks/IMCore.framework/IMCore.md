## IMCore

> `/System/Library/PrivateFrameworks/IMCore.framework/IMCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2fe0f4` | `0x2fed60` | **`+0xc6c`** |
| `__AUTH_CONST.__objc_const` | `0x22788` | `0x228e8` | **`+0x160`** |
| `__TEXT.__objc_methlist` | `0x190ac` | `0x1918c` | **`+0xe0`** |
| `__TEXT.__gcc_except_tab` | `0x1198c` | `0x11a44` | **`+0xb8`** |
| `__DATA_CONST.__objc_selrefs` | `0xecd0` | `0xed80` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x131a5` | `0x13225` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0xc370` | `0xc3a0` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x2230` | `0x2258` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0xbc00` | `0xbc20` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x240fb` | `0x240db` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0x12f8` | `0x1310` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x28d0` | `0x28e8` | **`+0x18`** |

### Other Changes

```diff

-1491.200.95.0.0
+1491.200.101.2.5

-  Functions: 15201
-  Symbols:   2728
-  CStrings:  5027
+  Functions: 15220
+  Symbols:   2736
+  CStrings:  5028
Symbols:
+ _IMChatPropertyPromotedToKnownByReply
+ _IMServiceCapabilityDetectInternationalSenderBySIMRegion
+ _IMSharedHelperCurrentRegionCode
+ _IMSharedHelperCurrentRegionRestrictsUnknownSenders
+ _IMSharedHelperCurrentRegionStrengthensUnknownSenderScamWarnings
+ _IMSharedHelperUnknownSenderCopyRestrictedInCurrentRegion
+ _IMSharedHelperUnknownSenderLinkRestrictionDisabled
+ _OBJC_CLASS_$_IMCTQuickSwitchInfo
CStrings:
+ "(IMChat) Unknown sender link properties changed"
+ "<%@, serviceVariant: %lu, filterCategory: %tu, spam: %@, sendersUnknown: %@, responded: %@, initiatedByMe: %@, promotedToKnownByReply: %@, numberOfTimesResponded: %ld, activeTelephonyConversationUUID: %@, isChatBot: %@>"
+ "B"
+ "Not showing unknown international status item. hasUnknownInternationalSender=%@"
- "2"
- "<%@, serviceVariant: %lu, filterCategory: %tu, spam: %@, sendersUnknown: %@, responded: %@, activeTelephonyConversationUUID: %@, isChatBot: %@>"
- "Not showing unknown international status item. chat.isFiltered=%@ and hasUnknownInternationalParticipant=%@"
```
