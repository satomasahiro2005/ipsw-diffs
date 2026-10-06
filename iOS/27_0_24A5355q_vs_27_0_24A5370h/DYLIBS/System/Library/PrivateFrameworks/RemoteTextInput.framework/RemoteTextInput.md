## RemoteTextInput

> `/System/Library/PrivateFrameworks/RemoteTextInput.framework/RemoteTextInput`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20db8` | `0x20da8` | **`-0x10`** |

### Other Changes

```text
Functions:
~ -[RTIInputSystemClient initWithMachNames:] : 576 -> 572
~ -[RTIInputSystemClient _beginAllActiveSessionsForServices:force:] : 364 -> 360
~ -[RTIInputSystemSession enumerateSessionDelegatesUsingBlock:] : 352 -> 348
~ -[RTISupplementalLexicon initWithTISupplementalLexicon:iconProvider:] : 484 -> 480
~ -[RTISupplementalLexicon enumerateSupplementalItems:] : 412 -> 408
~ +[RTIDocumentState _enumerateDocumentRects:options:block:] : 260 -> 276
~ -[RTIInputSystemClient addMachNames:] : 244 -> 240
~ -[RTIInputSystemClient _endAllActiveSessionsForServices:animated:completion:] : 680 -> 676
~ -[RTIInputSystemClient notifyServiceOfPause:withReason:] : 440 -> 436
```
