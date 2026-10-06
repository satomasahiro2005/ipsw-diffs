## NotesUI

> `/System/Library/PrivateFrameworks/NotesUI.framework/NotesUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2acc20` | `0x2b4058` | **`+0x7438`** |
| `__TEXT.__oslogstring` | `0x9937` | `0xa002` | **`+0x6cb`** |
| `__TEXT.__swift5_typeref` | `0xc34e` | `0xc6ec` | **`+0x39e`** |
| `__AUTH_CONST.__objc_const` | `0x245d8` | `0x24840` | **`+0x268`** |
| `__TEXT.__const` | `0x9b64` | `0x9d64` | **`+0x200`** |
| `__DATA.__data` | `0x55d4` | `0x578c` | **`+0x1b8`** |
| `__DATA.__bss` | `0x4370` | `0x4500` | **`+0x190`** |
| `__AUTH_CONST.__cfstring` | `0xc2a0` | `0xc400` | **`+0x160`** |
| `__TEXT.__cstring` | `0x13de7` | `0x13f37` | **`+0x150`** |
| `__TEXT.__objc_methlist` | `0x172e0` | `0x173e8` | **`+0x108`** |
| `__AUTH.__objc_data` | `0x3fb8` | `0x40a8` | **`+0xf0`** |
| `__TEXT.__constg_swiftt` | `0x391c` | `0x3a00` | **`+0xe4`** |
| `__TEXT.__unwind_info` | `0x9ab0` | `0x9b90` | **`+0xe0`** |
| `__TEXT.__swift5_reflstr` | `0x1f87` | `0x2047` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x9e18` | `0x9d68` | **`-0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0x10078` | `0x10110` | **`+0x98`** |
| `__DATA_CONST.__got` | `0x2e00` | `0x2e90` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x6420` | `0x6488` | **`+0x68`** |
| `__TEXT.__swift5_fieldmd` | `0x22dc` | `0x2344` | **`+0x68`** |
| `__DATA_DIRTY.__data` | `0x24c0` | `0x2460` | **`-0x60`** |
| `__AUTH_CONST.__auth_got` | `0x3160` | `0x31a0` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x46f8` | `0x4730` | **`+0x38`** |
| `__TEXT.__swift5_assocty` | `0x7c0` | `0x7f0` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x48cc` | `0x48f0` | **`+0x24`** |
| `__DATA_CONST.__objc_classlist` | `0xac0` | `0xad8` | **`+0x18`** |
| `__DATA_DIRTY.__objc_data` | `0x4010` | `0x4028` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x244` | `0x258` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x3e8` | `0x3f4` | **`+0xc`** |
| `__DATA_CONST.__objc_protolist` | `0x3b8` | `0x3c0` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x168` | `0x170` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x6b0` | `0x6b8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x2e4` | `0x2ec` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1244` | `0x1248` | **`+0x4`** |
| `__TEXT.__swift5_capture` | `0x1ed8` | `0x1edc` | **`+0x4`** |

### Other Changes

```diff

-2985.0.0.202.2
+2991.0.0.0.0

