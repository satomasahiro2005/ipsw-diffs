## libNFC_Comet.dylib

> `/usr/lib/libNFC_Comet.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc16ac` | `0xc8930` | **`+0x7284`** |
| `__AUTH_CONST.__const` | `0x460` | `0x2d00` | **`+0x28a0`** |
| `__AUTH.__data` | `0x3658` | `0x1fd8` | **`-0x1680`** |
| `__DATA_DIRTY.__data` | `0x1320` | `0x1e` | **`-0x1302`** |
| `__TEXT.__unwind_info` | `0x1230` | `0x12c0` | **`+0x90`** |
| `__TEXT.__cstring` | `0x3c358` | `0x3c39c` | **`+0x44`** |
| `__DATA.__common` | `0x38` | `0x48` | **`+0x10`** |
| `__TEXT.__const` | `0xa60` | `0xa70` | **`+0x10`** |

### Other Changes

```diff

-370.33.1.0.0
+370.37.0.0.0

-  Functions: 1859
+  Functions: 1867

-  CStrings:  5846
+  CStrings:  5850
CStrings:
+ "MW Version NFC5.1_R5.9"
+ "hDriverHandle.hHandle"
+ "phLibNfc_ConnectExtensionFelica_Cb: Lower layer has returned invalid LibNfc context"
+ "phLibNfc_PrintLibNfcCritInfo: Invalid Controller Type "
+ "phLibNfc_ReActivateComplete: Lower layer has returned Null LibNfc context"
+ "phLibNfc_RemoteDev_Connect_Cb: Lower layer has returned Invalid LibNfc context"
+ "phLibNfc_SetEepromParamsProc"
+ "phLibNfc_ShutdownCb: Lower layer Reset Failed"
+ "phLibNfc_ShutdownCb: Lower layer has passed Null Libnfc context"
+ "phLibNfc_ShutdownCb: Lower layer may have some issue"
+ "phLibNfc_SwioPadNtfHandler: Temperature NTF with extra bytes received"
+ "phNciNfc_WaitForDeactvNtf"
+ "phUtilNfc_DeInitializeStackHandle"
+ "phUtilNfc_InitializeStackHandle"
- "Lower layer Reset Failed"
- "Lower layer has passed Null Libnfc context"
- "Lower layer has returned Invalid LibNfc context"
- "Lower layer has returned Null LibNfc context"
- "Lower layer has returned invalid LibNfc context"
- "Lower layer may have some issue"
- "MW Version NFC5.1_R5.7"
- "hDriverHandle"
- "phNciNfc_getSequenceLength"
- "phUtilNfc_GetLibNfcContextFromCtrlType"
```
