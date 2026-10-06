## TemplateKit

> `/System/Library/PrivateFrameworks/TemplateKit.framework/TemplateKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43490` | `0x4364c` | **`+0x1bc`** |
| `__TEXT.__oslogstring` | `0x15` | `0x95` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x5d8` | `0x638` | **`+0x60`** |
| `__TEXT.__dlopen_cstrs` | `—` | `0x5e` | **`+0x5e`** |
| `__TEXT.__cstring` | `0x833` | `0x863` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1138` | `0x1168` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x8f0` | `0x910` | **`+0x20`** |
| `__DATA.__bss` | `0x518` | `0x538` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x880` | `0x898` | **`+0x18`** |
| `__TEXT.__const` | `0x65a` | `0x66a` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x164` | `0x174` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x578` | `0x580` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a40` | `0x2a48` | **`+0x8`** |

### Other Changes

```diff

-668.101.0.0.0
+672.1.0.0.0

+  - /System/Library/PrivateFrameworks/SoftLinking.framework/SoftLinking

-  Functions: 1866
-  Symbols:   3078
-  CStrings:  102
+  Functions: 1872
+  Symbols:   3092
+  CStrings:  107
Symbols:
+ GCC_except_table7
+ _GenerativeModelsLibraryCore.frameworkLibrary
+ _TLKCampoUIEnabled.onceToken
+ ___GenerativeModelsLibraryCore_block_invoke
+ ___TLKCampoUIEnabled_block_invoke
+ ___block_descriptor_40_e5_v8?0l
+ ___block_descriptor_40_e8_32r_e5_v8?0lr32l8
+ ___getGMAvailabilityWrapperClass_block_invoke
+ __os_log_default
+ __os_log_error_impl
+ __sl_dlopen
+ _abort_report_np
+ _audit_stringGenerativeModels
+ _getGMAvailabilityWrapperClass.softClass
+ _objc_getClass
- _AFIsLinwoodEnabledAndAvailable
CStrings:
+ "%s"
+ "GMAvailabilityWrapper"
+ "TLKCampoUIEnabled: GenerativeModels framework or GMAvailabilityWrapper class not available; treating Enhanced Siri as not shown"
+ "Unable to find class %s"
+ "softlink:o:path:/System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels"
```
