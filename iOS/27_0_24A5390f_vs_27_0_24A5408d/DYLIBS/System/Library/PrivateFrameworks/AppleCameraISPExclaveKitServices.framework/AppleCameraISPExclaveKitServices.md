## AppleCameraISPExclaveKitServices

> `/System/Library/PrivateFrameworks/AppleCameraISPExclaveKitServices.framework/AppleCameraISPExclaveKitServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x1185d0` | `0x118bd0` | **`+0x600`** |
| `__TEXT.__text` | `0x30c0c` | `0x30e68` | **`+0x25c`** |
| `__TEXT.__oslogstring` | `0x431e` | `0x434e` | **`+0x30`** |
| `__TEXT.__const` | `0x2ea` | `0x2fa` | **`+0x10`** |

### Other Changes

```diff

-20.57.3.0.0
+20.62.0.0.0

-  Functions: 1175
+  Functions: 1176

-  CStrings:  802
+  CStrings:  803
Functions:
~ __ZN28ISPExclaveKitFileDumpService14_copyoutBufferEP21FileServiceBufferInfo : 832 -> 840
~ __Z31_ispExclaveKitCommandAlgoEnablej : 416 -> 408
~ __Z32ispExclaveKitCommandChAlgoEnableP20sExclaveKitIspCmdHdr : 3832 -> 3888
~ __Z24ispExclaveKitCommandChOnP20sExclaveKitIspCmdHdr : 572 -> 580
~ __Z32ispExclavePrivatePropertiesResetv : 984 -> 1156
~ _OUTLINED_FUNCTION_11 : 16 -> 12
+ _OUTLINED_FUNCTION_12
~ __Z34ispExclaveKitCommandChSendMetadataP20sExclaveKitIspCmdHdr : 1172 -> 1456
~ __Z33ispExclaveKitCommandFrameworkInitP20sExclaveKitIspCmdHdr : 284 -> 300
~ __Z33_configureEkPropertyWriteInternalP20sExclaveKitIspCmdHdrjj : 104 -> 112
~ __Z32ispExclavePrivatePropertiesResetv.cold.2 : 80 -> 84
~ __Z32ispExclavePrivatePropertiesResetv.cold.3 : 80 -> 84
~ __Z32ispExclavePrivatePropertiesResetv.cold.4 : 68 -> 76
~ __Z32ispExclavePrivatePropertiesResetv.cold.5 : 80 -> 84
~ __Z32ispExclavePrivatePropertiesResetv.cold.6 : 80 -> 84
~ __Z32ispExclavePrivatePropertiesResetv.cold.7 : 68 -> 76
~ __Z32ispExclavePrivatePropertiesResetv.cold.8 : 80 -> 84
~ __Z32ispExclavePrivatePropertiesResetv.cold.9 : 80 -> 84
~ __Z32ispExclavePrivatePropertiesResetv.cold.10 : 68 -> 76
CStrings:
+ "%s:%d - ch:%u intrinsics: [%f %f %f %f %f %f %f %f %f]\n"
```
