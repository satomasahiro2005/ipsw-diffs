## AppleAccount

> `/System/Library/PrivateFrameworks/AppleAccount.framework/AppleAccount`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a191c` | `0x1a534c` | **`+0x3a30`** |
| `__TEXT.__const` | `0x10970` | `0x10d70` | **`+0x400`** |
| `__TEXT.__eh_frame` | `0x7348` | `0x7640` | **`+0x2f8`** |
| `__DATA.__bss` | `0x18cb0` | `0x18f30` | **`+0x280`** |
| `__AUTH_CONST.__const` | `0xd1b0` | `0xd2c0` | **`+0x110`** |
| `__TEXT.__swift5_typeref` | `0x395e` | `0x3a6c` | **`+0x10e`** |
| `__TEXT.__unwind_info` | `0x63a0` | `0x6470` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x11442` | `0x11392` | **`-0xb0`** |
| `__AUTH_CONST.__cfstring` | `0xd5c0` | `0xd520` | **`-0xa0`** |
| `__TEXT.__oslogstring` | `0x1347d` | `0x1351d` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x25c8` | `0x2624` | **`+0x5c`** |
| `__DATA.__data` | `0x4404` | `0x445c` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x2a18` | `0x2a60` | **`+0x48`** |
| `__TEXT.__swift_as_cont` | `0x4c8` | `0x4fc` | **`+0x34`** |
| `__TEXT.__swift5_reflstr` | `0x15ba` | `0x15ea` | **`+0x30`** |
| `__TEXT.__swift5_acfuncs` | `0x17c` | `0x1a4` | **`+0x28`** |
| `__TEXT.__swift5_builtin` | `0x168` | `0x190` | **`+0x28`** |
| `__TEXT.__swift5_mpenum` | `0x50` | `0x6c` | **`+0x1c`** |
| `__TEXT.__swift_as_ret` | `0x274` | `0x290` | **`+0x1c`** |
| `__TEXT.__swift5_proto` | `0xc5c` | `0xc70` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x240` | `0x254` | **`+0x14`** |
| `__AUTH_CONST.__objc_const` | `0x269d0` | `0x269e0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x5250` | `0x5240` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x814` | `0x804` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x2e0` | `0x2d8` | **`-0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x4a70` | `0x4a68` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0xb564` | `0xb56c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x348` | `0x350` | **`+0x8`** |

### Other Changes

