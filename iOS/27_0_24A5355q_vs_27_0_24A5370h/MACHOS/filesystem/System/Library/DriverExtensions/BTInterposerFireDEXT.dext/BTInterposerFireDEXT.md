## BTInterposerFireDEXT

> `/System/Library/DriverExtensions/BTInterposerFireDEXT.dext/BTInterposerFireDEXT`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4` | `0x1a70` | **`+0x1a6c`** |
| `__DATA_CONST.__const` | `—` | `0x650` | **`+0x650`** |
| `__TEXT.__const` | `—` | `0x540` | **`+0x540`** |
| `__TEXT.__oslogstring` | `—` | `0x3b6` | **`+0x3b6`** |
| `__TEXT.__auth_stubs` | `—` | `0x1f0` | **`+0x1f0`** |
| `__DATA_CONST.__auth_got` | `—` | `0xf8` | **`+0xf8`** |
| `__TEXT.__cstring` | `—` | `0xbb` | **`+0xbb`** |
| `__TEXT.__unwind_info` | `0x58` | `0xc0` | **`+0x68`** |
| `__DATA.__common` | `—` | `0x20` | **`+0x20`** |
| `__DATA_CONST.__got` | `—` | `0x20` | **`+0x20`** |
| `__DATA_CONST.__osclassinfo` | `—` | `0x20` | **`+0x20`** |

### Other Changes

```diff

-2700.37.0.0.0
+2700.41.1.1.0

