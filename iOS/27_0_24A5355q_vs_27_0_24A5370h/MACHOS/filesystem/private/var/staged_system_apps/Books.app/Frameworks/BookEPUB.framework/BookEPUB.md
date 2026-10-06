## BookEPUB

> `/private/var/staged_system_apps/Books.app/Frameworks/BookEPUB.framework/BookEPUB`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27a6c4` | `0x27f4d8` | **`+0x4e14`** |
| `__TEXT.__objc_methname` | `0x14088` | `0x14458` | **`+0x3d0`** |
| `__DATA.__objc_const` | `0x10ac0` | `0x10d00` | **`+0x240`** |
| `__TEXT.__eh_frame` | `0x5174` | `0x53ac` | **`+0x238`** |
| `__TEXT.__objc_stubs` | `0xa700` | `0xa920` | **`+0x220`** |
| `__DATA.__data` | `0xcc78` | `0xce28` | **`+0x1b0`** |
| `__DATA.__bss` | `0xdea0` | `0xe020` | **`+0x180`** |
| `__TEXT.__const` | `0x1e060` | `0x1e1e0` | **`+0x180`** |
| `__DATA.__objc_data` | `0x55d8` | `0x5750` | **`+0x178`** |
| `__TEXT.__objc_methtype` | `0x4374` | `0x44d4` | **`+0x160`** |
| `__TEXT.__constg_swiftt` | `0x9418` | `0x9570` | **`+0x158`** |
| `__TEXT.__swift5_reflstr` | `0x699d` | `0x6add` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0xc513` | `0xc643` | **`+0x130`** |
| `__DATA_CONST.__const` | `0x15690` | `0x15790` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x57c8` | `0x58a0` | **`+0xd8`** |
| `__TEXT.__swift5_fieldmd` | `0x5cb4` | `0x5d7c` | **`+0xc8`** |
| `__TEXT.__swift5_typeref` | `0x65ce` | `0x6690` | **`+0xc2`** |
| `__DATA.__objc_selrefs` | `0x4170` | `0x4230` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x6f40` | `0x6ff8` | **`+0xb8`** |
| `__TEXT.__cstring` | `0x9001` | `0x90a1` | **`+0xa0`** |
| `__TEXT.__ustring` | `0x32336` | `0x322be` | **`-0x78`** |
| `__TEXT.__swift5_capture` | `0x230c` | `0x2368` | **`+0x5c`** |
| `__TEXT.__objc_classname` | `0x1dce` | `0x1e0e` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x5640` | `0x5660` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x23c` | `0x258` | **`+0x1c`** |
| `__TEXT.__gcc_except_tab` | `0x1f40` | `0x1f58` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x12e0` | `0x12f0` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x208` | `0x218` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x3e20` | `0x3e30` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x7cc` | `0x7d8` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x104` | `0x110` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x1f28` | `0x1f30` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xde8` | `0xde0` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x528` | `0x530` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0xf0` | `0xf8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x4c0` | `0x4c8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x108` | `0x110` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2a8` | `0x2ac` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-6629.0.0.0.0
+6636.0.0.0.0

