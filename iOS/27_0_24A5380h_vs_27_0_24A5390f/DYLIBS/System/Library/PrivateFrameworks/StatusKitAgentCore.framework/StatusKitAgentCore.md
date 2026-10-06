## StatusKitAgentCore

> `/System/Library/PrivateFrameworks/StatusKitAgentCore.framework/StatusKitAgentCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x1ae8` | `0x1f88` | **`+0x4a0`** |
| `__AUTH.__objc_data` | `0x1738` | `0x1360` | **`-0x3d8`** |
| `__DATA_DIRTY.__objc_data` | `0x3700` | `0x3ad0` | **`+0x3d0`** |
| `__DATA.__data` | `0x1fc0` | `0x1c30` | **`-0x390`** |
| `__DATA.__bss` | `0x4600` | `0x4280` | **`-0x380`** |
| `__DATA_DIRTY.__bss` | `0x12d0` | `0x14d0` | **`+0x200`** |
| `__TEXT.__text` | `0x1bcb6c` | `0x1bca14` | **`-0x158`** |
| `__AUTH.__data` | `0x2b8` | `0x198` | **`-0x120`** |
| `__TEXT.__oslogstring` | `0x19166` | `0x19266` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0x3320` | `0x3240` | **`-0xe0`** |
| `__AUTH_CONST.__const` | `0x66f8` | `0x6628` | **`-0xd0`** |
| `__TEXT.__const` | `0x5cb8` | `0x5c08` | **`-0xb0`** |
| `__TEXT.__cstring` | `0x971c` | `0x96ac` | **`-0x70`** |
| `__AUTH_CONST.__objc_intobj` | `0x390` | `0x3d8` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0xb138` | `0xb0f0` | **`-0x48`** |
| `__TEXT.__unwind_info` | `0x5cf0` | `0x5cb8` | **`-0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x14a4` | `0x1470` | **`-0x34`** |
| `__TEXT.__swift5_reflstr` | `0x1557` | `0x1527` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x11760` | `0x11740` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x1c24` | `0x1c08` | **`-0x1c`** |
| `__DATA.__common` | `0x18` | `—` | **`-0x18`** |
| `__DATA_CONST.__const` | `0x21c8` | `0x21b0` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x44b0` | `0x4498` | **`-0x18`** |
| `__DATA_DIRTY.__common` | `0xa0` | `0xb0` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x29c4` | `0x29b6` | **`-0xe`** |
| `__TEXT.__swift5_proto` | `0x2c8` | `0x2bc` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1608` | `0x1600` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xd80` | `0xd88` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1d4` | `0x1d0` | **`-0x4`** |

### Other Changes

```diff

-149.100.1.0.0
+151.100.1.0.0

