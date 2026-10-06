## AppleCameraISPExclaveKitServices

> `/System/Library/PrivateFrameworks/AppleCameraISPExclaveKitServices.framework/AppleCameraISPExclaveKitServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30f50` | `0x32b94` | **`+0x1c44`** |
| `__TEXT.__cstring` | `0x8896` | `0x8d16` | **`+0x480`** |
| `__DATA_CONST.__const` | `0x1128` | `0x1210` | **`+0xe8`** |
| `__TEXT.__oslogstring` | `0x434e` | `0x442e` | **`+0xe0`** |
| `__TEXT.__gcc_except_tab` | `0x8c8` | `0x928` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x9a8` | `0x9d8` | **`+0x30`** |

### Other Changes

```diff

-20.77.1.0.0
+20.104.4.0.0

-  Functions: 1176
-  Symbols:   772
-  CStrings:  808
+  Functions: 1197
+  Symbols:   782
+  CStrings:  824
Symbols:
+ __Z34ispExclaveKitCommandChInitScanModeP20sExclaveKitIspCmdHdr
+ __Z37ispExclaveKitCommandChGetGmcAnalyticsP20sExclaveKitIspCmdHdr
+ ____Z34ispExclaveKitCommandChInitScanModeP20sExclaveKitIspCmdHdr_block_invoke
+ ____Z37ispExclaveKitCommandChGetGmcAnalyticsP20sExclaveKitIspCmdHdr_block_invoke
+ ____ZL16decodeAnstResultI26sExclaveKitIspCmdChRunAnstEbP61applecamera_anstmodule_ispexclavecorechrunkitanstresultv150_sPT__block_invoke
+ ____ZL16decodeAnstResultI38sExclaveKitIspCmdChRunAnst__DeprecatedEbP61applecamera_anstmodule_ispexclavecorechrunkitanstresultv150_sPT__block_invoke
+ ____ZL30_ispExclaveKitCommandChRunAnstI26sExclaveKitIspCmdChRunAnstE27eIspExclaveKitCmdHandlerErrPT__block_invoke
+ ____ZL30_ispExclaveKitCommandChRunAnstI38sExclaveKitIspCmdChRunAnst__DeprecatedE27eIspExclaveKitCmdHandlerErrPT__block_invoke
+ _applecamera_attentionawarenessmodule_ekattentionawareness_getgmcanalytics
+ _applecamera_attentionawarenessmodule_ekattentionawareness_getgmcanalytics__result_get_success
+ _applecamera_attentionawarenessmodule_ekattentionawareness_initscanmode
+ _applecamera_attentionawarenessmodule_ekattentionawareness_initscanmode__result_get_success
+ _applecamera_attentionawarenessmodule_ekgmcanalyticsoutput__decode
- GCC_except_table13
- ____Z29ispExclaveKitCommandChRunAnstP20sExclaveKitIspCmdHdr_block_invoke
- ____ZL16decodeAnstResultP61applecamera_anstmodule_ispexclavecorechrunkitanstresultv150_sP26sExclaveKitIspCmdChRunAnst_block_invoke
CStrings:
+ "%s:%d - [IR-EK] PCEMgr Finished (gmcRunResult=%u)\n"
+ "%s:%d - [IR-EK] getGmcAnalytics\n"
+ "%s:%d - [IR-EK] getGmcAnalytics Finished\n"
+ "%s:%d - [IR-EK] initScanMode\n"
+ "%s:%d - [IR-EK] initScanMode Finished\n"
+ "%s:%d - get GMC analytics\n"
+ "%s:%d - init scan mode\n"
+ "ISP_EXCLAVEKIT_CMD_CH_GET_GMC_ANALYTICS"
+ "ISP_EXCLAVEKIT_CMD_CH_INIT_SCAN_MODE"
+ "TB_FATAL: invalid result returned from getGmcAnalytics"
+ "TB_FATAL: invalid result returned from getGmcAnalytics (%s:%d)\n"
+ "TB_FATAL: invalid result returned from initScanMode"
+ "TB_FATAL: invalid result returned from initScanMode (%s:%d)\n"
+ "_ispExclaveKitCommandChRunAnst"
+ "ispExclaveKitCommandChGetGmcAnalytics"
+ "ispExclaveKitCommandChInitScanMode"
+ "v248@?0{applecamera_attentionawarenessmodule_ekattentionawareness_getgmcanalytics__result_s=C(?={applecamera_exclavesispshared_exclavesisperror_s=Q}{applecamera_attentionawarenessmodule_ekgmcanalyticsoutput_s=BQ{applecamera_attentionawarenessmodule_gmccontrollerstatus_s=Q}QdQdddddBddddQBddddBdddddd})}8"
+ "v24@?0Q8r^{applecamera_anstmodule_anstfacev1502_s=II{applecamera_anstmodule_anstcategory2_s=Q}{applecamera_anstmodule_anstrect2_s=ffff}{applecamera_anstmodule_anstfaceposedegree_s=Q(?={?=I})}{applecamera_anstmodule_anstfaceposedegree_s=Q(?={?=I})}{applecamera_anstmodule_anstfaceposedegree_s=Q(?={?=I})}{applecamera_anstmodule_anstfaceposedegree_s=Q(?={?=I})}{applecamera_anstmodule_anstfaceposedegree_s=Q(?={?=I})}BfB{applecamera_anstmodule_anstconfidence_s=Q}{applecamera_anstmodule_anstconfidence_s=Q}{applecamera_anstmodule_anstconfidence_s=Q}{applecamera_anstmodule_anstconfidence_s=Q}{applecamera_anstmodule_anstconfidence_s=Q}{applecamera_anstmodule_anstconfidence_s=Q}{applecamera_anstmodule_anstconfidence_s=Q}}16"
+ "v24@?0{applecamera_attentionawarenessmodule_ekattentionawareness_channelrunpce__result_s=C(?={applecamera_exclavesispshared_exclavesisperror_s=Q}I)}8"
+ "v24@?0{applecamera_attentionawarenessmodule_ekattentionawareness_initscanmode__result_s=C(?={applecamera_exclavesispshared_exclavesisperror_s=Q}{applecamera_attentionawarenessmodule_ekinitscanmodeoutput_s=B})}8"
- "%s:%d - [IR-EK] PCEMgr Finished\n"
- "ispExclaveKitCommandChRunAnst"
- "v24@?0Q8r^{applecamera_anstmodule_anstfacev1502_s=II{applecamera_anstmodule_anstcategory2_s=Q}{applecamera_anstmodule_anstrect2_s=ffff}{applecamera_anstmodule_anstfaceposedegree_s=Q(?={?=I})}{applecamera_anstmodule_anstfaceposedegree_s=Q(?={?=I})}{applecamera_anstmodule_anstfaceposedegree_s=Q(?={?=I})}{applecamera_anstmodule_anstfaceposedegree_s=Q(?={?=I})}{applecamera_anstmodule_anstfaceposedegree_s=Q(?={?=I})}BfB{applecamera_anstmodule_anstconfidence_s=Q}}16"
- "v24@?0{applecamera_attentionawarenessmodule_ekattentionawareness_channelrunpce__result_s=C(?={applecamera_exclavesispshared_exclavesisperror_s=Q}B)}8"
```
