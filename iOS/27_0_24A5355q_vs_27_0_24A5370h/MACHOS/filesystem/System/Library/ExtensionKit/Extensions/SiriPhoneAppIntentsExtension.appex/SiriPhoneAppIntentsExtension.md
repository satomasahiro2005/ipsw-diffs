## SiriPhoneAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/SiriPhoneAppIntentsExtension.appex/SiriPhoneAppIntentsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdc3c` | `0xdc74` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x8e0` | `0x8f0` | **`+0x10`** |
| `__TEXT.__const` | `0x20c8` | `0x20d8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x470` | `0x478` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x608` | `0x610` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x828` | `0x830` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.32.7.0.0
+3600.38.6.0.0

-  Functions: 764
-  Symbols:   2155
+  Functions: 765
+  Symbols:   2158
Symbols:
+ _$s10AppIntents16IntentValueQueryP23allowedExecutionTargetsAA0cgH0VvgZTq
+ _$s10AppIntents16IntentValueQueryPAAE23allowedExecutionTargetsAA0cgH0VvgZ
+ _$s28SiriPhoneAppIntentsExtension0a3KitB27DestinationIntentValueQueryV0cD00hiJ0AadEP23allowedExecutionTargetsAD0hlM0VvgZTW
Functions:
~ _$ss11_StringGutsV16_deconstructUTF87scratchyXlSg5owner_xSi6lengthSb11usesScratchSb15allocatedMemorytSwSg_ts8_PointerRzlFSV_Tgq5 : 268 -> 264
~ _$s28SiriPhoneAppIntentsExtension0a3KitB27DestinationIntentValueQueryV6values3forSayAA0afbG0OG13FlowToolTypes0afJ8CriteriaV_tYaKFTY0_ : 2640 -> 2696
+ _$s28SiriPhoneAppIntentsExtension0a3KitB27DestinationIntentValueQueryV0cD00hiJ0AadEP23allowedExecutionTargetsAD0hlM0VvgZTW
~ _OUTLINED_FUNCTION_2 : 20 -> 12
~ _OUTLINED_FUNCTION_3 : 12 -> 20
```
