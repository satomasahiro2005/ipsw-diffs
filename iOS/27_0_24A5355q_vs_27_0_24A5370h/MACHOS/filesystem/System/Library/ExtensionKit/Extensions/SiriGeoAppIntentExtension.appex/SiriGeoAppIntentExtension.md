## SiriGeoAppIntentExtension

> `/System/Library/ExtensionKit/Extensions/SiriGeoAppIntentExtension.appex/SiriGeoAppIntentExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0xe70` | `0xe80` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x740` | `0x748` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x750` | `0x758` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.30.13.0.0
+3600.36.4.0.0

-  Functions: 1348
-  Symbols:   3634
+  Functions: 1349
+  Symbols:   3637
Symbols:
+ _$s10AppIntents16IntentValueQueryP23allowedExecutionTargetsAA0cgH0VvgZTq
+ _$s10AppIntents16IntentValueQueryPAAE23allowedExecutionTargetsAA0cgH0VvgZ
+ _$s25SiriGeoAppIntentExtension25ThirdPartyMapsSchemaTypesO11PlaceEntityV0K5QueryV0C7Intents0d5ValueM0AahIP23allowedExecutionTargetsAH0dqR0VvgZTW
Functions:
~ _$ss11_StringGutsV16_deconstructUTF87scratchyXlSg5owner_xSi6lengthSb11usesScratchSb15allocatedMemorytSwSg_ts8_PointerRzlFSV_Tgq5 : 268 -> 264
~ _$s25SiriGeoAppIntentExtension25ThirdPartyMapsSchemaTypesO15PlaceUnionValueO15placeDescriptor0B7Toolbox0kO0Vvg : 56 -> 52
+ _$s25SiriGeoAppIntentExtension25ThirdPartyMapsSchemaTypesO11PlaceEntityV0K5QueryV0C7Intents0d5ValueM0AahIP23allowedExecutionTargetsAH0dqR0VvgZTW
~ _$s25SiriGeoAppIntentExtension25ThirdPartyMapsSchemaTypesO22TransportationTypeEnumO26caseDisplayRepresentations_WZ : 1740 -> 1776
~ _$s25SiriGeoAppIntentExtension25ThirdPartyMapsSchemaTypesO25NavigationPreferencesEnumO26caseDisplayRepresentations_WZ : 2036 -> 2024
~ _$s25SiriGeoAppIntentExtension25ThirdPartyMapsSchemaTypesO14PriceRangeEnumO26caseDisplayRepresentations_WZ : 1776 -> 1756
```
