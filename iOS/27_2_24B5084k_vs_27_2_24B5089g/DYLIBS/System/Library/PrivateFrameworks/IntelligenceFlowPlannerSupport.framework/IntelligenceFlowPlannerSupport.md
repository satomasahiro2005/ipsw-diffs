## IntelligenceFlowPlannerSupport

> `/System/Library/PrivateFrameworks/IntelligenceFlowPlannerSupport.framework/IntelligenceFlowPlannerSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10374bc` | `0x104b9c8` | **`+0x1450c`** |
| `__DATA_DIRTY.__bss` | `0x47980` | `0x4c380` | **`+0x4a00`** |
| `__DATA.__bss` | `0x11b508` | `0x1171f8` | **`-0x4310`** |
| `__DATA_DIRTY.__data` | `0x1ef00` | `0x22d50` | **`+0x3e50`** |
| `__AUTH.__data` | `0x1b1a8` | `0x189a0` | **`-0x2808`** |
| `__DATA.__data` | `0x17d70` | `0x16bf0` | **`-0x1180`** |
| `__TEXT.__eh_frame` | `0xb7b7c` | `0xb85e4` | **`+0xa68`** |
| `__TEXT.__const` | `0xc97a8` | `0xc9fb8` | **`+0x810`** |
| `__AUTH_CONST.__const` | `0x8ef28` | `0x8f730` | **`+0x808`** |
| `__TEXT.__unwind_info` | `0x46648` | `0x45fc0` | **`-0x688`** |
| `__TEXT.__oslogstring` | `0x21bf9` | `0x221e0` | **`+0x5e7`** |
| `__TEXT.__cstring` | `0x2d11f` | `0x2d47f` | **`+0x360`** |
| `__TEXT.__swift5_typeref` | `0x2737e` | `0x27668` | **`+0x2ea`** |
| `__TEXT.__swift5_fieldmd` | `0x237e8` | `0x23a98` | **`+0x2b0`** |
| `__TEXT.__constg_swiftt` | `0x1e1f8` | `0x1e47c` | **`+0x284`** |
| `__TEXT.__swift5_reflstr` | `0x127f6` | `0x12a16` | **`+0x220`** |
| `__AUTH_CONST.__auth_got` | `0x1b640` | `0x1b7d0` | **`+0x190`** |
| `__AUTH_CONST.__objc_const` | `0x7370` | `0x7440` | **`+0xd0`** |
| `__TEXT.__swift5_capture` | `0xc548` | `0xc5f4` | **`+0xac`** |
| `__DATA_DIRTY.__objc_data` | `0x488` | `0x528` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1620` | `0x16a8` | **`+0x88`** |
| `__DATA_DIRTY.__common` | `0xb60` | `0xbd8` | **`+0x78`** |
| `__TEXT.__swift_as_cont` | `0x6940` | `0x69b8` | **`+0x78`** |
| `__TEXT.__swift_as_ret` | `0x4f58` | `0x4fb4` | **`+0x5c`** |
| `__AUTH.__objc_data` | `0xa0` | `0x50` | **`-0x50`** |
| `__TEXT.__swift_as_entry` | `0x3944` | `0x3990` | **`+0x4c`** |
| `__DATA.__common` | `0x298` | `0x250` | **`-0x48`** |
| `__TEXT.__swift5_proto` | `0xe058` | `0xe09c` | **`+0x44`** |
| `__TEXT.__swift5_types` | `0x3228` | `0x3264` | **`+0x3c`** |
| `__TEXT.__swift5_builtin` | `0x438` | `0x44c` | **`+0x14`** |
| `__TEXT.__swift5_mpenum` | `0x218` | `0x22c` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x568` | `0x570` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x1b8` | `0x1bc` | **`+0x4`** |

### Other Changes

```diff

-3605.14.3.501.4
+3605.16.9.501.1

+  - /System/Library/PrivateFrameworks/CDMFoundation.framework/CDMFoundation

+  - /System/Library/PrivateFrameworks/LinkMetadata.framework/LinkMetadata

+  - /System/Library/PrivateFrameworks/SiriNLUTypes.framework/SiriNLUTypes

