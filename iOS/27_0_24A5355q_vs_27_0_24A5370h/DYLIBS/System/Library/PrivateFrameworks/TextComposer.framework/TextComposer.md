## TextComposer

> `/System/Library/PrivateFrameworks/TextComposer.framework/TextComposer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x10be8` | `0x10248` | **`-0x9a0`** |
| `__AUTH.__data` | `0x4268` | `0x39f8` | **`-0x870`** |
| `__TEXT.__eh_frame` | `0xd840` | `0xd080` | **`-0x7c0`** |
| `__DATA.__bss` | `0x229c0` | `0x22380` | **`-0x640`** |
| `__TEXT.__const` | `0x16fe4` | `0x169a4` | **`-0x640`** |
| `__AUTH_CONST.__const` | `0x10420` | `0xfe30` | **`-0x5f0`** |
| `__TEXT.__oslogstring` | `0xa422` | `0xa7a2` | **`+0x380`** |
| `__TEXT.__constg_swiftt` | `0x489c` | `0x4524` | **`-0x378`** |
| `__TEXT.__swift5_fieldmd` | `0x4bcc` | `0x4938` | **`-0x294`** |
| `__TEXT.__unwind_info` | `0x8890` | `0x8648` | **`-0x248`** |
| `__AUTH.__objc_data` | `0x3570` | `0x3390` | **`-0x1e0`** |
| `__TEXT.__cstring` | `0x10d5b` | `0x10b7b` | **`-0x1e0`** |
| `__AUTH_CONST.__cfstring` | `0xd500` | `0xd620` | **`+0x120`** |
| `__TEXT.__gcc_except_tab` | `0x1a70` | `0x1b84` | **`+0x114`** |
| `__TEXT.__swift_as_cont` | `0xa98` | `0x9a8` | **`-0xf0`** |
| `__DATA_CONST.__const` | `0x2710` | `0x27e0` | **`+0xd0`** |
| `__TEXT.__swift_as_ret` | `0x6dc` | `0x634` | **`-0xa8`** |
| `__TEXT.__swift_as_entry` | `0x5c0` | `0x534` | **`-0x8c`** |
| `__TEXT.__objc_methlist` | `0x5a00` | `0x5a70` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x3240` | `0x32a8` | **`+0x68`** |
| `__DATA_CONST.__objc_classlist` | `0x698` | `0x638` | **`-0x60`** |
| `__DATA_DIRTY.__bss` | `0x14c0` | `0x1460` | **`-0x60`** |
| `__TEXT.__swift5_proto` | `0x1200` | `0x11a0` | **`-0x60`** |
| `__DATA_CONST.__objc_arraydata` | `0x1ed0` | `0x1f20` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x100c` | `0xfbc` | **`-0x50`** |
| `__DATA.__data` | `0x2480` | `0x24b0` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x291b` | `0x28eb` | **`-0x30`** |
| `__TEXT.__swift5_types` | `0x658` | `0x628` | **`-0x30`** |
| `__TEXT.__text` | `0x1d073c` | `0x1d0764` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1df8` | `0x1e18` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x720` | `0x738` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xd80` | `0xd68` | **`-0x18`** |
| `__DATA_DIRTY.__data` | `0x6d0` | `0x6e8` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x4149` | `0x4157` | **`+0xe`** |
| `__DATA.__objc_ivar` | `0x57c` | `0x584` | **`+0x8`** |

### Other Changes

```diff

-211.7.2.0.0
+211.13.0.0.0

