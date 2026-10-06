## QuickLookSupport

> `/System/Library/PrivateFrameworks/QuickLookSupport.framework/QuickLookSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x157ec` | `0x15794` | **`-0x58`** |

### Other Changes

```diff

-215.0.0.0.0
+216.0.0.0.0
Functions:
~ _QLPreviewCopyEmbeddedIWorkData : 1616 -> 1612
~ ___QLPreviewCopyEmbeddedIWorkData_block_invoke : 664 -> 660
~ ___63-[QLExtensionManagerCache _didReceiveNewMatchingExtensionList:]_block_invoke : 784 -> 776
~ ___123-[QLExtensionManagerCache extensionWithMatchingAttributes:allowExtensionsForParentTypes:extensionPath:firstPartyExtension:]_block_invoke_2 : 1704 -> 1700
~ +[QLExtensionManagerCache bestMatchingExtensionsFromSupportingExtensions:includingExtensionsWithSupportingParentTypes:byContentType:] : 1252 -> 1244
~ -[QLExtensionManagerCache _supportedContentTypesFromExtension:matches:allowMatchingWithParentTypes:] : 1024 -> 1016
~ +[QLUTIManager _recursiveValueInDictionary:forType:alreadySeenUTIs:matchedValueToTypeBlock:validationBlock:] : 940 -> 936
~ +[QLUTIManager _selectParentUTIForUTI:fromParentUTIs:dictionary:alreadySeenUTIs:matchedValueToTypeBlock:validationBlock:] : 592 -> 588
~ -[QLExtensionManager qlExtensionForContentType:allowExtensionsForParentTypes:firstPartyExtension:applicationBundleIdentifier:extensionPath:extensionType:generationType:shouldUseRestrictedExtension:] : 920 -> 916
~ _QLImageIOCreateScaledImageOfMaximumAndMinimumSize : 376 -> 364
~ -[QLExtension _callExtensionRequestHandlers] : 264 -> 260
~ ___58+[QLPreviewURLProtocol registerURL:mimeType:textEncoding:]_block_invoke : 672 -> 668
~ +[QLPreviewURLProtocol _unregisterURL:] : 540 -> 536
~ ___53+[QLPreviewURLProtocol unregisterURLs:andPreviewURL:]_block_invoke : 324 -> 320
~ ___52+[QLPreviewURLProtocol appendData:forURL:lastChunk:]_block_invoke : 740 -> 736
~ ___40+[QLPreviewURLProtocol setError:forURL:]_block_invoke : 516 -> 512
~ ___40-[QLPreviewParts computePreviewInThread]_block_invoke : 488 -> 484
```
