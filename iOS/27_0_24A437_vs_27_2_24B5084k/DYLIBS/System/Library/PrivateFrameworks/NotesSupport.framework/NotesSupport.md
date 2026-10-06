## NotesSupport

> `/System/Library/PrivateFrameworks/NotesSupport.framework/NotesSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x585dc` | `0x584fc` | **`-0xe0`** |
| `__TEXT.__oslogstring` | `0x4496` | `0x4526` | **`+0x90`** |
| `__AUTH_CONST.__const` | `0x16a0` | `0x1620` | **`-0x80`** |
| `__AUTH_CONST.__cfstring` | `0x4640` | `0x45e0` | **`-0x60`** |
| `__TEXT.__cstring` | `0x4749` | `0x4709` | **`-0x40`** |
| `__DATA_DIRTY.__bss` | `0x741` | `0x709` | **`-0x38`** |
| `__TEXT.__objc_methlist` | `0x4460` | `0x4480` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x13a8` | `0x1390` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3258` | `0x3270` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1d48` | `0x1d30` | **`-0x18`** |
| `__DATA.__data` | `0x6f4` | `0x704` | **`+0x10`** |
| `__TEXT.__const` | `0xb5c` | `0xb6c` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x7a0` | `0x7b0` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0xec` | `0xde` | **`-0xe`** |
| `__TEXT.__swift_as_cont` | `0x2c` | `0x30` | **`+0x4`** |

### Other Changes

```diff

-3001.2.2.0.0
+3001.40.8.100.1

-  Functions: 2578
-  Symbols:   3789
-  CStrings:  1080
+  Functions: 2565
+  Symbols:   3768
+  CStrings:  1068
Symbols:
+ -[ICCDCSIReindexer fullyStagedSinceLastReindex]
+ -[NSString(IC) ic_rangeIsCaretAtLineStart:]
+ GCC_except_table63
+ GCC_except_table65
+ _ICInternalSettingsAddSummaryToNoteIncludesTitleAndDate
+ _ICInternalSettingsIsAddSummaryToNoteMenuItemEnabled
+ _kICAddSummaryToNoteIncludesTitleAndDate
+ _kICEnableAddSummaryToNoteMenuItem
+ _kICSummarizationStructureMode
+ _swift_release_x9
- GCC_except_table62
- _ICInternalSettingsIsAppleAccountBrandingEnabled
- _ICInternalSettingsIsBlockQuoteEnabled
- _ICInternalSettingsIsBlockQuoteEnabled.isEnabled
- _ICInternalSettingsIsBlockQuoteEnabled.onceToken
- _ICInternalSettingsIsCollapsibleSectionsEnabled
- _ICInternalSettingsIsCollapsibleSectionsEnabled.isEnabled
- _ICInternalSettingsIsCollapsibleSectionsEnabled.onceToken
- _ICInternalSettingsIsEmphasisEnabled
- _ICInternalSettingsIsGraphingEnabled
- _ICInternalSettingsIsGreyParrotEnabled
- _ICInternalSettingsIsMathEnabled
- _ICInternalSettingsIsMathEnabled.isEnabled
- _ICInternalSettingsIsMathEnabled.onceToken
- _ICInternalSettingsIsNotesMathEnabled
- _ICInternalSettingsIsPaperKitMathEnabled
- _ICInternalSettingsIsScrubbingEnabled
- _ICInternalSettingsIsTextKit2Enabled
- _ICInternalSettingsIsTextKit2Enabled.isEnabled
- _ICInternalSettingsIsTextKit2Enabled.onceToken
- ___ICInternalSettingsIsBlockQuoteEnabled_block_invoke
- ___ICInternalSettingsIsCollapsibleSectionsEnabled_block_invoke
- ___ICInternalSettingsIsMathEnabled_block_invoke
- ___ICInternalSettingsIsTextKit2Enabled_block_invoke
- _kICEnableBlockQuote
- _kICEnableCollapsibleSections
- _kICEnableEmphasis
- _kICEnableMath
- _kICEnableScrubbing
- _kICEnableTextKit2
- _swift_release_x10
CStrings:
+ "AddSummaryToNoteIncludesTitleAndDate"
+ "EnableAddSummaryToNoteMenuItem"
+ "ICGeneralASRAvailabilityDidBecomeAvailable"
+ "PersonaDebug: performBlockInPersonaContext {accountID: %@, accountPersonaID: %@, currentPersona: %@ (unique:%@, type:%lu), sandboxMode: %@}"
+ "internalSettings.summarizationStructureMode"
- "AABranding"
- "AppleAccount"
- "BlockQuote"
- "CollapsibleSections"
- "Emphasis"
- "EnableBlockQuote"
- "EnableCollapsibleSections"
- "EnableEmphasis"
- "EnableMath"
- "EnableScrubbing"
- "EnableTextKit2"
- "Graphing"
- "GreyParrot"
- "Math"
- "MathPaper"
- "Scrubbing"
- "TextKit2"
```
