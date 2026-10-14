## SiriFindMy

> `/System/Library/PrivateFrameworks/SiriFindMy.framework/SiriFindMy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x191a2c` | `0x16d52c` | **`-0x24500`** |
| `__TEXT.__eh_frame` | `0xb7d4` | `0xc09c` | **`+0x8c8`** |
| `__AUTH_CONST.__const` | `0xed40` | `0xe548` | **`-0x7f8`** |
| `__TEXT.__swift5_capture` | `0x1d74` | `0x1864` | **`-0x510`** |
| `__TEXT.__oslogstring` | `0x77f5` | `0x7b35` | **`+0x340`** |
| `__TEXT.__swift_as_cont` | `0xb5c` | `0x8b8` | **`-0x2a4`** |
| `__TEXT.__swift_as_ret` | `0x960` | `0x6f4` | **`-0x26c`** |
| `__TEXT.__const` | `0x14f58` | `0x15148` | **`+0x1f0`** |
| `__DATA.__bss` | `0x1a800` | `0x1a980` | **`+0x180`** |
| `__TEXT.__swift5_typeref` | `0x7cc0` | `0x7d88` | **`+0xc8`** |
| `__DATA.__data` | `0x54d8` | `0x5588` | **`+0xb0`** |
| `__AUTH_CONST.__auth_got` | `0x2740` | `0x27e0` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x6a80` | `0x6a10` | **`-0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x50f4` | `0x5160` | **`+0x6c`** |
| `__TEXT.__constg_swiftt` | `0x5e8c` | `0x5ee8` | **`+0x5c`** |
| `__TEXT.__swift5_assocty` | `0xba8` | `0xbf0` | **`+0x48`** |
| `__TEXT.__cstring` | `0x2913` | `0x2953` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x3c18` | `0x3c48` | **`+0x30`** |
| `__DATA.__common` | `0x510` | `0x528` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1408` | `0x1420` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0xf30` | `0xf3c` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x628` | `0x634` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x5c8` | `0x5d4` | **`+0xc`** |
| `__AUTH.__objc_data` | `0x1e18` | `0x1e20` | **`+0x8`** |

### Other Changes

```diff

-3605.18.1.0.0
+3605.19.1.0.0

+  - /System/Library/PrivateFrameworks/LinkServices.framework/LinkServices

-  Functions: 10921
-  Symbols:   3094
-  CStrings:  817
+  Functions: 10493
+  Symbols:   3108
+  CStrings:  829
Symbols:
+ _OBJC_CLASS_$_LNEnvironment
+ _OBJC_CLASS_$_NSUserActivity
+ ___swift_closure_destructor.14Tm
+ _objc_retain_x9
+ _symbolic $s18AppIntentsServices0A20IntentRepresentationP
+ _symbolic _____ 10SiriFindMy29PlaySoundIntentRepresentationV
+ _symbolic _____ 10SiriFindMy30OpenModuleIntentRepresentationV
+ _symbolic _____ 10SiriFindMy30OpenPersonIntentRepresentationV
+ _symbolic _____Sg 10Foundation4UUIDV
+ _symbolic _____Sg 13SiriUtilities11DeviceIdiomO
+ _symbolic _____Sg 18AppIntentsServices18SnippetEnvironmentV
+ _symbolic _____Sg 22UniformTypeIdentifiers6UTTypeV
+ _symbolic _____Sg_ABt 13SiriUtilities11DeviceIdiomO
+ _symbolic ______p 18AppIntentsServices0A20IntentRepresentationP
+ _symbolic ______pSg 18AppIntentsServices0A20IntentRepresentationP
+ _symbolic _____y_____G 18AppIntentsServices0A19IntentSuccessResultV s5NeverO
+ _symbolic _____y_____G 18AppIntentsServices12IntentOutputV s5NeverO
+ _symbolic _____y_____G 18AppIntentsServices15IntentParameterC 10SiriFindMy24ItemEntityRepresentationC
+ _symbolic _____y______yptG s23_ContiguousArrayStorageC s11AnyHashableV
+ _type_layout_string 10SiriFindMy29PlaySoundIntentRepresentationV
+ _type_layout_string 10SiriFindMy30OpenModuleIntentRepresentationV
+ _type_layout_string 10SiriFindMy30OpenPersonIntentRepresentationV
- _OUTLINED_FUNCTION_136
- _OUTLINED_FUNCTION_137
- _OUTLINED_FUNCTION_138
- _OUTLINED_FUNCTION_139
- _OUTLINED_FUNCTION_140
- ___swift_closure_destructor.102Tm
- ___swift_closure_destructor.12Tm
- ___swift_closure_destructor.8Tm
CStrings:
+ "AppIntentsSpecification is nil. Returning..."
+ "Device is not a watch or a home accessory, sending empty pre handle intent output."
+ "Device is on a home accessory. We will not speak the failure message because we have opened up the person module on the accessory"
+ "Failed to produce output with app intent. %s - %s."
+ "Home Accessory requires us to call an appIntent to play sound"
+ "OpenModuleIntent"
+ "OpenPersonIntent"
+ "Request is running on home accessory. Performing local perform of intents..."
+ "Request originated from personal request device (HomeAccessory/HomePod), skipping unlock check."
+ "Sending dialog with app intent representation instead of snippet: %s"
+ "Sending dialog with app intent specification instead of snippet: %s"
+ "There was an error performing local perform of intent: %s."
+ "UnifiedIdentifier seems to be empty. Returning a failure message..."
- "Device is not a watch, sending empty pre handle intent output."
```