-  Functions: 14783
-  Symbols:   15916
-  CStrings:  3211
+  Functions: 14839
+  Symbols:   15986
+  CStrings:  3249
Symbols:
+ +[ICSystemPaperTextAttachment flushAllPendingPaperChanges]
+ +[UIAction(IC) ic_showInFolderActionWithHandler:]
+ -[ICSinglePixelHorizontalLineView sizeLayoutAttribute]
+ -[ICSinglePixelLineView addSizeConstraint]
+ -[ICSinglePixelLineView findSizeLayoutConstraintIfExists]
+ -[ICSinglePixelLineView hasSetUpSizeConstraint]
+ -[ICSinglePixelLineView ic_displayScale]
+ -[ICSinglePixelLineView setHasSetUpSizeConstraint:]
+ -[ICSinglePixelLineView setUpSizeConstraintIfNecessary]
+ -[ICSinglePixelLineView updateConstraints]
+ -[ICSinglePixelVerticalLineView sizeLayoutAttribute]
+ -[ICSystemPaperTextAttachment _commonInit]
+ -[ICSystemPaperTextAttachment _flushPendingPaperChange]
+ -[ICThumbnailService hasInFlightGenerationForConfiguration:]
+ -[NotesBackgroundView _ic_textLayoutFragmentHitTestableViewAtPoint:inView:]
+ -[UICollectionView(IC) ic_selectAllItemsAnimated:]
+ -[UICollectionView(IC) ic_selectAllItems]
+ _ICNoteFastSyncSessionActiveDidChangeNotification
+ _ICPaperSearchIndexerGetPDFPageString
+ _ICThumbnailGeneratorNoteSignpostLog.log
+ _ICThumbnailGeneratorNoteSignpostLog.onceToken
+ _ICWidgetKindQuickNote
+ _OBJC_CLASS_$_ICSinglePixelHorizontalLineView
+ _OBJC_CLASS_$_ICSinglePixelLineView
+ _OBJC_CLASS_$_ICSinglePixelVerticalLineView
+ _OBJC_IVAR_$_ICSinglePixelLineView._hasSetUpSizeConstraint
+ _OBJC_METACLASS_$_ICSinglePixelHorizontalLineView
+ _OBJC_METACLASS_$_ICSinglePixelLineView
+ _OBJC_METACLASS_$_ICSinglePixelVerticalLineView
+ __OBJC_$_INSTANCE_METHODS_ICSinglePixelHorizontalLineView
+ __OBJC_$_INSTANCE_METHODS_ICSinglePixelLineView
+ __OBJC_$_INSTANCE_METHODS_ICSinglePixelVerticalLineView
+ __OBJC_$_INSTANCE_VARIABLES_ICSinglePixelLineView
+ __OBJC_$_PROP_LIST_ICSinglePixelLineView
+ __OBJC_$_PROTOCOL_REFS_ICAXTextLayoutFragmentHitTestable
+ __OBJC_CLASS_RO_$_ICSinglePixelHorizontalLineView
+ __OBJC_CLASS_RO_$_ICSinglePixelLineView
+ __OBJC_CLASS_RO_$_ICSinglePixelVerticalLineView
+ __OBJC_LABEL_PROTOCOL_$_ICAXTextLayoutFragmentHitTestable
+ __OBJC_METACLASS_RO_$_ICSinglePixelHorizontalLineView
+ __OBJC_METACLASS_RO_$_ICSinglePixelLineView
+ __OBJC_METACLASS_RO_$_ICSinglePixelVerticalLineView
+ __OBJC_PROTOCOL_$_ICAXTextLayoutFragmentHitTestable
+ __OBJC_PROTOCOL_REFERENCE_$_ICAXTextLayoutFragmentHitTestable
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9fqe220106Em
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ ___60-[ICThumbnailService hasInFlightGenerationForConfiguration:]_block_invoke
+ ___ICThumbnailGeneratorNoteSignpostLog_block_invoke
+ ___block_descriptor_80_e8_32s40s48s56bs64r72r_e27_v40?08{_NSRange=QQ}16^B32ls56l8s32l8r64l8s40l8s48l8r72l8
+ ___swift_closure_destructor.171Tm
+ ___swift_closure_destructor.22Tm
+ ___swift_closure_destructor.34Tm
+ _associated conformance 7NotesUI36DynamicTextSizeLimitedOnlyByWhatFits33_84AEAF20244DF014EA2B1246A9CFA161LLV05SwiftB012ViewModifierAA4BodyAeFP_AE0R0
+ _get_witness_table 7SwiftUI12ViewThatFitsVyAA12TupleContentVyAA0C0PAAE15dynamicTypeSizeyQrqd__SXRd__AA07DynamiciJ0O5BoundRtd__lFQOyAA01_c9Modifier_G0Vy05NotesB00k4Textj17LimitedOnlyByWhatE033_84AEAF20244DF014EA2B1246A9CFA161LLVG_s19PartialRangeThroughVyAJGQo__AgAEAHyQrqd__SXRd__AjLRSlFQOyAS_s0Z9RangeUpToVyAJGQo_A_A_A_A_AWA_A_A_A_A_AWQPGGAaFHPyHC
+ _get_witness_table 7SwiftUI4ViewRzlAA15ModifiedContentVyx05NotesB036DynamicTextSizeLimitedOnlyByWhatFits33_84AEAF20244DF014EA2B1246A9CFA161LLVGAaBHPxAaBHD1__AhA0C8ModifierHPyHCHC
+ _objc_retain_x12
+ _symbolic SaySo24ICThumbnailConfigurationCG
+ _symbolic _____ 7NotesUI27SystemPaperThumbnailServiceC22QuickNoteWidgetContext33_675513D4B9F6791B95CEC757F8ECB79FLLV
+ _symbolic _____ 7NotesUI36DynamicTextSizeLimitedOnlyByWhatFits33_84AEAF20244DF014EA2B1246A9CFA161LLV
+ _symbolic _____ 7SwiftUI4AxisO3SetV
+ _symbolic _____ So15ICThumbnailTypeV
+ _symbolic _____SgXw 7NotesUI27SystemPaperThumbnailServiceC
+ _symbolic _____y_____G 7SwiftUI21_ViewModifier_ContentV 05NotesB036DynamicTextSizeLimitedOnlyByWhatFits33_84AEAF20244DF014EA2B1246A9CFA161LLV
+ _symbolic _____y_____G s16PartialRangeUpToV 7SwiftUI15DynamicTypeSizeO
+ _symbolic _____y_____G s19PartialRangeThroughV 7SwiftUI15DynamicTypeSizeO
+ _symbolic _____y______G 7Combine10PublishersO12HandleEventsV So20NSNotificationCenterC10FoundationE9PublisherV
+ _symbolic _____y______GSg 7Combine10PublishersO12HandleEventsV So20NSNotificationCenterC10FoundationE9PublisherV
+ _symbolic _____y___________y_____y_____y_____G______y_____GQo_______yAF______yAHGQo_A4mj5mJQPGG 7SwiftUI13_VariadicViewO4TreeV AA16_SizeFittingRootV AA12TupleContentV AA0D0PAAE011dynamicTypeF0yQrqd__SXRd__AA07DynamiclF0O5BoundRtd__lFQO AA01_d9Modifier_J0V 05NotesB00m4TextF21LimitedOnlyByWhatFits33_84AEAF20244DF014EA2B1246A9CFA161LLV s19PartialRangeThroughV AN AkAEALyQrqd__SXRd__AnPRSlFQO s16PartialRangeUpToV
+ _symbolic _____y______y_AAy______GSo9NSRunLoopCGG 7Combine10PublishersO12HandleEventsV AC8DebounceV So20NSNotificationCenterC10FoundationE9PublisherV
+ _symbolic _____y______y_AAy______GSo9NSRunLoopCGGSg 7Combine10PublishersO12HandleEventsV AC8DebounceV So20NSNotificationCenterC10FoundationE9PublisherV
+ _symbolic _____y______y_AAy______GxGGSg 7Combine10PublishersO12HandleEventsV AC8DebounceV So20NSNotificationCenterC10FoundationE9PublisherV
+ _symbolic _____y______y______GG 7Combine10PublishersO12HandleEventsV AC6FilterV So20NSNotificationCenterC10FoundationE9PublisherV
+ _symbolic _____y______y______GGSg 7Combine10PublishersO12HandleEventsV AC6FilterV So20NSNotificationCenterC10FoundationE9PublisherV
+ _symbolic _____y______y______GSo9NSRunLoopCG 7Combine10PublishersO8DebounceV AC12HandleEventsV So20NSNotificationCenterC10FoundationE9PublisherV
+ _symbolic _____y______y__________G_____y______y_AFy______GSo9NSRunLoopCGGAFy______y_AHGGAIG 7Combine10PublishersO6Merge4V AA5EmptyV 10Foundation12NotificationV s5NeverO AC12HandleEventsV AC8DebounceV So20NSNotificationCenterCAHE9PublisherV AC6FilterV
+ _symbolic _____y______y______y__________G_____y______y_AGy______GSo9NSRunLoopCGGAGy______y_AIGGAJGytG 7Combine10PublishersO3MapV AC6Merge4V AA5EmptyV 10Foundation12NotificationV s5NeverO AC12HandleEventsV AC8DebounceV So20NSNotificationCenterCAJE9PublisherV AC6FilterV
+ _symbolic _____y______y______y______y______y______y_ShySo15NSManagedObjectCG_____GACy______AIGGACy______y_ALSo9NSRunLoopCGAHGGSo6ICNoteCGGSo17OS_dispatch_queueCG 7Combine10PublishersO8DebounceV AC6FilterV AC10CompactMapV AC5MergeV AC04FlatF0V AC8SequenceV s5NeverO So20NSNotificationCenterC10FoundationE9PublisherV AC9ReceiveOnV
+ _symbolic _____y______y______y______y______y______y_ShySo15NSManagedObjectCG_____GACy______AIGGACy______y_ALSo9NSRunLoopCGAHGGSo6ICNoteCGGSo17OS_dispatch_queueCGSg 7Combine10PublishersO8DebounceV AC6FilterV AC10CompactMapV AC5MergeV AC04FlatF0V AC8SequenceV s5NeverO So20NSNotificationCenterC10FoundationE9PublisherV AC9ReceiveOnV
+ _symbolic _____y_____y_____G______y_____GQo_ 7SwiftUI4ViewPAAE15dynamicTypeSizeyQrqd__SXRd__AA07DynamiceF0O5BoundRtd__lFQO AA01_C16Modifier_ContentV 05NotesB00g4TextF21LimitedOnlyByWhatFits33_84AEAF20244DF014EA2B1246A9CFA161LLV s16PartialRangeUpToV AF
+ _symbolic _____y_____y_____G______y_____GQo_ 7SwiftUI4ViewPAAE15dynamicTypeSizeyQrqd__SXRd__AA07DynamiceF0O5BoundRtd__lFQO AA01_C16Modifier_ContentV 05NotesB00g4TextF21LimitedOnlyByWhatFits33_84AEAF20244DF014EA2B1246A9CFA161LLV s19PartialRangeThroughV AF
+ _symbolic _____y_____y_____G______y_____GQo_______yAC______yAEGQo_A4jg5jGt 7SwiftUI4ViewPAAE15dynamicTypeSizeyQrqd__SXRd__AA07DynamiceF0O5BoundRtd__lFQO AA01_C16Modifier_ContentV 05NotesB00g4TextF21LimitedOnlyByWhatFits33_84AEAF20244DF014EA2B1246A9CFA161LLV s19PartialRangeThroughV AF AcAEADyQrqd__SXRd__AfHRSlFQO s0xY4UpToV
+ _symbolic _____y_____y_____y_____y_____G______y_____GQo_______yAE______yAGGQo_A4li5lIQPGG 7SwiftUI12ViewThatFitsV AA12TupleContentV AA0C0PAAE15dynamicTypeSizeyQrqd__SXRd__AA07DynamiciJ0O5BoundRtd__lFQO AA01_c9Modifier_G0V 05NotesB00k4Textj17LimitedOnlyByWhatE033_84AEAF20244DF014EA2B1246A9CFA161LLV s19PartialRangeThroughV AJ AgAEAHyQrqd__SXRd__AjLRSlFQO s0Z9RangeUpToV
+ _symbolic _____yx_____G 7SwiftUI15ModifiedContentV 05NotesB036DynamicTextSizeLimitedOnlyByWhatFits33_84AEAF20244DF014EA2B1246A9CFA161LLV
+ _type_layout_string 7NotesUI36DynamicTextSizeLimitedOnlyByWhatFits33_84AEAF20244DF014EA2B1246A9CFA161LLV
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorIfNS_9allocatorIfEEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9fqe220100Em
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- ___block_descriptor_80_e8_32s40s48s56bs64r72r_e27_v40?08{_NSRange=QQ}16^B32ls56l8r64l8s32l8r72l8s40l8s48l8
- ___swift_closure_destructor.16Tm
- ___swift_closure_destructor.182Tm
- ___swift_closure_destructor.35Tm
- ___swift_closure_destructor.47Tm
- _allocateMultiDimensionalBuffer
- _symbolic _____y______GSg 7Combine10PublishersO6FilterV So20NSNotificationCenterC10FoundationE9PublisherV
- _symbolic _____y______So9NSRunLoopCG 7Combine10PublishersO8DebounceV So20NSNotificationCenterC10FoundationE9PublisherV
- _symbolic _____y______So9NSRunLoopCGSg 7Combine10PublishersO8DebounceV So20NSNotificationCenterC10FoundationE9PublisherV
- _symbolic _____y______xGSg 7Combine10PublishersO8DebounceV So20NSNotificationCenterC10FoundationE9PublisherV
- _symbolic _____y______y__________G_____y______So9NSRunLoopCG_____y_AGGAGG 7Combine10PublishersO6Merge4V AA5EmptyV 10Foundation12NotificationV s5NeverO AC8DebounceV So20NSNotificationCenterCAHE9PublisherV AC6FilterV
- _symbolic _____y______y______y__________G_____y______So9NSRunLoopCG_____y_AHGAHGytG 7Combine10PublishersO3MapV AC6Merge4V AA5EmptyV 10Foundation12NotificationV s5NeverO AC8DebounceV So20NSNotificationCenterCAJE9PublisherV AC6FilterV
CStrings:
+ "Accelerating Quick Note thumbnails on background"
+ "Cannot render Quick Note widget thumbnail pair: note unavailable {identifier: %s}"
+ "Failed to crop Large widget thumbnail from XL {cropRect: %fx%f, sourceSize: %ldx%ld}"
+ "Failed to derive Large widget thumbnail: XL source has no CGImage backing"
+ "Flushing pending paper change for %@"
+ "ICNoteFastSyncSessionActiveDidChange"
+ "Show in Enclosing Folder"
+ "ThumbnailGeneration"
+ "[QNDBG] Thumbnail generation start {type: %ld}"
+ "[QNDBG] WidgetTimelineReloader contextDidSave (will debounce)"
+ "[QNDBG] WidgetTimelineReloader contextDidSave fired after debounce"
+ "[QNDBG] WidgetTimelineReloader didFinishBackgroundFetch fired"
+ "[QNDBG] WidgetTimelineReloader reloadAllTimelines"
+ "[QNDBG] WidgetTimelineReloader willResignActive fired"
+ "[QNDBG] ensureThumbnailsOnBackground accelerating regen {noteId: %s}"
+ "[QNDBG] ensureThumbnailsOnBackground enter"
+ "[QNDBG] ensureThumbnailsOnBackground expired before completion {noteId: %s}"
+ "[QNDBG] ensureThumbnailsOnBackground generation already in flight, skipping {noteId: %s}"
+ "[QNDBG] ensureThumbnailsOnBackground no recent QN, skipping"
+ "[QNDBG] ensureThumbnailsOnBackground thumbnails fresh, skipping {noteId: %s}"
+ "[QNDBG] invalidateCacheConfigurations cleared {noteId: %s}"
+ "[QNDBG] invalidateCacheConfigurations enter {noteId: %s}"
+ "[QNDBG] regenerateThumbnailsIfMissing enter"
+ "[QNDBG] regenerateThumbnailsIfMissing found missing or stale, regenerating {noteId: %s}"
+ "[QNDBG] regenerateThumbnailsIfMissing no recent QN, skipping"
+ "[QNDBG] regenerateThumbnailsIfMissing thumbnails present and fresh, skipping {noteId: %s}"
+ "[QNDBG] updateIfNeeded(for notes:) completion, notify when done"
+ "[QNDBG] updateIfNeeded(for notes:) enter {count: %ld}"
+ "[QNDBG] widgetThumbnail nil {type: %s, thumbnailId: %s, imageUrlExists: %{bool}d, imageUrl: %s}"
+ "_ICSystemPaperTextAttachmentShouldFlushPendingChangesNotification"
+ "appearance.darkmode"
+ "appearance.lightmode"
+ "clock.badge.checkmark"
+ "clock.badge.xmark"
+ "exclamationmark.triangle"
+ "hammer"
+ "paragraph"
+ "tag.slash"
+ "text.line.2.summary"
+ "type=%ld"
- "Cannot retrieve widget thumbnail {accountId: %s, noteId: %s, url: %s}"
- "text.line.3.summary"
```
