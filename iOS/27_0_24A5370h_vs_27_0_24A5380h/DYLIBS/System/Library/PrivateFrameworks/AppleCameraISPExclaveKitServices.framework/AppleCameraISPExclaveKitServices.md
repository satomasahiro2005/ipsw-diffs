## AppleCameraISPExclaveKitServices

> `/System/Library/PrivateFrameworks/AppleCameraISPExclaveKitServices.framework/AppleCameraISPExclaveKitServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2fd40` | `0x30b60` | **`+0xe20`** |
| `__TEXT.__cstring` | `0x8566` | `0x8876` | **`+0x310`** |
| `__DATA_CONST.__const` | `0x10b8` | `0x1128` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x42ae` | `0x431e` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x898` | `0x8c8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x988` | `0x9a8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x578` | `0x588` | **`+0x10`** |
| `__TEXT.__const` | `0x2fa` | `0x2ea` | **`-0x10`** |

### Other Changes

```diff

-20.50.6.0.0
+20.55.3.0.0

-  Functions: 1158
-  Symbols:   763
-  CStrings:  789
+  Functions: 1174
+  Symbols:   772
+  CStrings:  802
Symbols:
+ __Z35ispExclaveKitCommandChSetGmcResultsP20sExclaveKitIspCmdHdr
+ __Z44ispExclaveKitCommandChFidSessionConfigUpdateP20sExclaveKitIspCmdHdr
+ ____Z35ispExclaveKitCommandChSetGmcResultsP20sExclaveKitIspCmdHdr_block_invoke
+ ____Z44ispExclaveKitCommandChFidSessionConfigUpdateP20sExclaveKitIspCmdHdr_block_invoke
+ _applecamera_attentionawarenessmodule_ekattentionawareness_setgmcresults
+ _applecamera_attentionawarenessmodule_ekattentionawareness_setgmcresults__result_get_success
+ _applecamera_fidflowmodule_ekfidflow_channelfidsessionconfigupdate
+ _tb_message_raw_decode_f64
+ _tb_message_raw_encode_f64
CStrings:
+ "%s:%d - Attention: p %f r %f yaw %f ori %u dist %f w %f h %f x %f y %f\n\n"
+ "%s:%d - [IR-EK] setGmcResults\n"
+ "%s:%d - [IR-EK] setGmcResults Finished\n"
+ "%s:%d - set GMC results\n"
+ "ISP_EXCLAVEKIT_CMD_CH_FID_SESSION_CONFIG_UPDATE"
+ "ISP_EXCLAVEKIT_CMD_CH_SET_GMC_RESULTS"
+ "TB_FATAL: invalid result returned from channelFidSessionConfigUpdate"
+ "TB_FATAL: invalid result returned from channelFidSessionConfigUpdate (%s:%d)\n"
+ "TB_FATAL: invalid result returned from setGmcResults"
+ "TB_FATAL: invalid result returned from setGmcResults (%s:%d)\n"
+ "ispExclaveKitCommandChFidSessionConfigUpdate"
+ "ispExclaveKitCommandChSetGmcResults"
+ "v24@?0{applecamera_fidflowmodule_ekfidflow_channelfidsessionconfigupdate__result_s=C(?={applecamera_exclavesispshared_exclavesisperror_s=Q})}8"
+ "v280@?0{applecamera_fidflowmodule_ekfidflow_channelrunfidflow__result_s=C(?={applecamera_exclavesispshared_exclavesisperror_s=Q}{applecamera_fidflowmodule_fidresult_s={applecamera_fidflowmodule_frameinfo_s=Q{applecamera_fidflowmodule_fidframetype_s=Q}II{applecamera_fidflowmodule_bufferdescriptor_s=QQQ{applecamera_fidflowmodule_bufferformatdescriptor_s=IIII{applecamera_fidflowmodule_elementformat_s=Q}{applecamera_fidflowmodule_channellayout_s=Q}I}}{applecamera_fidflowmodule_bufferdescriptor_s=QQQ{applecamera_fidflowmodule_bufferformatdescriptor_s=IIII{applecamera_fidflowmodule_elementformat_s=Q}{applecamera_fidflowmodule_channellayout_s=Q}I}}{applecamera_fidflowmodule_bufferdescriptor_s=QQQ{applecamera_fidflowmodule_bufferformatdescriptor_s=IIII{applecamera_fidflowmodule_elementformat_s=Q}{applecamera_fidflowmodule_channellayout_s=Q}I}}}{applecamera_fidflowmodule_fidstate_s=BI}{applecamera_fidflowmodule_fidattentioninfo_s={applecamera_fidflowmodule_facerectf_s=ffff}{applecamera_fidflowmodule_headpose_s=fffIf}BB}})}8"
+ "v48@?0{applecamera_attentionawarenessmodule_ekattentionawareness_setgmcresults__result_s=C(?={applecamera_exclavesispshared_exclavesisperror_s=Q}{applecamera_attentionawarenessmodule_eksetgmcresultsoutput_s=dddB})}8"
- "%s:%d - Attention: p %f r %f yaw %f ori %u w %f h %f x %f y %f\n\n"
- "v280@?0{applecamera_fidflowmodule_ekfidflow_channelrunfidflow__result_s=C(?={applecamera_exclavesispshared_exclavesisperror_s=Q}{applecamera_fidflowmodule_fidresult_s={applecamera_fidflowmodule_frameinfo_s=Q{applecamera_fidflowmodule_fidframetype_s=Q}II{applecamera_fidflowmodule_bufferdescriptor_s=QQQ{applecamera_fidflowmodule_bufferformatdescriptor_s=IIII{applecamera_fidflowmodule_elementformat_s=Q}{applecamera_fidflowmodule_channellayout_s=Q}I}}{applecamera_fidflowmodule_bufferdescriptor_s=QQQ{applecamera_fidflowmodule_bufferformatdescriptor_s=IIII{applecamera_fidflowmodule_elementformat_s=Q}{applecamera_fidflowmodule_channellayout_s=Q}I}}{applecamera_fidflowmodule_bufferdescriptor_s=QQQ{applecamera_fidflowmodule_bufferformatdescriptor_s=IIII{applecamera_fidflowmodule_elementformat_s=Q}{applecamera_fidflowmodule_channellayout_s=Q}I}}}{applecamera_fidflowmodule_fidstate_s=BI}{applecamera_fidflowmodule_fidattentioninfo_s={applecamera_fidflowmodule_facerectf_s=ffff}{applecamera_fidflowmodule_headpose_s=fffI}BB}})}8"
```
