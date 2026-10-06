## TelephonyUtilities

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/TelephonyUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x2920` | `0x2fd8` | **`+0x6b8`** |
| `__DATA_DIRTY.__objc_data` | `0x2da8` | `0x26f0` | **`-0x6b8`** |
| `__TEXT.__text` | `0x19d6a0` | `0x19db34` | **`+0x494`** |
| `__TEXT.__oslogstring` | `0x13c17` | `0x13b77` | **`-0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x2aeb0` | `0x2af38` | **`+0x88`** |
| `__TEXT.__cstring` | `0x141c6` | `0x14236` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x1b5c8` | `0x1b630` | **`+0x68`** |
| `__AUTH_CONST.__cfstring` | `0x12540` | `0x125a0` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0xb788` | `0xb7c0` | **`+0x38`** |
| `__DATA.__data` | `0x3d38` | `0x3d58` | **`+0x20`** |
| `__DATA.__bss` | `0x7640` | `0x7650` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xfe8` | `0xff8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x6d40` | `0x6d50` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x18f8` | `0x1900` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x37e0` | `0x37d8` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x140` | `0x13c` | **`-0x4`** |

### Other Changes

```diff

-1612.100.3.2.1
+1614.100.3.2.1

-  Functions: 11534
-  Symbols:   16021
-  CStrings:  4600
+  Functions: 11544
+  Symbols:   16034
+  CStrings:  4603
Symbols:
+ +[TUJoinContinuityConversationRequest requestForJoinWithUUID:isAudioEnabled:isVideoEnabled:isOutgoing:]
+ +[TUJoinConversationRequest isOutgoingFromURLComponents:]
+ -[TUFeatureFlags receiverSmartCropEnabled]
+ -[TUJoinContinuityConversationRequest initWithUUID:isAudioEnabled:isVideoEnabled:wantsStagingArea:isOutgoing:]
+ -[TUJoinContinuityConversationRequest isOutgoing]
+ -[TUJoinConversationRequest isOutgoingQueryItem]
+ -[TUJoinConversationRequest isOutgoing]
+ -[TUJoinConversationRequest setIsOutgoing:]
+ -[TUSubtitleProvider localizedSubtitleForRecentCall:handle:contact:includeCallNotes:]
+ GCC_except_table111
+ GCC_except_table114
+ GCC_except_table163
+ _OBJC_IVAR_$_TUJoinContinuityConversationRequest._isOutgoing
+ _OBJC_IVAR_$_TUJoinConversationRequest._isOutgoing
+ _TUNearbyInvitationTimeout
+ _TUShouldUseSuperboxForAllProviders
- GCC_except_table110
- GCC_except_table113
- _TUShouldUseSuperBoxTelephonyProviderKey
CStrings:
+ " isOutgoing=%d"
+ "DefaultNearbyMemberTimeOutOverride"
+ "ReceiverSmartCrop"
+ "TUShouldUseSuperboxForAllProviders"
- "Because this is an internal install and the %@ default is set, com.apple.Superbox (aka Speakerbox)                     is acting as the telephony provider"
```
