## HashtagImagesExtension

> `/Applications/HashtagImages.app/PlugIns/HashtagImagesExtension.appex/HashtagImagesExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc4c8` | `0xa1e4` | **`-0x22e4`** |
| `__DATA.__objc_const` | `0xa28` | `0x278` | **`-0x7b0`** |
| `__TEXT.__objc_methname` | `0x10b6` | `0xa43` | **`-0x673`** |
| `__TEXT.__objc_stubs` | `0xec0` | `0xaa0` | **`-0x420`** |
| `__DATA.__data` | `0x418` | `0x128` | **`-0x2f0`** |
| `__TEXT.__objc_methtype` | `0x496` | `0x1bd` | **`-0x2d9`** |
| `__DATA_CONST.__const` | `0x6a0` | `0x3f8` | **`-0x2a8`** |
| `__TEXT.__objc_methlist` | `0x46c` | `0x1e8` | **`-0x284`** |
| `__TEXT.__auth_stubs` | `0x920` | `0xb60` | **`+0x240`** |
| `__DATA.__objc_selrefs` | `0x578` | `0x360` | **`-0x218`** |
| `__TEXT.__swift5_capture` | `0x2ac` | `0x16c` | **`-0x140`** |
| `__DATA_CONST.__auth_got` | `0x498` | `0x5b8` | **`+0x120`** |
| `__DATA.__bss` | `0x100` | `—` | **`-0x100`** |
| `__TEXT.__swift5_typeref` | `0x2ae` | `0x1ff` | **`-0xaf`** |
| `__TEXT.__swift5_reflstr` | `0x11a` | `0x73` | **`-0xa7`** |
| `__TEXT.__unwind_info` | `0x3b8` | `0x318` | **`-0xa0`** |
| `__TEXT.__eh_frame` | `0x178` | `0x208` | **`+0x90`** |
| `__TEXT.__cstring` | `0x399` | `0x320` | **`-0x79`** |
| `__TEXT.__swift5_fieldmd` | `0xd8` | `0x68` | **`-0x70`** |
| `__TEXT.__const` | `0x210` | `0x1a8` | **`-0x68`** |
| `__TEXT.__objc_classname` | `0x132` | `0xcf` | **`-0x63`** |
| `__DATA_CONST.__objc_protolist` | `0x60` | `0x10` | **`-0x50`** |
| `__DATA.__objc_data` | `0x1c0` | `0x190` | **`-0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x80` | `0x60` | **`-0x20`** |
| `__DATA_CONST.__objc_protorefs` | `0x30` | `0x10` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x80` | `0x64` | **`-0x1c`** |
| `__TEXT.__swift5_proto` | `0x8` | `—` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0xc` | `0x8` | **`-0x4`** |
| `__TEXT.__swift_as_cont` | `0x8` | `0xc` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x10` | `0x14` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3400.1.6.30.0
-  - /System/Library/Frameworks/AVFoundation.framework/AVFoundation
+3400.1.6.36.0

-  - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics
-  - /System/Library/Frameworks/CoreMedia.framework/CoreMedia
-  - /System/Library/Frameworks/CoreVideo.framework/CoreVideo

-  - /System/Library/Frameworks/ImageIO.framework/ImageIO

-  - /System/Library/Frameworks/QuartzCore.framework/QuartzCore

-  - /System/Library/PrivateFrameworks/AggregateDictionary.framework/AggregateDictionary

-  - /usr/lib/libMobileGestalt.dylib

-  Functions: 301
-  Symbols:   150
-  CStrings:  269
+  Functions: 207
+  Symbols:   154
+  CStrings:  156
Symbols:
+ _NSLocalizedDescriptionKey
+ _NSSearchPathForDirectoriesInDomains
+ _NSURLErrorDomain
+ _OBJC_CLASS_$_NSFileManager
+ _OBJC_CLASS_$_STSImageCache
+ _OBJC_CLASS_$_UIAlertAction
+ _OBJC_CLASS_$_UIAlertController
+ _OBJC_CLASS_$_UIGraphicsImageRenderer
+ _objc_retain_x1
+ _objc_retain_x28
+ _swift_dynamicCastClass
+ _swift_errorRelease
+ _swift_errorRetain
+ _swift_initStackObject
+ _swift_isEscapingClosureAtFileLocation
+ _swift_setDeallocating
+ _swift_willThrow
- _OBJC_CLASS_$_OS_dispatch_queue
- _OBJC_CLASS_$_STSFeedbackReporter
- _OBJC_CLASS_$_STSPicker
- _OBJC_CLASS_$_STSSearchBrowserRootViewController
- _OBJC_CLASS_$_STSSearchModel
- _OBJC_CLASS_$_STSZKWBrowserHeaderView
- _objc_retain_x2
- _objc_retain_x24
- _objc_retain_x25
- _swift_getTypeByMangledNameInContextInMetadataState2
- _swift_release_n
- _swift_retain_x23
- _swift_retain_x26
CStrings:
+ "ERROR_DESC_UNSUPPORTED_FILETYPE"
+ "Error inserting attachment: %@"
+ "Failed to write tmp image file: %@"
+ "HashtagImagesExtension/STSMessagesAppViewController+RootHosting.swift"
+ "Image download failed: %@"
+ "SHARE_IMAGE_FAILED_ALERT_TITLE"
+ "STSResultDetailHostingDelegate"
+ "STSSearchRootContainerHostingDelegate"
+ "actionWithTitle:style:handler:"
+ "addAction:"
+ "addSubview:"
+ "alertControllerWithTitle:message:preferredStyle:"
+ "code"
+ "defaultManager"
+ "didAutoFocusSearch"
+ "domain"
+ "drawViewHierarchyInRect:afterScreenUpdates:"
+ "fetchImageDataWithURL:priority:isSource:begin:progress:completion:"
+ "imageWithActions:"
+ "initWithBounds:"
+ "layoutIfNeeded"
+ "localizedDescription"
+ "presentViewController:animated:completion:"
+ "punchout"
+ "removeItemAtPath:error:"
+ "removeItemAtURL:error:"
+ "resultDetailHostingControllerDidDismiss:"
+ "resultDetailHostingControllerDidInsert:"
+ "resultDetailHostingControllerDidSelectProvider:"
+ "rootContainer"
+ "scheme"
+ "searchRootContainerDidActivateSearch"
+ "searchRootContainerDidPreviewResult:"
+ "searchRootContainerDidSelectCategoryQuery:isRecent:isSuggested:"
+ "searchRootContainerDidSelectCategoryResult:"
+ "searchRootContainerDidSelectImage:"
+ "searchRootContainerDidSelectVideo:"
+ "setTranslatesAutoresizingMaskIntoConstraints:"
+ "sharedCache"
+ "stringByAppendingPathComponent:"
+ "urls"
+ "v16@?0@\"UIGraphicsImageRendererContext\"8"
+ "v24@0:8@\"SFSearchResult\"16"
+ "v24@0:8@\"UIViewController\"16"
+ "v24@?0q8q16"
+ "v32@0:8@\"NSString\"16B24B28"
+ "v32@0:8@16B24B28"
+ "v48@?0@\"NSData\"8@\"STSAnimatedImageInfo\"16@\"NSString\"24@\"NSDictionary\"32@\"NSError\"40"
- "#16@0:8"
- "@\"NSString\"16@0:8"
- "@16@0:8"
- "@24@0:8:16"
- "@32@0:8:16@24"
- "@40@0:8:16@24@32"
- "B16@0:8"
- "B24@0:8#16"
- "B24@0:8:16"
- "B24@0:8@\"Protocol\"16"
- "B24@0:8@\"STSPicker\"16"
- "B24@0:8@\"STSSearchBrowserRootViewController\"16"
- "B24@0:8@\"UIGestureRecognizer\"16"
- "B24@0:8@16"
- "B32@0:8@\"UIGestureRecognizer\"16@\"UIEvent\"24"
- "B32@0:8@\"UIGestureRecognizer\"16@\"UIGestureRecognizer\"24"
- "B32@0:8@\"UIGestureRecognizer\"16@\"UIPress\"24"
- "B32@0:8@\"UIGestureRecognizer\"16@\"UITouch\"24"
- "B32@0:8@16@24"
- "Error inserting attachment to current conversation %@"
- "HashtagImagesExtension/STSMessagesAppViewController+BrowserDelegate.swift"
- "HashtagImagesExtension/STSMessagesAppViewController+PickerDelegate.swift"
- "HashtagImagesExtension2"
- "NSObject"
- "PARSessionDelegate"
- "Q16@0:8"
- "STSPickerSelectionDelegate"
- "STSRecentsDelegate"
- "STSSearchBrowserRootViewControllerDelegate"
- "T#,R"
- "T@\"NSString\",?,R,C"
- "T@\"NSString\",R,C"
- "TQ,R"
- "UIGestureRecognizerDelegate"
- "Vv16@0:8"
- "^{_NSZone=}16@0:8"
- "autorelease"
- "becomeFirstResponder"
- "browser:didSearchFor:"
- "browser:didSelectCategoryResult:"
- "browser:didSelectProviderLink:"
- "browser:didSelectResult:withPayload:"
- "browser:requestSuggestionsFor:"
- "browserDidDeleteQuery"
- "browserDidScroll:"
- "browserDidTapLogo:"
- "browserIsPresentedFullscreen:"
- "browserSearchBarButtonClicked:"
- "browserSearchBarCancelButtonClicked:"
- "browserSuggestionButtonClicked:suggestion:"
- "cancelImageDownloads"
- "class"
- "clear"
- "conformsToProtocol:"
- "copy"
- "deactivateConstraints:"
- "debugDescription"
- "description"
- "didEngageProviderLogo"
- "didEngageResult:"
- "didSearchWithSuggestedQuery:"
- "enableSearchButton"
- "engagementFeedbackBlock"
- "fetchCategories"
- "gestureRecognizer:shouldBeRequiredToFailByGestureRecognizer:"
- "gestureRecognizer:shouldReceiveEvent:"
- "gestureRecognizer:shouldReceivePress:"
- "gestureRecognizer:shouldReceiveTouch:"
- "gestureRecognizer:shouldRecognizeSimultaneouslyWithGestureRecognizer:"
- "gestureRecognizer:shouldRequireFailureOfGestureRecognizer:"
- "gestureRecognizerShouldBegin:"
- "hash"
- "https://www.bing.com/images/search"
- "imageURL"
- "initWithSearchModel:"
- "initWithSearchModel:showSuggestions:"
- "invalidateIntrinsicContentSize"
- "isEqual:"
- "isFirstResponder"
- "isKindOfClass:"
- "isMemberOfClass:"
- "isPickerVisible"
- "isProxy"
- "layoutMargins"
- "performSelector:"
- "performSelector:withObject:"
- "performSelector:withObject:withObject:"
- "performZKWSearchQuery"
- "performZKWSearchQueryWithCompletion:"
- "pickerView"
- "pickerViewController"
- "query"
- "release"
- "removeFromParentViewController"
- "requestExpandedPresentationStyleForBrowser:completion:"
- "resetContent"
- "retain"
- "retainCount"
- "rootConstraints"
- "safeAreaLayoutGuide"
- "searchBar"
- "searchBrowserHost"
- "searchBrowserRootViewController"
- "searchBrowserRootViewControllerDidSelectCancel:"
- "searchBrowserRootViewControllerSearchBarShouldBeginEditing:"
- "searchBrowserSearchModel"
- "searchHeaderView"
- "searchViewDidAppearWithEvent:"
- "searchViewDidDisappear"
- "secondaryTitle"
- "self"
- "sendVisibleResultsFeedback"
- "session %@ parsec bag failed to load: %@"
- "session %@ parsec bag loaded"
- "session:bag:didLoadWithError:"
- "session:didDeleteResource:"
- "session:didDownloadResource:"
- "setBottomInset:"
- "setContentView:"
- "setConversationID:"
- "setDelegate:"
- "setHeaderView:"
- "setParsecSession:"
- "setPickerSelectionDelegate:"
- "setPresentationStyle:"
- "setRecentResults:"
- "setRecentsDelegate:"
- "setSelectionDelegate:"
- "setText:"
- "setTopInset:"
- "sharedInstance"
- "showCategories"
- "showPickerAndPerformQuery:requestType:"
- "snapshotImage"
- "superclass"
- "superview"
- "text"
- "transitionFromViewController:toViewController:duration:options:animations:completion:"
- "updateRecentResults:"
- "updating recent results"
- "v12@?0B8"
- "v20@?0B8@\"NSError\"12"
- "v24@0:8@\"NSArray\"16"
- "v24@0:8@\"STSPicker\"16"
- "v24@0:8@\"STSSearchBrowserRootViewController\"16"
- "v32@0:8@\"PARSession\"16@\"NSString\"24"
- "v32@0:8@\"STSPicker\"16@\"NSString\"24"
- "v32@0:8@\"STSPicker\"16@\"SFSearchResult\"24"
- "v32@0:8@\"STSPicker\"16@\"SFSearchSuggestion\"24"
- "v32@0:8@\"STSPicker\"16@?<v@?>24"
- "v32@0:8@16@24"
- "v32@0:8@16@?24"
- "v40@0:8@\"PARSession\"16@\"PARBag\"24@\"NSError\"32"
- "v40@0:8@\"STSPicker\"16@\"SFSearchResult\"24@\"STSPayload\"32"
- "v40@0:8@16@24@32"
- "videoURL"
- "willMoveToParentViewController:"
- "zkwHeaderView"
- "zkwPicker"
- "zkwSearchModel"
- "zone"
```
