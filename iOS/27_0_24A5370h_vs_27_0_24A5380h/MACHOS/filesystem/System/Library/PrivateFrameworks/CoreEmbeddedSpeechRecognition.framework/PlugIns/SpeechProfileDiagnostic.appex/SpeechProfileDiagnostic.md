## SpeechProfileDiagnostic

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/PlugIns/SpeechProfileDiagnostic.appex/SpeechProfileDiagnostic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a8` | `0x52c` | **`+0x84`** |
| `__TEXT.__objc_stubs` | `0x140` | `0x1a0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0xee` | `0x137` | **`+0x49`** |
| `__DATA.__objc_selrefs` | `0x60` | `0x78` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x38` | `0x44` | **`+0xc`** |
| `__TEXT.__oslogstring` | `0xcf` | `0xc4` | **`-0xb`** |
| `__DATA_CONST.__got` | `0x20` | `0x28` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.70.8.0.0
+3600.70.20.1.1

-  Functions: 4
-  Symbols:   32
-  CStrings:  27
+  Functions: 5
+  Symbols:   33
+  CStrings:  30
Symbols:
+ _OBJC_CLASS_$_CESRUserVocabProfileLogger
Functions:
~ sub_100000c50 : 584 -> 140
+ sub_100000cdc
CStrings:
+ "%s Found %lu loggable profile paths: %@"
+ "_loggableProfilePaths"
+ "addObjectsFromArray:"
+ "loggableUserVocabProfilePaths"
- "%s Found %lu loggable speech profiles at paths: %@"
```
