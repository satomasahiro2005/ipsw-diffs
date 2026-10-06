## AppleCameraISPExclaveKitServices

> `/System/Library/PrivateFrameworks/AppleCameraISPExclaveKitServices.framework/AppleCameraISPExclaveKitServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2fb5c` | `0x2fd40` | **`+0x1e4`** |
| `__DATA.__data` | `0x1184c8` | `0x1185d0` | **`+0x108`** |
| `__TEXT.__cstring` | `0x85d6` | `0x8566` | **`-0x70`** |
| `__TEXT.__oslogstring` | `0x430e` | `0x42ae` | **`-0x60`** |
| `__DATA.__bss` | `0x38` | `—` | **`-0x38`** |
| `__DATA.__common` | `0x60` | `0x98` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x520` | `0x540` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x968` | `0x988` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x560` | `0x578` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x884` | `0x898` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x10c8` | `0x10b8` | **`-0x10`** |
| `__TEXT.__const` | `0x2ea` | `0x2fa` | **`+0x10`** |

### Other Changes

```diff

-20.47.7.0.0
+20.50.6.0.0

-  Functions: 1155
-  Symbols:   755
-  CStrings:  792
+  Functions: 1158
+  Symbols:   763
+  CStrings:  789
Symbols:
+ GCC_except_table13
+ GCC_except_table21
+ _OUTLINED_FUNCTION_24
+ __Z22isUSODataReplayEnabledP21ISPExclaveKitDefaults
+ __Z25isUSODataReplayDefaultSetP21ISPExclaveKitDefaults
+ __Z47isNewSharedMemoryReplayBufferDumpOverlayEnabledP21ISPExclaveKitDefaults
+ __ZN28ISPExclaveKitFileDumpService17addEkDebugServiceEm
+ __ZN28ISPExclaveKitFileDumpService30_dumpBufferDoneSignalToExclaveE21FileServiceBufferInfo46applecamera_ispexclavekitdebugmodule_ekdebug_s
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIP21FileServiceBufferInfoEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__15dequeI21FileServiceBufferInfoNS_9allocatorIS1_EEE26__maybe_remove_front_spareB9fqe220106Eb
+ __ZNSt3__15dequeI21FileServiceBufferInfoNS_9allocatorIS1_EEED2B9fqe220106Ev
+ __ZNSt3__15mutex4lockEv
+ __ZNSt3__15mutex6unlockEv
+ __ZNSt3__15mutexD1Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ ____ZN28ISPExclaveKitFileDumpService30_dumpBufferDoneSignalToExclaveE21FileServiceBufferInfo46applecamera_ispexclavekitdebugmodule_ekdebug_s_block_invoke
+ _applecamera_ispexclavekitdebugmodule_ekdebug_channelnewsharedmemoryreplaybuffergetdone
+ _pHostMetaManager
- _OUTLINED_FUNCTION_23
- _OUTLINED_FUNCTION_26
- __Z33ispExclaveKitCommandChFidGetStateP20sExclaveKitIspCmdHdr
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220100Em
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIP21FileServiceBufferInfoEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__15dequeI21FileServiceBufferInfoNS_9allocatorIS1_EEE26__maybe_remove_front_spareB9fqe220100Eb
- __ZNSt3__15dequeI21FileServiceBufferInfoNS_9allocatorIS1_EEED2B9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- __ZZL20_sensorMetaInjectionPKN25ISPExclaveKitAutoExposure31sExclaveKitIspCmdChSendMetadataEP57applecamera_ispexclavekitshared_ekchannelsensormetadata_sE17s_hostMetaManager
- ____Z33ispExclaveKitCommandChFidGetStateP20sExclaveKitIspCmdHdr_block_invoke
- _applecamera_fidflowmodule_ekfidflow_channelfidgetstate
CStrings:
+ "%s:%d - [EK] send buffer done signal back to Exclave\n"
+ "%s:%d - ch:%u rawFrame.bufferId:%llu isReady:%u coachingStatus:%u Attn:%u FD:%u\n"
+ "%s:%d - isUSODataReplayDefaultSet=%d\n"
+ "%s:%d - isUSODataReplayEnabled=%d\n"
+ "%s:%d - pHostMetaManager not created for chIdx=%d\n"
+ "%s:%d - usoDataReplayEnabled=%d\n"
+ "TB_FATAL: invalid result returned from channelNewSharedMemoryReplayBufferGetDone"
+ "TB_FATAL: invalid result returned from channelNewSharedMemoryReplayBufferGetDone (%s:%d)\n"
+ "_dumpBufferDoneSignalToExclave"
+ "usoDataReplayEnabled"
+ "v24@?0{applecamera_ispexclavekitdebugmodule_ekdebug_channelnewsharedmemoryreplaybuffergetdone__result_s=C(?={applecamera_exclavesispshared_exclavesisperror_s=Q})}8"
+ "v280@?0{applecamera_fidflowmodule_ekfidflow_channelrunfidflow__result_s=C(?={applecamera_exclavesispshared_exclavesisperror_s=Q}{applecamera_fidflowmodule_fidresult_s={applecamera_fidflowmodule_frameinfo_s=Q{applecamera_fidflowmodule_fidframetype_s=Q}II{applecamera_fidflowmodule_bufferdescriptor_s=QQQ{applecamera_fidflowmodule_bufferformatdescriptor_s=IIII{applecamera_fidflowmodule_elementformat_s=Q}{applecamera_fidflowmodule_channellayout_s=Q}I}}{applecamera_fidflowmodule_bufferdescriptor_s=QQQ{applecamera_fidflowmodule_bufferformatdescriptor_s=IIII{applecamera_fidflowmodule_elementformat_s=Q}{applecamera_fidflowmodule_channellayout_s=Q}I}}{applecamera_fidflowmodule_bufferdescriptor_s=QQQ{applecamera_fidflowmodule_bufferformatdescriptor_s=IIII{applecamera_fidflowmodule_elementformat_s=Q}{applecamera_fidflowmodule_channellayout_s=Q}I}}}{applecamera_fidflowmodule_fidstate_s=BI}{applecamera_fidflowmodule_fidattentioninfo_s={applecamera_fidflowmodule_facerectf_s=ffff}{applecamera_fidflowmodule_headpose_s=fffI}BB}})}8"
- "%s:%d - Created ISPExclaveKitHostMetaManager for channel %d\n"
- "%s:%d - FidGetState\n"
- "%s:%d - ch:%u pCmdChFid->result.frameInfo.rawFrame.bufferId: %llu, isReady: %u, coachingStatus: %u\n"
- "%s:%d - invalid channel index=%d\n"
- "%s:%d - pCmdChFid->result.isReady: %u, coachingStatus: %u\n"
- "%s:%d - run ISP_EXCLAVEKIT_CMD_CH_FID_GET_STATE!\n"
- "%s:%d - tb_res->value.success.isReady: %u, coachingStatus: %u\n"
- "ISPExclaveKitCmdHandlerChAe.cpp"
- "ISP_EXCLAVEKIT_CMD_CH_FID_GET_STATE"
- "TB_FATAL: invalid result returned from channelFidGetState"
- "TB_FATAL: invalid result returned from channelFidGetState (%s:%d)\n"
- "decodeFidState"
- "ispExclaveKitCommandChFidGetState"
- "v24@?0{applecamera_fidflowmodule_ekfidflow_channelfidgetstate__result_s=C(?={applecamera_exclavesispshared_exclavesisperror_s=Q}{applecamera_fidflowmodule_fidstate_s=BI})}8"
- "v296@?0{applecamera_fidflowmodule_ekfidflow_channelrunfidflow__result_s=C(?={applecamera_exclavesispshared_exclavesisperror_s=Q}{applecamera_fidflowmodule_fidresult_s={applecamera_fidflowmodule_frameinfo_s=Q{applecamera_fidflowmodule_fidframetype_s=Q}II{applecamera_fidflowmodule_bufferdescriptor_s=QQQ{applecamera_fidflowmodule_bufferformatdescriptor_s=IIII{applecamera_fidflowmodule_elementformat_s=Q}{applecamera_fidflowmodule_channellayout_s=Q}I}}{applecamera_fidflowmodule_bufferdescriptor_s=QQQ{applecamera_fidflowmodule_bufferformatdescriptor_s=IIII{applecamera_fidflowmodule_elementformat_s=Q}{applecamera_fidflowmodule_channellayout_s=Q}I}}{applecamera_fidflowmodule_bufferdescriptor_s=QQQ{applecamera_fidflowmodule_bufferformatdescriptor_s=IIII{applecamera_fidflowmodule_elementformat_s=Q}{applecamera_fidflowmodule_channellayout_s=Q}I}}}{applecamera_fidflowmodule_fidstate_s=BI}{applecamera_fidflowmodule_fidattentioninfo_s={applecamera_fidflowmodule_facerectf_s=ffff}{applecamera_fidflowmodule_headpose_s=fffI}{applecamera_fidflowmodule_vector2f_s=ff}{applecamera_fidflowmodule_eyeopen_s=ff}B}})}8"
```
