## AppIntentSchemas

> `/System/Library/PrivateFrameworks/AppIntentSchemas.framework/AppIntentSchemas`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x83db8` | `0x87000` | **`+0x3248`** |
| `__TEXT.__eh_frame` | `0x34b8` | `0x3858` | **`+0x3a0`** |
| `__TEXT.__const` | `0xd9b8` | `0xdb48` | **`+0x190`** |
| `__DATA.__bss` | `0xc980` | `0xcb00` | **`+0x180`** |
| `__AUTH_CONST.__const` | `0x6be1` | `0x6d59` | **`+0x178`** |
| `__TEXT.__cstring` | `0x26e3` | `0x27f3` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0x2ed0` | `0x2fb0` | **`+0xe0`** |
| `__AUTH_CONST.__auth_got` | `0xad0` | `0xb78` | **`+0xa8`** |
| `__TEXT.__swift5_fieldmd` | `0x360c` | `0x36b4` | **`+0xa8`** |
| `__DATA.__data` | `0x1418` | `0x14a0` | **`+0x88`** |
| `__TEXT.__swift5_typeref` | `0x26e5` | `0x2759` | **`+0x74`** |
| `__TEXT.__constg_swiftt` | `0x216c` | `0x21d0` | **`+0x64`** |
| `__TEXT.__swift5_mpenum` | `0xc0` | `0x100` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x2397` | `0x23c7` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0xcc8` | `0xcd4` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x330` | `0x33c` | **`+0xc`** |

### Other Changes

```diff

-3502.0.43.9.0
+3502.0.45.4.0
+  - /System/Library/Frameworks/CryptoKit.framework/CryptoKit

-  Functions: 5121
+  Functions: 5161

-  CStrings:  393
+  CStrings:  399
Symbols:
+ ___swift_memcpy256_8
+ ___swift_memcpy264_8
+ ___swift_memcpy265_8
+ _associated conformance 16AppIntentSchemas0B14SystemProtocolO16PrimitiveWrapperO17CallingCodingKeys33_119E0A448DF9B22AC10813446D563D60LLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 16AppIntentSchemas0B14SystemProtocolO16PrimitiveWrapperO17CallingCodingKeys33_119E0A448DF9B22AC10813446D563D60LLOs0I3KeyAAs28CustomDebugStringConvertible
+ _swift_getAtKeyPath
+ _swift_retain
+ _swift_retain_x8
+ _symbolic Say_____G 10Foundation11JSONEncoderC16OutputFormattingV
+ _symbolic _____ 16AppIntentSchemas0B14SystemProtocolO16PrimitiveWrapperO17CallingCodingKeys33_119E0A448DF9B22AC10813446D563D60LLO
+ _symbolic _____ 16AppIntentSchemas12EntitySchemaV17PropertyReferenceV
+ _symbolic _____ 16AppIntentSchemas12SchemaHasherO
+ _symbolic _____ySnySiGG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G s22KeyedDecodingContainerV 16AppIntentSchemas0E14SystemProtocolO16PrimitiveWrapperO17CallingCodingKeys33_119E0A448DF9B22AC10813446D563D60LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 16AppIntentSchemas0E14SystemProtocolO16PrimitiveWrapperO17CallingCodingKeys33_119E0A448DF9B22AC10813446D563D60LLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation11JSONEncoderC16OutputFormattingV
+ _symbolic _____y______pG s23_ContiguousArrayStorageC s7CVarArgP
+ _type_layout_string 16AppIntentSchemas12EntitySchemaV17PropertyReferenceV
- _OUTLINED_FUNCTION_127
- _OUTLINED_FUNCTION_128
- _OUTLINED_FUNCTION_129
- _OUTLINED_FUNCTION_130
- _OUTLINED_FUNCTION_131
- _OUTLINED_FUNCTION_132
- _OUTLINED_FUNCTION_133
- _OUTLINED_FUNCTION_134
- _OUTLINED_FUNCTION_135
- _OUTLINED_FUNCTION_136
- _OUTLINED_FUNCTION_137
- _OUTLINED_FUNCTION_138
- _OUTLINED_FUNCTION_139
- ___swift_memcpy224_8
- ___swift_memcpy232_8
- ___swift_memcpy233_8
- _swift_retain_x26
- _swift_retain_x28
CStrings:
+ "Create metadata table"
+ "EntitySchema subtitle references unknown property '"
+ "EntitySchema title references unknown property '"
+ "INSERT INTO metadata (hash) VALUES (?)"
+ "SELECT hash FROM metadata LIMIT 1"
+ "_subtitle"
```
