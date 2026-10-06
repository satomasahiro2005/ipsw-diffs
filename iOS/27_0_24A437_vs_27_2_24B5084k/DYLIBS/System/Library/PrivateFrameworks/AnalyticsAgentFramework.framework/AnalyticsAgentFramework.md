## AnalyticsAgentFramework

> `/System/Library/PrivateFrameworks/AnalyticsAgentFramework.framework/AnalyticsAgentFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e944` | `0x23174` | **`+0x4830`** |
| `__TEXT.__eh_frame` | `0x1f70` | `0x265c` | **`+0x6ec`** |
| `__TEXT.__const` | `0x808` | `0xc00` | **`+0x3f8`** |
| `__AUTH_CONST.__const` | `0xa80` | `0xe40` | **`+0x3c0`** |
| `__DATA.__bss` | `—` | `0x380` | **`+0x380`** |
| `__TEXT.__swift5_typeref` | `0x68c` | `0x8c0` | **`+0x234`** |
| `__TEXT.__unwind_info` | `0x880` | `0xa60` | **`+0x1e0`** |
| `__TEXT.__gcc_except_tab` | `0xc60` | `0xe28` | **`+0x1c8`** |
| `__TEXT.__oslogstring` | `0xffb` | `0x117b` | **`+0x180`** |
| `__DATA.__data` | `0x238` | `0x360` | **`+0x128`** |
| `__TEXT.__constg_swiftt` | `0x3cc` | `0x4c4` | **`+0xf8`** |
| `__TEXT.__swift5_fieldmd` | `0x314` | `0x3e0` | **`+0xcc`** |
| `__AUTH_CONST.__objc_const` | `0x1890` | `0x1918` | **`+0x88`** |
| `__TEXT.__swift5_capture` | `0x194` | `0x21c` | **`+0x88`** |
| `__TEXT.__swift5_reflstr` | `0x295` | `0x315` | **`+0x80`** |
| `__TEXT.__swift5_assocty` | `0x60` | `0xd8` | **`+0x78`** |
| `__AUTH_CONST.__auth_got` | `0x7c8` | `0x820` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0xb58` | `0xba0` | **`+0x48`** |
| `__TEXT.__cstring` | `0x58c` | `0x5cc` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x88` | `0xc0` | **`+0x38`** |
| `__TEXT.__swift_as_ret` | `0x64` | `0x8c` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x14` | `0x38` | **`+0x24`** |
| `__AUTH.__data` | `0x120` | `0x140` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x34` | `0x50` | **`+0x1c`** |
| `__TEXT.__swift5_types` | `0x38` | `0x4c` | **`+0x14`** |
| `__TEXT.__swift5_protos` | `0x18` | `0x1c` | **`+0x4`** |

### Other Changes

