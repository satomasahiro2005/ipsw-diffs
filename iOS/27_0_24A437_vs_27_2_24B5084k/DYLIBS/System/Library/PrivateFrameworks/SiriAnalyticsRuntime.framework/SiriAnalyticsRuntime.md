## SiriAnalyticsRuntime

> `/System/Library/PrivateFrameworks/SiriAnalyticsRuntime.framework/SiriAnalyticsRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa998` | `0xbecc` | **`+0x1534`** |
| `__DATA.__bss` | `0x680` | `0xb80` | **`+0x500`** |
| `__TEXT.__const` | `0x876` | `0xb16` | **`+0x2a0`** |
| `__TEXT.__eh_frame` | `0x4c8` | `0x6a0` | **`+0x1d8`** |
| `__AUTH_CONST.__const` | `0xdb8` | `0xf20` | **`+0x168`** |
| `__TEXT.__unwind_info` | `0x2e0` | `0x3b8` | **`+0xd8`** |
| `__TEXT.__swift5_typeref` | `0x2e1` | `0x383` | **`+0xa2`** |
| `__DATA.__data` | `0x150` | `0x1d8` | **`+0x88`** |
| `__TEXT.__constg_swiftt` | `0x31c` | `0x380` | **`+0x64`** |
| `__TEXT.__swift5_fieldmd` | `0x1c0` | `0x220` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x6f` | `0xce` | **`+0x5f`** |
| `__TEXT.__swift5_assocty` | `0x78` | `0xc0` | **`+0x48`** |
| `__TEXT.__swift5_reflstr` | `0x133` | `0x176` | **`+0x43`** |
| `__AUTH_CONST.__auth_got` | `0x480` | `0x4b8` | **`+0x38`** |
| `__TEXT.__swift5_proto` | `0x54` | `0x7c` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x3c` | `0x48` | **`+0xc`** |
| `__DATA_DIRTY.__data` | `0x588` | `0x580` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x14` | `0x1c` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x10` | `0x14` | **`+0x4`** |

### Other Changes

```diff

-3600.85.1.0.0
+3605.27.1.1.1

-  - /System/Library/PrivateFrameworks/BiomeStorage.framework/BiomeStorage
-  - /System/Library/PrivateFrameworks/BiomeStreams.framework/BiomeStreams

-  - /System/Library/PrivateFrameworks/FeedbackLogger.framework/FeedbackLogger
-  - /System/Library/PrivateFrameworks/MobileKeyBag.framework/MobileKeyBag
-  - /System/Library/PrivateFrameworks/SiriInstrumentation.framework/SiriInstrumentation
+  - /System/Library/PrivateFrameworks/SiriAnalytics.framework/SiriAnalytics

-  Functions: 377
-  Symbols:   255
-  CStrings:  12
+  Functions: 441
+  Symbols:   284
+  CStrings:  14
Symbols:
+ _OUTLINED_FUNCTION_21
+ _OUTLINED_FUNCTION_22
+ _OUTLINED_FUNCTION_23
+ _OUTLINED_FUNCTION_24
+ _OUTLINED_FUNCTION_25
+ _OUTLINED_FUNCTION_26
+ _OUTLINED_FUNCTION_27
+ _OUTLINED_FUNCTION_28
+ _OUTLINED_FUNCTION_29
+ _OUTLINED_FUNCTION_30
+ _OUTLINED_FUNCTION_31
+ ___swift_instantiateConcreteTypeFromMangledNameAbstractV2
+ _associated conformance 20SiriAnalyticsRuntime24StagingPoolPolicyHeadersV11ProtoFieldsOSHAASQ
+ _associated conformance 20SiriAnalyticsRuntime24StagingPoolPolicyHeadersV11ProtoFieldsOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 20SiriAnalyticsRuntime24StagingPoolPolicyHeadersV8Dendrite12ProtoMessageAA0I6FieldsAdEP_SY
+ _associated conformance 20SiriAnalyticsRuntime24StagingPoolPolicyHeadersV8Dendrite12ProtoMessageAA0I6FieldsAdEP_s12CaseIterable
+ _associated conformance 20SiriAnalyticsRuntime24StagingPoolPolicyHeadersV8Dendrite12ProtoMessageAaD0iJ6Reader
+ _associated conformance 20SiriAnalyticsRuntime24StagingPoolPolicyHeadersV8Dendrite12ProtoMessageAaD0iJ6Writer
+ _associated conformance 20SiriAnalyticsRuntime24StagingPoolPolicyHeadersV8Dendrite12ProtoMessageAaD17DataRepresentable
+ _associated conformance 20SiriAnalyticsRuntime24StagingPoolPolicyHeadersV8Dendrite17DataRepresentableAaD0I8Readable
+ _associated conformance 20SiriAnalyticsRuntime24StagingPoolPolicyHeadersV8Dendrite18ProtoMessageReaderAaD10AnyBuilder
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _symbolic $s8Dendrite12ProtoMessageP
+ _symbolic $ss12CaseIterableP
+ _symbolic Say_____G 20SiriAnalyticsRuntime24StagingPoolPolicyHeadersV11ProtoFieldsO
+ _symbolic _____ 20SiriAnalyticsRuntime24StagingPoolPolicyHeadersV
+ _symbolic _____ 20SiriAnalyticsRuntime24StagingPoolPolicyHeadersV11ProtoFieldsO
+ _symbolic _____ 20SiriAnalyticsRuntime27StagingPoolStreamDefinitionO
+ _symbolic _____y_____G 8Dendrite11TypedStreamC 20SiriAnalyticsRuntime24StagingPoolPolicyHeadersV
CStrings:
+ "Applied size quota to staging pool at: %s."
+ "Staging pool path: %s does not exist, exiting."
```
