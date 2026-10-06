## VisualVoicemail

> `/System/Library/PrivateFrameworks/VisualVoicemail.framework/VisualVoicemail`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ac28` | `0x1abfc` | **`-0x2c`** |

### Other Changes

```diff

-949.0.0.0.0
+952.0.0.0.0
Functions:
~ +[VMConfiguration metadataDictionaryForSpeechAssetWithLanguage:] : 1384 -> 1380
~ -[VMVoicemailManager voicemailsPassingTest:] : 368 -> 364
~ -[VMVoicemailManager deleteVoicemails:] : 672 -> 668
~ -[VMVoicemailManager markVoicemailsAsRead:] : 588 -> 584
~ ___43-[VMVoicemailManager markVoicemailsAsRead:]_block_invoke : 392 -> 388
~ -[VMVoicemailManager trashVoicemails:] : 668 -> 664
~ -[VMVoicemailManager removeVoicemailsFromTrash:] : 588 -> 584
~ ___48-[VMVoicemailManager removeVoicemailsFromTrash:]_block_invoke : 288 -> 284
~ -[VMVoicemailTranscript initWithTranscription:] : 616 -> 612
~ -[VMVoicemailTranscript initWithTranscriberResult:] : 680 -> 676
~ -[VMVoicemailTranscript debugDescription] : 488 -> 484
```
