## PrivateMLClientInferenceProvider

> `/System/Library/PrivateFrameworks/PrivateMLClientInferenceProvider.framework/PrivateMLClientInferenceProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa062c` | `0xa0204` | **`-0x428`** |
| `__AUTH_CONST.__const` | `0x1a60` | `0x1a09` | **`-0x57`** |
| `__TEXT.__eh_frame` | `0x2fe0` | `0x2fb0` | **`-0x30`** |
| `__TEXT.__swift5_capture` | `0x7b4` | `0x790` | **`-0x24`** |
| `__TEXT.__oslogstring` | `0x3f7b` | `0x3f59` | **`-0x22`** |
| `__TEXT.__unwind_info` | `0xf58` | `0xf38` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0xc2f` | `0xc1c` | **`-0x13`** |
| `__TEXT.__cstring` | `0xef1` | `0xee7` | **`-0xa`** |
| `__AUTH_CONST.__auth_got` | `0x1cf8` | `0x1d00` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xbc0` | `0xbc7` | **`+0x7`** |
| `__TEXT.__const` | `0x1ff8` | `0x1ff4` | **`-0x4`** |
| `__TEXT.__swift_as_cont` | `0x270` | `0x26c` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x10c` | `0x108` | **`-0x4`** |

### Other Changes

```diff

-218.6.0.0.0
+218.9.0.0.0

-  Functions: 1050
+  Functions: 1049

-  CStrings:  396
+  CStrings:  394
Symbols:
+ ___swift_closure_destructor.36Tm
+ ___swift_closure_destructor.54Tm
+ _symbolic _____Sg s5Int32V
- ___swift_closure_destructor.37Tm
- ___swift_closure_destructor.41Tm
- ___swift_closure_destructor.55Tm
CStrings:
+ "%s prewarm initiated. sessionUUID=%s modelBundleIdentifier=%s featureIdentifier=%s bundleIdentifier=%s originatingBundleIdentifier=%s model=%s adapter=%stokenizerResource=%s"
- " streaming replay write"
- "%s prewarm initiated. sessionUUID=%s modelBundleIdentifier=%s featureIdentifier=%s bundleIdentifier=%s model=%s adapter=%stokenizerResource=%s"
- "Writing CompletePrompt to disk complete."
```
