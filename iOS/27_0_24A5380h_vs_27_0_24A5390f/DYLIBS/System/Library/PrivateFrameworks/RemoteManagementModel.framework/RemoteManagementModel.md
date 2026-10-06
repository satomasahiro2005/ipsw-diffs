## RemoteManagementModel

> `/System/Library/PrivateFrameworks/RemoteManagementModel.framework/RemoteManagementModel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__objc_data` | `0x2148` | `0x33e0` | **`+0x1298`** |
| `__AUTH.__objc_data` | `0x1298` | `0xa0` | **`-0x11f8`** |
| `__TEXT.__text` | `0x55e38` | `0x56ef4` | **`+0x10bc`** |
| `__AUTH_CONST.__objc_const` | `0xecb8` | `0xf068` | **`+0x3b0`** |
| `__AUTH_CONST.__cfstring` | `0x7340` | `0x7540` | **`+0x200`** |
| `__TEXT.__objc_methlist` | `0x81a4` | `0x8394` | **`+0x1f0`** |
| `__TEXT.__cstring` | `0x4a22` | `0x4b85` | **`+0x163`** |
| `__DATA_CONST.__objc_selrefs` | `0x2200` | `0x2298` | **`+0x98`** |
| `__DATA.__objc_ivar` | `0x874` | `0x8a4` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1458` | `0x1488` | **`+0x30`** |
| `__AUTH_CONST.__objc_intobj` | `0x2a48` | `0x2a60` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x600` | `0x610` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x530` | `0x540` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x420` | `0x430` | **`+0x10`** |

### Other Changes

