## MobileNotes

> `/private/var/staged_system_apps/MobileNotes.app/MobileNotes`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f9458` | `0x4f5760` | **`-0x3cf8`** |
| `__TEXT.__objc_methname` | `0x54627` | `0x54867` | **`+0x240`** |
| `__TEXT.__objc_stubs` | `0x37420` | `0x37560` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0x1117e` | `0x1103e` | **`-0x140`** |
| `__TEXT.__eh_frame` | `0x189e4` | `0x18910` | **`-0xd4`** |
| `__TEXT.__auth_stubs` | `0x84d0` | `0x8570` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1c790` | `0x1c810` | **`+0x80`** |
| `__TEXT.__const` | `0x1f554` | `0x1f4e4` | **`-0x70`** |
| `__TEXT.__oslogstring` | `0xf196` | `0xf206` | **`+0x70`** |
| `__DATA.__objc_selrefs` | `0x116c0` | `0x11710` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x4278` | `0x42c8` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x5280` | `0x5230` | **`-0x50`** |
| `__TEXT.__gcc_except_tab` | `0x37e4` | `0x37a0` | **`-0x44`** |
| `__DATA_CONST.__const` | `0x1e3c0` | `0x1e380` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x19f5c` | `0x19f9c` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0xae59` | `0xae99` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0xa740` | `0xa720` | **`-0x20`** |
| `__DATA.__objc_const` | `0x29a70` | `0x29a88` | **`+0x18`** |
| `__DATA.__objc_data` | `0xf980` | `0xf998` | **`+0x18`** |
| `__DATA.__bss` | `0x26cc8` | `0x26cd8` | **`+0x10`** |
| `__DATA.__data` | `0x122b4` | `0x122c4` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x82b4` | `0x82c4` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x98b0` | `0x98a0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x11888` | `0x11890` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_replace`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3001.40.9.100.1
+3001.40.11.102.1

+  - /System/Library/Frameworks/WebKit.framework/WebKit

-  Functions: 23976
-  Symbols:   4532
-  CStrings:  17097
+  Functions: 23979
+  Symbols:   4543
+  CStrings:  17112
Symbols:
+ _$s10Foundation16AttributedStringV6appendyyxAA0bC8ProtocolRzlF
+ _CGContextDrawPDFPage
+ _CGContextScaleCTM
+ _CGContextTranslateCTM
+ _CGDataProviderCreateWithCFData
+ _CGDataProviderRelease
+ _CGPDFDocumentCreateWithProvider
+ _CGPDFDocumentGetPage
+ _CGPDFDocumentRelease
+ _CGPDFPageGetBoxRect
+ _ICInternalSettingsIsTextKit2PrintingEnabled
+ _OBJC_CLASS_$_UIGraphicsPDFRenderer
+ _OBJC_CLASS_$_UIGraphicsPDFRendererFormat
+ _OBJC_CLASS_$_UIViewPrintFormatter
+ _OBJC_CLASS_$_WKPDFConfiguration
+ _UILayoutFittingExpandedSize
+ _UIRectFill
- _$s11NotesShared24ManagedEntityContextTypeO4htmlyA2CmFWC
- _$s11NotesShared24ManagedEntityContextTypeO6modernyA2CmFWC
- _$s11NotesShared24ManagedEntityContextTypeOMa
- _$s11NotesShared24ManagedEntityContextTypeOSQAAMc
- _$s11NotesShared24ManagedEntityContextTypeOs23CustomStringConvertibleAAMc
- _$s7SwiftUI4TextV1poiyA2C_ACtFZ
CStrings:
+ "%@ cancelling import because destination folder lost its context or was deleted"
+ "@\"UICloudSharingController\"16@?0@\"UICloudSharingController\"8"
+ "Could not generate HTML note screenshot PDF %@"
+ "Generated HTML note screenshot PDF: %lu bytes"
+ "PDFDataWithActions:"
+ "TB,V_isApplyingStateRestoreArchive"
+ "beginPage"
+ "com.apple.notes.sharing-extension.image-preview-generation"
+ "configuredCloudSharingControllerForObject:presentingViewController:popoverBarButtonItem:dismissed:"
+ "createPDFWithConfiguration:completionHandler:"
+ "ensureLayoutForRange:"
+ "generatePreviewWithAttachments:completion:"
+ "generateVideoPreviewUsingAttachment:completion:"
+ "glyphRangeForCharacterRange:actualCharacterRange:"
+ "ic_generateScreenshotPDFForHTMLNoteEditorWithCompletion:"
+ "ic_generateScreenshotPDFForNoteEditorWithCompletion:"
+ "ic_previewImageWithCompletion:"
+ "initWithBounds:format:"
+ "invalidateLastSearchInput"
+ "manageShareButtonTitle"
+ "manageShareCloudSharingControllerForObject:presentingViewController:popoverBarButtonItem:"
+ "noteEditorActionMenuShouldShow:"
+ "preferredFormat"
+ "setAllowTransparentBackground:"
+ "setManageButtonTitle:"
+ "setRect:"
+ "setWillPresentCloudSharingController:"
+ "shouldShowMenu"
+ "showsManageShareButton"
+ "textContainerForGlyphAtIndex:effectiveRange:"
+ "v16@?0@\"ICSEMediaPreview\"8"
+ "v16@?0@\"UIGraphicsPDFRendererContext\"8"
- "%@.pdf"
- "Could not generate PDF %@"
- "TB,N,V_isApplyingStateRestoreArchive"
- "Unknown context type: %s"
- "addPrintFormatter:startingAtPageAtIndex:"
- "createAndPresentCloudSharingControllerBySender:"
- "dataWithContentsOfURL:"
- "didPressManageShareButton"
- "generatePreviewWithAttachments:"
- "generateVideoPreviewUsingAttachment:"
- "ic_previewImage"
- "pageCount"
- "savePDFToURL:showProgress:completionHandler:"
- "setDidPressManageShareButton:"
- "setPrintPageRenderer:"
- "showShare"
- "showSharedFolderActions:"
```
