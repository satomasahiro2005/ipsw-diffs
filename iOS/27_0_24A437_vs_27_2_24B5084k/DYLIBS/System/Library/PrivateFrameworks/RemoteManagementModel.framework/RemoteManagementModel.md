## RemoteManagementModel

> `/System/Library/PrivateFrameworks/RemoteManagementModel.framework/RemoteManagementModel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x56f9c` | `0x58804` | **`+0x1868`** |
| `__AUTH_CONST.__objc_const` | `0xf008` | `0xf588` | **`+0x580`** |
| `__TEXT.__objc_methlist` | `0x8394` | `0x8684` | **`+0x2f0`** |
| `__AUTH.__objc_data` | `0xa0` | `0x1e0` | **`+0x140`** |
| `__AUTH_CONST.__cfstring` | `0x7540` | `0x75e0` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x1480` | `0x14e0` | **`+0x60`** |
| `__DATA.__objc_ivar` | `0x8a8` | `0x8e0` | **`+0x38`** |
| `__TEXT.__cstring` | `0x4b75` | `0x4ba4` | **`+0x2f`** |
| `__DATA_CONST.__got` | `0x608` | `0x628` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x538` | `0x558` | **`+0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0x430` | `0x450` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x878` | `0x890` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x22b8` | `0x22c8` | **`+0x10`** |

### Other Changes

