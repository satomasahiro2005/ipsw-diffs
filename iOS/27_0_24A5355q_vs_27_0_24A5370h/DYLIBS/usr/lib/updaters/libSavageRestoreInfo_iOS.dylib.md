## libSavageRestoreInfo_iOS.dylib

> `/usr/lib/updaters/libSavageRestoreInfo_iOS.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8dac` | `0x8e28` | **`+0x7c`** |

### Other Changes

```diff

-7.113.1.0.0
+7.114.0.0.0

-  Functions: 90
+  Functions: 89
Functions:
~ _CreateJasmineIRMeasurementDictVT : 508 -> 520
~ _GetYonkersFabRevisionTags : 308 -> 332
~ _GetYonkersIRFabRevisionTags : 140 -> 148
~ _OUTLINED_FUNCTION_2 : 32 -> 36
~ _OUTLINED_FUNCTION_4 : 16 -> 28
~ _OUTLINED_FUNCTION_6 : 28 -> 24
+ _SavageUpdaterGetTags
- _SavageUpdaterGetTags
- _SavageUpdaterCreateRequestWithLogging
~ __loadAndMeasureVTFile : 408 -> 424
~ _GetJasmineIRMeasurementTags : 512 -> 536
~ _GetYonkersIRxMeasurementTags : 628 -> 656
~ _GetYonkersIRMeasurementTags : 428 -> 432
~ __hexStringToBytes : 240 -> 252
~ _CreateYonkersIRRequestDictForTATSU : 3220 -> 3228
```
