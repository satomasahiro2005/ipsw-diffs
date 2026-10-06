## ADFollowUpExtension

> `/System/Library/ExtensionKit/Extensions/ADFollowUpExtension.appex/ADFollowUpExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a424` | `0x17458` | **`-0x2fcc`** |
| `__TEXT.__objc_stubs` | `0x1320` | `0xcc0` | **`-0x660`** |
| `__TEXT.__objc_methname` | `0x18b1` | `0x1364` | **`-0x54d`** |
| `__DATA.__objc_data` | `0x768` | `0x4e8` | **`-0x280`** |
| `__DATA.__objc_selrefs` | `0x688` | `0x4d0` | **`-0x1b8`** |
| `__DATA.__objc_const` | `0x950` | `0x8b0` | **`-0xa0`** |
| `__TEXT.__swift5_typeref` | `0x4fc` | `0x474` | **`-0x88`** |
| `__DATA.__bss` | `0x658` | `0x5d8` | **`-0x80`** |
| `__DATA.__data` | `0x758` | `0x6d8` | **`-0x80`** |
| `__TEXT.__objc_methtype` | `0x811` | `0x791` | **`-0x80`** |
| `__TEXT.__constg_swiftt` | `0x4b0` | `0x434` | **`-0x7c`** |
| `__TEXT.__const` | `0x8ac` | `0x848` | **`-0x64`** |
| `__TEXT.__objc_methlist` | `0x474` | `0x414` | **`-0x60`** |
| `__TEXT.__oslogstring` | `0xb2d` | `0xb7d` | **`+0x50`** |
| `__TEXT.__cstring` | `0x64b` | `0x601` | **`-0x4a`** |
| `__DATA_CONST.__got` | `0x2f0` | `0x2a8` | **`-0x48`** |
| `__DATA_CONST.__auth_ptr` | `0x220` | `0x260` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x520` | `0x4e8` | **`-0x38`** |
| `__TEXT.__auth_stubs` | `0x1580` | `0x15a0` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x254` | `0x234` | **`-0x20`** |
| `__TEXT.__swift5_assocty` | `0x60` | `0x48` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x14` | **`-0x14`** |
| `__TEXT.__objc_classname` | `0x1f1` | `0x202` | **`+0x11`** |
| `__DATA_CONST.__auth_got` | `0xad0` | `0xae0` | **`+0x10`** |
| `__DATA.__common` | `0x40` | `0x48` | **`+0x8`** |
| `__DATA.__objc_stublist` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x6c8` | `0x6c0` | **`-0x8`** |
| `__DATA_CONST.__objc_catlist2` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x28` | **`-0x8`** |
| `__TEXT.__swift5_capture` | `0x174` | `0x178` | **`+0x4`** |
| `__TEXT.__swift5_proto` | `0x30` | `0x2c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4.0.37.0.0
+4.0.39.0.0

+  - /System/Library/PrivateFrameworks/AppDistributionUI.framework/AppDistributionUI

-  - /System/Library/PrivateFrameworks/OnBoardingKit.framework/OnBoardingKit

-  - /System/Library/PrivateFrameworks/UIFoundation.framework/UIFoundation

-  Functions: 363
-  Symbols:   249
-  CStrings:  399
+  Functions: 348
+  Symbols:   232
+  CStrings:  334
Symbols:
+ _OBJC_METACLASS_$__TtC17AppDistributionUI33ConfirmationSheetLayoutController
+ _swift_initClassMetadata2
- _CGRectGetWidth
- _OBJC_CLASS_$_NSLayoutConstraint
- _OBJC_CLASS_$_OBBoldTrayButton
- _OBJC_CLASS_$_OBLinkTrayButton
- _OBJC_CLASS_$_OBWelcomeController
- _OBJC_CLASS_$_UIDevice
- _OBJC_CLASS_$_UIFont
- _OBJC_CLASS_$_UIImageView
- _OBJC_CLASS_$_UILabel
- _OBJC_CLASS_$_UILayoutGuide
- _OBJC_CLASS_$_UIStackView
- _OBJC_CLASS_$_UITapGestureRecognizer
- _OBJC_METACLASS_$_OBWelcomeController
- _UIFontTextStyleBody
- _UIFontTextStyleHeadline
- _objc_release_x9
- _swift_dynamicCastObjCClass
- _swift_isUniquelyReferenced_nonNull_bridgeObject
- _swift_release_x25
CStrings:
+ "[%s] Primary button press ignored; Oslo authentication already in progress"
+ "primaryActionState"
- "_systemImageNamed:"
- "_systemImageNamed:withConfiguration:"
- "activateConstraints:"
- "addArrangedSubview:"
- "addButton:"
- "addGestureRecognizer:"
- "animateAlongsideTransition:completion:"
- "animateWithDuration:animations:"
- "arrangedSubviews"
- "boldButton"
- "bounds"
- "buttonLayoutGuide"
- "buttonTray"
- "buttonTrayLandscapeConstraints"
- "buttonTrayPortraitLeadingConstraint"
- "buttonTrayPortraitTrailingConstraint"
- "constraintGreaterThanOrEqualToAnchor:constant:"
- "constraintLessThanOrEqualToConstant:"
- "constraints"
- "contentView"
- "currentDevice"
- "deactivateConstraints:"
- "firstAttribute"
- "firstItem"
- "headerView"
- "info.circle.fill"
- "initWithImage:"
- "initWithTarget:action:"
- "isIPad"
- "layoutIfNeeded"
- "linkButton"
- "moreInformationPressed"
- "navigationItem"
- "preferredFontForTextStyle:"
- "primaryButton"
- "primaryButtonPressed"
- "removeArrangedSubview:"
- "responseHandled"
- "secondItem"
- "secondaryButton"
- "secondaryButtonPressed"
- "secondaryLabelColor"
- "sectionConstraints"
- "setAxis:"
- "setConstant:"
- "setContentMode:"
- "setDefinesPresentationContext:"
- "setDirectionalLayoutMargins:"
- "setDistribution:"
- "setFont:"
- "setImage:"
- "setModalInPresentation:"
- "setNumberOfLines:"
- "setPriority:"
- "setSpacing:"
- "setText:"
- "setTextColor:"
- "setTintColor:"
- "setTitle:"
- "setUserInteractionEnabled:"
- "superview"
- "systemImageNamed:"
- "userInterfaceIdiom"
- "v16@?0@\"<UIViewControllerTransitionCoordinatorContext>\"8"
- "v40@0:8{CGSize=dd}16@32"
- "valueForKey:"
- "viewWillTransitionToSize:withTransitionCoordinator:"
```
