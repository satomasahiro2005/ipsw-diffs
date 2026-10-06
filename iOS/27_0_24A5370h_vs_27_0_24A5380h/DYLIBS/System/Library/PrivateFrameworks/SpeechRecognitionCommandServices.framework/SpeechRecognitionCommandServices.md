## SpeechRecognitionCommandServices

> `/System/Library/PrivateFrameworks/SpeechRecognitionCommandServices.framework/SpeechRecognitionCommandServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11af74` | `0x11adf8` | **`-0x17c`** |
| `__TEXT.__oslogstring` | `0x40c` | `0x470` | **`+0x64`** |
| `__TEXT.__cstring` | `0x2674c` | `0x266fc` | **`-0x50`** |
| `__AUTH_CONST.__cfstring` | `0x2500` | `0x24e0` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0xc78` | `0xc70` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x3b0` | `0x3b8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xe30` | `0xe38` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x5af0` | `0x5af4` | **`+0x4`** |

### Other Changes

```diff

-32.0.0.0.0
+33.0.0.0.0

-  Functions: 2820
+  Functions: 2821
Symbols:
+ _OBJC_CLASS_$_VCLog
- _swift_willThrowTypedImpl
CStrings:
+ "Error in buildGrammarForCommandTree, dictionary neither text, child or identifier = <%{sensitive}@>"
+ "unspecified"
- "%@,%@"
- "Error in buildGrammarForCommandTree, dictionary neither text, child or identifier = <%@>"
```
