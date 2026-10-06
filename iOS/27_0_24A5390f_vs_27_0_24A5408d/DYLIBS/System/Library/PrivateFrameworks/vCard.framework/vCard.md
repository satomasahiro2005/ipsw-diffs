## vCard

> `/System/Library/PrivateFrameworks/vCard.framework/vCard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x247fc` | `0x24824` | **`+0x28`** |

### Other Changes

```diff

-3839.100.3.2.1
+3844.100.1.0.0
Functions:
~ -[CNVCardLexer nextTokenPeekUnicode:length:] : 580 -> 588
~ -[CNVCardLexer nextUnicodeStringStopTokens:quotedPrintable:trim:maximumValueLength:] : 956 -> 964
~ -[CNVCardLexer unicodeSkipToStopTokens:] : 304 -> 308
~ -[CNVCardLexer nextUnicodeBase64Line:] : 404 -> 408
~ -[CNVCardLexer advanceToUnicodeString] : 324 -> 328
~ -[CNVCardLexer advanceToEOLUnicode] : 80 -> 88
~ -[CNVCardLexer advancePastEOLUnicode] : 312 -> 316
```
