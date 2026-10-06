## TCC

> `/System/Library/PrivateFrameworks/TCC.framework/TCC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16694` | `0x169b8` | **`+0x324`** |
| `__TEXT.__cstring` | `0x3547` | `0x35bc` | **`+0x75`** |
| `__TEXT.__oslogstring` | `0x1796` | `0x17fa` | **`+0x64`** |
| `__DATA_CONST.__const` | `0x1920` | `0x1948` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x630` | `0x640` | **`+0x10`** |

### Other Changes

```diff

-919.0.0.0.0
+921.0.0.0.0

-  Functions: 614
-  Symbols:   974
-  CStrings:  631
+  Functions: 619
+  Symbols:   977
+  CStrings:  634
Symbols:
+ ___tcc_authorization_bundle_identifier_report_use_block_invoke
+ _tcc_authorization_bundle_identifier_report_use
+ _tcc_message_options_set_attributed_bundle_identifier
CStrings:
+ "%s: error creating a UTF-8 string from the attributed bundle identifier, reporting use unattributed"
+ "TCCD_MSG_MESSAGE_OPTION_ATTRIBUTED_BUNDLE_IDENTIFIER_KEY"
+ "tcc_authorization_bundle_identifier_report_use_block_invoke"
```