```diff

-624.2.3.0.0
+624.40.12.0.0

-  Functions: 2730
-  Symbols:   5037
-  CStrings:  998
+  Functions: 2790
+  Symbols:   5150
+  CStrings:  1003
Symbols:
+ +[RMModelAccountCardDAVDeclaration buildWithIdentifier:visibleName:hostName:port:path:authenticationCredentialsAssetReference:VPNUUID:communicationServiceRules:]
+ +[RMModelAccountCardDAVDeclaration_CommunicationServiceRules allowedPayloadKeys]
+ +[RMModelAccountCardDAVDeclaration_CommunicationServiceRules buildRequiredOnly]
+ +[RMModelAccountCardDAVDeclaration_CommunicationServiceRules buildWithDefaultServiceHandlers:]
+ +[RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers allowedPayloadKeys]
+ +[RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers buildRequiredOnly]
+ +[RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers buildWithAudioCall:]
+ +[RMModelAccountGoogleDeclaration buildWithIdentifier:visibleName:userIdentityAssetReference:VPNUUID:communicationServiceRules:]
+ +[RMModelAccountGoogleDeclaration_CommunicationServiceRules allowedPayloadKeys]
+ +[RMModelAccountGoogleDeclaration_CommunicationServiceRules buildRequiredOnly]
+ +[RMModelAccountGoogleDeclaration_CommunicationServiceRules buildWithDefaultServiceHandlers:]
+ +[RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers allowedPayloadKeys]
+ +[RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers buildRequiredOnly]
+ +[RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers buildWithAudioCall:]
+ +[RMModelAccountMailDeclaration buildWithIdentifier:visibleName:userIdentityAssetReference:incomingServer:outgoingServer:SMIME:allowMove:allowAppSheet:allowMailRecentsSyncing:enableMailDrop:VPNUUID:]
+ +[RMModelStatusAccountListExchange buildWithIdentifier:removed:declarationIdentifier:visibleName:protocolType:hostname:port:username:isMailEnabled:areCalendarsEnabled:areContactsEnabled:areNotesEnabled:areRemindersEnabled:]
+ -[RMModelAccountCardDAVDeclaration payloadCommunicationServiceRules]
+ -[RMModelAccountCardDAVDeclaration payloadVPNUUID]
+ -[RMModelAccountCardDAVDeclaration setPayloadCommunicationServiceRules:]
+ -[RMModelAccountCardDAVDeclaration setPayloadVPNUUID:]
+ -[RMModelAccountCardDAVDeclaration_CommunicationServiceRules .cxx_destruct]
+ -[RMModelAccountCardDAVDeclaration_CommunicationServiceRules copyWithZone:]
+ -[RMModelAccountCardDAVDeclaration_CommunicationServiceRules loadFromDictionary:serializationType:error:]
+ -[RMModelAccountCardDAVDeclaration_CommunicationServiceRules payloadDefaultServiceHandlers]
+ -[RMModelAccountCardDAVDeclaration_CommunicationServiceRules serializeWithType:]
+ -[RMModelAccountCardDAVDeclaration_CommunicationServiceRules setPayloadDefaultServiceHandlers:]
+ -[RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers .cxx_destruct]
+ -[RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers copyWithZone:]
+ -[RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers loadFromDictionary:serializationType:error:]
+ -[RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers payloadAudioCall]
+ -[RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers serializeWithType:]
+ -[RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers setPayloadAudioCall:]
+ -[RMModelAccountGoogleDeclaration payloadCommunicationServiceRules]
+ -[RMModelAccountGoogleDeclaration payloadVPNUUID]
+ -[RMModelAccountGoogleDeclaration setPayloadCommunicationServiceRules:]
+ -[RMModelAccountGoogleDeclaration setPayloadVPNUUID:]
+ -[RMModelAccountGoogleDeclaration_CommunicationServiceRules .cxx_destruct]
+ -[RMModelAccountGoogleDeclaration_CommunicationServiceRules copyWithZone:]
+ -[RMModelAccountGoogleDeclaration_CommunicationServiceRules loadFromDictionary:serializationType:error:]
+ -[RMModelAccountGoogleDeclaration_CommunicationServiceRules payloadDefaultServiceHandlers]
+ -[RMModelAccountGoogleDeclaration_CommunicationServiceRules serializeWithType:]
+ -[RMModelAccountGoogleDeclaration_CommunicationServiceRules setPayloadDefaultServiceHandlers:]
+ -[RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers .cxx_destruct]
+ -[RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers copyWithZone:]
+ -[RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers loadFromDictionary:serializationType:error:]
+ -[RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers payloadAudioCall]
+ -[RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers serializeWithType:]
+ -[RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers setPayloadAudioCall:]
+ -[RMModelAccountMailDeclaration payloadAllowAppSheet]
+ -[RMModelAccountMailDeclaration payloadAllowMailRecentsSyncing]
+ -[RMModelAccountMailDeclaration payloadAllowMove]
+ -[RMModelAccountMailDeclaration payloadEnableMailDrop]
+ -[RMModelAccountMailDeclaration payloadVPNUUID]
+ -[RMModelAccountMailDeclaration setPayloadAllowAppSheet:]
+ -[RMModelAccountMailDeclaration setPayloadAllowMailRecentsSyncing:]
+ -[RMModelAccountMailDeclaration setPayloadAllowMove:]
+ -[RMModelAccountMailDeclaration setPayloadEnableMailDrop:]
+ -[RMModelAccountMailDeclaration setPayloadVPNUUID:]
+ -[RMModelStatusAccountListExchange setStatusProtocolType:]
+ -[RMModelStatusAccountListExchange statusProtocolType]
+ _OBJC_CLASS_$_RMModelAccountCardDAVDeclaration_CommunicationServiceRules
+ _OBJC_CLASS_$_RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ _OBJC_CLASS_$_RMModelAccountGoogleDeclaration_CommunicationServiceRules
+ _OBJC_CLASS_$_RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ _OBJC_IVAR_$_RMModelAccountCardDAVDeclaration._payloadCommunicationServiceRules
+ _OBJC_IVAR_$_RMModelAccountCardDAVDeclaration._payloadVPNUUID
+ _OBJC_IVAR_$_RMModelAccountCardDAVDeclaration_CommunicationServiceRules._payloadDefaultServiceHandlers
+ _OBJC_IVAR_$_RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers._payloadAudioCall
+ _OBJC_IVAR_$_RMModelAccountGoogleDeclaration._payloadCommunicationServiceRules
+ _OBJC_IVAR_$_RMModelAccountGoogleDeclaration._payloadVPNUUID
+ _OBJC_IVAR_$_RMModelAccountGoogleDeclaration_CommunicationServiceRules._payloadDefaultServiceHandlers
+ _OBJC_IVAR_$_RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers._payloadAudioCall
+ _OBJC_IVAR_$_RMModelAccountMailDeclaration._payloadAllowAppSheet
+ _OBJC_IVAR_$_RMModelAccountMailDeclaration._payloadAllowMailRecentsSyncing
+ _OBJC_IVAR_$_RMModelAccountMailDeclaration._payloadAllowMove
+ _OBJC_IVAR_$_RMModelAccountMailDeclaration._payloadEnableMailDrop
+ _OBJC_IVAR_$_RMModelAccountMailDeclaration._payloadVPNUUID
+ _OBJC_IVAR_$_RMModelStatusAccountListExchange._statusProtocolType
+ _OBJC_METACLASS_$_RMModelAccountCardDAVDeclaration_CommunicationServiceRules
+ _OBJC_METACLASS_$_RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ _OBJC_METACLASS_$_RMModelAccountGoogleDeclaration_CommunicationServiceRules
+ _OBJC_METACLASS_$_RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ _RMModelStatusAccountListExchange_ProtocolType_EAS
+ _RMModelStatusAccountListExchange_ProtocolType_EWS
+ _RMModelStatusAccountListExchange_ProtocolType_graph
+ __OBJC_$_CLASS_METHODS_RMModelAccountCardDAVDeclaration_CommunicationServiceRules
+ __OBJC_$_CLASS_METHODS_RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_$_CLASS_METHODS_RMModelAccountGoogleDeclaration_CommunicationServiceRules
+ __OBJC_$_CLASS_METHODS_RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_$_CLASS_PROP_LIST_RMModelAccountCardDAVDeclaration_CommunicationServiceRules
+ __OBJC_$_CLASS_PROP_LIST_RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_$_CLASS_PROP_LIST_RMModelAccountGoogleDeclaration_CommunicationServiceRules
+ __OBJC_$_CLASS_PROP_LIST_RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_$_INSTANCE_METHODS_RMModelAccountCardDAVDeclaration_CommunicationServiceRules
+ __OBJC_$_INSTANCE_METHODS_RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_$_INSTANCE_METHODS_RMModelAccountGoogleDeclaration_CommunicationServiceRules
+ __OBJC_$_INSTANCE_METHODS_RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_$_INSTANCE_VARIABLES_RMModelAccountCardDAVDeclaration_CommunicationServiceRules
+ __OBJC_$_INSTANCE_VARIABLES_RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_$_INSTANCE_VARIABLES_RMModelAccountGoogleDeclaration_CommunicationServiceRules
+ __OBJC_$_INSTANCE_VARIABLES_RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_$_PROP_LIST_RMModelAccountCardDAVDeclaration_CommunicationServiceRules
+ __OBJC_$_PROP_LIST_RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_$_PROP_LIST_RMModelAccountGoogleDeclaration_CommunicationServiceRules
+ __OBJC_$_PROP_LIST_RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_CLASS_RO_$_RMModelAccountCardDAVDeclaration_CommunicationServiceRules
+ __OBJC_CLASS_RO_$_RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_CLASS_RO_$_RMModelAccountGoogleDeclaration_CommunicationServiceRules
+ __OBJC_CLASS_RO_$_RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_METACLASS_RO_$_RMModelAccountCardDAVDeclaration_CommunicationServiceRules
+ __OBJC_METACLASS_RO_$_RMModelAccountCardDAVDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_METACLASS_RO_$_RMModelAccountGoogleDeclaration_CommunicationServiceRules
+ __OBJC_METACLASS_RO_$_RMModelAccountGoogleDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ ___60-[RMModelAccountGoogleDeclaration serializePayloadWithType:]_block_invoke
+ ___61-[RMModelAccountCardDAVDeclaration serializePayloadWithType:]_block_invoke
+ ___79-[RMModelAccountGoogleDeclaration_CommunicationServiceRules serializeWithType:]_block_invoke
+ ___80-[RMModelAccountCardDAVDeclaration_CommunicationServiceRules serializeWithType:]_block_invoke
- +[RMModelAccountCardDAVDeclaration buildWithIdentifier:visibleName:hostName:port:path:authenticationCredentialsAssetReference:]
- +[RMModelAccountGoogleDeclaration buildWithIdentifier:visibleName:userIdentityAssetReference:]
- +[RMModelAccountMailDeclaration buildWithIdentifier:visibleName:userIdentityAssetReference:incomingServer:outgoingServer:SMIME:]
- +[RMModelStatusAccountListExchange buildWithIdentifier:removed:declarationIdentifier:visibleName:hostname:port:username:isMailEnabled:areCalendarsEnabled:areContactsEnabled:areNotesEnabled:areRemindersEnabled:]
CStrings:
+ "EAS"
+ "EWS"
+ "Graph"
+ "protocol-type"
+ "statusProtocolType"
```
