## ToolKit

> `/System/Library/PrivateFrameworks/ToolKit.framework/ToolKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x501310` | `0x5079ec` | **`+0x66dc`** |
| `__AUTH_CONST.__const` | `0x2d770` | `0x2dd10` | **`+0x5a0`** |
| `__DATA_DIRTY.__bss` | `0x47380` | `0x47900` | **`+0x580`** |
| `__TEXT.__unwind_info` | `0x1b780` | `0x1bce0` | **`+0x560`** |
| `__DATA.__bss` | `0x941d0` | `0x93dd0` | **`-0x400`** |
| `__DATA_DIRTY.__data` | `0x12c78` | `0x12fe8` | **`+0x370`** |
| `__TEXT.__eh_frame` | `0x34a58` | `0x34d90` | **`+0x338`** |
| `__TEXT.__const` | `0x7b7d8` | `0x7b9a8` | **`+0x1d0`** |
| `__TEXT.__swift5_capture` | `0x3e48` | `0x3fd4` | **`+0x18c`** |
| `__DATA.__data` | `0xfe00` | `0xfc90` | **`-0x170`** |
| `__AUTH.__data` | `0x2c50` | `0x2b00` | **`-0x150`** |
| `__TEXT.__swift5_reflstr` | `0x9847` | `0x9947` | **`+0x100`** |
| `__TEXT.__cstring` | `0x9774` | `0x9834` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x14964` | `0x14a20` | **`+0xbc`** |
| `__TEXT.__swift5_fieldmd` | `0x14180` | `0x14230` | **`+0xb0`** |
| `__AUTH_CONST.__objc_const` | `0x1df8` | `0x1e78` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0xf0f0` | `0xf168` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0x4e3c` | `0x4e8c` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x2810` | `0x2838` | **`+0x28`** |
| `__DATA.__common` | `0x958` | `0x978` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0xc8c` | `0xca8` | **`+0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0xda0` | `0xdb8` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x624` | `0x634` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x7d4` | `0x7e4` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x6f10` | `0x6f1c` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x340` | `0x348` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x18a4` | `0x18ac` | **`+0x8`** |

### Other Changes

```diff

-5110.0.8.0.0
+5111.0.2.0.0

-  Functions: 45907
-  Symbols:   10365
-  CStrings:  1783
+  Functions: 46042
+  Symbols:   10383
+  CStrings:  1790
Symbols:
+ ___swift_memcpy266_8
+ _associated conformance 7ToolKit18RuntimeDeviceStateO36UseModelWebSearchAvailableCodingKeys33_544A1612C069EACB692538B73095D1A6LLOs0K3KeyAAs23CustomStringConvertible
+ _associated conformance 7ToolKit18RuntimeDeviceStateO36UseModelWebSearchAvailableCodingKeys33_544A1612C069EACB692538B73095D1A6LLOs0K3KeyAAs28CustomDebugStringConvertible
+ _dispatch_sync
+ _flat unique So8NSObject_p
+ _symbolic Ig_
+ _symbolic Say______pG So8NSObjectP
+ _symbolic _____ 7ToolKit0A26DatabaseReopenAvailabilityV
+ _symbolic _____ 7ToolKit18RuntimeDeviceStateO36UseModelWebSearchAvailableCodingKeys33_544A1612C069EACB692538B73095D1A6LLO
+ _symbolic _____SgXw 7ToolKit0A8DatabaseC
+ _symbolic _____SgXw 7ToolKit30DatabaseTypeDefinitionProviderC
+ _symbolic _____SgXw 7ToolKit35DatabaseContainerDefinitionProviderC
+ _symbolic _____SgXwz_Xx 7ToolKit0A8DatabaseC
+ _symbolic _____SgXwz_Xx 7ToolKit30DatabaseTypeDefinitionProviderC
+ _symbolic _____SgXwz_Xx 7ToolKit35DatabaseContainerDefinitionProviderC
+ _symbolic _____y_____G s22KeyedDecodingContainerV 7ToolKit18RuntimeDeviceStateO36UseModelWebSearchAvailableCodingKeys33_544A1612C069EACB692538B73095D1A6LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7ToolKit18RuntimeDeviceStateO36UseModelWebSearchAvailableCodingKeys33_544A1612C069EACB692538B73095D1A6LLO
+ _symbolic ytSg
+ _symbolic ytSgIeAgHr_
- ___swift_memcpy258_8
CStrings:
+ "DeviceStateUseModelWebSearchAvailable"
+ "ToolDatabase auto-reopen failed: %@"
+ "ToolDatabase reopened onto %s"
+ "WFToolDatabaseAutoReopenEnabled"
+ "com.apple.siri.shortcuts"
+ "com.apple.toolkit.tooldatabase.reopen"
+ "useModelWebSearchAvailable"
```
