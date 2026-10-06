## libMIPCSdk.dylib

> `/usr/lib/libMIPCSdk.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x378c48` | `0x37b7e4` | **`+0x2b9c`** |
| `__AUTH_CONST.__const` | `0x2ce90` | `0x2d100` | **`+0x270`** |
| `__TEXT.__gcc_except_tab` | `0x1e240` | `0x1e3b4` | **`+0x174`** |
| `__TEXT.__const` | `0x14840` | `0x14970` | **`+0x130`** |
| `__TEXT.__unwind_info` | `0xc400` | `0xc4a8` | **`+0xa8`** |
| `__TEXT.__cstring` | `0x14513` | `0x145a7` | **`+0x94`** |

### Other Changes

```diff

-175.0.0.0.0
+176.0.0.0.0

-  Functions: 11117
-  Symbols:   18916
-  CStrings:  2017
+  Functions: 11154
+  Symbols:   18975
+  CStrings:  2021
Symbols:
+ __ZN4mipc12ConfirmationILt63488EED0Ev
+ __ZN4mipc12ConfirmationILt63488EED1Ev
+ __ZN4mipc12ConfirmationILt63489EED0Ev
+ __ZN4mipc12ConfirmationILt63489EED1Ev
+ __ZN4mipc12dale_skpr_v220Test_Defer_Afmic_Cnf11deserializeEv
+ __ZN4mipc12dale_skpr_v220Test_Defer_Afmic_CnfC1ENS_5ErrorENS_5SimIdE
+ __ZN4mipc12dale_skpr_v220Test_Defer_Afmic_CnfC1EPKhm
+ __ZN4mipc12dale_skpr_v220Test_Defer_Afmic_CnfC2ENS_5ErrorENS_5SimIdE
+ __ZN4mipc12dale_skpr_v220Test_Defer_Afmic_CnfC2EPKhm
+ __ZN4mipc12dale_skpr_v220Test_Defer_Afmic_CnfD0Ev
+ __ZN4mipc12dale_skpr_v220Test_Defer_Afmic_CnfD1Ev
+ __ZN4mipc12dale_skpr_v220Test_Defer_Afmic_CnfD2Ev
+ __ZN4mipc12dale_skpr_v220Test_Defer_Afmic_ReqC1ENS_5SimIdE
+ __ZN4mipc12dale_skpr_v220Test_Defer_Afmic_ReqC2ENS_5SimIdE
+ __ZN4mipc12dale_skpr_v220Test_Defer_Afmic_ReqD0Ev
+ __ZN4mipc12dale_skpr_v220Test_Defer_Afmic_ReqD1Ev
+ __ZN4mipc12dale_skpr_v220Test_Defer_Afmic_ReqD2Ev
+ __ZN4mipc12dale_skpr_v224Test_Override_Config_Cnf11deserializeEv
+ __ZN4mipc12dale_skpr_v224Test_Override_Config_CnfC1ENS_5ErrorENS_5SimIdE
+ __ZN4mipc12dale_skpr_v224Test_Override_Config_CnfC1EPKhm
+ __ZN4mipc12dale_skpr_v224Test_Override_Config_CnfC2ENS_5ErrorENS_5SimIdE
+ __ZN4mipc12dale_skpr_v224Test_Override_Config_CnfC2EPKhm
+ __ZN4mipc12dale_skpr_v224Test_Override_Config_CnfD0Ev
+ __ZN4mipc12dale_skpr_v224Test_Override_Config_CnfD1Ev
+ __ZN4mipc12dale_skpr_v224Test_Override_Config_CnfD2Ev
+ __ZN4mipc12dale_skpr_v224Test_Override_Config_ReqC1ENS_5SimIdE
+ __ZN4mipc12dale_skpr_v224Test_Override_Config_ReqC2ENS_5SimIdE
+ __ZN4mipc12dale_skpr_v224Test_Override_Config_ReqD0Ev
+ __ZN4mipc12dale_skpr_v224Test_Override_Config_ReqD1Ev
+ __ZN4mipc12dale_skpr_v224Test_Override_Config_ReqD2Ev
+ __ZNK4mipc12dale_skpr_v220Test_Defer_Afmic_Cnf7getSizeEv
+ __ZNK4mipc12dale_skpr_v220Test_Defer_Afmic_Req7getSizeEv
+ __ZNK4mipc12dale_skpr_v220Test_Defer_Afmic_Req9serializeEv
+ __ZNK4mipc12dale_skpr_v224Test_Override_Config_Cnf7getSizeEv
+ __ZNK4mipc12dale_skpr_v224Test_Override_Config_Req7getSizeEv
+ __ZNK4mipc12dale_skpr_v224Test_Override_Config_Req9serializeEv
+ __ZNK4mipc9tlv_arrayIjLm16ELb1EE6getBufEv
+ __ZTIN4mipc12ConfirmationILt63488EEE
+ __ZTIN4mipc12ConfirmationILt63489EEE
+ __ZTIN4mipc12dale_skpr_v220Test_Defer_Afmic_CnfE
+ __ZTIN4mipc12dale_skpr_v220Test_Defer_Afmic_ReqE
+ __ZTIN4mipc12dale_skpr_v224Test_Override_Config_CnfE
+ __ZTIN4mipc12dale_skpr_v224Test_Override_Config_ReqE
+ __ZTIN4mipc7RequestILt63488EEE
+ __ZTIN4mipc7RequestILt63489EEE
+ __ZTSN4mipc12ConfirmationILt63488EEE
+ __ZTSN4mipc12ConfirmationILt63489EEE
+ __ZTSN4mipc12dale_skpr_v220Test_Defer_Afmic_CnfE
+ __ZTSN4mipc12dale_skpr_v220Test_Defer_Afmic_ReqE
+ __ZTSN4mipc12dale_skpr_v224Test_Override_Config_CnfE
+ __ZTSN4mipc12dale_skpr_v224Test_Override_Config_ReqE
+ __ZTSN4mipc7RequestILt63488EEE
+ __ZTSN4mipc7RequestILt63489EEE
+ __ZTVN4mipc12ConfirmationILt63488EEE
+ __ZTVN4mipc12ConfirmationILt63489EEE
+ __ZTVN4mipc12dale_skpr_v220Test_Defer_Afmic_CnfE
+ __ZTVN4mipc12dale_skpr_v220Test_Defer_Afmic_ReqE
+ __ZTVN4mipc12dale_skpr_v224Test_Override_Config_CnfE
+ __ZTVN4mipc12dale_skpr_v224Test_Override_Config_ReqE
CStrings:
+ "dale_skpr_v2::Test_Defer_Afmic_Cnf"
+ "dale_skpr_v2::Test_Defer_Afmic_Req"
+ "dale_skpr_v2::Test_Override_Config_Cnf"
+ "dale_skpr_v2::Test_Override_Config_Req"
```