```diff

-1059.1.1.0.0
+1061.0.0.0.0

-  Functions: 9070
-  Symbols:   9972
-  CStrings:  3709
+  Functions: 9114
+  Symbols:   9988
+  CStrings:  3706
Symbols:
+ -[AATrustedContact firstNameOrHandleForDisplay]
+ ___swift_closure_destructor.109Tm
+ ___swift_closure_destructor.113Tm
+ _associated conformance 12AppleAccount0aB12ToolXPCErrorO22ServiceErrorCodingKeys33_8ED6417259195D25C9BF59936E2C6D5CLLOSHAASQ
+ _associated conformance 12AppleAccount0aB12ToolXPCErrorO22ServiceErrorCodingKeys33_8ED6417259195D25C9BF59936E2C6D5CLLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 12AppleAccount0aB12ToolXPCErrorO22ServiceErrorCodingKeys33_8ED6417259195D25C9BF59936E2C6D5CLLOs0G3KeyAAs28CustomDebugStringConvertible
+ _get_enum_tag_for_layout_string 12AppleAccount0aB12ToolXPCErrorO
+ _get_enum_tag_for_layout_string 12AppleAccount20IdentityLoadingStateO
+ _get_type_metadata 15Synchronization5MutexVy12AppleAccount20IdentityLoadingStateOG noncopyable
+ _get_type_metadata 15Synchronization5MutexVySDy12AppleAccount7AltDSIDCAD08IdentityD0V7account_yAD0G0Cc8callback10Foundation4UUIDVSg05knownG2ID14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceVSg06remoteR0AD0G13ObserverTokenVSg5tokentGG noncopyable
+ _get_type_metadata 15Synchronization5MutexVySbG noncopyable
+ _symbolic SDy__________7account_y_____c8callback_____Sg15knownIdentityID_____Sg15remoteInterface_____Sg5tokentG 12AppleAccount7AltDSIDC AA08IdentityB0V AA0E0C 10Foundation4UUIDV 14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV AA0E13ObserverTokenV
+ _symbolic SS7message_t
+ _symbolic _____ 12AppleAccount0aB12ToolXPCErrorO22ServiceErrorCodingKeys33_8ED6417259195D25C9BF59936E2C6D5CLLO
+ _symbolic _____ 12AppleAccount20IdentityLoadingStateO
+ _symbolic _____7account______Iegg_8callback_____Sg15knownIdentityID_____Sg15remoteInterface_____Sg5tokent 12AppleAccount08IdentityB0V AA0C0C 10Foundation4UUIDV 14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV AA0C13ObserverTokenV
+ _symbolic _____7account_yyc8callback_____Sg15knownIdentityID_____Sg15remoteInterface_____Sg5tokent 12AppleAccount08IdentityB0V 10Foundation4UUIDV 14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV AA0C13ObserverTokenV
+ _symbolic _____7account_yyc8callback_____Sg15knownIdentityID_____Sg15remoteInterface_____Sg5tokentSg 12AppleAccount08IdentityB0V 10Foundation4UUIDV 14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV AA0C13ObserverTokenV
+ _symbolic _____Sg 12AppleAccount21IdentityObserverTokenV
+ _symbolic _____Sg 14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV
+ _symbolic ___________7account_yyc8callback_____Sg15knownIdentityID_____Sg15remoteInterface_____Sg5tokentt 12AppleAccount7AltDSIDC AA08IdentityB0V 10Foundation4UUIDV 14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV AA0E13ObserverTokenV
+ _symbolic _____ySDy__________7account_y_____c8callback_____Sg15knownIdentityID_____Sg15remoteInterface_____Sg5tokentGG 15Synchronization5MutexVAARi_zrlE 12AppleAccount7AltDSIDC AD08IdentityD0V AD0G0C 10Foundation4UUIDV 14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV AD0G13ObserverTokenV
+ _symbolic _____ySbG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____y_____7account_y_____c8callback_____Sg15knownIdentityID_____Sg15remoteInterface_____Sg5tokentG s23_ContiguousArrayStorageC 12AppleAccount08IdentityE0V AC0F0C 10Foundation4UUIDV 14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV AC0F13ObserverTokenV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 12AppleAccount20IdentityLoadingStateO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12AppleAccount0dE12ToolXPCErrorO22ServiceErrorCodingKeys33_8ED6417259195D25C9BF59936E2C6D5CLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12AppleAccount0dE12ToolXPCErrorO22ServiceErrorCodingKeys33_8ED6417259195D25C9BF59936E2C6D5CLLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV
+ _symbolic _____y__________7account_y_____c8callback_____Sg15knownIdentityID_____Sg15remoteInterface_____Sg5tokentG s18_DictionaryStorageC 12AppleAccount7AltDSIDC AC08IdentityD0V AC0G0C 10Foundation4UUIDV 14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV AC0G13ObserverTokenV
+ _type_layout_string 12AppleAccount20IdentityLoadingStateO
- +[AAPreferences isRCInSettingsEnabled]
- +[AAPreferences isRCUpsellEnabled]
- ___swift_closure_destructor.102Tm
- ___swift_closure_destructor.98Tm
- _get_type_metadata 15Synchronization5MutexVy12AppleAccount8IdentityCSgG noncopyable
- _swift_coroFrameAlloc
- _symbolic SDy__________15remoteInterface______5tokeny_____c8callback_____7account_____Sg15knownIdentityIDtG 12AppleAccount7AltDSIDC 14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV AA21IdentityObserverTokenV AA0J0C AA0jB0V 10Foundation4UUIDV
- _symbolic _____15remoteInterface______5token_____Iegg_8callback_____7account_____Sg15knownIdentityIDt 14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV 12AppleAccount21IdentityObserverTokenV AH0H0C AH0hG0V 10Foundation4UUIDV
- _symbolic _____15remoteInterface______5tokenyyc8callback_____7account_____Sg15knownIdentityIDt 14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV 12AppleAccount21IdentityObserverTokenV AH0hG0V 10Foundation4UUIDV
- _symbolic _____15remoteInterface______5tokenyyc8callback_____7account_____Sg15knownIdentityIDtSg 14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV 12AppleAccount21IdentityObserverTokenV AH0hG0V 10Foundation4UUIDV
- _symbolic ___________15remoteInterface______5tokenyyc8callback_____7account_____Sg15knownIdentityIDtt 12AppleAccount7AltDSIDC 14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV AA21IdentityObserverTokenV AA0jB0V 10Foundation4UUIDV
- _symbolic _____y_____15remoteInterface______5tokeny_____c8callback_____7account_____Sg15knownIdentityIDtG s23_ContiguousArrayStorageC 14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV 12AppleAccount21IdentityObserverTokenV AJ0K0C AJ0kJ0V 10Foundation4UUIDV
- _symbolic _____y_____SgG 15Synchronization5MutexVAARi_zrlE 12AppleAccount8IdentityC
- _symbolic _____y__________15remoteInterface______5tokeny_____c8callback_____7account_____Sg15knownIdentityIDtG s18_DictionaryStorageC 12AppleAccount7AltDSIDC 14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV AC21IdentityObserverTokenV AC0L0C AC0lD0V 10Foundation4UUIDV
CStrings:
+ "$s12AppleAccount28$IdentityXPCServiceInterfaceC13stopObserving5tokenyAA0C13ObserverTokenV_tYaKFTE"
+ "Registration deferred: app backgrounded"
+ "Registration deferred: app backgrounded mid-connect"
+ "Registration deferred: failed to start observing identity changes: %@"
+ "Stopped observing identity changes for account: %s (no interface)"
+ "deleteCachedIdentity(account:)"
- "CUSTODIAN_MESSAGES_INVITE_TEXT"
- "CUSTODIAN_SPLASH_SCREEN_THIRD_BULLET_DESCRIPTION"
- "CUSTODIAN_SPLASH_SCREEN_THIRD_BULLET_DESCRIPTION_NEW"
- "CUSTODIAN_SPLASH_SCREEN_THIRD_BULLET_TITLE"
- "CUSTODIAN_SPLASH_SCREEN_THIRD_BULLET_TITLE_NEW"
- "Cannot register observer while the app is backgrounded"
- "Failed to start observing identity changes: %@"
- "RCUpsellMiniBuddy"
- "UpdatedRCFlow"
```
