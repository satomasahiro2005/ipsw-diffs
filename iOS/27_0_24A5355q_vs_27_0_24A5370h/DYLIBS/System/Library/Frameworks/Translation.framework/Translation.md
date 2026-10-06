## Translation

> `/System/Library/Frameworks/Translation.framework/Translation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b720` | `0x5bfc0` | **`+0x8a0`** |
| `__AUTH_CONST.__objc_const` | `0xbaf8` | `0xbde0` | **`+0x2e8`** |
| `__TEXT.__objc_methlist` | `0x5b88` | `0x5cb0` | **`+0x128`** |
| `__AUTH.__objc_data` | `0x98` | `0x138` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x3324` | `0x33b4` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x3c00` | `0x3c80` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x1e58` | `0x1ea0` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x1c10` | `0x1c50` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x5146` | `0x5176` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x898` | `0x8b0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x580` | `0x590` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x318` | `0x328` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2840` | `0x2850` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x298` | `0x2a8` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x8e0` | `0x8e8` | **`+0x8`** |

### Other Changes

```diff

-380.1.0.0.0
+384.1.0.0.0

-  Functions: 2838
-  Symbols:   4296
-  CStrings:  926
+  Functions: 2859
+  Symbols:   4346
+  CStrings:  931
Symbols:
+ +[_LTNullableLocalePair supportsSecureCoding]
+ +[_LTSELFLoggingTranslateAPIContext supportsSecureCoding]
+ +[_LTTranslator selfLoggingInvocationCancelledForIDs:localePair:]
+ +[_LTTranslator selfLoggingInvocationDidError:invocationId:localePair:]
+ -[_LTLanguageStatusConfiguration multicastKey]
+ -[_LTNullableLocalePair .cxx_destruct]
+ -[_LTNullableLocalePair copyWithZone:]
+ -[_LTNullableLocalePair encodeWithCoder:]
+ -[_LTNullableLocalePair initWithCoder:]
+ -[_LTNullableLocalePair initWithLocalePair:]
+ -[_LTNullableLocalePair initWithSourceLocale:targetLocale:]
+ -[_LTNullableLocalePair localePair]
+ -[_LTNullableLocalePair sourceLocale]
+ -[_LTNullableLocalePair targetLocale]
+ -[_LTSELFLoggingInvocationOptions initWithTask:inputMode:invocationType:translateAPIContext:]
+ -[_LTSELFLoggingInvocationOptions translateAPIContext]
+ -[_LTSELFLoggingTranslateAPIContext .cxx_destruct]
+ -[_LTSELFLoggingTranslateAPIContext encodeWithCoder:]
+ -[_LTSELFLoggingTranslateAPIContext initWithCoder:]
+ -[_LTSELFLoggingTranslateAPIContext initWithLocalePair:]
+ -[_LTSELFLoggingTranslateAPIContext localePair]
+ -[_LTStreamingOutput detailedModelVersion]
+ -[_LTStreamingOutput initWithText:sourceText:locale:isFinal:sourceIdentifier:modelVersion:detailedModelVersion:]
+ -[_LTStreamingOutput modelVersion]
+ GCC_except_table25
+ GCC_except_table29
+ _OBJC_CLASS_$__LTNullableLocalePair
+ _OBJC_CLASS_$__LTSELFLoggingTranslateAPIContext
+ _OBJC_IVAR_$__LTNullableLocalePair._sourceLocale
+ _OBJC_IVAR_$__LTNullableLocalePair._targetLocale
+ _OBJC_IVAR_$__LTSELFLoggingInvocationOptions._translateAPIContext
+ _OBJC_IVAR_$__LTSELFLoggingTranslateAPIContext._localePair
+ _OBJC_IVAR_$__LTStreamingOutput._detailedModelVersion
+ _OBJC_IVAR_$__LTStreamingOutput._modelVersion
+ _OBJC_METACLASS_$__LTNullableLocalePair
+ _OBJC_METACLASS_$__LTSELFLoggingTranslateAPIContext
+ __OBJC_$_CLASS_METHODS__LTNullableLocalePair
+ __OBJC_$_CLASS_METHODS__LTSELFLoggingTranslateAPIContext
+ __OBJC_$_CLASS_PROP_LIST__LTNullableLocalePair
+ __OBJC_$_CLASS_PROP_LIST__LTSELFLoggingTranslateAPIContext
+ __OBJC_$_INSTANCE_METHODS__LTNullableLocalePair
+ __OBJC_$_INSTANCE_METHODS__LTSELFLoggingTranslateAPIContext
+ __OBJC_$_INSTANCE_VARIABLES__LTNullableLocalePair
+ __OBJC_$_INSTANCE_VARIABLES__LTSELFLoggingTranslateAPIContext
+ __OBJC_$_PROP_LIST__LTNullableLocalePair
+ __OBJC_$_PROP_LIST__LTSELFLoggingTranslateAPIContext
+ __OBJC_CLASS_PROTOCOLS_$__LTNullableLocalePair
+ __OBJC_CLASS_PROTOCOLS_$__LTSELFLoggingTranslateAPIContext
+ __OBJC_CLASS_RO_$__LTNullableLocalePair
+ __OBJC_CLASS_RO_$__LTSELFLoggingTranslateAPIContext
+ __OBJC_METACLASS_RO_$__LTNullableLocalePair
+ __OBJC_METACLASS_RO_$__LTSELFLoggingTranslateAPIContext
+ ___65+[_LTTranslator selfLoggingInvocationCancelledForIDs:localePair:]_block_invoke
+ ___71+[_LTTranslator selfLoggingInvocationDidError:invocationId:localePair:]_block_invoke
+ ___block_descriptor_56_e8_32s40s48s_e46_v24?0"<_LTTextTranslationService>"8?<v?>16ls32l8s40l8s48l8
+ _kLTDebugSimulateAIModelsDownloading
+ _unexpectedEngineTypeException
- +[_LTTranslator selfLoggingInvocationCancelledForIDs:]
- +[_LTTranslator selfLoggingInvocationDidError:invocationId:]
- -[_LTStreamingOutput initWithText:sourceText:locale:isFinal:sourceIdentifier:]
- GCC_except_table32
- ___54+[_LTTranslator selfLoggingInvocationCancelledForIDs:]_block_invoke
- ___60+[_LTTranslator selfLoggingInvocationDidError:invocationId:]_block_invoke
- __keyForConfig
CStrings:
+ "2"
+ "DebugSimulateAIModelsDownloading"
+ "Observation multicast for key '%{public}@': [%{public}@]"
+ "Observation replay for key '%{public}@': [%{public}@]"
+ "Received an unexpected on device engine type %zu"
+ "_LTUnexpectedOnDeviceEngineTypeException"
+ "translateAPIContext"
- "Obsv mlcast for key '%{public}@': [%@]"
- "Obsv replay [%{public}@]"
```
