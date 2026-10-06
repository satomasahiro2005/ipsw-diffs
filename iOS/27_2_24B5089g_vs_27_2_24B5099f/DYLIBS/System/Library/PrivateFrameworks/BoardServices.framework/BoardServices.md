## BoardServices

> `/System/Library/PrivateFrameworks/BoardServices.framework/BoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ef24` | `0x8007c` | **`+0x1158`** |
| `__AUTH_CONST.__const` | `0x1df8` | `0x2040` | **`+0x248`** |
| `__DATA.__bss` | `0x1300` | `0x1500` | **`+0x200`** |
| `__TEXT.__const` | `0x19d8` | `0x1af8` | **`+0x120`** |
| `__TEXT.__swift5_typeref` | `0x8c8` | `0x9be` | **`+0xf6`** |
| `__TEXT.__constg_swiftt` | `0x868` | `0x94c` | **`+0xe4`** |
| `__AUTH_CONST.__auth_got` | `0xec8` | `0xf68` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x480` | `0x50c` | **`+0x8c`** |
| `__TEXT.__eh_frame` | `0x1c08` | `0x1bb8` | **`-0x50`** |
| `__AUTH_CONST.__objc_const` | `0x6650` | `0x6698` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x28a1` | `0x28e2` | **`+0x41`** |
| `__TEXT.__unwind_info` | `0x2a40` | `0x2a78` | **`+0x38`** |
| `__DATA.__data` | `0x1610` | `0x1640` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x634` | `0x660` | **`+0x2c`** |
| `__TEXT.__cstring` | `0x7804` | `0x781e` | **`+0x1a`** |
| `__DATA.__common` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x5c8` | `0x5e0` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x64` | `0x50` | **`-0x14`** |
| `__TEXT.__swift_as_ret` | `0x64` | `0x50` | **`-0x14`** |
| `__DATA_CONST.__objc_protolist` | `0x1f0` | `0x200` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x90` | `0xa0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xa4` | `0xb0` | **`+0xc`** |
| `__AUTH.__data` | `0x430` | `0x428` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x13d8` | `0x13d0` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x8c` | `0x94` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x7c` | `0x80` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-827.2.1.1.0
+827.2.3.0.0

-  Functions: 1923
-  Symbols:   2860
-  CStrings:  1007
+  Functions: 1969
+  Symbols:   2884
+  CStrings:  1009
Symbols:
+ __IVARS__TtC13BoardServices25ServiceConnectionListener
+ ___swift_allocate_value_buffer
+ ___swift_closure_destructor.14Tm
+ ___swift_closure_destructor.79Tm
+ ___swift_project_value_buffer
+ ___unnamed_1
+ ___unnamed_11
+ __swiftImmortalRefCount
+ __swift_stdlib_bridgeErrorToNSError
+ _flat unique So13BSXPCEncoding_p
+ _flat unique So36BSServiceConnectionCommonConfiguring_p
+ _flat unique So36BSServiceConnectionInitiatingOptions_p
+ _get_enum_tag_for_layout_string 10Foundation4DataV15_RepresentationO
+ _get_enum_tag_for_layout_string 10Foundation4DataVSg
+ _swift_allocateGenericClassMetadata
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
+ _swift_initClassMetadata2
+ _swift_once
+ _swift_slowAlloc
+ _symbolic So40BSServiceConnectionListenerConfigurationC
+ _symbolic So40BSServiceInitiatingConnectionMultiplexerCSg
+ _symbolic So8NSObjectCSg
+ _symbolic _____ 10Foundation4DataV
+ _symbolic _____ 13BoardServices14InitiatingRoleV17ConnectionOptionsV
+ _symbolic _____ 13BoardServices25ServiceConnectionListenerC
+ _symbolic _____ 13BoardServices25ServiceConnectionListenerC23NoInitiatingContextData33_ED4D3A0035BF3333C40FF73FC8C2E143LLV
+ _symbolic _____ 13BoardServices30ServiceConnectionConfigurationV
+ _symbolic _____Sg 10Foundation4DataV
+ _symbolic _____SgIeghHn_Sg 13BoardServices10AuditTokenV
+ _symbolic _____Sg_yyYaYbcSgt 13BoardServices14ReceivingProxyV
+ _symbolic _____Sg_yycSgt 13BoardServices14ReceivingProxyV
+ _symbolic ______pIgg_ So13BSXPCEncodingP
+ _symbolic ______pIgg_ So36BSServiceConnectionCommonConfiguringP
+ _symbolic ______pIgg_ So36BSServiceConnectionInitiatingOptionsP
+ _symbolic _____ySo27BSServiceConnectionListenerCSgG 2os21OSAllocatedUnfairLockV
+ _symbolic _____ySo27BSServiceConnectionListenerCSg_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
+ _symbolic _____yx_G7context______10auditTokent 13BoardServices14InitiatingRoleV17ActivationContextV AA10AuditTokenV
+ _symbolic _____yx_G7context______yx_G9observerst 13BoardServices14InitiatingRoleV17ActivationContextV AC0E9ObserversV
+ _symbolic _____yxq______GIeghn_ 13BoardServices17ServiceConnectionV AA12ListenerRoleV
+ _symbolic _____yxq______Gqd__Ieghnn_ 13BoardServices17ServiceConnectionV AA12ListenerRoleV
+ _symbolic yycSg
+ _type_layout_string 13BoardServices15MessagingPolicyRzlAA14InitiatingRoleV17ConnectionOptionsVyx_G
+ _type_layout_string 13BoardServices30ServiceConnectionConfigurationV
- ___swift_closure_destructor.80Tm
- ___swift_memcpy40_8
- _get_enum_tag_for_layout_string 13BoardServices10AuditTokenVSgIeghHn_Sg
- _get_enum_tag_for_layout_string IeghH_Sg
- _objc_retain_x11
- _swift_bridgeObjectRelease_n
- _swift_getTupleTypeMetadata3
- _symbolic IeghH_
- _symbolic _____ 13BoardServices12ListenerRoleV13ConfigurationV
- _symbolic _____ 13BoardServices14InitiatingRoleV13ConfigurationV
- _symbolic _____13configuration______Sg14receivingProxyt 13BoardServices12ListenerRoleV13ConfigurationV AA14ReceivingProxyV
- _symbolic _____13configuration_t 13BoardServices12ListenerRoleV13ConfigurationV
- _symbolic _____SgIeghHn_ 13BoardServices10AuditTokenV
- _symbolic _____SgytIeghHnr_ 13BoardServices10AuditTokenV
- _symbolic _____yx_G13configuration______yx_G7context_____10auditTokent 13BoardServices14InitiatingRoleV13ConfigurationV AC17ActivationContextV AA10AuditTokenV
- _symbolic _____yx_G13configuration______yx_G7context_____yx_G9observerst 13BoardServices14InitiatingRoleV13ConfigurationV AC17ActivationContextV AC0F9ObserversV
- _symbolic _____yx_G13configuration_t 13BoardServices14InitiatingRoleV13ConfigurationV
- _symbolic _____yxq______yqd__GG_____SgIeghHnn_Sg 13BoardServices17ServiceConnectionV AA14InitiatingRoleV AA10AuditTokenV
- _symbolic ytIeghHr_
- _symbolic yyYaYbcSg
- _type_layout_string 13BoardServices12ListenerRoleV13ConfigurationV
- _type_layout_string 13BoardServices15MessagingPolicyRzlAA14InitiatingRoleV13ConfigurationVyx_G
CStrings:
+ "No initiating context data"
+ "ServiceConnection"
+ "Unable to decode initiating connection context (expected %s): %@"
+ "activate(activationHandler:interruptionHandler:invalidationHandler:)"
+ "activate(with:at:activationHandler:interruptionHandler:invalidationHandler:)"
+ "context auditToken "
+ "context observers "
- "activate(activationHandler:interruptionHandler:)"
- "activate(with:at:activationHandler:interruptionHandler:)"
- "configuration context auditToken "
- "configuration context observers "
- "configuration receivingProxy "
```
