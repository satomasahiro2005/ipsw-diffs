## AppleIDSetupUI

> `/System/Library/PrivateFrameworks/AppleIDSetupUI.framework/AppleIDSetupUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x186590` | `0x1876a0` | **`+0x1110`** |
| `__AUTH_CONST.__const` | `0xa7f0` | `0xa920` | **`+0x130`** |
| `__TEXT.__const` | `0xd6f4` | `0xd7f4` | **`+0x100`** |
| `__TEXT.__swift5_typeref` | `0xee60` | `0xef10` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x4e29` | `0x4e89` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x3e52` | `0x3eb2` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x3530` | `0x357c` | **`+0x4c`** |
| `__TEXT.__swift5_capture` | `0x2c98` | `0x2cd8` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d18` | `0x1d50` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x118e0` | `0x11908` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x14d0` | `0x14f0` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0xb68d` | `0xb6ad` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x5688` | `0x56a4` | **`+0x1c`** |
| `__TEXT.__swift5_builtin` | `0x1b8` | `0x1cc` | **`+0x14`** |
| `__AUTH.__data` | `0x3b10` | `0x3b20` | **`+0x10`** |
| `__DATA.__data` | `0x5728` | `0x5718` | **`-0x10`** |
| `__TEXT.__swift5_mpenum` | `0x10` | `0x20` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2510` | `0x2508` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x56a8` | `0x56a0` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x3ac` | `0x3b0` | **`+0x4`** |

### Other Changes

```diff

-124.0.0.0.0
+125.0.0.0.0

-  Functions: 7224
-  Symbols:   3174
-  CStrings:  1278
+  Functions: 7233
+  Symbols:   3188
+  CStrings:  1281
Symbols:
+ _OBJC_CLASS_$_AAFAnalyticsEvent
+ _OBJC_CLASS_$_AAFAnalyticsReporter
+ _OBJC_CLASS_$_AAFAnalyticsTransportRTC
+ __IVARS__TtC14AppleIDSetupUI28SignInOptionsAnalyticsSender
+ ___swift_closure_destructor.101Tm
+ ___swift_closure_destructor.140Tm
+ ___swift_closure_destructor.43Tm
+ _get_enum_tag_for_layout_string 14AppleIDSetupUI18SignInOptionsEventO
+ _kAAFFlowIdString
+ _symbolic SS6flowID_SS6methodSb17proxAuthAvailablet
+ _symbolic SS6flowID_Sb17proxAuthAvailableSi11optionCountt
+ _symbolic SS6flowID_t
+ _symbolic So20AAFAnalyticsReporterC
+ _symbolic _____ 14AppleIDSetupUI18SignInOptionsEventO
+ _symbolic _____AAIegnn_ 12AppleIDSetup10SetupModelV5StateO
+ _symbolic _____AASo9ACAccountCSgytIegnnnr_ 12AppleIDSetup10SetupModelV5StateO
+ _symbolic _____ySo9ACAccountCG 12AppleIDSetup12_objcCodableV
+ _symbolic _____ySo9ACAccountCGSg 12AppleIDSetup12_objcCodableV
+ _symbolic y______AASo9ACAccountCSgtcSg 12AppleIDSetup10SetupModelV5StateO
+ _type_layout_string 14AppleIDSetupUI18SignInOptionsEventO
- ___swift_closure_destructor.123Tm
- ___swift_closure_destructor.84Tm
- _symbolic SS_So8NSObjectCt
- _symbolic _____ySSSo8NSObjectCG s18_DictionaryStorageC
- _symbolic _____ySS_So8NSObjectCtG s23_ContiguousArrayStorageC
- _symbolic y______AAtcSg 12AppleIDSetup10SetupModelV5StateO
CStrings:
+ "AISChildSetupPresenter: Removing family picker view controller by restoration identifier"
+ "AISFamilyPickerRemoteUIPage"
+ "com.apple.aaa.dnu"
+ "com.apple.appleidsetup"
+ "isProxAuthAvailable"
- "AISChildSetupPresenter: Removing previous view controller: %ld"
- "proxAuthAvailable"
```
