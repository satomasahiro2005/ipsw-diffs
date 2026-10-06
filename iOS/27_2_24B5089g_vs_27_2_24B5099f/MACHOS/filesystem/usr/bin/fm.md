## fm

> `/usr/bin/fm`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf162c` | `0x104890` | **`+0x13264`** |
| `__TEXT.__cstring` | `0x796a` | `0x81aa` | **`+0x840`** |
| `__TEXT.__const` | `0x60dc` | `0x672c` | **`+0x650`** |
| `__DATA.__bss` | `0x8b00` | `0x9100` | **`+0x600`** |
| `__TEXT.__eh_frame` | `0x5540` | `0x59f0` | **`+0x4b0`** |
| `__DATA_CONST.__const` | `0x41c8` | `0x4480` | **`+0x2b8`** |
| `__DATA.__objc_const` | `0xe20` | `0x10d0` | **`+0x2b0`** |
| `__DATA.__data` | `0x2e08` | `0x30a8` | **`+0x2a0`** |
| `__TEXT.__swift5_fieldmd` | `0x1bf8` | `0x1e20` | **`+0x228`** |
| `__TEXT.__swift5_reflstr` | `0x15a6` | `0x17a6` | **`+0x200`** |
| `__TEXT.__unwind_info` | `0x23f8` | `0x25e0` | **`+0x1e8`** |
| `__TEXT.__auth_stubs` | `0x3620` | `0x3740` | **`+0x120`** |
| `__TEXT.__swift5_typeref` | `0x18b1` | `0x19bd` | **`+0x10c`** |
| `__TEXT.__constg_swiftt` | `0x12ac` | `0x138c` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x9bd` | `0xa8b` | **`+0xce`** |
| `__DATA_CONST.__auth_ptr` | `0x8a0` | `0x960` | **`+0xc0`** |
| `__DATA_CONST.__auth_got` | `0x1b18` | `0x1ba8` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0x9d8` | `0xa38` | **`+0x60`** |
| `__DATA.__common` | `0x430` | `0x480` | **`+0x50`** |
| `__DATA.__objc_data` | `0xf0` | `0x140` | **`+0x50`** |
| `__TEXT.__swift5_assocty` | `0xf0` | `0x140` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x3a4` | `0x3f0` | **`+0x4c`** |
| `__TEXT.__swift_as_ret` | `0x228` | `0x260` | **`+0x38`** |
| `__TEXT.__swift5_proto` | `0x494` | `0x4c4` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `0xdc` | `0x104` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x161` | `0x181` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x124` | `0x140` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x850` | `0x868` | **`+0x18`** |
| `__TEXT.__swift5_mpenum` | `0x40` | `0x58` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x208` | `0x220` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-2.1.7.1.102
+2.1.13.0.0