-  Functions: 7791
-  Symbols:   14219
-  CStrings:  2606
+  Functions: 7777
+  Symbols:   14183
+  CStrings:  2600
Symbols:
+ -[SKAPresenceClient clientPrefixedPresenceIdentifierForPresenceIdentifier:serviceIdentifier:error:]
+ _$s18StatusKitAgentCore18SKAPresenceProfileC16identifierPrefix11channelType7options9pushTopic27serverObservableAdopterName17serviceIdentifier21subscribedFilterState24maxPersistentPayloadSize0w8PresenceyZ018presenceTTLSeconds0I10TTLSeconds018idsFirewallServiceQ023presenceProtocolVersion25persistentProtocolVersionACSS_AC011ChannelSyncJ0OAA0eF7OptionsVAA014SKAProfilePushM0CAC0S0OAYSo08SKATopicU0VAC0yZ0OA1_S2dSSAC15ProtocolVersionOA3_tcfCTq
+ _$s18StatusKitAgentCore18SKAPresenceProfileC16identifierPrefix11channelType7options9pushTopic27serverObservableAdopterName17serviceIdentifier21subscribedFilterState24maxPersistentPayloadSize0w8PresenceyZ018presenceTTLSeconds0I10TTLSeconds018idsFirewallServiceQ023presenceProtocolVersion25persistentProtocolVersionACSS_AC011ChannelSyncJ0OAA0eF7OptionsVAA014SKAProfilePushM0CAC0S0OAYSo08SKATopicU0VAC0yZ0OA1_S2dSSAC15ProtocolVersionOA3_tcfcTf4nnngnnnnnnnnnnn_n
+ _$s18StatusKitAgentCore26SKAIncomingMessageMetadataC8prioritySivg
+ _$s18StatusKitAgentCore26SKAIncomingMessageMetadataC8prioritySivgTo
+ _$s18StatusKitAgentCore26SKAIncomingMessageMetadataC8prioritySivpMV
+ _RPOptionStatusFlags
+ __PROPERTIES__TtC18StatusKitAgentCore26SKAIncomingMessageMetadata
- +[NSString(StatusKitAgent) descriptionFromSKUpdatePriority:]
- -[NSString(StatusKitAgent) clientIdentifierPrefixFromPresenceIdentifier]
- -[NSString(StatusKitAgent) ska_sha256Hash]
- -[SKAPresenceClient clientPrefixedPresenceIdentifierForPresenceIdentifier:serviceIdentifier:]
- -[SKAServerBag forceSharedOwnershipAuthForPresence]
- _$s18StatusKitAgentCore18SKAPresenceProfileC15ChannelSyncTypeOSHAASH13_rawHashValue4seedS2i_tFTWTm
- _$s18StatusKitAgentCore18SKAPresenceProfileC15ChannelSyncTypeOSHAASH9hashValueSivgTWTm
- _$s18StatusKitAgentCore18SKAPresenceProfileC16identifierPrefix11channelType7options9pushTopic27serverObservableAdopterName17serviceIdentifier21subscribedFilterState24maxPersistentPayloadSize0w8PresenceyZ018presenceTTLSeconds0I10TTLSeconds018idsFirewallServiceQ00N12BackingStore23presenceProtocolVersion25persistentProtocolVersionACSS_AC011ChannelSyncJ0OAA0eF7OptionsVAA014SKAProfilePushM0CAC0S0OAZSo08SKATopicU0VAC0yZ0OA2_S2dSSAC18ServerBackingStoreOAC15ProtocolVersionOA6_tcfCTq
- _$s18StatusKitAgentCore18SKAPresenceProfileC16identifierPrefix11channelType7options9pushTopic27serverObservableAdopterName17serviceIdentifier21subscribedFilterState24maxPersistentPayloadSize0w8PresenceyZ018presenceTTLSeconds0I10TTLSeconds018idsFirewallServiceQ00N12BackingStore23presenceProtocolVersion25persistentProtocolVersionACSS_AC011ChannelSyncJ0OAA0eF7OptionsVAA014SKAProfilePushM0CAC0S0OAZSo08SKATopicU0VAC0yZ0OA2_S2dSSAC18ServerBackingStoreOAC15ProtocolVersionOA6_tcfcTf4nnngnnnnnnnnnnnn_n
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOAESQAAWL
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOAESQAAWl
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOMF
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOMa
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOMf
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOMn
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreON
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOSHAAMc
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOSHAAMcMK
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOSHAASH13_rawHashValue4seedS2i_tFTW
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOSHAASH4hash4intoys6HasherVz_tFTW
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOSHAASH9hashValueSivgTW
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOSHAASQWb
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOSQAAMc
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOSQAAMcMK
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOSQAASQ2eeoiySbx_xtFZTW
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOWV
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOs23CustomStringConvertibleAAMc
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOs23CustomStringConvertibleAAMcMK
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOs23CustomStringConvertibleAAsAFP11descriptionSSvgTW
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOwet
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOwst
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOwug
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOwui
- _$s18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOwup
- _$s18StatusKitAgentCore18SKAPresenceProfileC18serverBackingStoreAC06ServerhI0Ovg
- _$s18StatusKitAgentCore18SKAPresenceProfileC18serverBackingStoreAC06ServerhI0OvgTv_r
- _$s18StatusKitAgentCore18SKAPresenceProfileC19_serverBackingStoreAC06ServerhI0OvpWvd
- _$s18StatusKitAgentCore18SKAPresenceProfileC9serverBagSo09SKAServerH9Providing_s8SendablepvpZ
- _$s18StatusKitAgentCore18SKAPresenceProfileC9serverBag_WZ
- _$s18StatusKitAgentCore18SKAPresenceProfileC9serverBag_Wz
- __OBJC_$_CATEGORY_CLASS_METHODS_NSString_$_StatusKitAgent
- _associated conformance 18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreOSHAASQ
- _strlen
- _symbolic _____ 18StatusKitAgentCore18SKAPresenceProfileC18ServerBackingStoreO
CStrings:
+ "Could not derive a client-prefixed presence identifier"
+ "Could not derive a client-prefixed presence identifier, client identifier prefix was nil { presenceIdentifier: %{public}@, serviceIdentifier: %{public}@, clientConnection: %@ }"
+ "Could not derive a client-prefixed presence identifier, presence identifier was nil { serviceIdentifier: %{public}@, clientConnection: %@ }"
- "%02x"
- ", serverBackingStore="
- "-"
- "SKUpdatePriorityDefault"
- "SKUpdatePriorityHigh"
- "SKUpdatePriorityMedium"
- "Server bag indicates should force shared ownership auth: %@"
- "Unknown Priority"
- "shared-channels-force-shared-ownership-auth-presence"
```
