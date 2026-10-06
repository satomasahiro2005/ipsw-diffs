## SiriInstrumentation

> `/System/Library/PrivateFrameworks/SiriInstrumentation.framework/SiriInstrumentation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xddf1d4` | `0xddfae8` | **`+0x914`** |
| `__AUTH_CONST.__const` | `0x27218` | `0x27338` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x10ff04` | `0x10ff94` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x184b80` | `0x184bf0` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x44460` | `0x44488` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x4cc8` | `0x4cf0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x834e0` | `0x83500` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x34598` | `0x345b8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x98e0c` | `0x98e16` | **`+0xa`** |
| `__DATA.__objc_ivar` | `0x13168` | `0x13170` | **`+0x8`** |

### Other Changes

```diff

-3605.29.1.0.0
+3605.33.1.0.0

-  Functions: 96254
-  Symbols:   134773
-  CStrings:  17961
+  Functions: 96268
+  Symbols:   134787
+  CStrings:  17962
Symbols:
+ -[ORCHSchemaORCHIFProxyRequestFailed addErrors:]
+ -[ORCHSchemaORCHIFProxyRequestFailed clearErrors]
+ -[ORCHSchemaORCHIFProxyRequestFailed deleteErrors]
+ -[ORCHSchemaORCHIFProxyRequestFailed errorsAtIndex:]
+ -[ORCHSchemaORCHIFProxyRequestFailed errorsCount]
+ -[ORCHSchemaORCHIFProxyRequestFailed errors]
+ -[ORCHSchemaORCHIFProxyRequestFailed setErrors:]
+ -[SAMSchemaWKAExecutionInfo deleteStepCount]
+ -[SAMSchemaWKAExecutionInfo hasStepCount]
+ -[SAMSchemaWKAExecutionInfo setHasStepCount:]
+ -[SAMSchemaWKAExecutionInfo setStepCount:]
+ -[SAMSchemaWKAExecutionInfo stepCount]
+ OBJC_IVAR_$_ORCHSchemaORCHIFProxyRequestFailed._errors
+ OBJC_IVAR_$_SAMSchemaWKAExecutionInfo._stepCount
CStrings:
+ "stepCount"
```