-  Functions: 11308
-  Symbols:   1472
-  CStrings:  5766
+  Functions: 11364
+  Symbols:   1475
+  CStrings:  5813
Symbols:
+ _OBJC_CLASS_$_BEScrimCoverView
+ _OBJC_CLASS_$_CABasicAnimation
+ _OBJC_METACLASS_$_BEScrimCoverView
+ _kCAFillModeBoth
+ _swift_retain_x9
- _OBJC_CLASS_$_CATransition
- _kCATransitionFade
CStrings:
+ "#PaginationOperation: %s ordinal:%ld #pageCount:%ld scrollingElementSize:%s scrollViewContentSize:%s"
+ "#PaginationOperation: %s ordinal:%ld stable presentation update did not fire within %fs; proceeding anyway"
+ "#PaginationOperation: %s ordinal:%ld waiting for stable presentation update"
+ "#reevaluatePaginationData Updated content size of ordinal:%ld from %s to %s"
+ "#reevaluatePaginationData configurationKey mismatch: webView:%s expected:%s"
+ "#reevaluatePaginationData ordinal %ld did NOT actually change: pageCount:%ld size %s"
+ "#reevaluatePaginationData ordinal %ld did actually change. New pageCount:%ld Size: %s"
+ "#requestedLoc Using pageFallback offset %ld for ordinal %ld"
+ "#stalePagination: Discarding stale result for ordinal:%ld. Incoming pageCount:%ld < existing pageCount:%ld contentSize:%s existing:%s"
+ "//  Copyright © 2019 Apple Inc. All rights reserved.\nReflect.defineProperty(window,'__ibooks_image_filter',{value:{},writable:!1}),(e=>{e._applyImageElementFilter=function(e,t){const r=new URL(e.src);window.matchMedia&&window.matchMedia('(prefers-color-scheme: dark)').matches&&r.searchParams.set('be_interfaceStyle','dark'),r.searchParams.set('be_filter',t),e.src=r.toString()},e.refetchVisibleImages=function(t){const r=document.querySelectorAll('img[src*=\"ibooksimg:\"]'),i=r.length;for(let a=0;a<i;a++){const i=r[a];e._applyImageElementFilter(i,t)}}})(__ibooks_image_filter);\n"
+ "<BEScrimCoverView:%p ordinal:%ld frame:%@>"
+ "@\"UIMenu\"40@0:8@\"UIEditMenuInteraction\"16@\"UIEditMenuConfiguration\"24@\"NSArray\"32"
+ "BEScrimCoverView"
+ "BookEPUB6"
+ "Capturing #pageCount:%ld for ordinal:%ld wasReevaluation:%{bool}d webView:%s"
+ "Completed pagination of ordinal:%ld pageCount:%ld contentSize:%s"
+ "FAILURE: #PaginationOperation Cancelled before stable update"
+ "FAILURE: #PaginationOperation Cancelled waiting for stable update"
+ "Paginate: %ld using webView:%s forDisplay:%{bool}d #contentConfig:%s op:%s"
+ "Reevaluation operation canceled for ordinal: %ld operation %@ webViewKey:%s"
+ "T@\"UIView\",&,N"
+ "Task: paginating %ld documents for key: %s"
+ "Tq,N,V_ordinal"
+ "UIEditMenuInteractionDelegate"
+ "] {\nbackground-color: "
+ "_ordinal"
+ "animationWithKeyPath:"
+ "backgroundPaginationTask"
+ "be_addContentCoverWithColor:ordinal:"
+ "be_contentCoverView"
+ "be_doAfterNextStablePresentationUpdate:withTimeout:"
+ "convertRect:toView:"
+ "convertTime:fromLayer:"
+ "editMenuInteraction:menuForConfiguration:suggestedActions:"
+ "editMenuInteraction:targetRectForConfiguration:"
+ "editMenuInteraction:willDismissMenuForConfiguration:animator:"
+ "editMenuInteraction:willPresentMenuForConfiguration:animator:"
+ "editMenuTargetRect"
+ "initWithControlPoints::::"
+ "installedAnchor"
+ "isActive"
+ "isInRotationTransition"
+ "makePaginatingWebViewAsync()"
+ "navigationController"
+ "opaqueSeparatorColor"
+ "pageLabelExternalConstraint"
+ "pageLabelRegionSubject"
+ "pendingScrubberVisibility"
+ "prefersCompactNumberPadLayout"
+ "readingLoupeViewInnerStrokeGradientLayer"
+ "revealWhenStable: stable presentation update did not fire within %fs; removing cover anyway"
+ "scrubberVisibilitySubject"
+ "setBe_contentCoverView:"
+ "setBeginTime:"
+ "setFillMode:"
+ "setFromValue:"
+ "setLocations:"
+ "setPrefersCompactNumberPadLayout:"
+ "setToValue:"
+ "toolbar"
+ "toolbarSuperviewObservation"
+ "v32@0:8@?16d24"
+ "v40@0:8@\"UIEditMenuInteraction\"16@\"UIEditMenuConfiguration\"24@\"<UIEditMenuInteractionAnimating>\"32"
+ "viewIsAppearing:"
+ "viewWillDisappear:"
+ "{CGRect={CGPoint=dd}{CGSize=dd}}32@0:8@\"UIEditMenuInteraction\"16@\"UIEditMenuConfiguration\"24"
+ "{CGRect={CGPoint=dd}{CGSize=dd}}32@0:8@16@24"
- "\nbackground-color: "
- "#reevaluatePaginationData ordinal %ld did NOT actually change: size %s"
- "#reevaluatePaginationData ordinal %ld did actually change. New Size: %s"
- "-webkit-filter: invert("
- "//  Copyright © 2019 Apple Inc. All rights reserved.\nReflect.defineProperty(window,'__ibooks_image_filter',{value:{},writable:!1}),(e=>{e._applyImageElementFilter=function(e,t){if('true'!==e.getAttribute('__ibooks_respect_image_size')){const i=new URL(e.src);window.matchMedia&&window.matchMedia('(prefers-color-scheme: dark)').matches&&i.searchParams.set('be_interfaceStyle','dark'),i.searchParams.set('be_filter',t),e.src=i.toString()}},e.refetchVisibleImages=function(t){const i=document.querySelectorAll('img[src*=\"ibooksimg:\"]'),r=i.length;for(let a=0;a<r;a++){const r=i[a];e._applyImageElementFilter(r,t)}}})(__ibooks_image_filter);\n"
- "Adding %ld operations for key: %s"
- "Capturing #pageCount:%ld for ordinal:%ld"
- "Completed pagination of %s"
- "Delaying running pagination JS information gathering for ordinal: %ld while our webView was in a transitionary state! be_contentView.size:%s webView.size:%s attempts: %ld WKScrollViewHasAnimations: %{bool}d WKContentViewHasAnimations: %{bool}d"
- "No signals will be fired that we're done so pagination will never be 'done' and things will be messed up"
- "Operation canceled for ordinal: %ld operation %@ webViewKey:%s"
- "Paginate: %ld using webView:%s #contentConfig:%s op:%s"
- "Running pagination for ordinal: %ld after %ld attempts.\n    Current Sizes: be_contentView.size:%f webView.size:%f"
- "Updated content size of %ld from %s to %s"
- "We did not have `self` inside our `paginationCompletion`."
- "animationKeys"
- "changeTextTransition"
- "hmm"
- "isFooterVisible"
- "isScrubberVisibleSubject"
```
