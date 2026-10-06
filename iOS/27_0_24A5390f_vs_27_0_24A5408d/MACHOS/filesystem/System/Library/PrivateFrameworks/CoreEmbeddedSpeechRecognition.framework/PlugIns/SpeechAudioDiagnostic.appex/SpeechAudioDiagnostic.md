## SpeechAudioDiagnostic

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/PlugIns/SpeechAudioDiagnostic.appex/SpeechAudioDiagnostic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0xc0` | `0xe0` | **`+0x20`** |
| `__TEXT.__text` | `0x8d4` | `0x8e0` | **`+0xc`** |
| `__TEXT.__cstring` | `0x15b` | `0x162` | **`+0x7`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.70.32.0.0
+3600.70.47.0.0

-  CStrings:  48
+  CStrings:  49
Functions:
~ sub_100000ce8 : 1128 -> 1140
CStrings:
+ "%@ - %@%@"
+ ".wav"
+ "yyyy-MM-dd HH:mm:ss"
- "%@ - %@"
- "MM/dd/yyyy HH:mm:ss"
```
