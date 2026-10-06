## MagnifierSupport

> `/System/Library/PrivateFrameworks/MagnifierSupport.framework/MagnifierSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x400704` | `0x3ff62c` | **`-0x10d8`** |
| `__DATA.__bss` | `0x1b728` | `0x1b5b8` | **`-0x170`** |
| `__TEXT.__const` | `0x227b0` | `0x22640` | **`-0x170`** |
| `__TEXT.__eh_frame` | `0x14408` | `0x142c8` | **`-0x140`** |
| `__AUTH_CONST.__const` | `0x19d98` | `0x19cf8` | **`-0xa0`** |
| `__TEXT.__swift5_typeref` | `0x1be40` | `0x1bda2` | **`-0x9e`** |
| `__TEXT.__cstring` | `0xf32a` | `0xf2ca` | **`-0x60`** |
| `__TEXT.__unwind_info` | `0xc618` | `0xc5c0` | **`-0x58`** |
| `__DATA.__data` | `0x99e0` | `0x9990` | **`-0x50`** |
| `__TEXT.__constg_swiftt` | `0xbad8` | `0xba8c` | **`-0x4c`** |
| `__TEXT.__swift5_capture` | `0x5724` | `0x56ec` | **`-0x38`** |
| `__TEXT.__oslogstring` | `0x75c4` | `0x7594` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0xdd27` | `0xdcf7` | **`-0x30`** |
| `__AUTH.__data` | `0x6490` | `0x64b0` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x13038` | `0x13058` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xa10` | `0xa30` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x19d8` | `0x19b8` | **`-0x20`** |
| `__DATA.__common` | `0x9e0` | `0x9c8` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x4318` | `0x4330` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x3a58` | `0x3a68` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x98e0` | `0x98d0` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0xf80` | `0xf70` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0xed0` | `0xec4` | **`-0xc`** |
| `__TEXT.__swift_as_entry` | `0x54c` | `0x540` | **`-0xc`** |
| `__DATA_DIRTY.__objc_data` | `0x3b48` | `0x3b50` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x614` | `0x60c` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x80c` | `0x808` | **`-0x4`** |

### Other Changes

```diff

-291.4.2.0.0
+291.4.4.0.0

-  Functions: 17189
-  Symbols:   6327
-  CStrings:  1942
+  Functions: 17172
+  Symbols:   6316
+  CStrings:  1938
Symbols:
+ _AXDeviceIsViridian
+ _AXGenerativeModelAssetsReady
+ _OBJC_CLASS_$_AXLiveRecognitionAskParameters
+ ___swift_closure_destructor.105Tm
+ ___swift_closure_destructor.55Tm
- ___swift_closure_destructor.103Tm
- ___swift_closure_destructor.58Tm
- _associated conformance 16MagnifierSupport20FindSessionAppIntentV0E7Intents0eF0AA13PerformResultAdEP_AD0fI0
- _associated conformance 16MagnifierSupport20FindSessionAppIntentV0E7Intents0eF0AA14SummaryContentAdEP_AD09ParameterH0
- _associated conformance 16MagnifierSupport20FindSessionAppIntentV0E7Intents0eF0AaD09_SupportsE12Dependencies
- _associated conformance 16MagnifierSupport20FindSessionAppIntentV0E7Intents0eF0AaD24PersistentlyIdentifiable
- _get_witness_table 10AppIntents22IntentParameterSummaryVy16MagnifierSupport011FindSessionaC0VGAA0dE0HPyHC
- _symbolic _____ 16MagnifierSupport20FindSessionAppIntentV
- _symbolic _____y_____G 10AppIntents0A14ShortcutPhraseV 16MagnifierSupport011FindSessionA6IntentV
- _symbolic _____y_____G 10AppIntents22IntentParameterSummaryV 16MagnifierSupport011FindSessionaC0V
- _symbolic _____y_____G 10AppIntents22ParameterSummaryStringV 16MagnifierSupport011FindSessionA6IntentV
- _symbolic _____y______G 10AppIntents0A14ShortcutPhraseV19StringInterpolationV 16MagnifierSupport011FindSessionA6IntentV
- _symbolic _____y______G 10AppIntents22ParameterSummaryStringV0E13InterpolationV 16MagnifierSupport011FindSessionA6IntentV
- _symbolic _____y__________ySSGG s7KeyPathC 16MagnifierSupport20FindSessionAppIntentV 0G7Intents0H9ParameterC
- _symbolic _____y_____y_____GG s23_ContiguousArrayStorageC 10AppIntents0D14ShortcutPhraseV 16MagnifierSupport011FindSessionD6IntentV
- _type_layout_string 16MagnifierSupport20FindSessionAppIntentV
CStrings:
- " in the current camera view."
- "Could not complete FindSessionAppIntent: %@"
- "FIND_SESSION_APP_INTENT_TITLE"
- "magnifyingglass.circle.fill"
```
