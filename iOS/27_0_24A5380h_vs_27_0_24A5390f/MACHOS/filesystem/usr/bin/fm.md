## fm

> `/usr/bin/fm`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb5210` | `0xbe35c` | **`+0x914c`** |
| `__TEXT.__cstring` | `0x534a` | `0x5ada` | **`+0x790`** |
| `__DATA_CONST.__const` | `0x2e80` | `0x30b0` | **`+0x230`** |
| `__TEXT.__swift5_reflstr` | `0xeb7` | `0x1046` | **`+0x18f`** |
| `__TEXT.__auth_stubs` | `0x3060` | `0x3190` | **`+0x130`** |
| `__TEXT.__swift5_fieldmd` | `0x1294` | `0x13bc` | **`+0x128`** |
| `__TEXT.__swift5_typeref` | `0x11af` | `0x12a9` | **`+0xfa`** |
| `__DATA.__objc_const` | `0xbf0` | `0xcd0` | **`+0xe0`** |
| `__TEXT.__const` | `0x3fa4` | `0x405c` | **`+0xb8`** |
| `__DATA.__data` | `0x2008` | `0x20b8` | **`+0xb0`** |
| `__TEXT.__eh_frame` | `0x3df8` | `0x3ea0` | **`+0xa8`** |
| `__TEXT.__objc_methname` | `0x77d` | `0x81d` | **`+0xa0`** |
| `__DATA_CONST.__auth_got` | `0x1838` | `0x18d0` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x1958` | `0x19b8` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0xcb8` | `0xd08` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x730` | `0x770` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x7f4` | `0x824` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x7b0` | `0x7d8` | **`+0x28`** |
| `__DATA.__common` | `0x278` | `0x290` | **`+0x18`** |
| `__TEXT.__swift5_mpenum` | `0x34` | `0x28` | **`-0xc`** |
| `__TEXT.__swift5_proto` | `0x2bc` | `0x2c8` | **`+0xc`** |
| `__TEXT.__swift5_protos` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x19c` | `0x1a4` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xdc` | `0xe0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-2.0.59.0.0
+2.0.63.0.0

+  - /System/Library/Frameworks/_Vision_FoundationModels.framework/_Vision_FoundationModels

+  - /usr/lib/swift/libswiftAVFoundation.dylib
+  - /usr/lib/swift/libswiftAccelerate.dylib
+  - /usr/lib/swift/libswiftCompression.dylib

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

+  - /usr/lib/swift/libswiftMLCompute.dylib

+  - /usr/lib/swift/libswiftQuartzCore.dylib

-  Functions: 1775
-  Symbols:   1169
-  CStrings:  478
+  Functions: 1819
+  Symbols:   1203
+  CStrings:  509
Symbols:
+ _$s16FoundationModels10AttachmentV5labelyACyxGSSF
+ _$s16FoundationModels10AttachmentVA2A05ImageC7ContentVRszlE8imageURL11orientationACyAEG0A00G0V_So26CGImagePropertyOrientationVSgtcfC
+ _$s16FoundationModels10AttachmentVMn
+ _$s16FoundationModels10AttachmentVyxGAA19PromptRepresentableAAMc
+ _$s16FoundationModels19SystemLanguageModelC10tokenCount3forSix_tYaKAA19PromptRepresentableRzlF
+ _$s16FoundationModels19SystemLanguageModelC10tokenCount3forSix_tYaKAA19PromptRepresentableRzlFTu
+ _$s16FoundationModels20LanguageModelSessionC13ToolCallErrorV010underlyingH0s0H0_pvg
+ _$s16FoundationModels20LanguageModelSessionC13ToolCallErrorV4toolAA0F0_pvg
+ _$s16FoundationModels20LanguageModelSessionC13ToolCallErrorVMa
+ _$s16FoundationModels20LanguageModelSessionC7prewarm12promptPrefixyAA6PromptVSg_tF
+ _$s16FoundationModels22ImageAttachmentContentVMn
+ _$s16FoundationModels4ToolMp
+ _$s16FoundationModels4ToolP11descriptionSSvgTj
+ _$s16FoundationModels4ToolP4nameSSvgTj
+ _$s22ArgumentParserInternal0A4HelpVs32ExpressibleByStringInterpolationAAMc
+ _$s24_Vision_FoundationModels17BarcodeReaderToolV0bC00F0AAMc
+ _$s24_Vision_FoundationModels17BarcodeReaderToolV4name11descriptionACSSSg_AFtcfC
+ _$s24_Vision_FoundationModels17BarcodeReaderToolVMa
+ _$s24_Vision_FoundationModels17BarcodeReaderToolVMn
+ _$s24_Vision_FoundationModels7OCRToolV0bC04ToolAAMc
+ _$s24_Vision_FoundationModels7OCRToolV4name11descriptionACSSSg_AFtcfC
+ _$s24_Vision_FoundationModels7OCRToolVMa
+ _$s24_Vision_FoundationModels7OCRToolVMn
+ _$sSS15reserveCapacityyySiF
+ _$ss15ContinuousClockV7InstantV1loiySbAD_ADtFZ
+ _$ss15ContinuousClockV7InstantV8advanced2byADs8DurationV_tF
+ _$ss15ContinuousClockV7InstantVSLsMc
+ _$ss32ExpressibleByStringInterpolationPss07DefaultcD0V0cD0RtzrlE06stringD0xAD_tcfC
+ _$ss8DurationV1loiySbAB_ABtFZ
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftMLCompute
+ __swift_FORCE_LOAD_$_swiftQuartzCore
+ _swift_getTupleTypeMetadata2
- _$s16FoundationModels12InstructionsVAA0C13RepresentableAAWP
- _swift_retain_x28
CStrings:
+ " --image value(s). Provide at most one --label per --image."
+ " --label value(s) for "
+ " fm> [Cancelled.]\n"
+ " label "
+ "'\nfm count-tokens -i 'You are a helpful assistant' '"
+ "' is not enabled."
+ "' | fm count-tokens"
+ "--label has no effect without an image-using tool. Enable --tool barcode or --tool ocr (or drop the --label flag)."
+ "--save-transcript <f>"
+ "--transcript <f>"
+ ". /tools add <name> · /tools remove <name>"
+ ". Enable with /tools add <name>."
+ "/resume requires a session name. Use /sessions to list saved sessions."
+ "/tools [add|remove <name>]"
+ "/tools add requires a tool name (e.g. /tools add barcode)"
+ "/tools remove requires a tool name (e.g. /tools remove ocr)"
+ "A short, descriptive title for this conversation — 2 to 4 lowercase words joined by hyphens, e.g. swift-concurrency, recipe-suggestions, code-review"
+ "AutomationTools.Zap.FMCLI.serve"
+ "Built-in tool to enable ("
+ "Built-in tool to enable (repeatable). Known: "
+ "Cannot specify both a saved transcript and --instructions. The transcript already contains its instructions."
+ "Continue a saved conversation from its transcript"
+ "Continue an earlier conversation: load a saved transcript so the model picks up with its previous turns as context"
+ "Count the number of tokens using the on-device system model's tokenizer. Supports positional prompts, --text and --image segments, --instructions, and a saved --transcript.\n\nA bare prompt is counted as raw content on its own. Add --instructions or --transcript to instead count the framed request the model actually receives, including the chat-template turn markers the model injects around it.\n\nWhen stdout is a terminal the output is prefixed with 'Token count: '; when piped or redirected (or when --quiet is passed) only the integer is printed. When no prompt is given on the command line, the prompt is read from standard input if stdin is piped."
+ "Count the tokens in a prompt, instructions, or transcript."
+ "Failed to resume: "
+ "Format responses using Markdown: use headings (#, ##, ###), bold (**text**), inline code (`text`), fenced code blocks, and bullet lists (- item). Do NOT wrap the entire response in a code fence."
+ "Label for the corresponding --image (paired by order)"
+ "Label for the corresponding --image (repeatable, paired by order). Requires --tool. Defaults to 'image_<index>'."
+ "List, add, or remove built-in tools ("
+ "No built-in tools are available in this build."
+ "No built-in tools are available in this build. Drop the --tool flag."
+ "No tools enabled. Known: "
+ "Path to a saved transcript to count. Its turns are counted as a framed conversation."
+ "Press Ctrl+C again to exit."
+ "Save the transcript to a file after responding. An absolute path is used as-is; a bare filename is saved in the current directory."
+ "Save transcript to a file after responding"
+ "Saved transcript to count as a framed conversation"
+ "The --schema option is not supported with the count-tokens command"
+ "The --verbose option is not supported with the count-tokens command. Use --quiet for bare-integer output in scripts."
+ "Tools are available for this conversation. When the user's request matches one of\nthe available tools, you MUST invoke the tool — do not answer from memory, do not\nask the user to run it themselves, and do not describe what the tool would do.\nCall the tool, then base your reply on its result.\n\nAvailable tools:\n"
+ "Transcript saved to: "
+ "Use /tools to list active tools."
+ "Warning: Failed to save transcript '"
+ "echo 'What is Swift?' | fm count-tokens"
+ "fm count-tokens '"
+ "fm count-tokens 'Hello world'"
+ "fm count-tokens 'What is Swift?'"
+ "fm count-tokens --image photo.jpg --text 'Describe this image'"
+ "fm count-tokens --transcript session.json"
+ "fm count-tokens -i 'Answer concisely'"
+ "fm count-tokens -i 'You are a helpful assistant' 'What is Swift?'"
+ "idleExitHintExpiry"
+ "interruptRequested"
+ "lastCancelAt"
+ "nextImageLabelID"
+ "pendingImageLabels"
+ "saveTranscriptPath"
+ "statusNotice"
+ "tools"
- "'\nfm token-count -i 'You are a helpful assistant' '"
- "' | fm token-count"
- "--load-transcript <f>"
- "--save-transcript <n>"
- "/[a-z][a-z0-9]*(-[a-z][a-z0-9]*){1,2}/"
- "/load requires a session name. Use /history to list sessions."
- "2-3 hyphen-separated lowercase words suitable for a filename, e.g. swift-concurrency, recipe-suggestions, code-review"
- "Cannot specify both --load-transcript and --instructions. The transcript already contains its instructions."
- "Count the number of tokens the request would consume using the on-device system model's tokenizer. Supports positional prompts, --text and --image segments, --instructions, and --load-transcript.\n\nWhen stdout is a terminal the output is prefixed with 'Token count: '; when piped or redirected (or when --quiet is passed) only the integer is printed. When no prompt is given on the command line, the prompt is read from standard input if stdin is piped."
- "Count the tokens in a prompt, instructions, or saved transcript."
- "Failed to load: "
- "Format responses using Markdown: use headings (#, ##, ###),\nbold (**text**), inline code (`text`), fenced code blocks,\nand bullet lists (- item). Do NOT wrap the entire response in a code fence."
- "Loaded session '"
- "Path to a saved transcript"
- "Path to a saved transcript for conversational context"
- "Save the session transcript to ~/.fm/sessions/<name> after responding"
- "Save transcript after responding"
- "Saved transcript to seed the count"
- "The --schema option is not supported with the token-count command"
- "The --verbose option is not supported with the token-count command. Use --quiet for bare-integer output in scripts."
- "Warning: Failed to save session '"
- "echo 'What is Swift?' | fm token-count"
- "fm token-count '"
- "fm token-count 'Hello world'"
- "fm token-count 'What is Swift?'"
- "fm token-count --image photo.jpg --text 'Describe this image'"
- "fm token-count --load-transcript session.json 'Follow up'"
- "fm token-count -i 'Answer concisely'"
- "fm token-count -i 'You are a helpful assistant' 'What is Swift?'"
```
