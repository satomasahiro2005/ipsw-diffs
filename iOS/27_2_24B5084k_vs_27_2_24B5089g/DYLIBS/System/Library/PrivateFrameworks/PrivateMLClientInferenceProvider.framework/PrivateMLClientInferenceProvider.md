## PrivateMLClientInferenceProvider

> `/System/Library/PrivateFrameworks/PrivateMLClientInferenceProvider.framework/PrivateMLClientInferenceProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9fb9c` | `0xa062c` | **`+0xa90`** |
| `__DATA_DIRTY.__data` | `0x8e8` | `0x9b0` | **`+0xc8`** |
| `__AUTH.__data` | `0x620` | `0x578` | **`-0xa8`** |
| `__TEXT.__eh_frame` | `0x2f78` | `0x2fe0` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x3f1b` | `0x3f7b` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x1ca8` | `0x1cf8` | **`+0x50`** |
| `__DATA.__common` | `0x30` | `0x8` | **`-0x28`** |
| `__DATA_DIRTY.__common` | `0x20` | `0x48` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0xba2` | `0xbc0` | **`+0x1e`** |
| `__TEXT.__const` | `0x1fe8` | `0x1ff8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xf48` | `0xf58` | **`+0x10`** |

### Other Changes

```diff

-218.5.0.0.0
+218.6.0.0.0

-  Functions: 1044
-  Symbols:   526
-  CStrings:  395
+  Functions: 1050
+  Symbols:   529
+  CStrings:  396
Symbols:
+ _symbolic _____Sg 15PrivateMLClient31Tie_CloudGuardrailsOutputPolicyV17ContentSafetyModeO
+ _symbolic _____Sg 15TokenGeneration23CloudGuardrailsEnvelopeV12OutputPolicyV17ContentSafetyModeO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 15PrivateMLClient31Tie_CloudGuardrailsOutputPolicyV
CStrings:
+ "cloudGuardrailsEnvelope set with inputPolicies: %{private}s, inputProcessingPolicies: %{private}s, outputPolicies: %{private}s"
+ "cloudGuardrailsEnvelope: unrecognized output content safety mode, returning nil"
- "cloudGuardrailsEnvelope set with inputPolicies: %{private}s, inputProcessingPolicies: %{private}s"
```
