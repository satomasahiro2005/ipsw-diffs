## PhoneSuggestions

> `/System/Library/Siri/DM/SiriSuggestions/Owners/PhoneSuggestions.bundle/PhoneSuggestions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9e24` | `0x9e10` | **`-0x14`** |
| `__TEXT.__auth_stubs` | `0xa10` | `0xa20` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x510` | `0x518` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.32.7.0.0
+3600.38.6.0.0

-  Functions: 383
+  Functions: 382
Symbols:
+ _objc_release_x24
- _OUTLINED_FUNCTION_41
Functions:
~ _$s16PhoneSuggestions22ResolveStartCallParamsC16resolveParameter9parameter10suggestion11interaction11environmentSayypG04SiriB3Kit010ResolvableH0C_AJ19CandidateSuggestion_pAJ11Interaction_pAJ19EnvironmentSnapshot_ptYaFTY6_ : 4920 -> 4896
~ _$sSTsSQ7ElementRpzrlE8containsySbABFSaySSG_Tg5 : 112 -> 128
~ _$ss15_arrayForceCastySayq_GSayxGr0_lF16PhoneSuggestions25StartCallSuggestionParamsV_ypTg5 : 268 -> 280
~ _$s16PhoneSuggestions22ResolveStartCallParamsC13getPersonName33_9F3EE7A6F073E610217CE4D11DC5618CLL11suggestionsSSSgyp_tF : 632 -> 648
~ _$ss11_StringGutsV16_deconstructUTF87scratchyXlSg5owner_xSi6lengthSb11usesScratchSb15allocatedMemorytSwSg_ts8_PointerRzlFSV_Tgq5 : 268 -> 264
~ _OUTLINED_FUNCTION_9 : 16 -> 12
+ _OUTLINED_FUNCTION_11
- _OUTLINED_FUNCTION_17
~ _OUTLINED_FUNCTION_29 : 36 -> 32
~ _OUTLINED_FUNCTION_30 : 32 -> 24
~ _OUTLINED_FUNCTION_32 : 24 -> 20
~ _OUTLINED_FUNCTION_33 : 20 -> 12
~ _OUTLINED_FUNCTION_34 : 12 -> 20
~ _OUTLINED_FUNCTION_35 : 20 -> 32
~ _OUTLINED_FUNCTION_39 : 32 -> 24
- _OUTLINED_FUNCTION_41
```
