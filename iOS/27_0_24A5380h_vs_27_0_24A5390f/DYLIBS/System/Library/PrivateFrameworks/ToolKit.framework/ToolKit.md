## ToolKit

> `/System/Library/PrivateFrameworks/ToolKit.framework/ToolKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4cdab0` | `0x4d47b8` | **`+0x6d08`** |
| `__TEXT.__eh_frame` | `0x32838` | `0x32ab8` | **`+0x280`** |
| `__TEXT.__oslogstring` | `0x407c` | `0x42bc` | **`+0x240`** |
| `__DATA.__bss` | `0x93640` | `0x93840` | **`+0x200`** |
| `__TEXT.__cstring` | `0x9224` | `0x93a4` | **`+0x180`** |
| `__AUTH_CONST.__const` | `0x2bcb0` | `0x2bdf0` | **`+0x140`** |
| `__TEXT.__const` | `0x7acd8` | `0x7ade8` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0x1aaf8` | `0x1abc8` | **`+0xd0`** |
| `__DATA.__data` | `0xfb90` | `0xfc40` | **`+0xb0`** |
| `__AUTH.__data` | `0x28b8` | `0x2950` | **`+0x98`** |
| `__TEXT.__swift5_capture` | `0x34e4` | `0x3574` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x146a8` | `0x14730` | **`+0x88`** |
| `__TEXT.__swift5_reflstr` | `0x93a7` | `0x9417` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x13d2c` | `0x13d84` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0xee9c` | `0xeee0` | **`+0x44`** |
| `__TEXT.__objc_methlist` | `0x228` | `0x240` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x5b4` | `0x5a0` | **`-0x14`** |
| `__DATA_DIRTY.__data` | `0x12c68` | `0x12c78` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x6eb0` | `0x6ec0` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x1c68` | `0x1c70` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xd38` | `0xd40` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x3b0` | `0x3b8` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x330` | `0x328` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x1868` | `0x186c` | **`+0x4`** |

### Other Changes

```diff

-5032.5.0.0.0
+5034.0.12.100.0

-  Functions: 44650
-  Symbols:   10286
-  CStrings:  1710
+  Functions: 44732
+  Symbols:   10300
+  CStrings:  1728
Symbols:
+ _NSCocoaErrorDomain
+ _OUTLINED_FUNCTION_588
+ _OUTLINED_FUNCTION_589
+ _OUTLINED_FUNCTION_590
+ ___swift__destructor.189Tm
+ ___swift_closure_destructor.293Tm
+ ___swift_get_extra_inhabitant_index.129Tm
+ ___swift_memcpy296_8
+ ___swift_store_extra_inhabitant_index.130Tm
+ _associated conformance 7ToolKit0A10DefinitionV10FetchErrorOSHAASQ
+ _associated conformance 7ToolKit0A8DatabaseC5ErrorO10Foundation09LocalizedD0AAsAD
+ _symbolic Say_____G 7ToolKit31TypeDisplayRepresentationRecordV
+ _symbolic Say_____GSg 7ToolKit31TypeDisplayRepresentationRecordV
+ _symbolic Si15databaseVersion_Si08expectedB0t
+ _symbolic _____ 7ToolKit0A10DefinitionV10FetchErrorO
+ _symbolic _____Sg 12GRDBInternal8DatabaseC
+ _symbolic _____Sg 7ToolKit0A13ExecutorEventO
+ _symbolic _____Sg 7ToolKit0A18LocalizationRecordV
+ _symbolic _____y_____G 12GRDBInternal21QueryInterfaceRequestV 7ToolKit0E18LocalizationRecordV
+ _symbolic _____y_____G 12GRDBInternal21QueryInterfaceRequestV 7ToolKit30ContainerMetadataSynonymRecordV
+ _symbolic _____y_____G 12GRDBInternal21QueryInterfaceRequestV 7ToolKit31TypeDisplayRepresentationRecordV
- ___swift__destructor.188Tm
- ___swift_closure_destructor.270Tm
- ___swift_get_extra_inhabitant_index.128Tm
- ___swift_memcpy288_8
- ___swift_store_extra_inhabitant_index.129Tm
- _get_enum_tag_for_layout_string 7ToolKit0A13ExecutorEventO
- _type_layout_string 7ToolKit0A13ExecutorEventO
CStrings:
+ ") is incompatible with expected version ("
+ "). Wait for indexing to complete and retry."
+ "<personNameComponents>"
+ "<searchableItem>"
+ "Database schema version ("
+ "Failed to build TypeDefinition for type %s (kind: %s) at resolved locale '%s': %@"
+ "Invalid environment: "
+ "Missing database file"
+ "Missing display representation for type %s at resolved locale '%s'; falling back to locale '%s'"
+ "Missing display representation for type %s in every indexed locale"
+ "Missing tool definition"
+ "Session %s received opensIntent"
+ "Session %s received opensIntent but no tool invocation is in progress"
+ "Skipping row that failed to transform for request: %{public}s due to error: %{public}s"
+ "Tool %lld has no '%{public}s' localization at locale '%{public}s'; falling back to '%{public}s'"
+ "Undeclared container: "
+ "Undeclared type: "
+ "allDisplayRepresentations"
```