```diff

-624.0.8.0.0
+624.0.10.0.0

-  Functions: 2689
-  Symbols:   4972
-  CStrings:  983
+  Functions: 2729
+  Symbols:   5042
+  CStrings:  999
Symbols:
+ +[RMModelAccountCalDAVDeclaration buildWithIdentifier:visibleName:hostName:port:path:authenticationCredentialsAssetReference:VPNUUID:]
+ +[RMModelAccountExchangeDeclaration buildWithIdentifier:visibleName:enabledProtocolTypes:userIdentityAssetReference:hostName:port:path:externalHostName:externalPort:externalPath:graphHostName:oAuth:authenticationCredentialsAssetReference:authenticationIdentityAssetReference:SMIME:allowMove:allowAppSheet:allowMailRecentsSyncing:enableMailDrop:mailNumberOfPastDaysToSync:mailServiceActive:lockMailService:contactsServiceActive:lockContactsService:calendarServiceActive:lockCalendarService:remindersServiceActive:lockRemindersService:notesServiceActive:lockNotesService:VPNUUID:communicationServiceRules:]
+ +[RMModelAccountExchangeDeclaration_CommunicationServiceRules allowedPayloadKeys]
+ +[RMModelAccountExchangeDeclaration_CommunicationServiceRules buildRequiredOnly]
+ +[RMModelAccountExchangeDeclaration_CommunicationServiceRules buildWithDefaultServiceHandlers:]
+ +[RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers allowedPayloadKeys]
+ +[RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers buildRequiredOnly]
+ +[RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers buildWithAudioCall:]
+ +[RMModelAccountLDAPDeclaration buildWithIdentifier:visibleName:hostName:port:authenticationCredentialsAssetReference:searchSettings:VPNUUID:]
+ +[RMModelAccountSubscribedCalendarDeclaration buildWithIdentifier:visibleName:calendarURL:authenticationCredentialsAssetReference:VPNUUID:]
+ -[RMModelAccountCalDAVDeclaration payloadVPNUUID]
+ -[RMModelAccountCalDAVDeclaration setPayloadVPNUUID:]
+ -[RMModelAccountExchangeDeclaration payloadAllowAppSheet]
+ -[RMModelAccountExchangeDeclaration payloadAllowMailRecentsSyncing]
+ -[RMModelAccountExchangeDeclaration payloadAllowMove]
+ -[RMModelAccountExchangeDeclaration payloadCommunicationServiceRules]
+ -[RMModelAccountExchangeDeclaration payloadEnableMailDrop]
+ -[RMModelAccountExchangeDeclaration payloadMailNumberOfPastDaysToSync]
+ -[RMModelAccountExchangeDeclaration payloadVPNUUID]
+ -[RMModelAccountExchangeDeclaration setPayloadAllowAppSheet:]
+ -[RMModelAccountExchangeDeclaration setPayloadAllowMailRecentsSyncing:]
+ -[RMModelAccountExchangeDeclaration setPayloadAllowMove:]
+ -[RMModelAccountExchangeDeclaration setPayloadCommunicationServiceRules:]
+ -[RMModelAccountExchangeDeclaration setPayloadEnableMailDrop:]
+ -[RMModelAccountExchangeDeclaration setPayloadMailNumberOfPastDaysToSync:]
+ -[RMModelAccountExchangeDeclaration setPayloadVPNUUID:]
+ -[RMModelAccountExchangeDeclaration_CommunicationServiceRules .cxx_destruct]
+ -[RMModelAccountExchangeDeclaration_CommunicationServiceRules copyWithZone:]
+ -[RMModelAccountExchangeDeclaration_CommunicationServiceRules loadFromDictionary:serializationType:error:]
+ -[RMModelAccountExchangeDeclaration_CommunicationServiceRules payloadDefaultServiceHandlers]
+ -[RMModelAccountExchangeDeclaration_CommunicationServiceRules serializeWithType:]
+ -[RMModelAccountExchangeDeclaration_CommunicationServiceRules setPayloadDefaultServiceHandlers:]
+ -[RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers .cxx_destruct]
+ -[RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers copyWithZone:]
+ -[RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers loadFromDictionary:serializationType:error:]
+ -[RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers payloadAudioCall]
+ -[RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers serializeWithType:]
+ -[RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers setPayloadAudioCall:]
+ -[RMModelAccountLDAPDeclaration payloadVPNUUID]
+ -[RMModelAccountLDAPDeclaration setPayloadVPNUUID:]
+ -[RMModelAccountSubscribedCalendarDeclaration payloadVPNUUID]
+ -[RMModelAccountSubscribedCalendarDeclaration setPayloadVPNUUID:]
+ _OBJC_CLASS_$_RMModelAccountExchangeDeclaration_CommunicationServiceRules
+ _OBJC_CLASS_$_RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ _OBJC_IVAR_$_RMModelAccountCalDAVDeclaration._payloadVPNUUID
+ _OBJC_IVAR_$_RMModelAccountExchangeDeclaration._payloadAllowAppSheet
+ _OBJC_IVAR_$_RMModelAccountExchangeDeclaration._payloadAllowMailRecentsSyncing
+ _OBJC_IVAR_$_RMModelAccountExchangeDeclaration._payloadAllowMove
+ _OBJC_IVAR_$_RMModelAccountExchangeDeclaration._payloadCommunicationServiceRules
+ _OBJC_IVAR_$_RMModelAccountExchangeDeclaration._payloadEnableMailDrop
+ _OBJC_IVAR_$_RMModelAccountExchangeDeclaration._payloadMailNumberOfPastDaysToSync
+ _OBJC_IVAR_$_RMModelAccountExchangeDeclaration._payloadVPNUUID
+ _OBJC_IVAR_$_RMModelAccountExchangeDeclaration_CommunicationServiceRules._payloadDefaultServiceHandlers
+ _OBJC_IVAR_$_RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers._payloadAudioCall
+ _OBJC_IVAR_$_RMModelAccountLDAPDeclaration._payloadVPNUUID
+ _OBJC_IVAR_$_RMModelAccountSubscribedCalendarDeclaration._payloadVPNUUID
+ _OBJC_METACLASS_$_RMModelAccountExchangeDeclaration_CommunicationServiceRules
+ _OBJC_METACLASS_$_RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_$_CLASS_METHODS_RMModelAccountExchangeDeclaration_CommunicationServiceRules
+ __OBJC_$_CLASS_METHODS_RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_$_CLASS_PROP_LIST_RMModelAccountExchangeDeclaration_CommunicationServiceRules
+ __OBJC_$_CLASS_PROP_LIST_RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_$_INSTANCE_METHODS_RMModelAccountExchangeDeclaration_CommunicationServiceRules
+ __OBJC_$_INSTANCE_METHODS_RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_$_INSTANCE_VARIABLES_RMModelAccountExchangeDeclaration_CommunicationServiceRules
+ __OBJC_$_INSTANCE_VARIABLES_RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_$_PROP_LIST_RMModelAccountExchangeDeclaration_CommunicationServiceRules
+ __OBJC_$_PROP_LIST_RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_CLASS_RO_$_RMModelAccountExchangeDeclaration_CommunicationServiceRules
+ __OBJC_CLASS_RO_$_RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ __OBJC_METACLASS_RO_$_RMModelAccountExchangeDeclaration_CommunicationServiceRules
+ __OBJC_METACLASS_RO_$_RMModelAccountExchangeDeclaration_CommunicationServiceRulesDefaultServiceHandlers
+ ___62-[RMModelAccountExchangeDeclaration serializePayloadWithType:]_block_invoke_4
+ ___81-[RMModelAccountExchangeDeclaration_CommunicationServiceRules serializeWithType:]_block_invoke
- +[RMModelAccountCalDAVDeclaration buildWithIdentifier:visibleName:hostName:port:path:authenticationCredentialsAssetReference:]
- +[RMModelAccountExchangeDeclaration buildWithIdentifier:visibleName:enabledProtocolTypes:userIdentityAssetReference:hostName:port:path:externalHostName:externalPort:externalPath:graphHostName:oAuth:authenticationCredentialsAssetReference:authenticationIdentityAssetReference:SMIME:mailServiceActive:lockMailService:contactsServiceActive:lockContactsService:calendarServiceActive:lockCalendarService:remindersServiceActive:lockRemindersService:notesServiceActive:lockNotesService:]
- +[RMModelAccountLDAPDeclaration buildWithIdentifier:visibleName:hostName:port:authenticationCredentialsAssetReference:searchSettings:]
- +[RMModelAccountSubscribedCalendarDeclaration buildWithIdentifier:visibleName:calendarURL:authenticationCredentialsAssetReference:]
CStrings:
+ "AllowAppSheet"
+ "AllowMailRecentsSyncing"
+ "AllowMove"
+ "AudioCall"
+ "CommunicationServiceRules"
+ "DefaultServiceHandlers"
+ "EnableMailDrop"
+ "MailNumberOfPastDaysToSync"
+ "payloadAllowAppSheet"
+ "payloadAllowMailRecentsSyncing"
+ "payloadAllowMove"
+ "payloadAudioCall"
+ "payloadCommunicationServiceRules"
+ "payloadDefaultServiceHandlers"
+ "payloadEnableMailDrop"
+ "payloadMailNumberOfPastDaysToSync"
```
