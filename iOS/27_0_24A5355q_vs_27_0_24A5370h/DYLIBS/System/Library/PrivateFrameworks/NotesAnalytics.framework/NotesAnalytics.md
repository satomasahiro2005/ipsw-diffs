## NotesAnalytics

> `/System/Library/PrivateFrameworks/NotesAnalytics.framework/NotesAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5f034` | `0x5efe4` | **`-0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x3c30` | `0x3c38` | **`+0x8`** |
| `__TEXT.__const` | `0x140` | `0x138` | **`-0x8`** |

### Other Changes

```diff

-2985.0.0.202.2
+2991.0.0.0.0
Functions:
~ -[_ICNANoteReportToAccount updateNoteTwoFactorMatrixWithIndex:] : 116 -> 132
~ -[_ICNANoteReportToAccount completeTwoFactorMatrixReportingForCurrentNote] : 64 -> 72
~ ___42-[ICNASnapshotReporter submitMiniSnapshot]_block_invoke : 580 -> 576
~ ___42-[ICNASnapshotReporter submitMiniSnapshot]_block_invoke_2 : 504 -> 500
~ ___38-[ICNASnapshotReporter snapshotDevice]_block_invoke : 312 -> 308
~ ___38-[ICNASnapshotReporter snapshotDevice]_block_invoke_2 : 316 -> 312
~ -[ICNASnapshotReporter snapshotModernAccount:reportedDataToDevice:reportedDataFromFolderToDevice:reportedDataFromNoteToDevice:] : 10648 -> 10644
~ -[ICNASnapshotReporter snapshotHTMLAccount:reportedDataToDevice:reportedDataFromFolderToDevice:reportedDataFromNoteToDevice:] : 3556 -> 3552
~ -[ICNASnapshotReporter snapshotHTMLFolder:reportedDataToAccount:reportedDataToDevice:noteReportToAccount:reportedDataFromNoteToDevice:] : 676 -> 684
~ -[ICNASnapshotReporter snapshotModernNote:reportedDataToAccount:reportToDevice:reportedDataFromAttachmentToAccount:] : 5244 -> 5240
~ ___116-[ICNASnapshotReporter snapshotModernNote:reportedDataToAccount:reportToDevice:reportedDataFromAttachmentToAccount:]_block_invoke_2 : 292 -> 288
~ -[ICNASearchResultExposureReporter _exposureDataThreadUnsafe] : 976 -> 972
~ +[ICNAReferringInboundURLFilter foundMatchingPrefixAmongCandidates:forInputString:matchingPrefixInplaceResult:] : 316 -> 312
~ ___59-[ICNAMultiSceneSessionTracker endAllSessionsAndInvalidate]_block_invoke : 292 -> 288
~ ___50-[ICNAMultiSceneSessionTracker sessionSummaryData]_block_invoke : 344 -> 340
~ ___45-[ICNAMultiSceneSessionTracker hasLiveTimers]_block_invoke : 316 -> 312
~ ___39-[ICNAEventReporter flushAllTimedData:]_block_invoke : 372 -> 368
~ -[ICNAEventReporter submitPendingInlineDrawingDataForNote:] : 1320 -> 1328
~ ___90-[ICNAEventReporter submitMentionAddEventForNote:mentionID:participantID:viaAutoComplete:]_block_invoke : 664 -> 660
~ ___89-[ICNAEventReporter submitHashtagAddEventForNote:tokenContentIdentifier:viaAutoComplete:]_block_invoke : 660 -> 656
~ ___50-[ICNAEventReporter noteContentDataForModernNote:]_block_invoke_2 : 268 -> 260
~ +[ICNAEventReporter inlineAttachmentReportForModernNote:faultOutInlineAttachmentsAfterDone:] : 1352 -> 1348
~ -[ICNAEventReporter pencilStrokeCountForDrawing:] : 268 -> 264
~ ___40-[ICNAController appSessionDidTerminate]_block_invoke : 412 -> 408
~ ___39-[ICNAController orientationDidChange:]_block_invoke_2 : 368 -> 364
~ ___36-[ICNAController accountTypeSummary]_block_invoke : 624 -> 620
~ ___36-[ICNAController accountTypeSummary]_block_invoke_2 : 636 -> 632
~ ___69-[ICNAController pushDataObjects:unique:onlyOnce:subTrackerProvider:]_block_invoke : 640 -> 632
~ ___61-[ICNAController pushDataObjects:unique:onlyOnce:subTracker:]_block_invoke : 620 -> 612
~ ___53-[ICNAController popDataObjectsWithTypes:subTracker:]_block_invoke : 376 -> 372
~ ___47-[ICNAController removePreSydneyDAnalyticsData]_block_invoke : 1232 -> 1228
```
