## MobileCal

> `/private/var/staged_system_apps/MobileCal.app/MobileCal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x174ee4` | `0x177890` | **`+0x29ac`** |
| `__TEXT.__objc_methname` | `0x34ceb` | `0x351ab` | **`+0x4c0`** |
| `__TEXT.__objc_stubs` | `0x27980` | `0x27d60` | **`+0x3e0`** |
| `__DATA.__objc_const` | `0x1dec8` | `0x1e1b8` | **`+0x2f0`** |
| `__TEXT.__cstring` | `0x6a65` | `0x6d39` | **`+0x2d4`** |
| `__TEXT.__objc_methlist` | `0x17800` | `0x179e0` | **`+0x1e0`** |
| `__DATA_CONST.__got` | `0x1450` | `0x15c8` | **`+0x178`** |
| `__TEXT.__auth_stubs` | `0x31c0` | `0x32e0` | **`+0x120`** |
| `__DATA.__objc_data` | `0x5c88` | `0x5da0` | **`+0x118`** |
| `__DATA.__objc_selrefs` | `0xc200` | `0xc310` | **`+0x110`** |
| `__DATA.__bss` | `0x10d8` | `0x11c8` | **`+0xf0`** |
| `__DATA_CONST.__cfstring` | `0x5200` | `0x52e0` | **`+0xe0`** |
| `__TEXT.__const` | `0x1784` | `0x1844` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x5f98` | `0x6058` | **`+0xc0`** |
| `__DATA_CONST.__auth_got` | `0x18f0` | `0x1980` | **`+0x90`** |
| `__DATA.__data` | `0x4350` | `0x43d0` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x48b8` | `0x4928` | **`+0x70`** |
| `__TEXT.__objc_methtype` | `0x99ad` | `0x9a1d` | **`+0x70`** |
| `__DATA_CONST.__auth_ptr` | `0x4f8` | `0x558` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0xf92` | `0xff0` | **`+0x5e`** |
| `__TEXT.__gcc_except_tab` | `0x18f4` | `0x1944` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0xa8c` | `0xac8` | **`+0x3c`** |
| `__TEXT.__objc_classname` | `0x2ec8` | `0x2ef8` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x6235` | `0x6205` | **`-0x30`** |
| `__DATA.__objc_ivar` | `0x17d4` | `0x1800` | **`+0x2c`** |
| `__TEXT.__swift5_fieldmd` | `0x44c` | `0x474` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x4eb` | `0x513` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x858` | `0x868` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x558` | `0x560` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x58` | `0x60` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x4c` | `0x50` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-29906.0.0.0.0
+29909.0.0.0.0

