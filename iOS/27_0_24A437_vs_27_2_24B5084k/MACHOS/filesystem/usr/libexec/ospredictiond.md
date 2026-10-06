## ospredictiond

> `/usr/libexec/ospredictiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x690c4` | `0x694a8` | **`+0x3e4`** |
| `__TEXT.__oslogstring` | `0x7474` | `0x7540` | **`+0xcc`** |
| `__TEXT.__objc_stubs` | `0x9960` | `0x99e0` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x15478` | `0x154f4` | **`+0x7c`** |
| `__TEXT.__cstring` | `0x55b4` | `0x5605` | **`+0x51`** |
| `__DATA.__objc_selrefs` | `0x3da0` | `0x3dc0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x4c8` | `0x4d0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-286.2.1.0.0
+288.40.3.0.0

-  Functions: 3339
-  Symbols:   287
-  CStrings:  4806
+  Functions: 3340
+  Symbols:   288
+  CStrings:  4814
Symbols:
+ _OBJC_CLASS_$_BMDeviceActivityPrediction
CStrings:
+ "Prediction"
+ "Queuing engagementEvent"
+ "Sent inactivity prediction event: confidenceLevel: %d - confidenceValue: %f - predictedDuration: %f - outputReason: %d"
+ "Unsupported Inactivity Predictor Output Confidence Level: %@"
+ "com.apple.osintelligence.inactivityprediction.addEventToActivityPredictionStream"
+ "initWithVersion:predictionType:confidenceLevel:confidenceValue:predictedDuration:outputReason:"
+ "sendEvent:"
+ "source"
```
