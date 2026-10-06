## TextToSpeechKonaSupport

> `/System/Library/PrivateFrameworks/TextToSpeechKonaSupport.framework/TextToSpeechKonaSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x112cc` | `0x112b4` | **`-0x18`** |

### Other Changes

```diff

-675.1.0.0.0
+676.0.0.0.0
Functions:
~ -[AXKonaSpeechSegment setText:] : 764 -> 752
~ -[AXKonaSpeechEngine _segmentsForText:] : 1912 -> 1908
~ ___39-[AXKonaSpeechEngine _segmentsForText:]_block_invoke : 776 -> 772
~ -[AXKonaSpeechEngine _preprocessTextForIrregularities:] : 556 -> 552
~ ___37-[AXKonaSpeechEngine synthesizeText:]_block_invoke : 716 -> 712
~ +[AXKonaSpeechEngine allVoices] : 1516 -> 1512
~ sub_20ef36418 -> sub_20fbf43f8 : 3852 -> 3856
~ sub_20ef384e8 -> sub_20fbf64cc : 476 -> 480
~ sub_20ef38790 -> sub_20fbf6778 : 280 -> 276
~ sub_20ef38d30 -> sub_20fbf6d14 : 1220 -> 1216
~ sub_20ef393e4 -> sub_20fbf73c4 : 304 -> 300
~ sub_20ef3a7d0 -> sub_20fbf87ac : 2100 -> 2084
~ sub_20ef3c010 -> sub_20fbf9fdc : 2208 -> 2212
~ sub_20ef3e830 -> sub_20fbfc800 : 252 -> 268
~ sub_20ef3e92c -> sub_20fbfc90c : 256 -> 264
```
