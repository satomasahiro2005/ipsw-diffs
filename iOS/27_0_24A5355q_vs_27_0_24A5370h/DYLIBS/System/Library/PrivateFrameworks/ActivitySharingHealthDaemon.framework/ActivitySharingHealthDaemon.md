## ActivitySharingHealthDaemon

> `/System/Library/PrivateFrameworks/ActivitySharingHealthDaemon.framework/ActivitySharingHealthDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6bb4` | `0x6b94` | **`-0x20`** |

### Other Changes

```diff

-2027.0.11.0.0
+2027.0.12.0.0
Functions:
~ ___78+[ASDatabaseCompetitionListEntryEntity _insertCompetitionLists:profile:error:]_block_invoke : 404 -> 400
~ ___78+[ASDatabaseCompetitionListEntryEntity _insertCompetitionLists:profile:error:]_block_invoke_2 : 384 -> 380
~ ___71+[ASDatabaseCompetitionListEntryJournalEntry applyEntries:withProfile:]_block_invoke : 380 -> 376
~ ___65+[ASDatabaseCompetitionEntity _insertCompetitions:profile:error:]_block_invoke : 404 -> 400
~ ___65+[ASDatabaseCompetitionEntity _insertCompetitions:profile:error:]_block_invoke_2 : 384 -> 380
~ ___62+[ASDatabaseCompetitionJournalEntry applyEntries:withProfile:]_block_invoke : 380 -> 376
~ ___70+[ASDatabaseCompetitionDeletionJournalEntry applyEntries:withProfile:]_block_invoke : 384 -> 380
~ -[ASDatabaseServer daemonReady:] : 416 -> 412
```