-  Functions: 103930
-  Symbols:   957
-  CStrings:  5688
+  Functions: 104343
+  Symbols:   977
+  CStrings:  5727
Symbols:
+ _APP_SANDBOX_READ
+ _OBJC_CLASS_$_CDMClient
+ _OBJC_CLASS_$_LNAssistantDefinedSchemaConformance
+ _OBJC_CLASS_$_LNAutoShortcut
+ _OBJC_CLASS_$_LNAutoShortcutLocalizedPhrase
+ _OBJC_CLASS_$_LNAutoShortcutsProvider
+ _OBJC_CLASS_$_LNMetadataProvider
+ _OBJC_CLASS_$_PLANNERTOOLSSchemaPLANNERTOOLSEntityRef
+ _OBJC_CLASS_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionErrorResult
+ _OBJC_CLASS_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionGeneralResult
+ _OBJC_CLASS_$_PLANNERTOOLSSchemaPLANNERTOOLSExecutionSuccessResult
+ _OBJC_CLASS_$_SASchemaSARemoteSearchCanceled
+ _OBJC_CLASS_$_SASchemaSARemoteSearchContext
+ _OBJC_CLASS_$_SASchemaSARemoteSearchEnded
+ _OBJC_CLASS_$_SASchemaSARemoteSearchFailed
+ _OBJC_CLASS_$_SASchemaSARemoteSearchStarted
+ _SANDBOX_EXTENSION_DEFAULT
+ __CFURLAttachSecurityScopeToFileURL
+ _objc_retain_x1
+ _strlen
CStrings:
+ " are already available — call them directly instead of loading them."
+ "%s %s: MessagesCustomReaction resolution failed, falling back to MessagesTapback: %@"
+ "Audio.RecognizeAudio@%s unsupported on device idiom %{public}s"
+ "FuzzyShortcutMatcher cannot extract identifiers against missing parse"
+ "FuzzyShortcutMatcher cannot match shortcut; CDMClient error: %s"
+ "FuzzyShortcutMatcher classifies `%{sensitive}s` as a non-schematized app intent match."
+ "FuzzyShortcutMatcher classifies `%{sensitive}s` as a schematized app intent match."
+ "FuzzyShortcutMatcher could not check for a shortcut: %s"
+ "FuzzyShortcutMatcher didn't classify `%{sensitive}s` as a shortcut because LinkServices doesn't see it."
+ "FuzzyShortcutMatcher does not classify `%{sensitive}s` as a shortcut."
+ "FuzzyShortcutMatcher extracted identifiers count: %ld"
+ "FuzzyShortcutMatcher had a problem with LinkServices looking for %{private}s shortcuts.  Underlying error is %s."
+ "FuzzyShortcutMatcher warmup failed: %s"
+ "FuzzyShortcutMatcher.fuzzyMatch"
+ "FuzzyShortcutMatcher.isSchematized"
+ "FuzzyShortcutMatcher.lookUpAppIntent"
+ "FuzzyShortcutMatcher.setupCDMShortcutDetector"
+ "Song recognition is not supported."
+ "The user is performing a request that requires their personal device, but that device's software is too old to handle it. Ask them to update it."
+ "User made a personal request but their companion's OS predates Linwood companion support, so no companion runtime exists for them."
+ "[FuzzyShortcutMatcher] - Action conformingSchemas: %s"
+ "[FuzzyShortcutMatcher] - assistantDefinedSchemas is empty array"
+ "[FuzzyShortcutMatcher] - assistantDefinedSchemas is nil"
+ "[StagedFileSecurityScope] sandbox_extension_issue_file failed: errno=%{public}d"
+ "[TrafficClassifier] no calibrated tau for locale=%{public}s - route_pegasus is unreachable."
+ "[TrafficClassifier] pegasus tau for %{public}s: %{public}f"
+ "alreadyAvailableTools"
+ "already_available_tools were already in the prompt — invoke them directly."
+ "code kind "
+ "companionOSNotSupported"
+ "error"
+ "error=%{public}s"
+ "error=nil"
+ "general"
+ "locale=%s"
+ "plannertool.result_ref"
+ "remote search request failed"
+ "resolveReactionEnum(query:bundleId:context:)"
+ "result=%{bool,public}d"
+ "unknown_tools do not exist; take names from the Toolbox Catalog rather than guessing."
+ "use_in_conjunction"
- ". Do not retry these — check the Toolbox Catalog for correct names."
- "Success. Note: the following tool names were not found and do not exist: "
```