```diff

-569.0.5.0.0
+577.40.5.0.0

+  - /System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth

-  Functions: 372
-  Symbols:   399
-  CStrings:  104
+  Functions: 490
+  Symbols:   456
+  CStrings:  111
Symbols:
+ GCC_except_table23
+ GCC_except_table25
+ GCC_except_table34
+ GCC_except_table35
+ GCC_except_table36
+ GCC_except_table37
+ GCC_except_table39
+ GCC_except_table40
+ GCC_except_table41
+ GCC_except_table43
+ GCC_except_table44
+ GCC_except_table47
+ GCC_except_table57
+ GCC_except_table58
+ GCC_except_table77
+ _OBJC_CLASS_$_CBController
+ _OBJC_CLASS_$_CBDevice
+ _OBJC_CLASS_$_NSLock
+ __IVARS__TtCV23AnalyticsAgentFrameworkP33_1ED0477C7E5B65EA93A9DD4CF3EE254E20CBControllerProvider10ResumeOnce
+ ___swift_closure_destructorTm
+ ___swift_memcpy1_1
+ ___unnamed_2
+ _associated conformance 23AnalyticsAgentFramework19BluetoothPowerStateOSHAASQ
+ _associated conformance 23AnalyticsAgentFramework28BluetoothConnectedTransportsVs10SetAlgebraAASQ
+ _associated conformance 23AnalyticsAgentFramework28BluetoothConnectedTransportsVs10SetAlgebraAAs25ExpressibleByArrayLiteral
+ _associated conformance 23AnalyticsAgentFramework28BluetoothConnectedTransportsVs9OptionSetAASY
+ _associated conformance 23AnalyticsAgentFramework28BluetoothConnectedTransportsVs9OptionSetAAs0H7Algebra
+ _swift_retain_x28
+ _symbolic $s23AnalyticsAgentFramework28BluetoothControllerProvidingP
+ _symbolic $sSY
+ _symbolic $ss10SetAlgebraP
+ _symbolic $ss25ExpressibleByArrayLiteralP
+ _symbolic $ss9OptionSetP
+ _symbolic ScCy_____5power_Sb8scanningtSg_____G 23AnalyticsAgentFramework19BluetoothPowerStateO s5NeverO
+ _symbolic ScCy_____5power_Sb8scanningtSg_____GSg 23AnalyticsAgentFramework19BluetoothPowerStateO s5NeverO
+ _symbolic ScCy_____Sg_____G 23AnalyticsAgentFramework28BluetoothConnectedTransportsV s5NeverO
+ _symbolic ScCy_____Sg_____GSg 23AnalyticsAgentFramework28BluetoothConnectedTransportsV s5NeverO
+ _symbolic ScCyxSg_____GSg s5NeverO
+ _symbolic ScTyyt_____GSg s5NeverO
+ _symbolic So6NSLockC
+ _symbolic _____ 23AnalyticsAgentFramework19BluetoothPowerStateO
+ _symbolic _____ 23AnalyticsAgentFramework20BluetoothStatusQueryV
+ _symbolic _____ 23AnalyticsAgentFramework20CBControllerProvider33_1ED0477C7E5B65EA93A9DD4CF3EE254ELLV
+ _symbolic _____ 23AnalyticsAgentFramework20CBControllerProvider33_1ED0477C7E5B65EA93A9DD4CF3EE254ELLV10ResumeOnceC
+ _symbolic _____ 23AnalyticsAgentFramework28BluetoothConnectedTransportsV
+ _symbolic _____ 24CoreAnalyticsSwiftBridge0aB8ConstantO15BluetoothStatusO
+ _symbolic _____5power_Sb8scanningtSg 23AnalyticsAgentFramework19BluetoothPowerStateO
+ _symbolic _____5power_Sb8scanningtSgIeghn_ 23AnalyticsAgentFramework19BluetoothPowerStateO
+ _symbolic _____5power_Sb8scanningtSgIeghy_ 23AnalyticsAgentFramework19BluetoothPowerStateO
+ _symbolic _____Sg 23AnalyticsAgentFramework28BluetoothConnectedTransportsV
+ _symbolic _____Sg 24CoreAnalyticsSwiftBridge0aB8ConstantO15BluetoothStatusO
+ _symbolic _____SgIeghn_ 23AnalyticsAgentFramework28BluetoothConnectedTransportsV
+ _symbolic _____SgIeghy_ 23AnalyticsAgentFramework28BluetoothConnectedTransportsV
+ _symbolic ______p 23AnalyticsAgentFramework28BluetoothControllerProvidingP
+ _symbolic _____y______5power_Sb8scanningtG 23AnalyticsAgentFramework20CBControllerProvider33_1ED0477C7E5B65EA93A9DD4CF3EE254ELLV10ResumeOnceC AA19BluetoothPowerStateO
+ _symbolic _____y______G 23AnalyticsAgentFramework20CBControllerProvider33_1ED0477C7E5B65EA93A9DD4CF3EE254ELLV10ResumeOnceC AA28BluetoothConnectedTransportsV
+ _type_layout_string 23AnalyticsAgentFramework20BluetoothStatusQueryV
+ _type_layout_string 23AnalyticsAgentFramework28BluetoothConnectedTransportsV
- GCC_except_table18
CStrings:
+ "[BluetoothStatusQuery] Bluetooth controller unavailable on this platform. Returning unknown."
+ "[BluetoothStatusQuery] Controller not powered on/available. Returning unknown."
+ "[BluetoothStatusQuery] No controller info. Returning unknown."
+ "[BluetoothStatusQuery] getControllerInfo error: %s"
+ "[BluetoothStatusQuery] getDevices error: %s"
+ "[BluetoothStatusQuery] result()"
+ "com.apple.coreanalytics.analyticsagent.bluetoothstatus"
```
