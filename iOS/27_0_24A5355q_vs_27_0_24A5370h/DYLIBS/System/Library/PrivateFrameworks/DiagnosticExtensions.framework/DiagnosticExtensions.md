## DiagnosticExtensions

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/DiagnosticExtensions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17b0c` | `0x17ac4` | **`-0x48`** |

### Other Changes

```text
Functions:
~ +[DEArchiver archiveDirectoryAt:deleteOriginal:progressHandler:] : 1616 -> 1612
~ +[DEAnnotation annotateURL:displayName:description:iconType:additionalInfo:error:] : 624 -> 620
~ -[DEExtension isLoggingEnabled] : 1328 -> 1324
~ ___38-[DEExtension performWithHostContext:]_block_invoke_2 : 848 -> 844
~ -[DEExtension loggingProfileURLsFromExtension] : 940 -> 936
~ -[DEExtensionContext attachmentsForParameters:withHandler:] : 600 -> 596
~ -[DEExtensionContext annotatedAttachmentsForParameters:withHandler:] : 420 -> 416
~ -[DEExtensionHostContext updatedParametersWithExtensionFileNameFromParameters:] : 616 -> 612
~ -[DEExtensionManager extensionForIdentifier:] : 340 -> 336
~ ___36-[DEExtensionManager loadExtensions]_block_invoke : 552 -> 548
~ ___43-[DEExtensionManager extensionsWithFilter:]_block_invoke : 480 -> 476
~ -[DEExtensionProvider filesInDir:matchingPattern:excludingPattern:] : 1080 -> 1064
~ _pgrep : 436 -> 456
~ +[DEUtils getDirectorySize:] : 1136 -> 1132
~ +[DEUtils findAllItems:includeDirs:] : 564 -> 560
~ +[DEUtils copyPaths:toDestinationDir:withZipName:] : 356 -> 352
~ +[DEUtils findEntriesInDirectory:createdAfter:matchingPattern:] : 688 -> 684
~ +[DEUtils processErrorResponse:] : 544 -> 540
~ +[DEAttachmentGroup createWithName:rootURL:] : 556 -> 552
~ -[DEAttachmentGroup attachToDestinationDir:useAppleArchive:] : 920 -> 916
~ +[DELoggingPreferences combinedLoggingPayloadForURLs:error:] : 820 -> 816
```
