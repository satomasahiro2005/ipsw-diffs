## com.apple.siri.embeddedspeech

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/XPCServices/com.apple.siri.embeddedspeech.xpc/com.apple.siri.embeddedspeech`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x331cc` | `0x33468` | **`+0x29c`** |
| `__TEXT.__cstring` | `0x4d58` | `0x4e02` | **`+0xaa`** |
| `__DATA_CONST.__const` | `0xcb8` | `0xce0` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x2de0` | `0x2e00` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1b8c` | `0x1b80` | **`-0xc`** |
| `__TEXT.__oslogstring` | `0x4b2c` | `0x4b37` | **`+0xb`** |
| `__DATA.__bss` | `0x140` | `0x148` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x788` | `0x790` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3600.70.20.1.1
+3600.70.32.0.0

-  Functions: 607
+  Functions: 609

-  CStrings:  2547
+  CStrings:  2550
CStrings:
+ "%s dealloc"
+ "-[ESSpeechProfileBuilderConnection dealloc]"
+ "CESREuclidVectorDB is not open for language: %@; fetchDatabaseWithLanguage: must complete successfully before this operation."
```