-  Functions: 13650
-  Symbols:   867
-  CStrings:  2876
+  Functions: 13521
+  Symbols:   873
+  CStrings:  2884
Symbols:
+ _CFStringTransform
+ _TCPostEditorOptionKeySkipTimer
+ _TCTextCompositionAssistantOptionKeyModelPromptIdentifier
+ _TCTextCompositionAssistantSmartActionContentModelOutput
+ _TCTextCompositionAssistantSmartActionEligibilityMap
+ _TCTextCompositionAssistantSmartActionIntentModelOutput
+ _TCTextCompositionAssistantSmartActionStructuredSearchFoundData
- _objc_release_x14
CStrings:
+ "("
+ ", TokenGenerator>"
+ "="
+ "Archetype query execution failed"
+ "ArchetypeService: querying for profiles matching conversation identifier: %{private}s"
+ "Failed to parse Archetype queries from model output"
+ "Halfwidth-Fullwidth"
+ "Invalid model output: Expected ChatOneShotGenerableResponseOutput<"
+ "ModelPromptIdentifier"
+ "ModelRunner: Calling countInputPromptTokens"
+ "ModelRunner: Calling countOutputPromptTokens"
+ "ModelRunner: Calling generate()"
+ "ModelRunner: Calling generative function"
+ "ModelRunner: Calling generative function for "
+ "ModelRunner: Calling generative function for PersonalizedSmartReplies"
+ "ModelRunner: Input sanitization"
+ "ModelRunner: Safety check"
+ "ModelRunner: Using output token count from promptCompletion"
+ "ModelRunner: countPromptTokens - Overestimate near limit, falling back to countTokens"
+ "ModelRunner: countPromptTokens - Using overestimated token count"
+ "ModelRunner: countPromptTokens - Using tokenGen.countTokens"
+ "SkipTimer"
+ "SmartActionContentModelOutput"
+ "SmartActionEligibilityMap"
+ "SmartActionIntentModelOutput"
+ "SmartActionStructuredSearchFoundData"
+ "TextComposer.ArchetypeRetrievalError"
+ "[SmartAction.OutputParsing] Model produced more than one (%lu) queries, using last"
+ "[SmartAction] Error querying Archetype: %@"
+ "[SmartAction] Fetching Archetype user info for association: '%{sensitive}s', attribute: '%{sensitive}s'"
+ "[TCTextCompositionAssistant] : Unsupported language %@ for ReviewOfInput"
+ "[TCTextCompositionAssistant] : proofreading review skipping code-switch sentence"
+ "[TCTextCompositionAssistant] stringContainsPossibleCodeSwitching: consecutive OOV threshold reached (language: %{public}@)"
+ "[TCTextCompositionAssistant] stringContainsPossibleCodeSwitching: knownWords=%{public}lu unknownWords=%{public}lu unknownPercentage=%{public}f ratioExceeded=%{public}d (language: %{public}@)"
+ "errorCode=%{public}ld resultCount=%{public}lu latencyMs=%{public}ld"
- "Calling generative function"
- "Calling generative function for "
- "Calling generative function for PersonalizedSmartReplies"
- "Failed to parse GLP queries from model output"
- "GLP query execution failed"
- "Invalid model output: response cannot be parsed as "
- "PCCAgentCompose"
- "PCCAgentCompose_visionOS"
- "ServerConciseTone.session"
- "ServerFriendlyTone.session"
- "ServerProfessionalTone.session"
- "TextComposer.GLPRetrievalError"
- "UseIFAskPQATool"
- "UseV10ResourceId"
- "UseV10ResourceId_visionOS"
- "[SmartAction] Error querying GLP with error: %@"
- "[SmartAction] Fetching GLP for association: '%{sensitive}s', attribute: '%{sensitive}s'"
- "[SmartAction] No valid queries parsed from %ld generated queries"
- "com.apple.textComposition.BulletsTransform"
- "com.apple.textComposition.TablesTransform"
- "com.apple.textComposition.TakeawaysTransform"
- "system<n> Make the given text into bullet points.<turn_end> user<n> {{ userContent }}<turn_end> assistant<n>"
- "system<n> Make the given text into keypoints.<turn_end> user<n> {{ userContent }}<turn_end> assistant<n>"
- "system<n> Make this text more concise.<turn_end> user<n> {{ userContent }}<turn_end> assistant<n>"
- "system<n> Make this text more friendly.<turn_end> user<n> {{ userContent }}<turn_end> assistant<n>"
- "system<n> Make this text more professional.<turn_end> user<n> {{ userContent }}<turn_end> assistant<n>"
- "system<n> Transform the given text into a table.<turn_end> user<n> {{ userContent }}<turn_end> assistant<n>"
```
