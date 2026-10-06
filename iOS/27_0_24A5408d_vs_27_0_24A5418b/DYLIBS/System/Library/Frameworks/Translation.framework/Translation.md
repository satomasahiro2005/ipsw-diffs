## Translation

> `/System/Library/Frameworks/Translation.framework/Translation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5cb08` | `0x5ccc4` | **`+0x1bc`** |
| `__AUTH_CONST.__cfstring` | `0x3d60` | `0x3e40` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x3414` | `0x3464` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x1ea0` | `0x1ed0` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x5306` | `0x5336` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1c78` | `0x1c80` | **`+0x8`** |

### Other Changes

```diff

-388.0.0.0.0
+389.1.0.0.0

-  Functions: 2896
-  Symbols:   4408
-  CStrings:  944
+  Functions: 2897
+  Symbols:   4409
+  CStrings:  952
Symbols:
+ __LTEngineInfoDescription
Functions:
+ __LTEngineInfoDescription
~ ___72-[_LTParagraphTranslationRequest _startTranslationWithTextService:done:]_block_invoke_2 : 168 -> 272
~ -[_LTTextToSpeechTranslationRequest translatorDidTranslate:] : 188 -> 300
~ -[_LTTranslationSession paragraphTranslation:result:error:] : 352 -> 464
CStrings:
+ "Translation completed using engine: %{public}@"
+ "ai-afm-lora"
+ "ai-ifp-lora"
+ "ai-mt-expert"
+ "none"
+ "traditional"
+ "traditional-server"
+ "unknown(%ld)"
```
