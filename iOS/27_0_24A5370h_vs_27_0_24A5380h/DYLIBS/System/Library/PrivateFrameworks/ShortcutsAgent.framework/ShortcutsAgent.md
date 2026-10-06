## ShortcutsAgent

> `/System/Library/PrivateFrameworks/ShortcutsAgent.framework/ShortcutsAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2aa4` | `0xa6154` | **`+0x36b0`** |
| `__DATA_DIRTY.__bss` | `0x100` | `0x800` | **`+0x700`** |
| `__DATA.__bss` | `0x13330` | `0x12ec0` | **`-0x470`** |
| `__DATA_DIRTY.__data` | `0x588` | `0x898` | **`+0x310`** |
| `__TEXT.__const` | `0xbdd0` | `0xc0b0` | **`+0x2e0`** |
| `__AUTH_CONST.__const` | `0x6da8` | `0x7008` | **`+0x260`** |
| `__AUTH.__data` | `0x1798` | `0x15b0` | **`-0x1e8`** |
| `__TEXT.__oslogstring` | `0xea6` | `0xcd6` | **`-0x1d0`** |
| `__TEXT.__swift5_typeref` | `0x33b8` | `0x34e6` | **`+0x12e`** |
| `__TEXT.__unwind_info` | `0x34f0` | `0x3608` | **`+0x118`** |
| `__TEXT.__swift5_reflstr` | `0x1777` | `0x1887` | **`+0x110`** |
| `__AUTH_CONST.__auth_got` | `0x16b8` | `0x17b8` | **`+0x100`** |
| `__TEXT.__swift5_fieldmd` | `0x26dc` | `0x2780` | **`+0xa4`** |
| `__DATA.__data` | `0x2e48` | `0x2db8` | **`-0x90`** |
| `__TEXT.__constg_swiftt` | `0x2894` | `0x2904` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x64e4` | `0x6554` | **`+0x70`** |
| `__AUTH.__objc_data` | `0xa0` | `0x50` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0xf0` | `0x140` | **`+0x50`** |
| `__TEXT.__swift5_assocty` | `0x5d8` | `0x608` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0xd98` | `0xdb8` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1f8` | `0x218` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x12c` | `0x140` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x9cc` | `0x9e0` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x388` | `0x398` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x67c` | `0x68c` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x338` | `0x344` | **`+0xc`** |
| `__DATA_DIRTY.__common` | `0x10` | `0x18` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-5028.0.21.0.0
+5032.5.0.0.0

+  - /System/Library/Frameworks/Intents.framework/Intents

-  Functions: 5285
-  Symbols:   1850
-  CStrings:  256
+  Functions: 5384
+  Symbols:   1873
+  CStrings:  251
Symbols:
+ _INEditDistanceBetweenStrings
+ _OBJC_CLASS_$_WFGenerativeShortcutsAvailabilityProvider
+ _OBJC_CLASS_$_WFWorkflowIcon
+ _WFGlyphCharacterForSystemImageName
+ _WFGlyphCharactersInSection
+ _WFSystemImageNameForGlyphCharacter
+ _associated conformance 14ShortcutsAgent12DaSErrorCodeOSHAASQ
+ _associated conformance 14ShortcutsAgent12DaSErrorCodeOSLAASQ
+ _associated conformance 14ShortcutsAgent12DaSErrorCodeOs12CaseIterableAA8AllCasessADP_Sl
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
+ _symbolic SJ
+ _symbolic SS14messageForUser_Sb24requiresThirdPartyActionSSSg14suggestedQueryt
+ _symbolic SS4name_Si8distancet
+ _symbolic SaySS4name_Si8distancetG
+ _symbolic SaySo8NSNumberCG
+ _symbolic Say_____G 14ShortcutsAgent12DaSErrorCodeO
+ _symbolic Say_____G7options_SSSg19renderedProgramNodet 14ShortcutsAgent10PickOptionO
+ _symbolic _____ 14ShortcutsAgent12DaSErrorCodeO
+ _symbolic _____ 14ShortcutsAgent16ModelCallMetricsV
+ _symbolic _____ So16WFGlyphCharacterV
+ _symbolic _____ySS4name_Si8distancetG 10Foundation17KeyPathComparatorV
+ _symbolic _____ySS4name_Si8distancetG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G s15EmptyCollectionV s7UnicodeO6ScalarV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So16WFGlyphCharacterV
+ _type_layout_string 14ShortcutsAgent16ModelCallMetricsV
- ___swift_memcpy57_8
- _symbolic Say_____G7options_t 14ShortcutsAgent10PickOptionO
CStrings:
+ "  (no close matches found)"
+ "Catalog entries: "
+ "Rendered program node string: %s"
+ "iconValidation"
+ "renderedProgramNode"
- ", show_step_by_step_bullets: "
- "Generative Shortcuts is restricted due to assetNotReady"
- "Generative Shortcuts is unavailable due to %s"
- "Generative Shortcuts not available due to unknown state"
- "Generative Shortcuts not available due to use case availability"
- "Generative experience disabled via WFManuallyDisableGenerativeExperience user default"
- "IgnoreAppleIntelligenceState"
- "WFManuallyDisableGenerativeExperience"
- "isGenerativeUseCaseEnabled returns false because feature flag is not enabled"
- "isGenerativeUseCaseEnabled returns true because IgnoreAppleIntelligenceState is set to true"
```