+  - /System/Library/PrivateFrameworks/Feedback.framework/Feedback
+  - /System/Library/PrivateFrameworks/FeedbackService.framework/FeedbackService

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 8300
-  Symbols:   1615
-  CStrings:  10704
+  Functions: 8356
+  Symbols:   1654
+  CStrings:  10772
Symbols:
+ _$s13CalendarUIKit27MagicComposeFeedbackPayloadO011descriptionF05eventSSSo7EKEventCSg_tFZ
+ _$s15FeedbackService14FBKSEvaluationC7SubjectO11interactionyAeA15FBKSInteractionCcAEmFWC
+ _$s15FeedbackService14FBKSEvaluationC7SubjectOMa
+ _$s15FeedbackService15FBKSInteractionC13FeatureDomainO8skipEnumyA2EmFWC
+ _$s15FeedbackService15FBKSInteractionC13FeatureDomainOMa
+ _$s15FeedbackService15FBKSInteractionC13featureDomain8bundleID16prefillQuestions24originalAnnotatedContent09generatedkL005extraL012modelVersion11diagnostics16auxiliaryMetrics14isHighPriorityA2C07FeatureE0O_SSSgSDyAA8FBKSFormC8QuestionOSaySSGGSgAC0kL0VSgAZSayAYGA2PSDySSSiGSgSbtcfc
+ _$s15FeedbackService15FBKSInteractionC16AnnotatedContentV12displayOrderSiSgvs
+ _$s15FeedbackService15FBKSInteractionC16AnnotatedContentV7payload11displayName11description04fileH05group8iconType14additionalInfoAeC0E0O_S4SSgAE04IconM0OSgSDyS2SGSgtcfC
+ _$s15FeedbackService15FBKSInteractionC16AnnotatedContentV8IconTypeOMa
+ _$s15FeedbackService15FBKSInteractionC16AnnotatedContentV8IconTypeOMn
+ _$s15FeedbackService15FBKSInteractionC16AnnotatedContentVMa
+ _$s15FeedbackService15FBKSInteractionC16AnnotatedContentVMn
+ _$s15FeedbackService15FBKSInteractionC16prefillQuestionsSDyAA8FBKSFormC8QuestionOSaySSGGSgvsTj
+ _$s15FeedbackService15FBKSInteractionC7ContentO4textyAESScAEmFWC
+ _$s15FeedbackService15FBKSInteractionC7ContentOMa
+ _$s15FeedbackService15FBKSInteractionCMa
+ _$s15FeedbackService8FBKSFormC8QuestionO13featureDomainyA2EmFWC
+ _$s15FeedbackService8FBKSFormC8QuestionO5titleyA2EmFWC
+ _$s15FeedbackService8FBKSFormC8QuestionOMa
+ _$s15FeedbackService8FBKSFormC8QuestionOMn
+ _$s15FeedbackService8FBKSFormC8QuestionOSHAAMc
+ _$s15FeedbackService8FBKSFormC8QuestionOSQAAMc
+ _$s8Feedback23FBKEvaluationControllerC21userDidReportAConcern7subject04showA4Form25associateWithAppleAccounty0A7Service14FBKSEvaluationC7SubjectO_S2bSgtFTj
+ _$s8Feedback23FBKEvaluationControllerC8delegateAcA0bC24DelegateDynamicPresenter_p_tcfC
+ _$s8Feedback23FBKEvaluationControllerCMa
+ _$s8Feedback23FBKEvaluationControllerCMn
+ _$s8Feedback35FBKEvaluationControllerDelegateBaseMp
+ _$s8Feedback35FBKEvaluationControllerDelegateBaseP17evaluationDidFail10controller5erroryAA0bC0C_s5Error_ptFTq
+ _$s8Feedback35FBKEvaluationControllerDelegateBaseP21evaluationDidComplete10controller0F0yAA0bC0C_0A7Service14FBKSEvaluationCtFTq
+ _$s8Feedback35FBKEvaluationControllerDelegateBaseP21evaluationDidComplete10controller8responseyAA0bC0C_AA0B0V8ResponseVtFTq
+ _$s8Feedback47FBKEvaluationControllerDelegateDynamicPresenterMp
+ _$s8Feedback47FBKEvaluationControllerDelegateDynamicPresenterP04viewC15ForPresentation10controllerSo06UIViewC0CAA0bC0C_tFTq
+ _$s8Feedback47FBKEvaluationControllerDelegateDynamicPresenterPAA0bcD4BaseTb
+ _$s8Feedback47FBKEvaluationControllerDelegateDynamicPresenterPAAE17evaluationDidFail10controller5erroryAA0bC0C_s5Error_ptF
+ _$s8Feedback47FBKEvaluationControllerDelegateDynamicPresenterPAAE21evaluationDidComplete10controller0G0yAA0bC0C_0A7Service14FBKSEvaluationCtF
+ _$s8Feedback47FBKEvaluationControllerDelegateDynamicPresenterPAAE21evaluationDidComplete10controller8responseyAA0bC0C_AA0B0V8ResponseVtF
+ _EKUIContainedControllerIdealHeight
+ _MGCopyAnswer
+ _OBJC_CLASS_$_CAShapeLayer
CStrings:
+ "@\"CAShapeLayer\""
+ "@\"MagicComposeFeedbackHandler\""
+ "@\"YearOverlayLegendView\""
+ "@40@0:8@16@24q32"
+ "Beta"
+ "Calendar Event Input"
+ "Description of the Magic Compose prompt attached to a Report a Concern submission"
+ "Description of the generated event attached to a Report a Concern submission"
+ "Display name for the event Magic Compose generated from the prompt attached to a Report a Concern submission"
+ "Display name for the user's natural-language Magic Compose prompt attached to a Report a Concern submission"
+ "Event details Calendar generated from your prompt"
+ "Hide Sidebar"
+ "Magic Compose: Report a Concern"
+ "MagicComposeFeedbackHandler"
+ "MobileCal.MagicComposeFeedbackHandler"
+ "ReleaseType"
+ "Show Sidebar"
+ "TB,N,V_prefersStackedLayout"
+ "Td,N,V_bottomPadding"
+ "The text you entered that Calendar used to generate the event"
+ "YearOverlayLegendView"
+ "_bottomPaddingForCalendarDate:"
+ "_detailViewControllerDismissesItself:"
+ "_detailViewControllerForEvent:proposedTimeAttendee:"
+ "_flattenedItemsOfGroups:"
+ "_inlineSearchCompleted"
+ "_itemWidthForLabel:"
+ "_layoutItemWithLine:label:thickness:originX:rowTop:rowHeight:"
+ "_lineLength"
+ "_magicComposeFeedbackHandler"
+ "_monthLineThickness"
+ "_monthStartLabel"
+ "_monthStartLine"
+ "_navbarLegend"
+ "_navbarLegendGeneration"
+ "_navbarLegendItem"
+ "_navigationTitleAlignment"
+ "_overlayLegend"
+ "_platterEnabled"
+ "_platterMaskLayer"
+ "_prefersCurrentContextEventPresentation"
+ "_prefersStackedLayout"
+ "_rowHeight"
+ "_setTitleAlignment:"
+ "_settleOffsetForYearHeader"
+ "_shouldShowNavbarLegend"
+ "_spacing"
+ "_tableViewStyle"
+ "_updateNavbarLegendForYear:"
+ "_yearBottomPadding"
+ "_yearLineThickness"
+ "_yearStartLabel"
+ "_yearStartLine"
+ "action"
+ "actionForLayer:forKey:"
+ "additionalTrailingBarButtonItems"
+ "allowsDividedListMode"
+ "centeredLegendTopOffsetForTraitCollection:"
+ "displayCornerRadius"
+ "drillIntoDayWithDate:animated:"
+ "feedbackController"
+ "heightForTraitCollection:inView:"
+ "initWithModel:window:tableViewStyle:"
+ "initWithPresenter:"
+ "initWithRootViewController:platterEnabled:"
+ "nextResponder"
+ "numberOfTapsRequiredForDayCellGesture"
+ "overlayYearStringForGregorianYearStartDate:inCalendar:"
+ "position"
+ "prefersStackedLayout"
+ "presenter"
+ "reportConcernWithPrompt:event:"
+ "searchResultsPresenter"
+ "setAutomaticallyShowsSearchResultsController:"
+ "setBottomPadding:"
+ "setEstimatedSectionFooterHeight:"
+ "setHidesSharedBackground:"
+ "setMagicComposeReportAConcernAction:"
+ "setPath:"
+ "setPrefersStackedLayout:"
+ "setSectionFooterHeight:"
+ "setSharesBackground:"
+ "setTitleContentAlpha:"
+ "setYearStartText:monthStartText:"
+ "singleLineHeightForTraitCollection:"
+ "stackedHeightForTraitCollection:"
+ "systemLayoutSizeFittingSize:withHorizontalFittingPriority:verticalFittingPriority:"
+ "titleContentAlpha"
+ "titleIsCenteredInView:"
+ "v24@?0@\"NSString\"8@\"EKEvent\"16"
+ "v64@0:8@16@24d32d40d48d56"
+ "validateCommand:"
+ "\xf0!"
- "The thin line already been initialized."
- "_initializeThinLine"
- "_layoutThinLine"
- "_overlayLegendMonthStartLabel"
- "_overlayLegendMonthStartLine"
- "_overlayLegendYearStartLabel"
- "_overlayLegendYearStartLine"
- "_pushDetailViewControllerForEvent:animated:showComments:proposedTimeAttendee:"
- "_supplementaryColumnViewControllerWrappingPaletteNav:forSupplementaryVC:"
- "_thinLine"
- "_thinLineColor"
- "all_on"
- "heightBetweenLineAndNumber"
- "inboxViewControllerWantsShowEvent:animated:showMode:"
- "keyboardLayoutGuide"
- "numberOfRowsInSection:"
- "overlayLegendFont"
- "overlayLegendLineLength"
- "overlayLegendMonthBaseline"
- "overlayLegendMonthLineThickness"
- "overlayLegendYearBaseline"
- "overlayLegendYearLineThickness"
- "setShowsCancelButton:"
- "thinLineHeight"
- "two_day_view"
```
