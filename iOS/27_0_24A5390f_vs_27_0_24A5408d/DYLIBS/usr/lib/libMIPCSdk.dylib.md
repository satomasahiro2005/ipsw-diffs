## libMIPCSdk.dylib

> `/usr/lib/libMIPCSdk.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37b7e4` | `0x37c488` | **`+0xca4`** |
| `__AUTH_CONST.__const` | `0x2d100` | `0x2d238` | **`+0x138`** |
| `__TEXT.__gcc_except_tab` | `0x1e3b4` | `0x1e450` | **`+0x9c`** |
| `__TEXT.__const` | `0x14970` | `0x14a00` | **`+0x90`** |
| `__TEXT.__cstring` | `0x145a7` | `0x145f5` | **`+0x4e`** |
| `__TEXT.__unwind_info` | `0xc4a8` | `0xc4f0` | **`+0x48`** |

### Other Changes

```diff

-176.0.0.0.0
+177.0.0.0.0

-  Functions: 11154
-  Symbols:   18975
-  CStrings:  2021
+  Functions: 11172
+  Symbols:   19004
+  CStrings:  2023
Symbols:
+ __ZN4mipc12ConfirmationILt63281EED0Ev
+ __ZN4mipc12ConfirmationILt63281EED1Ev
+ __ZN4mipc9dale_skpr27Service_Priority_Update_Cnf11deserializeEv
+ __ZN4mipc9dale_skpr27Service_Priority_Update_CnfC1ENS_5ErrorENS_5SimIdE
+ __ZN4mipc9dale_skpr27Service_Priority_Update_CnfC1EPKhm
+ __ZN4mipc9dale_skpr27Service_Priority_Update_CnfC2ENS_5ErrorENS_5SimIdE
+ __ZN4mipc9dale_skpr27Service_Priority_Update_CnfC2EPKhm
+ __ZN4mipc9dale_skpr27Service_Priority_Update_CnfD0Ev
+ __ZN4mipc9dale_skpr27Service_Priority_Update_CnfD1Ev
+ __ZN4mipc9dale_skpr27Service_Priority_Update_CnfD2Ev
+ __ZN4mipc9dale_skpr27Service_Priority_Update_ReqC1ENS_5SimIdE
+ __ZN4mipc9dale_skpr27Service_Priority_Update_ReqC2ENS_5SimIdE
+ __ZN4mipc9dale_skpr27Service_Priority_Update_ReqD0Ev
+ __ZN4mipc9dale_skpr27Service_Priority_Update_ReqD1Ev
+ __ZN4mipc9dale_skpr27Service_Priority_Update_ReqD2Ev
+ __ZNK4mipc9dale_skpr27Service_Priority_Update_Cnf7getSizeEv
+ __ZNK4mipc9dale_skpr27Service_Priority_Update_Req7getSizeEv
+ __ZNK4mipc9dale_skpr27Service_Priority_Update_Req9serializeEv
+ __ZTIN4mipc12ConfirmationILt63281EEE
+ __ZTIN4mipc7RequestILt63281EEE
+ __ZTIN4mipc9dale_skpr27Service_Priority_Update_CnfE
+ __ZTIN4mipc9dale_skpr27Service_Priority_Update_ReqE
+ __ZTSN4mipc12ConfirmationILt63281EEE
+ __ZTSN4mipc7RequestILt63281EEE
+ __ZTSN4mipc9dale_skpr27Service_Priority_Update_CnfE
+ __ZTSN4mipc9dale_skpr27Service_Priority_Update_ReqE
+ __ZTVN4mipc12ConfirmationILt63281EEE
+ __ZTVN4mipc9dale_skpr27Service_Priority_Update_CnfE
+ __ZTVN4mipc9dale_skpr27Service_Priority_Update_ReqE
CStrings:
+ "dale_skpr::Service_Priority_Update_Cnf"
+ "dale_skpr::Service_Priority_Update_Req"
```
