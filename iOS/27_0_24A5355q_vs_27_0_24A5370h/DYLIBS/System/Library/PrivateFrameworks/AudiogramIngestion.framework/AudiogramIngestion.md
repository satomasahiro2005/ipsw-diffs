## AudiogramIngestion

> `/System/Library/PrivateFrameworks/AudiogramIngestion.framework/AudiogramIngestion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x488f0` | `0x48b24` | **`+0x234`** |
| `__AUTH_CONST.__cfstring` | `0x1c20` | `0x1c40` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2298` | `0x22b0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x11ac` | `0x11b8` | **`+0xc`** |
| `__TEXT.__cstring` | `0x246e` | `0x2474` | **`+0x6`** |

### Other Changes

```diff

-527.0.0.0.0
+530.0.0.0.0

-  CStrings:  541
+  CStrings:  542
Symbols:
+ -[AIAudiogramIndividualFrequencyInputViewController headerBackgroundView]
+ -[AIAudiogramIndividualFrequencyInputViewController setHeaderBackgroundView:]
+ _OBJC_IVAR_$_AIAudiogramIndividualFrequencyInputViewController._headerBackgroundView
- -[AIAudiogramIndividualFrequencyInputViewController didAddBackgroundLayer]
- -[AIAudiogramIndividualFrequencyInputViewController setDidAddBackgroundLayer:]
- _OBJC_IVAR_$_AIAudiogramIndividualFrequencyInputViewController._didAddBackgroundLayer
Functions:
~ -[AIAudiogramIndividualFrequencyInputViewController viewDidLoad] : 2756 -> 3380
~ -[AIAudiogramIndividualFrequencyInputViewController viewWillAppear:] : 472 -> 240
~ ___93-[AIAudiogramIndividualFrequencyInputViewController earCellForTableView:atIndexPath:withEar:]_block_invoke : 532 -> 528
~ -[AIAudiogramIndividualFrequencyInputViewController .cxx_destruct] : 336 -> 356
~ -[AIAudiogramFinalResultViewController _updateMaxHearingLevelWidth] : 1168 -> 1164
~ ___72-[AIAudiogramFinalResultViewController tableView:cellForRowAtIndexPath:]_block_invoke_2 : 228 -> 220
~ ___62-[AIAudiogramIngestionEngine _audiogramMapFromRecognizedText:]_block_invoke : 96 -> 92
~ ___60-[AIAudiogramIngestionEngine _audiogramFromAudiogramPoints:]_block_invoke : 1220 -> 1216
~ -[AIAudiogramFrequencyInputCell setLeftEarMasked:] : 328 -> 324
~ -[AIAudiogramFrequencyInputCell _setWidth:forEar:] : 484 -> 480
~ -[AIAudiogramResultDateCell showActive:] : 356 -> 352
~ -[AIAudiogramIndividualFrequencyEarCell updateLeftEarSymbol:] : 544 -> 540
~ -[AIAudiogramIndividualFrequencyEarCell updateSymbols:ear:masked:] : 1276 -> 1364
~ ___64-[AIAudiogramEnrollmentViewController _showResultsForAudiogram:]_block_invoke.556 -> ___64-[AIAudiogramEnrollmentViewController _showResultsForAudiogram:]_block_invoke.577 : 544 -> 540
~ sub_24e418d20 -> sub_24f6aeee8 : 260 -> 272
~ sub_24e41b030 -> sub_24f6b1204 : 1872 -> 1876
~ sub_24e41e364 -> sub_24f6b453c : 336 -> 340
~ sub_24e41e4b4 -> sub_24f6b4690 : 760 -> 748
~ sub_24e41e7ac -> sub_24f6b497c : 308 -> 316
~ sub_24e41e8e0 -> sub_24f6b4ab8 : 628 -> 648
~ sub_24e41eb54 -> sub_24f6b4d40 : 564 -> 568
~ sub_24e41fbd4 -> sub_24f6b5dc4 : 1284 -> 1232
~ sub_24e420f04 -> sub_24f6b70c0 : 3724 -> 3740
~ sub_24e422108 -> sub_24f6b82d4 : 2144 -> 2148
~ sub_24e422e90 -> sub_24f6b9060 : 280 -> 276
~ sub_24e4237ec -> sub_24f6b99b8 : 256 -> 276
~ sub_24e4239d0 -> sub_24f6b9bb0 : 236 -> 256
~ sub_24e425060 -> sub_24f6bb254 : 1408 -> 1424
~ sub_24e4262e4 -> sub_24f6bc4e8 : 2020 -> 2008
~ sub_24e428c98 -> sub_24f6bee90 : 880 -> 888
~ sub_24e42a46c -> sub_24f6c066c : 1012 -> 1016
~ sub_24e42a860 -> sub_24f6c0a64 : 5556 -> 5600
~ sub_24e42be14 -> sub_24f6c2044 : 808 -> 812
CStrings:
+ "minus"
+ "\xf2"
- "\xe2"
```
