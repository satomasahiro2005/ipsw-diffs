## TextComposer

> `/System/Library/PrivateFrameworks/TextComposer.framework/TextComposer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cc9d4` | `0x1cebf4` | **`+0x2220`** |
| `__DATA.__bss` | `0x22120` | `0x225e0` | **`+0x4c0`** |
| `__AUTH_CONST.__cfstring` | `0xac80` | `0xaec0` | **`+0x240`** |
| `__TEXT.__const` | `0x16754` | `0x16984` | **`+0x230`** |
| `__AUTH_CONST.__const` | `0xfb10` | `0xfcd8` | **`+0x1c8`** |
| `__AUTH_CONST.__objc_const` | `0xfef0` | `0x10098` | **`+0x1a8`** |
| `__TEXT.__eh_frame` | `0xc930` | `0xcaa0` | **`+0x170`** |
| `__AUTH.__data` | `0x3690` | `0x37f8` | **`+0x168`** |
| `__TEXT.__unwind_info` | `0x84c0` | `0x85a8` | **`+0xe8`** |
| `__TEXT.__constg_swiftt` | `0x43f4` | `0x44ac` | **`+0xb8`** |
| `__TEXT.__swift5_fieldmd` | `0x485c` | `0x4910` | **`+0xb4`** |
| `__DATA_DIRTY.__bss` | `0x13e0` | `0x1470` | **`+0x90`** |
| `__TEXT.__gcc_except_tab` | `0x1cc4` | `0x1d54` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x28fb` | `0x296c` | **`+0x71`** |
| `__TEXT.__cstring` | `0x100eb` | `0x1015b` | **`+0x70`** |
| `__TEXT.__ustring` | `0x17ea` | `0x1852` | **`+0x68`** |
| `__AUTH.__objc_data` | `0x2d68` | `0x2db8` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x40b9` | `0x4108` | **`+0x4f`** |
| `__AUTH_CONST.__auth_got` | `0x1e08` | `0x1e50` | **`+0x48`** |
| `__TEXT.__swift5_proto` | `0x1178` | `0x11a8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2840` | `0x2818` | **`-0x28`** |
| `__TEXT.__objc_methlist` | `0x5a80` | `0x5aa8` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0x4f8` | `0x514` | **`+0x1c`** |
| `__DATA.__data` | `0x2390` | `0x23a8` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x1258` | `0x1270` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3288` | `0x32a0` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x918` | `0x930` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x5ec` | `0x604` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xd70` | `0xd80` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x618` | `0x628` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x618` | `0x628` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x728` | `0x730` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-211.20.0.0.0
+211.26.0.0.0

-  Functions: 13379
-  Symbols:   878
-  CStrings:  2567
+  Functions: 13448
+  Symbols:   885
+  CStrings:  2584
Symbols:
+ _CFLocaleCreate
+ _CFStringTokenizerAdvanceToNextToken
+ _CFStringTokenizerCopyCurrentTokenAttribute
+ _CFStringTokenizerCreate
+ _CFStringTokenizerGetCurrentTokenRange
+ _CFStringTokenizerSetString
+ _kCFStringTransformStripDiacritics
CStrings:
+ "** :"
+ "Intent detection model invocation failed: domain=%{public}@ code=%{public}ld"
+ "MailSnippet filter lang=%{public}@ | nWords=%lu (max=%lu, exceeded=%d) length=%lu (max=%lu, exceeded=%d) nNonWords=%lu (max=%lu, exceeded=%d)"
+ "MessagesReply.session"
+ "NSGrammarSystemCategory"
+ "No smart action intent detected (generated content is explicitly an empty string, or 'NA')"
+ "No smart action intent detected (model runner correctly threw an empty content error)"
+ "Routing deprecated long-form smart reply SPI to the Writing Assistant mail reply path"
+ "UseMailDraftGenerationResourceID"
+ "User questionnaire SPI is deprecated - returning empty results without invoking the model"
+ "[TCTextCompositionAssistant] : Unsupported diacritic-free %@ for ReviewOfInput"
+ "[TCTextCompositionAssistant] : User questionnaire SPI is deprecated - returning empty results without invoking the model"
+ "う"
+ "うが"
+ "お疲れ様"
+ "た"
+ "たが"
+ "ている"
+ "てる"
+ "でした"
+ "です"
+ "ます"
+ "ますか"
+ "ますが"
+ "られ"
+ "られる"
+ "れ"
+ "れる"
- "Model provided no output."
- "Possible Error in intent detection model invocation."
- "Possible Error: %@"
- "[TCTextCompositionAssistant] : Failed to build prompt (token: %lu)"
- "[TCTextCompositionAssistant] : Invoked computation of user questionnaire for long form replies"
- "[TCTextCompositionAssistant] : Invoked computation of user questionnaire for unsupported type: %@. Only %@ is supported"
- "[TCTextCompositionAssistant] : Model provided output - calling handler (type: questionnaire, token: %lu)"
- "[TCTextCompositionAssistant] : Possible Error in model invocation (token: %lu)"
- "[TCTextCompositionAssistant] : Successfully constructed questionnaire prompt (token: %lu)"
- "[TCTextCompositionAssistant] : mail SR QA:  not eligible - returning empty"
- "[WritingAssistantServer] modelServiceRequestPayload called"
```
