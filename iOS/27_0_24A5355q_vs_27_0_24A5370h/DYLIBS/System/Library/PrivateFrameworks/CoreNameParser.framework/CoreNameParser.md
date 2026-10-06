## CoreNameParser

> `/System/Library/PrivateFrameworks/CoreNameParser.framework/CoreNameParser`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5dcc` | `0x5da0` | **`-0x2c`** |

### Other Changes

```text
Functions:
~ __NPRemoveEmojis : 652 -> 648
~ -[NPNameParser namingTraditionForName:] : 1408 -> 1400
~ -[NPNameParser parseFullnameWithDefaultHMMClassifier:normalize:score:] : 1572 -> 1568
~ __NPTokenizeName : 700 -> 692
~ __NPCollapseWhitespaceAndStrip : 888 -> 892
~ -[NPHMMClassifier hiddenStatesFromObservationSequence:] : 2252 -> 2248
~ -[NPHMMClassifier validSequence:compoundsConstraints:labelsConstraints:] : 748 -> 740
~ -[NPComponentSequence oovTokens] : 400 -> 396
~ -[NPNameParser parseKoreanName:normalize:] : 1248 -> 1244
~ -[NPHMMClassifier candidatesBasedOnFormatSequence:] : 392 -> 388
```