-  Functions: 1
-  Symbols:   2
-  CStrings:  0
+  - /System/DriverKit/usr/lib/libc++.dylib
+  Functions: 44
+  Symbols:   118
+  CStrings:  26
Symbols:
+ _BTInterposerFireDEXT_Class
+ _IOFree
+ _IOMallocZeroTyped
+ _IORPCMessageFromMach
+ _OSAction_BTInterposerFireDEXT_RelayNcpEvent_Class
+ _OSAction_BTInterposerFireDEXT_RelayRxReady_Class
+ _OSAction_BTInterposerFireDEXT_RelayTxReady_Class
+ __Block_object_assign
+ __Block_object_dispose
+ __NSConcreteGlobalBlock
+ __NSConcreteStackBlock
+ __ZL24BTInterposerFireDEXT_NewP11OSMetaClass
+ __ZL39OSClassDescription_BTInterposerFireDEXT
+ __ZL46OSAction_BTInterposerFireDEXT_RelayRxReady_NewP11OSMetaClass
+ __ZL46OSAction_BTInterposerFireDEXT_RelayTxReady_NewP11OSMetaClass
+ __ZL47OSAction_BTInterposerFireDEXT_RelayNcpEvent_NewP11OSMetaClass
+ __ZL61OSClassDescription_OSAction_BTInterposerFireDEXT_RelayRxReady
+ __ZL61OSClassDescription_OSAction_BTInterposerFireDEXT_RelayTxReady
+ __ZL62OSClassDescription_OSAction_BTInterposerFireDEXT_RelayNcpEvent
+ __ZN11IOMemoryMap10GetAddressEv
+ __ZN12IOUserClient15_ExternalMethodEyPKyjP6OSDataP18IOMemoryDescriptorPyPjyPS3_S5_P8OSActionPFiP15OSMetaClassBase5IORPCE
+ __ZN12IOUserClient22AsyncCompletion_InvokeE5IORPCP15OSMetaClassBasePFvS2_P8OSActioniPKyjEPK11OSMetaClass
+ __ZN12IOUserClient23CopyClientMemoryForTypeEyPyPP18IOMemoryDescriptorPFiP15OSMetaClassBase5IORPCE
+ __ZN15IODispatchQueue12DispatchSyncEU13block_pointerFvvE
+ __ZN15IODispatchQueue6CreateEPKcyyPPS_
+ __ZN15OSMetaClassBase8DispatchE5IORPC
+ __ZN15OSMetaClassBase8IsRemoteEv
+ __ZN18IOMemoryDescriptor13CreateMappingEyyyyyPP11IOMemoryMapPFiP15OSMetaClassBase5IORPCE
+ __ZN20BTInterposerFireDEXT10Start_ImplEP9IOService
+ __ZN20BTInterposerFireDEXT11SendACLDataEPKhj
+ __ZN20BTInterposerFireDEXT17RelayRxReady_ImplEP8OSActioniPKyj
+ __ZN20BTInterposerFireDEXT17RelayTxReady_ImplEP8OSActioniPKyj
+ __ZN20BTInterposerFireDEXT18RelayNcpEvent_ImplEP8OSActioniPKyj
+ __ZN20BTInterposerFireDEXT24CreateActionRelayRxReadyEmPP8OSAction
+ __ZN20BTInterposerFireDEXT24CreateActionRelayTxReadyEmPP8OSAction
+ __ZN20BTInterposerFireDEXT25CreateActionRelayNcpEventEmPP8OSAction
+ __ZN20BTInterposerFireDEXT4freeEv
+ __ZN20BTInterposerFireDEXT4initEv
+ __ZN20BTInterposerFireDEXT8DispatchE5IORPC
+ __ZN20BTInterposerFireDEXT9Stop_ImplEP9IOService
+ __ZN20BTInterposerFireDEXT9_DispatchEPS_5IORPC
+ __ZN29BTInterposerFireDEXTMetaClass3NewEP8OSObject
+ __ZN29BTInterposerFireDEXTMetaClass8DispatchE5IORPC
+ __ZN42OSAction_BTInterposerFireDEXT_RelayRxReady8DispatchE5IORPC
+ __ZN42OSAction_BTInterposerFireDEXT_RelayRxReady9_DispatchEPS_5IORPC
+ __ZN42OSAction_BTInterposerFireDEXT_RelayTxReady8DispatchE5IORPC
+ __ZN42OSAction_BTInterposerFireDEXT_RelayTxReady9_DispatchEPS_5IORPC
+ __ZN43OSAction_BTInterposerFireDEXT_RelayNcpEvent8DispatchE5IORPC
+ __ZN43OSAction_BTInterposerFireDEXT_RelayNcpEvent9_DispatchEPS_5IORPC
+ __ZN51OSAction_BTInterposerFireDEXT_RelayRxReadyMetaClass3NewEP8OSObject
+ __ZN51OSAction_BTInterposerFireDEXT_RelayRxReadyMetaClass8DispatchE5IORPC
+ __ZN51OSAction_BTInterposerFireDEXT_RelayTxReadyMetaClass3NewEP8OSObject
+ __ZN51OSAction_BTInterposerFireDEXT_RelayTxReadyMetaClass8DispatchE5IORPC
+ __ZN52OSAction_BTInterposerFireDEXT_RelayNcpEventMetaClass3NewEP8OSObject
+ __ZN52OSAction_BTInterposerFireDEXT_RelayNcpEventMetaClass8DispatchE5IORPC
+ __ZN8OSAction18CreateWithTypeNameEP8OSObjectyymP8OSStringPPS_
+ __ZN8OSAction4freeEv
+ __ZN8OSAction6CancelEU13block_pointerFvvE
+ __ZN8OSAction9_DispatchEPS_5IORPC
+ __ZN8OSObject4initEv
+ __ZN8OSString11withCStringEPKc
+ __ZN9IOService11Stop_InvokeE5IORPCP15OSMetaClassBasePFiS2_PS_E
+ __ZN9IOService12Start_InvokeE5IORPCP15OSMetaClassBasePFiS2_PS_E
+ __ZN9IOService14_NewUserClientEjP12OSDictionaryPP12IOUserClientPFiP15OSMetaClassBase5IORPCE
+ __ZN9IOService4StopEPS_PFiP15OSMetaClassBase5IORPCE
+ __ZN9IOService4freeEv
+ __ZN9IOService4initEv
+ __ZN9IOService5StartEPS_PFiP15OSMetaClassBase5IORPCE
+ __ZN9IOService9_DispatchEPS_5IORPC
+ __ZNK15OSMetaClassBase12getMetaClassEv
+ __ZNK15OSMetaClassBase6retainEv
+ __ZNK15OSMetaClassBase7releaseEv
+ __ZNK15OSMetaClassBase9isEqualToEPKS_
+ __ZNK42OSAction_BTInterposerFireDEXT_RelayRxReady12getMetaClassEv
+ __ZNK42OSAction_BTInterposerFireDEXT_RelayTxReady12getMetaClassEv
+ __ZNK43OSAction_BTInterposerFireDEXT_RelayNcpEvent12getMetaClassEv
+ __ZNK8OSObject6retainEv
+ __ZNK8OSObject7releaseEv
+ __ZNK9IOService11GetProviderEv
+ __ZTV20BTInterposerFireDEXT
+ __ZTV29BTInterposerFireDEXTMetaClass
+ __ZTV42OSAction_BTInterposerFireDEXT_RelayRxReady
+ __ZTV42OSAction_BTInterposerFireDEXT_RelayTxReady
+ __ZTV43OSAction_BTInterposerFireDEXT_RelayNcpEvent
+ __ZTV51OSAction_BTInterposerFireDEXT_RelayRxReadyMetaClass
+ __ZTV51OSAction_BTInterposerFireDEXT_RelayTxReadyMetaClass
+ __ZTV52OSAction_BTInterposerFireDEXT_RelayNcpEventMetaClass
+ __ZThn24_N20BTInterposerFireDEXT4freeEv
+ __ZThn24_N20BTInterposerFireDEXT4initEv
+ __ZThn24_N8OSAction4freeEv
+ __ZThn24_N8OSObject4initEv
+ __ZThn48_N20BTInterposerFireDEXT11SendACLDataEPKhj
+ ____ZN20BTInterposerFireDEXT11SendACLDataEPKhj_block_invoke
+ ____ZN20BTInterposerFireDEXT17RelayTxReady_ImplEP8OSActioniPKyj_block_invoke
+ ____ZN20BTInterposerFireDEXT9Stop_ImplEP9IOService_block_invoke
+ ____ZN20BTInterposerFireDEXT9Stop_ImplEP9IOService_block_invoke_2
+ ____ZN20BTInterposerFireDEXT9Stop_ImplEP9IOService_block_invoke_3
+ ___block_descriptor_tmp
+ ___block_literal_global
+ ___copy_helper_block_8_32r40r
+ ___destroy_helper_block_8_32r40r
+ ___stack_chk_fail
+ ___stack_chk_guard
+ __block_descriptor_tmp
+ __block_literal_global
+ __os_log_default
+ __os_log_impl
+ _gBTInterposerFireDEXTMetaClass
+ _gBTInterposerFireDEXT_Declaration
+ _gOSAction_BTInterposerFireDEXT_RelayNcpEventMetaClass
+ _gOSAction_BTInterposerFireDEXT_RelayNcpEvent_Declaration
+ _gOSAction_BTInterposerFireDEXT_RelayRxReadyMetaClass
+ _gOSAction_BTInterposerFireDEXT_RelayRxReady_Declaration
+ _gOSAction_BTInterposerFireDEXT_RelayTxReadyMetaClass
+ _gOSAction_BTInterposerFireDEXT_RelayTxReady_Declaration
+ _memcpy
+ _os_log_type_enabled
- _DummySymbol
CStrings:
+ "BTInterposerFireDEXT: %s action registration failed: %d"
+ "BTInterposerFireDEXT: CopyClientMemoryForType(%llu) failed: %d"
+ "BTInterposerFireDEXT: CreateActionRelayNcpEvent failed: %d"
+ "BTInterposerFireDEXT: CreateActionRelayRxReady failed: %d"
+ "BTInterposerFireDEXT: CreateActionRelayTxReady failed: %d"
+ "BTInterposerFireDEXT: CreateMapping(%llu) failed: %d"
+ "BTInterposerFireDEXT: GetProvider returned nil"
+ "BTInterposerFireDEXT: IODispatchQueue::Create failed: %d"
+ "BTInterposerFireDEXT: Start ok"
+ "BTInterposerFireDEXT: Stop"
+ "BTInterposerFireDEXT: TxSubmit kick failed: %d — slot will drain on next kick"
+ "BTInterposerFireDEXT: _NewUserClient relay failed: %d"
+ "BTInterposerFireDEXT: invalid RX slot ring=%u chipSlotIdx=%u slotLen=%u — skipping"
+ "BTInterposerFireDEXT: relay regions mapped — pool=0x%llx meta=%p ring=%p"
+ "BTInterposerFireDEXT: relay user client opened"
+ "BTInterposerFireDEXT: super::Start failed: %d"
+ "BTInterposerFireDEXT::free"
+ "BTInterposerFireDEXT::init"
+ "NCP"
+ "OSAction_BTInterposerFireDEXT_RelayNcpEvent"
+ "OSAction_BTInterposerFireDEXT_RelayRxReady"
+ "OSAction_BTInterposerFireDEXT_RelayTxReady"
+ "RX"
+ "TX"
+ "com.apple.BTInterposerFireDEXT.txpending"
+ "v8@?0"
```