-  Functions: 2545
-  Symbols:   1308
-  CStrings:  642
+  Functions: 2682
+  Symbols:   1350
+  CStrings:  695
Symbols:
+ _$s10Foundation11FormatStylePAAs8DurationVAAE05UnitsbC0VRszrlE5units7allowed5width16maximumUnitCount09zeroValueE011valueLength14fractionalPartAGShyAG0J0VG_AG0J5WidthVSiSgAG04ZeromE15DisplayStrategyVAtG010FractionalqtU0VtFZ
+ _$s16FoundationModels10TranscriptV14ToolDefinitionV10parametersAA16GenerationSchemaVvg
+ _$s16FoundationModels10TranscriptV14ToolDefinitionV11descriptionSSvg
+ _$s16FoundationModels10TranscriptV14ToolDefinitionV4nameSSvg
+ _$s16FoundationModels10TranscriptV17StructuredSegmentV8rawValueSSvg
+ _$s16FoundationModels16GeneratedContentVAA015ConvertibleFromcD0AAWP
+ _$s16FoundationModels19SystemLanguageModelC10GuardrailsV25overridingInternalUseCaseyAESbF
+ _$s16FoundationModels19SystemLanguageModelC10GuardrailsV5cloudAEvgZ
+ _$s16FoundationModels4ToolP10parametersAA16GenerationSchemaVvgTq
+ _$s16FoundationModels4ToolP11descriptionSSvgTq
+ _$s16FoundationModels4ToolP24_makeDynamicInstructionsyAA01_eF7OutputsVAA9_DSLValueVyxG_AA01_eF6InputsVtFZTq
+ _$s16FoundationModels4ToolP28includesSchemaInInstructionsSbvgTq
+ _$s16FoundationModels4ToolP4call9arguments6OutputQz9ArgumentsQz_tYaKFTq
+ _$s16FoundationModels4ToolP4nameSSvgTq
+ _$s16FoundationModels4ToolP6OutputAC_AA19PromptRepresentableTn
+ _$s16FoundationModels4ToolP9ArgumentsAC_AA31ConvertibleFromGeneratedContentTn
+ _$s16FoundationModels4ToolPAAE24_makeDynamicInstructionsyAA01_eF7OutputsVAA9_DSLValueVyxG_AA01_eF6InputsVtFZ
+ _$s16FoundationModels4ToolPAAE28includesSchemaInInstructionsSbvg
+ _$s22ArgumentParserInternal14EnumerableFlagMp
+ _$s22ArgumentParserInternal14EnumerableFlagP4help3forAA0A4HelpVSgx_tFZTq
+ _$s22ArgumentParserInternal14EnumerableFlagP4name3forAA17NameSpecificationVx_tFZTq
+ _$s22ArgumentParserInternal14EnumerableFlagPAAE4help3forAA0A4HelpVSgx_tFZ
+ _$s22ArgumentParserInternal14EnumerableFlagPSQTb
+ _$s22ArgumentParserInternal14EnumerableFlagPs12CaseIterableTb
+ _$s22ArgumentParserInternal15FlagExclusivityV9exclusiveACvgZ
+ _$s22ArgumentParserInternal4FlagV11exclusivity4helpACyqd__SgGAA0D11ExclusivityV_AA0A4HelpVSgtcAFRszAA010EnumerableD0Rd__lufC
+ _$s22ArgumentParserInternal4FlagVAASbSgRszlE4name9inversion11exclusivity4helpACyADGAA17NameSpecificationV_AA0D9InversionVAA0D11ExclusivityVAA0A4HelpVSgtcfC
+ _$s6Output16FoundationModels4ToolPTl
+ _$s9Arguments16FoundationModels4ToolPTl
+ _$sSJ16wholeNumberValueSiSgvg
+ _$sSL1goiySbx_xtFZTq
+ _$sSL1loiySbx_xtFZTq
+ _$sSL2geoiySbx_xtFZTq
+ _$sSL2leoiySbx_xtFZTq
+ _$sSLMp
+ _$sSLSQTb
+ _$sSb22ArgumentParserInternal013ExpressibleByA0AAWP
+ _$ss15ContinuousClockV7InstantV3nowADvgZ
+ _$ss22KeyedDecodingContainerV15decodeIfPresent_6forKeySbSgSbm_xtKF
+ _$ss22KeyedEncodingContainerV15encodeIfPresent_6forKeyySbSg_xtKF
+ _$ss24_getErrorEmbeddedNSErroryyXlSgxs0B0RzlF
+ _$ss5NeverO16FoundationModels19PromptRepresentableACWP
+ _$ss8DurationV10FoundationE16UnitsFormatStyleV9UnitWidthV4wideAGvgZ
- _$s16FoundationModels20LanguageModelSessionC5model19transcriptWithToolsACx_AA10TranscriptVtcAA0cD0RzlufC
CStrings:
+ "' and is the only thing that can run it. Generation that may call it has to be driven with 'next', which returns calls unexecuted."
+ "' is not enabled. Use /tools to list active tools."
+ "' is not one this build knows"
+ "--[no-]ax-screen-reader"
+ "--set-ax-bell <b>"
+ "--set-ax-screen-reader"
+ "--set-no-ax-screen-reader"
+ "/model requires a model name."
+ "/resume requires a session name."
+ "Available: system, pcc."
+ "Context window size is not available for model '"
+ "Current instructions: "
+ "Failed to save session: "
+ "Failed to switch to '"
+ "Instructions set."
+ "Later turns may be refused — /save to keep history, then /clear to start fresh."
+ "No saved sessions."
+ "No tokens counted yet. The count starts after your next message."
+ "Or resume one by name with /resume <name>."
+ "Or switch by name with /model <name>. Currently on '"
+ "Persist screen reader mode off"
+ "Persist screen reader mode on"
+ "Persist the screen reader completion bell (true or false)"
+ "Persist whether screen reader mode rings the bell when a slow turn finishes"
+ "Picking one turns it on or off. Or use /tools add <name> and /tools remove <name>."
+ "Render output for a screen reader: plain lines, no animation or cursor redrawing"
+ "Render plain lines for a screen reader"
+ "Saved session as '"
+ "Screen reader completion bell set to "
+ "Screen reader mode set to "
+ "Set them with /instructions <text>."
+ "Show context window usage"
+ "Show token usage"
+ "Skipping license check. Detected internal build."
+ "Started a new session."
+ "The --set- options write settings and exit. They can be combined with each other, but not with options that start a chat session."
+ "The client declared '"
+ "There is no choice "
+ "Type 'exit' or press Ctrl+D to leave."
+ "Type a number to pick one."
+ "Unknown command '"
+ "Use /save if you want to keep this conversation."
+ "Use /sessions to list saved sessions."
+ "_TtC2fm9BasicREPL"
+ "announcedThreshold"
+ "ax-screen-reader"
+ "axScreenReaderSetting"
+ "contextSize"
+ "isBellEnabled"
+ "isInScreenReaderMode"
+ "less than a second"
+ "or type something else to leave the "
+ "pendingOutput"
+ "pendingSelection"
+ "progressNoticeStart"
+ "resumeName"
+ "set-ax-screen-reader"
+ "set-no-ax-screen-reader"
- " fm> [Cancelled.]\n"
- "--set-default-model must be used on its own."
- "/model requires a model name (system, pcc, or a model provider model)"
- "/resume requires a session name. Use /sessions to list saved sessions."
- "Warning: Failed to save session: "
```
