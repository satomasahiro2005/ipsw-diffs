## TelephonyUtilities

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/TelephonyUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19cb70` | `0x19d6a0` | **`+0xb30`** |
| `__AUTH_CONST.__objc_const` | `0x2ac98` | `0x2aeb0` | **`+0x218`** |
| `__TEXT.__objc_methlist` | `0x1b4b0` | `0x1b5c8` | **`+0x118`** |
| `__TEXT.__oslogstring` | `0x13b17` | `0x13c17` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0x12480` | `0x12540` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x14126` | `0x141c6` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0xb720` | `0xb788` | **`+0x68`** |
| `__AUTH.__objc_data` | `0x28d0` | `0x2920` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x6d00` | `0x6d40` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x37b0` | `0x37e0` | **`+0x30`** |
| `__TEXT.__const` | `0x40d8` | `0x40a8` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0x14d0` | `0x14f8` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x18e4` | `0x18f8` | **`+0x14`** |
| `__DATA.__data` | `0x3d28` | `0x3d38` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xfe0` | `0xfe8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x880` | `0x888` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x6e0` | `0x6e8` | **`+0x8`** |

### Other Changes

```diff

-1608.100.12.2.6
+1612.100.3.2.1

-  Functions: 11511
-  Symbols:   15978
-  CStrings:  4589
+  Functions: 11534
+  Symbols:   16021
+  CStrings:  4600
Symbols:
+ +[TUDegradationReport reportForDegradations:dateCallConnected:conversationReport:]
+ +[TUDegradationReport supportsSecureCoding]
+ +[TUICFInterface allowCallForDestinationIDs:providerIdentifier:]
+ +[TUICFInterface allowCallForDestinationIDs:providerIdentifier:queue:completionHandler:]
+ -[TUCallCenter reportDegradation:forGroupUUID:]
+ -[TUCallDisplayContext description]
+ -[TUCallServicesInterface reportDegradation:forGroupUUID:]
+ -[TUDegradationReport .cxx_destruct]
+ -[TUDegradationReport duration]
+ -[TUDegradationReport encodeWithCoder:]
+ -[TUDegradationReport initWithCoder:]
+ -[TUDegradationReport initWithType:startTimestamp:duration:]
+ -[TUDegradationReport initWithType:startTimestamp:duration:participantID:result:]
+ -[TUDegradationReport participantID]
+ -[TUDegradationReport result]
+ -[TUDegradationReport startTimestamp]
+ -[TUDegradationReport type]
+ -[TUFeatureFlags callContextCardAllLanguagesEnabled]
+ -[TUFeatureFlags smartVoicemailActionsAllLanguagesEnabled]
+ GCC_except_table110
+ GCC_except_table113
+ GCC_except_table149
+ GCC_except_table159
+ GCC_except_table162
+ GCC_except_table165
+ GCC_except_table168
+ GCC_except_table177
+ GCC_except_table180
+ GCC_except_table215
+ GCC_except_table237
+ GCC_except_table242
+ _ICFCallProviderShouldAllowIncomingGroupCallWithQueue
+ _OBJC_CLASS_$_TUDegradationReport
+ _OBJC_IVAR_$_TUDegradationReport._duration
+ _OBJC_IVAR_$_TUDegradationReport._participantID
+ _OBJC_IVAR_$_TUDegradationReport._result
+ _OBJC_IVAR_$_TUDegradationReport._startTimestamp
+ _OBJC_IVAR_$_TUDegradationReport._type
+ _OBJC_METACLASS_$_TUDegradationReport
+ _OUTLINED_FUNCTION_9
+ _TUBundleIdentifierContactsApplication
+ _TUCanShowContextCards
+ _TUNotificationFromTrustedXPCObject
+ __OBJC_$_CLASS_METHODS_TUDegradationReport
+ __OBJC_$_CLASS_PROP_LIST_TUDegradationReport
+ __OBJC_$_INSTANCE_METHODS_TUDegradationReport
+ __OBJC_$_INSTANCE_VARIABLES_TUDegradationReport
+ __OBJC_$_PROP_LIST_TUDegradationReport
+ __OBJC_CLASS_PROTOCOLS_$_TUDegradationReport
+ __OBJC_CLASS_RO_$_TUDegradationReport
+ __OBJC_METACLASS_RO_$_TUDegradationReport
+ ___64+[TUICFInterface allowCallForDestinationIDs:providerIdentifier:]_block_invoke
+ ___88+[TUICFInterface allowCallForDestinationIDs:providerIdentifier:queue:completionHandler:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e11_v16?0B8B12ls32l8
+ __xpc_type_data
+ _xpc_data_get_bytes_ptr
+ _xpc_data_get_length
+ _xpc_dictionary_get_string
+ _xpc_dictionary_get_value
+ _xpc_get_type
- -[TUDynamicCallDisplayContext description]
- GCC_except_table109
- GCC_except_table112
- GCC_except_table148
- GCC_except_table158
- GCC_except_table161
- GCC_except_table164
- GCC_except_table167
- GCC_except_table170
- GCC_except_table173
- GCC_except_table176
- GCC_except_table179
- GCC_except_table214
- GCC_except_table236
- GCC_except_table241
- _ICFCallProviderShouldAllowIncomingCallWithQueue
- ___63+[TUICFInterface allowCallForDestinationID:providerIdentifier:]_block_invoke
CStrings:
+ " contactIdentifiers=%@"
+ " suggestedNameOriginBundleID=%@"
+ "%ld,%d,%d,%ld,%ld;"
+ "%ld,%d,%d,-1,%ld;"
+ "%ld,%d,%d,0,%ld;"
+ "CallContextCardAllLanguages"
+ "Could not deserialize userInfo plist for trusted XPC event '%{public}s': %@"
+ "SmartVoicemailActionsAllLanguages"
+ "TUCallCenter: reportDegradation: %@ for group: %@"
+ "Unexpected plist type for trusted XPC event '%{public}s': %@"
+ "[WARN] Nil destinationID passed in, allowing call"
+ "[WARN] Timed out waiting for ICFCallProviderShouldAllowIncomingGroupCall(). Defaulting to allowCall=YES, fromBlockList=NO"
- "[WARN] Timed out waiting for ICFCallProviderShouldAllowIncomingCall(). Defaulting to allowCall=YES, fromBlockList=NO"
```
