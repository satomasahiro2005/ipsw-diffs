## PrivateMLClientInferenceProvider

> `/System/Library/PrivateFrameworks/PrivateMLClientInferenceProvider.framework/PrivateMLClientInferenceProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x909f8` | `0x91b44` | **`+0x114c`** |
| `__AUTH_CONST.__auth_got` | `0x19b8` | `0x19f0` | **`+0x38`** |
| `__TEXT.__cstring` | `0xdbb` | `0xdeb` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x3dab` | `0x3dcb` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xc21` | `0xc41` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0xb20` | `0xb32` | **`+0x12`** |
| `__DATA.__data` | `0x4f8` | `0x508` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x904` | `0x910` | **`+0xc`** |
| `__TEXT.__eh_frame` | `0x27e8` | `0x27e0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xcc0` | `0xcc8` | **`+0x8`** |

### Other Changes

```diff

-207.0.3.0.0
+212.0.0.0.0

-  Functions: 873
-  Symbols:   509
-  CStrings:  379
+  Functions: 876
+  Symbols:   512
+  CStrings:  381
Symbols:
+ _objc_retain_x21
+ _objc_retain_x27
+ _symbolic SS______t 15TokenGeneration0aB5ErrorO7ContextV
+ _symbolic _____Sg 15PrivateMLClient52Tokengenerationcore_Wireformat_PromptCompletionEventV06OneOf_G4TypeO
- _objc_retain_x25
CStrings:
+ "%s next() returned unhandled token type."
+ "%s received prompt completion event"
+ "%{private}s failed: unrecognized system-instruction prefix ID"
+ "Failed to emit AppleIntelligence end event for %{public}s: %@"
+ "Unrecognized system-instruction prefix ID: "
- "%s next() returned ending."
- "Failed to emit AppleIntelligence end event for requestOneShot: %@"
- "Failed to emit AppleIntelligence end event for requestStream: %@"
```
