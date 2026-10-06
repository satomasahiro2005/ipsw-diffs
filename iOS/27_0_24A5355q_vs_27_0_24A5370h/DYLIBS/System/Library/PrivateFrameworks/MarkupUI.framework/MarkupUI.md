## MarkupUI

> `/System/Library/PrivateFrameworks/MarkupUI.framework/MarkupUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28cc8` | `0x28c90` | **`-0x38`** |

### Other Changes

```diff

-577.0.0.0.0
+579.0.0.0.0
Functions:
~ ___77-[MUQuickLookContentEditorViewController _insertPagesFromFileURLs:afterPage:]_block_invoke : 520 -> 516
~ -[MUQuickLookContentEditorViewController _insertFileAtURL:type:afterPage:completionHandler:] : 544 -> 540
~ -[MUImageContentViewController updateDrawingGestureRecognizer:forPageAtIndex:withPriority:forAnnotationController:] : 988 -> 976
~ -[NSArray(Foundation_Extensions) muDeepMutableCopy] : 500 -> 496
~ _akMedian : 272 -> 256
~ -[MUPDFContentViewController _recoverFromRotation] : 444 -> 440
~ -[MUPDFContentViewController _medianSizeForCurrentDocumentInPDFViewWithGetter:] : 364 -> 356
~ +[MUCGPDFMarkupAnnotationAdaptor _concreteDictionaryRepresentationOfAKAnnotation:forPage:] : 920 -> 916
```
