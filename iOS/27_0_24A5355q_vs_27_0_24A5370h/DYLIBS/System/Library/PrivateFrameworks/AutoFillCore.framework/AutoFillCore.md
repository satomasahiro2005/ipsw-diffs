## AutoFillCore

> `/System/Library/PrivateFrameworks/AutoFillCore.framework/AutoFillCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9c2c` | `0x9c34` | **`+0x8`** |

### Other Changes

```text
Functions:
~ ___101-[AFSuggestionGenerationManager generateCreditCardAutoFillWithCompletionHandler:externalizedContext:]_block_invoke : 600 -> 596
~ -[AFSuggestionGenerationManager generateSuggestionsForContactAutoFill:textPrefix:] : 1640 -> 1660
~ ___95-[AFCredentialManager generateSignupAutoFillWithAutoFillMode:documentTraits:completionHandler:]_block_invoke : 292 -> 288
~ -[AFCredentialManager generateOneTimeCodeAutoFillSuggestionsWithDocumentTraits:completionHandler:] : 756 -> 752
```
