## NotesShared

> `/System/Library/PrivateFrameworks/NotesShared.framework/NotesShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34a028` | `0x34ab7c` | **`+0xb54`** |
| `__TEXT.__oslogstring` | `0x1cc89` | `0x1cd19` | **`+0x90`** |
| `__TEXT.__cstring` | `0x19344` | `0x193c4` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x18324` | `0x1838c` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x6510` | `0x6568` | **`+0x58`** |
| `__AUTH_CONST.__cfstring` | `0xfa00` | `0xfa40` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xcbf8` | `0xcc30` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0xf030` | `0xf068` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0xf0bc` | `0xf0e4` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x223e8` | `0x223f8` | **`+0x10`** |
| `__TEXT.__const` | `0xdb58` | `0xdb68` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2138` | `0x2130` | **`-0x8`** |

### Other Changes

```diff

-2998.0.0.0.0
+3001.2.1.0.0

-  - /System/Library/Frameworks/CoreImage.framework/CoreImage

-  Functions: 18532
-  Symbols:   17713
-  CStrings:  5272
+  Functions: 18547
+  Symbols:   17730
+  CStrings:  5277
Symbols:
+ +[ICCloudNotificationsController batchUpdateTopicSubscriptionsAllAccountsInBackground]
+ +[ICCloudNotificationsController finishUserNotificationsRegistrationUpdatingSubscriptionsWithAuthorization:]
+ +[ICNote contentInfoAttributedTextWithSnippet:attachmentContentInfoType:attachmentContentInfoCount:attachmentGraphInfoCount:account:]
+ +[ICNote contentInfoTextWithSnippet:attachmentContentInfoType:attachmentContentInfoCount:attachmentGraphInfoCount:account:]
+ +[ICNote graphContentInfoTextForCount:]
+ -[ICAttachmentPaperBundleModel paperHasGraph]
+ -[ICAttachmentPaperBundleModel setPaperHasGraph:]
+ -[ICDividerLineTextAttachment imageForBounds:textContainer:characterIndex:]
+ -[ICInlineAttachment cachedlinkedNoteIsPasswordProtected]
+ -[ICInlineAttachment linkedNoteIsPasswordProtected]
+ -[ICInlineAttachment setCachedlinkedNoteIsPasswordProtected:]
+ -[ICNote graphContentInfoCount]
+ GCC_except_table331
+ GCC_except_table354
+ _ICAttachmentPaperHasGraphMetadataKey
+ _OBJC_IVAR_$_ICInlineAttachment._cachedlinkedNoteIsPasswordProtected
+ ___22-[ICNoteData willSave]_block_invoke
+ ___31-[ICNote graphContentInfoCount]_block_invoke
+ ___42-[ICBackgroundTaskScheduler registerTask:]_block_invoke_3
+ ___49-[ICAttachmentPaperBundleModel setPaperHasGraph:]_block_invoke
+ ___51-[ICCloudSyncBackgroundTask runTaskWithCompletion:]_block_invoke_2
+ ___86+[ICCloudNotificationsController batchUpdateTopicSubscriptionsAllAccountsInBackground]_block_invoke
+ ___block_descriptor_48_e8_32r40r_e26_v24?0"ICAttachment"8^B16lr32l8r40l8
+ ___block_descriptor_56_e8_32s40r48w_e8_v12?0B8ls32l8r40l8w48l8
- +[ICNote contentInfoAttributedTextWithSnippet:attachmentContentInfoType:attachmentContentInfoCount:account:]
- -[ICInlineAttachment cachedLinkedNoteIsPasswordProtectedAndLocked]
- -[ICInlineAttachment linkedNoteIsPasswordProtectedAndLocked]
- -[ICInlineAttachment setCachedLinkedNoteIsPasswordProtectedAndLocked:]
- GCC_except_table327
- _OBJC_CLASS_$_CIImage
- _OBJC_IVAR_$_ICInlineAttachment._cachedLinkedNoteIsPasswordProtectedAndLocked
CStrings:
+ "NOTE_LIST_GRAPHS_%lu"
+ "Safety mechanism update required. You can see the status in [Settings](chinaai-settings)."
+ "User did not grant authorization for user notifications (via warming sheet)"
+ "User granted authorization for user notifications (via warming sheet)"
+ "hasGraphKey"
```
