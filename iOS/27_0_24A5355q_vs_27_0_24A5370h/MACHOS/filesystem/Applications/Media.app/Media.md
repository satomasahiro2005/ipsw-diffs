## Media

> `/Applications/Media.app/Media`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb8468` | `0xbc0e4` | **`+0x3c7c`** |
| `__TEXT.__objc_methname` | `0x78c5` | `0x7e45` | **`+0x580`** |
| `__DATA.__objc_data` | `0x2f60` | `0x3398` | **`+0x438`** |
| `__TEXT.__objc_stubs` | `0x3a60` | `0x3ce0` | **`+0x280`** |
| `__DATA.__objc_const` | `0x4070` | `0x42e0` | **`+0x270`** |
| `__TEXT.__objc_methtype` | `0x2bd1` | `0x2d91` | **`+0x1c0`** |
| `__DATA.__data` | `0x4ad0` | `0x4c80` | **`+0x1b0`** |
| `__TEXT.__constg_swiftt` | `0x3444` | `0x3598` | **`+0x154`** |
| `__TEXT.__eh_frame` | `0xf34` | `0x106c` | **`+0x138`** |
| `__DATA_CONST.__const` | `0x4410` | `0x4528` | **`+0x118`** |
| `__TEXT.__objc_methlist` | `0x1ffc` | `0x2104` | **`+0x108`** |
| `__DATA.__objc_selrefs` | `0x1970` | `0x1a70` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x1de0` | `0x1ec8` | **`+0xe8`** |
| `__TEXT.__const` | `0x6cd4` | `0x6db4` | **`+0xe0`** |
| `__TEXT.__swift5_typeref` | `0x75b2` | `0x7690` | **`+0xde`** |
| `__TEXT.__objc_classname` | `0xb54` | `0xbf4` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x19cd` | `0x1a5d` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x176c` | `0x17fc` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x191a` | `0x199a` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0xdec` | `0xe3c` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x3060` | `0x3090` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x3a89` | `0x3ab9` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xa70` | `0xa90` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1840` | `0x1858` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0xdc8` | `0xde0` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x150` | `0x168` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x1d0` | `0x1e0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x184` | `0x190` | **`+0xc`** |
| `__DATA_CONST.__objc_protorefs` | `0xe8` | `0xf0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-331.1.0.0.0
+334.0.0.0.0

-  Functions: 3179
-  Symbols:   1437
-  CStrings:  1855
+  Functions: 3251
+  Symbols:   1446
+  CStrings:  1908
Symbols:
+ _$s10Foundation12NotificationV8userInfoSDys11AnyHashableVypGSgvg
+ _CGRectGetMinY
+ _NSClassFromString
+ _OBJC_CLASS_$_UIFocusGuide
+ _OBJC_CLASS_$_UIFocusUpdateContext
+ _OBJC_CLASS_$_UIPresentationController
+ _OBJC_METACLASS_$_UIPresentationController
+ _UIFocusDidUpdateNotification
+ _UIFocusUpdateContextKey
CStrings:
+ "@\"<UIViewControllerAnimatedTransitioning>\"24@0:8@\"UIViewController\"16"
+ "@\"<UIViewControllerAnimatedTransitioning>\"40@0:8@\"UIViewController\"16@\"UIViewController\"24@\"UIViewController\"32"
+ "@\"<UIViewControllerInteractiveTransitioning>\"24@0:8@\"<UIViewControllerAnimatedTransitioning>\"16"
+ "@\"UIPresentationController\"40@0:8@\"UIViewController\"16@\"UIViewController\"24@\"UIViewController\"32"
+ "Media.RadioSheetPresentationController"
+ "Media.SheetTransitioningDelegate"
+ "Media/RadioUIMenuButton.swift"
+ "T{CGRect={CGPoint=dd}{CGSize=dd}},N,R"
+ "UIViewControllerTransitioningDelegate"
+ "_TtC5Media17RadioUIMenuButton"
+ "_TtC5Media26SheetTransitioningDelegate"
+ "_TtC5Media32RadioSheetPresentationController"
+ "_UIContextMenuCell"
+ "addLayoutGuide:"
+ "animateAlongsideTransition:completion:"
+ "animationControllerForDismissedController:"
+ "animationControllerForPresentedController:presentingController:sourceController:"
+ "bottomGuide"
+ "boundary leave detected — dismissing menu"
+ "containerViewWillLayoutSubviews"
+ "contextMenuInteraction"
+ "contextMenuInteraction:willDisplayMenuForConfiguration:animator:"
+ "contextMenuInteraction:willEndForConfiguration:animator:"
+ "convertRect:toView:"
+ "dimmingView"
+ "dismissMenu"
+ "dismissalTransitionWillBegin"
+ "focusObservation"
+ "frameOfPresentedViewInContainerView"
+ "horizontalInset"
+ "ignoreLocalRenderingModeForNowPlayingViewController:"
+ "init()"
+ "init(presentedViewController:presenting:)"
+ "initWithPresentedViewController:presentingViewController:"
+ "insertSubview:atIndex:"
+ "interactionControllerForDismissal:"
+ "interactionControllerForPresentation:"
+ "isDismissing"
+ "owningView"
+ "presentationControllerForPresentedViewController:presentingViewController:sourceViewController:"
+ "presentationTransitionWillBegin"
+ "presentedView"
+ "presentedViewController"
+ "presentingViewController"
+ "removeLayoutGuide:"
+ "safeAreaInsets"
+ "setFrame:"
+ "setPreferredFocusEnvironments:"
+ "setTransitioningDelegate:"
+ "soundSettingsTransitioningDelegate"
+ "superview"
+ "systemBackgroundColor"
+ "topGuide"
+ "transitionCoordinator"
+ "v16@?0@\"<UIViewControllerTransitionCoordinatorContext>\"8"
- "Media/RadioOptionsButton.swift"
- "Media/RadioSourcesButton.swift"
```
