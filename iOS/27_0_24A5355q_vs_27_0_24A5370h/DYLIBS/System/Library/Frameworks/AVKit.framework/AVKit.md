## AVKit

> `/System/Library/Frameworks/AVKit.framework/AVKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25f664` | `0x2648d0` | **`+0x526c`** |
| `__AUTH_CONST.__objc_const` | `0x37f70` | `0x38bf0` | **`+0xc80`** |
| `__TEXT.__objc_methlist` | `0x1eacc` | `0x1f11c` | **`+0x650`** |
| `__TEXT.__constg_swiftt` | `0x2b3c` | `0x2f00` | **`+0x3c4`** |
| `__TEXT.__unwind_info` | `0xa668` | `0xa328` | **`-0x340`** |
| `__TEXT.__const` | `0x81d8` | `0x84f8` | **`+0x320`** |
| `__AUTH.__objc_data` | `0x6448` | `0x66c8` | **`+0x280`** |
| `__TEXT.__swift5_typeref` | `0x79e0` | `0x7c56` | **`+0x276`** |
| `__DATA.__bss` | `0x5ca8` | `0x5ea8` | **`+0x200`** |
| `__TEXT.__cstring` | `0x12e42` | `0x13039` | **`+0x1f7`** |
| `__AUTH_CONST.__cfstring` | `0x9540` | `0x9720` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0xbeb7` | `0xc03e` | **`+0x187`** |
| `__AUTH_CONST.__const` | `0x8750` | `0x8860` | **`+0x110`** |
| `__TEXT.__swift5_fieldmd` | `0x1e38` | `0x1f2c` | **`+0xf4`** |
| `__DATA_CONST.__objc_selrefs` | `0xd330` | `0xd3f0` | **`+0xc0`** |
| `__DATA.__objc_ivar` | `0x3000` | `0x3080` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x1f66` | `0x1fe6` | **`+0x80`** |
| `__DATA_CONST.__got` | `0x1720` | `0x1768` | **`+0x48`** |
| `__DATA_CONST.__objc_classlist` | `0xad8` | `0xb18` | **`+0x40`** |
| `__DATA_CONST.__objc_superrefs` | `0x7f0` | `0x830` | **`+0x40`** |
| `__DATA.__data` | `0x5b30` | `0x5b50` | **`+0x20`** |
| `__TEXT.__swift5_protos` | `0x54` | `0x74` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x2c8` | `0x2d8` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x42bc` | `0x42b0` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1f70` | `0x1f78` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x244` | `0x24c` | **`+0x8`** |

### Other Changes

```diff

-1360.56.2.0.0
+1360.61.1.0.0

-  Functions: 14724
-  Symbols:   19982
-  CStrings:  2955
+  Functions: 14951
+  Symbols:   20239
+  CStrings:  2976
Symbols:
+ +[AVPlaybackUserInterfaceContentArtwork artworkWithURL:contentType:size:]
+ +[AVPlaybackUserInterfaceContentArtwork supportsSecureCoding]
+ +[AVPlaybackUserInterfaceContentMetadata supportsSecureCoding]
+ +[AVPlaybackUserInterfaceContentMetadataTemplate supportsSecureCoding]
+ +[AVPlaybackUserInterfaceContentURLArtwork supportsSecureCoding]
+ +[AVPlaybackUserInterfaceContentVideoProperties supportsSecureCoding]
+ +[AVPlaybackUserInterfaceMediaSelectionOption supportsSecureCoding]
+ +[AVPlaybackUserInterfaceTimelineSegment supportsSecureCoding]
+ -[AVMobileGlassAuxiliaryControlsView _sizeFittingControls:compressed:]
+ -[AVMobileGlassAuxiliaryControlsView systemLayoutSizeFittingSize:]
+ -[AVMobileGlassContentTabsContentView layoutMarginsDidChange]
+ -[AVMobileGlassControlsView bottomInsetForLayoutFrame]
+ -[AVMobileGlassControlsViewController _menuElementForControlItem:]
+ -[AVMobileGlassControlsViewController _menuElementForPictureInPicture]
+ -[AVMobileGlassControlsViewController _menuElementForRoutePicker]
+ -[AVMobileGlassControlsViewController _toggleMultiview]
+ -[AVMobileGlassControlsViewController displayModeControlsView:overflowMenuElementForControlWithIdentifier:]
+ -[AVMobileGlassControlsViewController embeddedInlineLayoutMargins]
+ -[AVMobileGlassControlsViewController setEmbeddedInlineLayoutMargins:]
+ -[AVMobileGlassDisplayModeControlsView _buttonForAction:]
+ -[AVMobileGlassDisplayModeControlsView overflowButtonDidHideContextMenu:]
+ -[AVMobileGlassDisplayModeControlsView overflowButtonWillHideContextMenu:animator:]
+ -[AVMobileGlassDisplayModeControlsView overflowButtonWillShowContextMenu:animator:]
+ -[AVMobileGlassDisplayModeControlsView overflowMenuItemsForControlOverflowButton:]
+ -[AVMobileGlassDisplayModeControlsView traitCollectionDidChange:]
+ -[AVMobileGlassPlaybackControlsView _updateBackwardSecondaryControlAccessibilityLabel]
+ -[AVMobileGlassPlaybackControlsView _updateForwardSecondaryControlAccessibilityLabel]
+ -[AVMobileGlassPlaybackControlsView sizeThatFits:]
+ -[AVPlaybackUserInterfaceContentArtwork copyWithZone:]
+ -[AVPlaybackUserInterfaceContentArtwork encodeWithCoder:]
+ -[AVPlaybackUserInterfaceContentArtwork hash]
+ -[AVPlaybackUserInterfaceContentArtwork initWithCoder:]
+ -[AVPlaybackUserInterfaceContentArtwork initWithSize:]
+ -[AVPlaybackUserInterfaceContentArtwork isEqual:]
+ -[AVPlaybackUserInterfaceContentArtwork isEqualToContentArtwork:]
+ -[AVPlaybackUserInterfaceContentArtwork size]
+ -[AVPlaybackUserInterfaceContentMetadata .cxx_destruct]
+ -[AVPlaybackUserInterfaceContentMetadata artworkRepresentations]
+ -[AVPlaybackUserInterfaceContentMetadata copyWithZone:]
+ -[AVPlaybackUserInterfaceContentMetadata encodeWithCoder:]
+ -[AVPlaybackUserInterfaceContentMetadata hasAudio]
+ -[AVPlaybackUserInterfaceContentMetadata hasLegible]
+ -[AVPlaybackUserInterfaceContentMetadata hash]
+ -[AVPlaybackUserInterfaceContentMetadata initWithCoder:]
+ -[AVPlaybackUserInterfaceContentMetadata initWithTemplate:]
+ -[AVPlaybackUserInterfaceContentMetadata initWithVideoProperties:hasAudio:hasLegible:title:subtitle:artworkRepresentations:]
+ -[AVPlaybackUserInterfaceContentMetadata isEqual:]
+ -[AVPlaybackUserInterfaceContentMetadata isEqualToMetadata:]
+ -[AVPlaybackUserInterfaceContentMetadata subtitle]
+ -[AVPlaybackUserInterfaceContentMetadata title]
+ -[AVPlaybackUserInterfaceContentMetadata videoProperties]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate .cxx_destruct]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate artworkRepresentations]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate copyWithZone:]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate encodeWithCoder:]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate hasAudio]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate hasLegible]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate hash]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate initWithCoder:]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate init]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate isEqual:]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate isEqualToMetadataTemplate:]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate setArtworkRepresentations:]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate setHasAudio:]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate setHasLegible:]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate setSubtitle:]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate setTitle:]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate setVideoProperties:]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate subtitle]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate title]
+ -[AVPlaybackUserInterfaceContentMetadataTemplate videoProperties]
+ -[AVPlaybackUserInterfaceContentURLArtwork .cxx_destruct]
+ -[AVPlaybackUserInterfaceContentURLArtwork contentType]
+ -[AVPlaybackUserInterfaceContentURLArtwork copyWithZone:]
+ -[AVPlaybackUserInterfaceContentURLArtwork encodeWithCoder:]
+ -[AVPlaybackUserInterfaceContentURLArtwork hash]
+ -[AVPlaybackUserInterfaceContentURLArtwork initWithCoder:]
+ -[AVPlaybackUserInterfaceContentURLArtwork initWithURL:contentType:size:]
+ -[AVPlaybackUserInterfaceContentURLArtwork isEqual:]
+ -[AVPlaybackUserInterfaceContentURLArtwork isEqualToContentURLArtwork:]
+ -[AVPlaybackUserInterfaceContentURLArtwork url]
+ -[AVPlaybackUserInterfaceContentVideoProperties copyWithZone:]
+ -[AVPlaybackUserInterfaceContentVideoProperties encodeWithCoder:]
+ -[AVPlaybackUserInterfaceContentVideoProperties hash]
+ -[AVPlaybackUserInterfaceContentVideoProperties initWithCoder:]
+ -[AVPlaybackUserInterfaceContentVideoProperties initWithPresentationSize:]
+ -[AVPlaybackUserInterfaceContentVideoProperties isEqual:]
+ -[AVPlaybackUserInterfaceContentVideoProperties isEqualToVideoProperties:]
+ -[AVPlaybackUserInterfaceContentVideoProperties presentationSize]
+ -[AVPlaybackUserInterfaceMediaSelectionOption .cxx_destruct]
+ -[AVPlaybackUserInterfaceMediaSelectionOption copyWithZone:]
+ -[AVPlaybackUserInterfaceMediaSelectionOption displayNameWithSymbolPlaceholder]
+ -[AVPlaybackUserInterfaceMediaSelectionOption displayName]
+ -[AVPlaybackUserInterfaceMediaSelectionOption encodeWithCoder:]
+ -[AVPlaybackUserInterfaceMediaSelectionOption extendedLanguageTag]
+ -[AVPlaybackUserInterfaceMediaSelectionOption hash]
+ -[AVPlaybackUserInterfaceMediaSelectionOption identifier]
+ -[AVPlaybackUserInterfaceMediaSelectionOption initWithCoder:]
+ -[AVPlaybackUserInterfaceMediaSelectionOption initWithDisplayName:identifier:extendedLanguageTag:mediaCharacteristics:]
+ -[AVPlaybackUserInterfaceMediaSelectionOption initWithDisplayName:identifier:extendedLanguageTag:mediaCharacteristics:mediaOptionSource:]
+ -[AVPlaybackUserInterfaceMediaSelectionOption initWithMediaOptionSource:extendedLanguageTag:]
+ -[AVPlaybackUserInterfaceMediaSelectionOption isAppleMachineGenerated]
+ -[AVPlaybackUserInterfaceMediaSelectionOption isAvailable]
+ -[AVPlaybackUserInterfaceMediaSelectionOption isEqual:]
+ -[AVPlaybackUserInterfaceMediaSelectionOption isEqualToTrackOption:]
+ -[AVPlaybackUserInterfaceMediaSelectionOption mediaCharacteristics]
+ -[AVPlaybackUserInterfaceMediaSelectionOption mediaOptionSource]
+ -[AVPlaybackUserInterfacePlaybackPosition hash]
+ -[AVPlaybackUserInterfacePlaybackPosition hostTime]
+ -[AVPlaybackUserInterfacePlaybackPosition initWithPosition:hostTime:rate:]
+ -[AVPlaybackUserInterfacePlaybackPosition isEqual:]
+ -[AVPlaybackUserInterfacePlaybackPosition isEqualToPlaybackPosition:]
+ -[AVPlaybackUserInterfacePlaybackPosition position]
+ -[AVPlaybackUserInterfacePlaybackPosition rate]
+ -[AVPlaybackUserInterfaceTimelineSegment .cxx_destruct]
+ -[AVPlaybackUserInterfaceTimelineSegment copyWithZone:]
+ -[AVPlaybackUserInterfaceTimelineSegment encodeWithCoder:]
+ -[AVPlaybackUserInterfaceTimelineSegment hash]
+ -[AVPlaybackUserInterfaceTimelineSegment identifier]
+ -[AVPlaybackUserInterfaceTimelineSegment initWithCoder:]
+ -[AVPlaybackUserInterfaceTimelineSegment initWithTimeRange:segmentType:marked:requiresLinearPlayback:identifier:]
+ -[AVPlaybackUserInterfaceTimelineSegment isEqual:]
+ -[AVPlaybackUserInterfaceTimelineSegment isEqualToTimelineSegment:]
+ -[AVPlaybackUserInterfaceTimelineSegment isMarked]
+ -[AVPlaybackUserInterfaceTimelineSegment requiresLinearPlayback]
+ -[AVPlaybackUserInterfaceTimelineSegment segmentType]
+ -[AVPlaybackUserInterfaceTimelineSegment timeRange]
+ -[UIView(AVAdditions) avkit_directionalHorizontalEdgeInsetsForBarOnEdge:extent:]
+ -[UIView(AVAdditions) avkit_horizontalEdgeInsetsForBarOnEdge:extent:]
+ GCC_except_table10054
+ GCC_except_table10189
+ GCC_except_table10191
+ GCC_except_table10205
+ GCC_except_table10239
+ GCC_except_table10249
+ GCC_except_table10399
+ GCC_except_table10405
+ GCC_except_table10446
+ GCC_except_table10468
+ GCC_except_table10674
+ GCC_except_table10696
+ GCC_except_table1896
+ GCC_except_table1925
+ GCC_except_table1930
+ GCC_except_table1933
+ GCC_except_table2052
+ GCC_except_table2162
+ GCC_except_table2235
+ GCC_except_table2290
+ GCC_except_table2358
+ GCC_except_table2396
+ GCC_except_table2509
+ GCC_except_table2532
+ GCC_except_table2709
+ GCC_except_table2785
+ GCC_except_table2814
+ GCC_except_table3009
+ GCC_except_table3234
+ GCC_except_table3243
+ GCC_except_table3258
+ GCC_except_table3275
+ GCC_except_table3277
+ GCC_except_table3288
+ GCC_except_table3332
+ GCC_except_table3381
+ GCC_except_table3397
+ GCC_except_table3622
+ GCC_except_table3625
+ GCC_except_table3630
+ GCC_except_table3632
+ GCC_except_table3636
+ GCC_except_table3661
+ GCC_except_table3676
+ GCC_except_table3689
+ GCC_except_table3734
+ GCC_except_table3743
+ GCC_except_table3748
+ GCC_except_table3779
+ GCC_except_table3791
+ GCC_except_table3819
+ GCC_except_table3825
+ GCC_except_table3839
+ GCC_except_table3846
+ GCC_except_table3848
+ GCC_except_table3920
+ GCC_except_table3944
+ GCC_except_table3953
+ GCC_except_table3986
+ GCC_except_table4011
+ GCC_except_table4069
+ GCC_except_table4146
+ GCC_except_table4231
+ GCC_except_table4271
+ GCC_except_table4304
+ GCC_except_table4358
+ GCC_except_table4376
+ GCC_except_table4386
+ GCC_except_table4394
+ GCC_except_table4404
+ GCC_except_table4417
+ GCC_except_table4421
+ GCC_except_table4422
+ GCC_except_table4451
+ GCC_except_table4452
+ GCC_except_table4453
+ GCC_except_table4466
+ GCC_except_table4468
+ GCC_except_table4478
+ GCC_except_table4482
+ GCC_except_table4484
+ GCC_except_table4495
+ GCC_except_table4499
+ GCC_except_table4501
+ GCC_except_table4504
+ GCC_except_table4506
+ GCC_except_table4551
+ GCC_except_table4553
+ GCC_except_table4611
+ GCC_except_table4622
+ GCC_except_table4625
+ GCC_except_table4626
+ GCC_except_table4627
+ GCC_except_table4640
+ GCC_except_table4643
+ GCC_except_table4713
+ GCC_except_table4718
+ GCC_except_table4839
+ GCC_except_table4910
+ GCC_except_table5068
+ GCC_except_table5078
+ GCC_except_table5083
+ GCC_except_table5153
+ GCC_except_table5256
+ GCC_except_table5263
+ GCC_except_table5265
+ GCC_except_table5291
+ GCC_except_table5407
+ GCC_except_table5545
+ GCC_except_table5552
+ GCC_except_table5555
+ GCC_except_table5586
+ GCC_except_table5587
+ GCC_except_table5686
+ GCC_except_table6179
+ GCC_except_table6212
+ GCC_except_table6215
+ GCC_except_table6216
+ GCC_except_table6221
+ GCC_except_table6243
+ GCC_except_table6337
+ GCC_except_table6432
+ GCC_except_table6470
+ GCC_except_table6472
+ GCC_except_table6506
+ GCC_except_table6507
+ GCC_except_table6541
+ GCC_except_table6543
+ GCC_except_table6592
+ GCC_except_table6652
+ GCC_except_table6677
+ GCC_except_table6684
+ GCC_except_table6687
+ GCC_except_table6695
+ GCC_except_table6700
+ GCC_except_table6703
+ GCC_except_table7035
+ GCC_except_table7041
+ GCC_except_table7045
+ GCC_except_table7049
+ GCC_except_table7061
+ GCC_except_table7081
+ GCC_except_table7090
+ GCC_except_table7092
+ GCC_except_table7103
+ GCC_except_table7148
+ GCC_except_table7200
+ GCC_except_table7333
+ GCC_except_table7639
+ GCC_except_table7694
+ GCC_except_table7844
+ GCC_except_table7851
+ GCC_except_table7908
+ GCC_except_table7925
+ GCC_except_table7943
+ GCC_except_table7954
+ GCC_except_table7960
+ GCC_except_table7970
+ GCC_except_table8023
+ GCC_except_table8025
+ GCC_except_table8032
+ GCC_except_table8038
+ GCC_except_table8070
+ GCC_except_table8086
+ GCC_except_table8109
+ GCC_except_table8134
+ GCC_except_table8141
+ GCC_except_table8146
+ GCC_except_table8149
+ GCC_except_table8150
+ GCC_except_table8151
+ GCC_except_table8162
+ GCC_except_table8165
+ GCC_except_table8223
+ GCC_except_table8289
+ GCC_except_table8313
+ GCC_except_table8402
+ GCC_except_table8421
+ GCC_except_table8443
+ GCC_except_table8473
+ GCC_except_table8477
+ GCC_except_table8633
+ GCC_except_table8691
+ GCC_except_table8693
+ GCC_except_table8877
+ GCC_except_table8890
+ GCC_except_table8911
+ GCC_except_table8934
+ GCC_except_table8944
+ GCC_except_table8962
+ GCC_except_table8963
+ GCC_except_table8967
+ GCC_except_table8975
+ GCC_except_table9031
+ GCC_except_table9328
+ GCC_except_table9346
+ GCC_except_table9503
+ GCC_except_table9505
+ GCC_except_table9507
+ GCC_except_table9509
+ GCC_except_table9540
+ GCC_except_table9548
+ GCC_except_table9578
+ GCC_except_table9604
+ GCC_except_table9622
+ GCC_except_table9626
+ GCC_except_table9630
+ GCC_except_table9632
+ GCC_except_table9704
+ GCC_except_table9727
+ GCC_except_table9755
+ GCC_except_table9767
+ GCC_except_table9772
+ GCC_except_table9788
+ GCC_except_table9890
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceContentArtwork
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceContentMetadata
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceContentMetadataTemplate
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceContentURLArtwork
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceContentVideoProperties
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceMediaSelectionOption
+ _OBJC_CLASS_$_AVPlaybackUserInterfacePlaybackPosition
+ _OBJC_CLASS_$_AVPlaybackUserInterfaceTimelineSegment
+ _OBJC_IVAR_$_AVMobileGlassControlsViewController._embeddedInlineLayoutMargins
+ _OBJC_IVAR_$_AVMobileGlassDisplayModeControlsView._overflowControl
+ _OBJC_IVAR_$_AVMobileGlassDisplayModeControlsView._overflowedIdentifiers
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceContentArtwork._size
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceContentMetadata._artworkRepresentations
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceContentMetadata._hasAudio
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceContentMetadata._hasLegible
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceContentMetadata._subtitle
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceContentMetadata._title
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceContentMetadata._videoProperties
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceContentMetadataTemplate._artworkRepresentations
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceContentMetadataTemplate._hasAudio
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceContentMetadataTemplate._hasLegible
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceContentMetadataTemplate._subtitle
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceContentMetadataTemplate._title
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceContentMetadataTemplate._videoProperties
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceContentURLArtwork._contentType
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceContentURLArtwork._url
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceContentVideoProperties._presentationSize
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceMediaSelectionOption._displayName
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceMediaSelectionOption._extendedLanguageTag
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceMediaSelectionOption._identifier
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceMediaSelectionOption._mediaCharacteristics
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceMediaSelectionOption._mediaOptionSource
+ _OBJC_IVAR_$_AVPlaybackUserInterfacePlaybackPosition._hostTime
+ _OBJC_IVAR_$_AVPlaybackUserInterfacePlaybackPosition._position
+ _OBJC_IVAR_$_AVPlaybackUserInterfacePlaybackPosition._rate
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceTimelineSegment._identifier
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceTimelineSegment._marked
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceTimelineSegment._requiresLinearPlayback
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceTimelineSegment._segmentType
+ _OBJC_IVAR_$_AVPlaybackUserInterfaceTimelineSegment._timeRange
+ _OBJC_METACLASS_$_AVPlaybackUserInterfaceContentArtwork
+ _OBJC_METACLASS_$_AVPlaybackUserInterfaceContentMetadata
+ _OBJC_METACLASS_$_AVPlaybackUserInterfaceContentMetadataTemplate
+ _OBJC_METACLASS_$_AVPlaybackUserInterfaceContentURLArtwork
+ _OBJC_METACLASS_$_AVPlaybackUserInterfaceContentVideoProperties
+ _OBJC_METACLASS_$_AVPlaybackUserInterfaceMediaSelectionOption
+ _OBJC_METACLASS_$_AVPlaybackUserInterfacePlaybackPosition
+ _OBJC_METACLASS_$_AVPlaybackUserInterfaceTimelineSegment
+ _UILayoutFittingCompressedSize
+ __OBJC_$_CLASS_METHODS_AVPlaybackUserInterfaceContentArtwork
+ __OBJC_$_CLASS_METHODS_AVPlaybackUserInterfaceContentMetadata
+ __OBJC_$_CLASS_METHODS_AVPlaybackUserInterfaceContentMetadataTemplate
+ __OBJC_$_CLASS_METHODS_AVPlaybackUserInterfaceContentURLArtwork
+ __OBJC_$_CLASS_METHODS_AVPlaybackUserInterfaceContentVideoProperties
+ __OBJC_$_CLASS_METHODS_AVPlaybackUserInterfaceMediaSelectionOption
+ __OBJC_$_CLASS_METHODS_AVPlaybackUserInterfaceTimelineSegment
+ __OBJC_$_CLASS_PROP_LIST_AVPlaybackUserInterfaceContentArtwork
+ __OBJC_$_CLASS_PROP_LIST_AVPlaybackUserInterfaceContentMetadata
+ __OBJC_$_CLASS_PROP_LIST_AVPlaybackUserInterfaceContentMetadataTemplate
+ __OBJC_$_CLASS_PROP_LIST_AVPlaybackUserInterfaceContentVideoProperties
+ __OBJC_$_CLASS_PROP_LIST_AVPlaybackUserInterfaceMediaSelectionOption
+ __OBJC_$_CLASS_PROP_LIST_AVPlaybackUserInterfaceTimelineSegment
+ __OBJC_$_INSTANCE_METHODS_AVPlaybackUserInterfaceContentArtwork
+ __OBJC_$_INSTANCE_METHODS_AVPlaybackUserInterfaceContentMetadata
+ __OBJC_$_INSTANCE_METHODS_AVPlaybackUserInterfaceContentMetadataTemplate
+ __OBJC_$_INSTANCE_METHODS_AVPlaybackUserInterfaceContentURLArtwork
+ __OBJC_$_INSTANCE_METHODS_AVPlaybackUserInterfaceContentVideoProperties
+ __OBJC_$_INSTANCE_METHODS_AVPlaybackUserInterfaceMediaSelectionOption
+ __OBJC_$_INSTANCE_METHODS_AVPlaybackUserInterfacePlaybackPosition
+ __OBJC_$_INSTANCE_METHODS_AVPlaybackUserInterfaceTimelineSegment
+ __OBJC_$_INSTANCE_VARIABLES_AVPlaybackUserInterfaceContentArtwork
+ __OBJC_$_INSTANCE_VARIABLES_AVPlaybackUserInterfaceContentMetadata
+ __OBJC_$_INSTANCE_VARIABLES_AVPlaybackUserInterfaceContentMetadataTemplate
+ __OBJC_$_INSTANCE_VARIABLES_AVPlaybackUserInterfaceContentURLArtwork
+ __OBJC_$_INSTANCE_VARIABLES_AVPlaybackUserInterfaceContentVideoProperties
+ __OBJC_$_INSTANCE_VARIABLES_AVPlaybackUserInterfaceMediaSelectionOption
+ __OBJC_$_INSTANCE_VARIABLES_AVPlaybackUserInterfacePlaybackPosition
+ __OBJC_$_INSTANCE_VARIABLES_AVPlaybackUserInterfaceTimelineSegment
+ __OBJC_$_PROP_LIST_AVPlaybackUserInterfaceContentArtwork
+ __OBJC_$_PROP_LIST_AVPlaybackUserInterfaceContentMetadata
+ __OBJC_$_PROP_LIST_AVPlaybackUserInterfaceContentMetadataTemplate
+ __OBJC_$_PROP_LIST_AVPlaybackUserInterfaceContentURLArtwork
+ __OBJC_$_PROP_LIST_AVPlaybackUserInterfaceContentVideoProperties
+ __OBJC_$_PROP_LIST_AVPlaybackUserInterfaceMediaSelectionOption
+ __OBJC_$_PROP_LIST_AVPlaybackUserInterfacePlaybackPosition
+ __OBJC_$_PROP_LIST_AVPlaybackUserInterfaceTimelineSegment
+ __OBJC_CLASS_PROTOCOLS_$_AVPlaybackUserInterfaceContentArtwork
+ __OBJC_CLASS_PROTOCOLS_$_AVPlaybackUserInterfaceContentMetadata
+ __OBJC_CLASS_PROTOCOLS_$_AVPlaybackUserInterfaceContentMetadataTemplate
+ __OBJC_CLASS_PROTOCOLS_$_AVPlaybackUserInterfaceContentVideoProperties
+ __OBJC_CLASS_PROTOCOLS_$_AVPlaybackUserInterfaceMediaSelectionOption
+ __OBJC_CLASS_PROTOCOLS_$_AVPlaybackUserInterfaceTimelineSegment
+ __OBJC_CLASS_RO_$_AVPlaybackUserInterfaceContentArtwork
+ __OBJC_CLASS_RO_$_AVPlaybackUserInterfaceContentMetadata
+ __OBJC_CLASS_RO_$_AVPlaybackUserInterfaceContentMetadataTemplate
+ __OBJC_CLASS_RO_$_AVPlaybackUserInterfaceContentURLArtwork
+ __OBJC_CLASS_RO_$_AVPlaybackUserInterfaceContentVideoProperties
+ __OBJC_CLASS_RO_$_AVPlaybackUserInterfaceMediaSelectionOption
+ __OBJC_CLASS_RO_$_AVPlaybackUserInterfacePlaybackPosition
+ __OBJC_CLASS_RO_$_AVPlaybackUserInterfaceTimelineSegment
+ __OBJC_METACLASS_RO_$_AVPlaybackUserInterfaceContentArtwork
+ __OBJC_METACLASS_RO_$_AVPlaybackUserInterfaceContentMetadata
+ __OBJC_METACLASS_RO_$_AVPlaybackUserInterfaceContentMetadataTemplate
+ __OBJC_METACLASS_RO_$_AVPlaybackUserInterfaceContentURLArtwork
+ __OBJC_METACLASS_RO_$_AVPlaybackUserInterfaceContentVideoProperties
+ __OBJC_METACLASS_RO_$_AVPlaybackUserInterfaceMediaSelectionOption
+ __OBJC_METACLASS_RO_$_AVPlaybackUserInterfacePlaybackPosition
+ __OBJC_METACLASS_RO_$_AVPlaybackUserInterfaceTimelineSegment
+ ___63-[AVMobileGlassControlsViewController _menuElementForMultiview]_block_invoke
+ __os_log_fault_impl
+ _associated conformance 5AVKit38AVPlaybackUserInterfaceContentMetadataV15VideoPropertiesVSHAASQ
+ _associated conformance 5AVKit38AVPlaybackUserInterfaceContentMetadataVSHAASQ
+ _get_witness_table 7SwiftUI14GeometryReaderVyAA19_ConditionalContentVyAA08ModifiedF0VyAGyACyAGyAA6HStackVyAA05TupleF0VyAEyAGyAGyAGyAGyAGyAA5ImageVAA18_AspectRatioLayoutVGAA11_ClipEffectVyAA16RoundedRectangleVGGAA06_FrameM0VGAOGAA31AccessibilityAttachmentModifierVGAGyAGyAGyAGyAtA016_BackgroundStyleU0VyAA8MaterialVGGAOGA0_GAXGGSg_AGyAA6VStackVyAKyAGyAGy5AVKit13AVInfoTabViewV25ScrollableDescriptionView33_6CA406F89E255038964B855E387E9448LLVAXGA0_G_AGyAA6SpacerVAA05_FlexrM0VGA15_26AVInfoTabMetadataStripViewVQPGGA26_GAGyAGyA14_yAA7ForEachVySaySo8UIActionCGSSA17_12ActionButtonA19_LLVGGA0_GAXGSgQPGGA15_015AVInfoTabButtonW0VGGA15_014GlassGroupViewU033_85582C688EDBE270D86ACAB4DC4CB8F7LLVGAA024_SafeAreaRegionsIgnoringM0VGAGyAGyAGyACyA14_yAKyA14_yAKyAGyAGyA20_A0_GAXG_AGyA29_A0_GQPGG_ACyAGyAIyA34_yA37_SSAGyA39_AXGGGA0_GGSgA24_QPGGGAA08_PaddingM0VGA48_GA53_GGGAA4ViewHPyHC
+ _symbolic $s5AVKit35AVPlaybackUserInterfaceControllableP
+ _symbolic $s5AVKit37AVPlaybackUserInterfaceVideoProvidingP
+ _symbolic $s5AVKit39AVPlaybackUserInterfaceTimeControllableP
+ _symbolic $s5AVKit40AVPlaybackUserInterfaceMetadataProvidingP
+ _symbolic $s5AVKit41AVPlaybackUserInterfaceVolumeControllableP
+ _symbolic $s5AVKit43AVPlaybackUserInterfacePlaybackControllableP
+ _symbolic $s5AVKit44AVPlaybackUserInterfaceThumbnailControllableP
+ _symbolic $s5AVKit49AVPlaybackUserInterfaceMediaSelectionControllableP
+ _symbolic SaySo37AVPlaybackUserInterfaceContentArtworkCG
+ _symbolic _____ 5AVKit38AVPlaybackUserInterfaceContentMetadataV
+ _symbolic _____ 5AVKit38AVPlaybackUserInterfaceContentMetadataV15VideoPropertiesV
+ _symbolic _____Sg 5AVKit38AVPlaybackUserInterfaceContentMetadataV15VideoPropertiesV
+ _symbolic _____y___________y_____y_____yAEyAEyAEyAEy__________G_____y_____GG_____GAGG_____GAEyAEyAEyAEyAJ_____y_____GGAGGAPGAMGGSg_AEy_____yACyAEyAEy_____AMGAPG_AEy__________G_____QPGGA4_GAEyAEyA_y_____ySaySo8UIActionCGSS_____GGAPGAMGSgQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_HStackLayoutV AA12TupleContentV AA012_ConditionalI0V AA08ModifiedI0V AA5ImageV AA012_AspectRatioG0V AA11_ClipEffectV AA16RoundedRectangleV AA06_FrameG0V AA31AccessibilityAttachmentModifierV AA016_BackgroundStyleV0V AA8MaterialV AA6VStackV 5AVKit09AVInfoTabD0V021ScrollableDescriptionD033_6CA406F89E255038964B855E387E9448LLV AA6SpacerV AA05_FlexsG0V A4_022AVInfoTabMetadataStripD0V AA7ForEachV A6_12ActionButtonA8_LLV
+ _symbolic _____y_____yAByAByAByABy__________G_____y_____GG_____GADG_____GAByAByAByAByAG_____y_____GGADGAMGAJGGSg 7SwiftUI19_ConditionalContentV AA08ModifiedD0V AA5ImageV AA18_AspectRatioLayoutV AA11_ClipEffectV AA16RoundedRectangleV AA06_FrameI0V AA31AccessibilityAttachmentModifierV AA016_BackgroundStyleQ0V AA8MaterialV
+ _symbolic _____y_____yAByAByAByABy__________G_____y_____GG_____GADG_____GAByAByAByAByAG_____y_____GGADGAMGAJGGSg_ABy_____y_____yAByABy_____AJGAMG_ABy__________G_____QPGGA2_GAByAByAXy_____ySaySo8UIActionCGSS_____GGAMGAJGSgt 7SwiftUI19_ConditionalContentV AA08ModifiedD0V AA5ImageV AA18_AspectRatioLayoutV AA11_ClipEffectV AA16RoundedRectangleV AA06_FrameI0V AA31AccessibilityAttachmentModifierV AA016_BackgroundStyleQ0V AA8MaterialV AA6VStackV AA05TupleD0V 5AVKit13AVInfoTabViewV021ScrollableDescriptionZ033_6CA406F89E255038964B855E387E9448LLV AA6SpacerV AA05_FlexnI0V AZ0xy13MetadataStripZ0V AA7ForEachV A0_12ActionButtonA2_LLV
+ _symbolic _____y_____y_____yACyAAyACy_____y_____yAByACyACyACyACyACy__________G_____y_____GG_____GAGG_____GACyACyACyACyAJ_____y_____GGAGGAPGAMGGSg_ACy_____yAEyACyACy_____AMGAPG_ACy__________G_____QPGGA4_GACyACyA_y_____ySaySo8UIActionCGSS_____GGAPGAMGSgQPGG_____GG_____G_____GACyACyACyAAyA_yAEyA_yAEyACyACyA0_APGAMG_ACyA6_APGQPGG_AAyACyADyA10_yA13_SSACyA14_AMGGGAPGGSgA3_QPGGG_____GA22_GA25_GGG 7SwiftUI14GeometryReaderV AA19_ConditionalContentV AA08ModifiedF0V AA6HStackV AA05TupleF0V AA5ImageV AA18_AspectRatioLayoutV AA11_ClipEffectV AA16RoundedRectangleV AA06_FrameM0V AA31AccessibilityAttachmentModifierV AA016_BackgroundStyleU0V AA8MaterialV AA6VStackV 5AVKit13AVInfoTabViewV25ScrollableDescriptionView33_6CA406F89E255038964B855E387E9448LLV AA6SpacerV AA05_FlexrM0V A2_26AVInfoTabMetadataStripViewV AA7ForEachV A4_12ActionButtonA6_LLV A2_015AVInfoTabButtonW0V A2_014GlassGroupViewU033_85582C688EDBE270D86ACAB4DC4CB8F7LLV AA024_SafeAreaRegionsIgnoringM0V AA08_PaddingM0V
+ _symbolic _____y_____y_____y_____yAAyAAyAAyAAyAAy__________G_____y_____GG_____GAFG_____GAAyAAyAAyAAyAI_____y_____GGAFGAOGALGGSg_AAy_____yACyAAyAAy_____ALGAOG_AAy__________G_____QPGGA3_GAAyAAyAZy_____ySaySo8UIActionCGSS_____GGAOGALGSgQPGG_____G 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA012_ConditionalD0V AA5ImageV AA18_AspectRatioLayoutV AA11_ClipEffectV AA16RoundedRectangleV AA06_FrameK0V AA31AccessibilityAttachmentModifierV AA016_BackgroundStyleS0V AA8MaterialV AA6VStackV 5AVKit13AVInfoTabViewV25ScrollableDescriptionView33_6CA406F89E255038964B855E387E9448LLV AA6SpacerV AA05_FlexpK0V A0_0yZ17MetadataStripViewV AA7ForEachV A2_12ActionButtonA4_LLV A0_0yz6ButtonU0V
+ _symbolic _____y_____y_____y_____yADyADyADyADy__________G_____y_____GG_____GAFG_____GADyADyADyADyAI_____y_____GGAFGAOGALGGSg_ADy_____yAByADyADy_____ALGAOG_ADy__________G_____QPGGA3_GADyADyAZy_____ySaySo8UIActionCGSS_____GGAOGALGSgQPGG 7SwiftUI6HStackV AA12TupleContentV AA012_ConditionalE0V AA08ModifiedE0V AA5ImageV AA18_AspectRatioLayoutV AA11_ClipEffectV AA16RoundedRectangleV AA06_FrameK0V AA31AccessibilityAttachmentModifierV AA016_BackgroundStyleS0V AA8MaterialV AA6VStackV 5AVKit13AVInfoTabViewV25ScrollableDescriptionView33_6CA406F89E255038964B855E387E9448LLV AA6SpacerV AA05_FlexpK0V A0_0yZ17MetadataStripViewV AA7ForEachV A2_12ActionButtonA4_LLV
+ _type_layout_string 5AVKit38AVPlaybackUserInterfaceContentMetadataV
+ _type_layout_string 5AVKit38AVPlaybackUserInterfaceContentMetadataV15VideoPropertiesV
- -[UIView(AVAdditions) avkit_directionalHorizontalEdgeInsetsForExtent:]
- -[UIView(AVAdditions) avkit_horizontalEdgeInsetsForExtent:]
- GCC_except_table10067
- GCC_except_table10069
- GCC_except_table10083
- GCC_except_table10117
- GCC_except_table10127
- GCC_except_table10277
- GCC_except_table10283
- GCC_except_table10324
- GCC_except_table10346
- GCC_except_table10546
- GCC_except_table10568
- GCC_except_table1895
- GCC_except_table1924
- GCC_except_table1929
- GCC_except_table1932
- GCC_except_table2051
- GCC_except_table2161
- GCC_except_table2234
- GCC_except_table2289
- GCC_except_table2357
- GCC_except_table2395
- GCC_except_table2508
- GCC_except_table2531
- GCC_except_table2708
- GCC_except_table2784
- GCC_except_table2813
- GCC_except_table3008
- GCC_except_table3233
- GCC_except_table3242
- GCC_except_table3257
- GCC_except_table3274
- GCC_except_table3276
- GCC_except_table3287
- GCC_except_table3331
- GCC_except_table3380
- GCC_except_table3396
- GCC_except_table3621
- GCC_except_table3624
- GCC_except_table3629
- GCC_except_table3631
- GCC_except_table3635
- GCC_except_table3660
- GCC_except_table3675
- GCC_except_table3688
- GCC_except_table3733
- GCC_except_table3742
- GCC_except_table3747
- GCC_except_table3778
- GCC_except_table3790
- GCC_except_table3818
- GCC_except_table3824
- GCC_except_table3838
- GCC_except_table3845
- GCC_except_table3847
- GCC_except_table3919
- GCC_except_table3942
- GCC_except_table3951
- GCC_except_table3984
- GCC_except_table4010
- GCC_except_table4068
- GCC_except_table4144
- GCC_except_table4230
- GCC_except_table4270
- GCC_except_table4303
- GCC_except_table4356
- GCC_except_table4374
- GCC_except_table4384
- GCC_except_table4392
- GCC_except_table4402
- GCC_except_table4415
- GCC_except_table4420
- GCC_except_table4454
- GCC_except_table4456
- GCC_except_table4467
- GCC_except_table4471
- GCC_except_table4473
- GCC_except_table4480
- GCC_except_table4487
- GCC_except_table4491
- GCC_except_table4493
- GCC_except_table4496
- GCC_except_table4498
- GCC_except_table4535
- GCC_except_table4545
- GCC_except_table4603
- GCC_except_table4609
- GCC_except_table4614
- GCC_except_table4618
- GCC_except_table4619
- GCC_except_table4632
- GCC_except_table4635
- GCC_except_table4704
- GCC_except_table4709
- GCC_except_table4830
- GCC_except_table4901
- GCC_except_table5057
- GCC_except_table5067
- GCC_except_table5072
- GCC_except_table5142
- GCC_except_table5245
- GCC_except_table5252
- GCC_except_table5254
- GCC_except_table5280
- GCC_except_table5396
- GCC_except_table5534
- GCC_except_table5541
- GCC_except_table5544
- GCC_except_table5575
- GCC_except_table5576
- GCC_except_table5675
- GCC_except_table6168
- GCC_except_table6201
- GCC_except_table6204
- GCC_except_table6205
- GCC_except_table6210
- GCC_except_table6232
- GCC_except_table6326
- GCC_except_table6421
- GCC_except_table6458
- GCC_except_table6460
- GCC_except_table6494
- GCC_except_table6495
- GCC_except_table6529
- GCC_except_table6531
- GCC_except_table6577
- GCC_except_table6637
- GCC_except_table6662
- GCC_except_table6669
- GCC_except_table6672
- GCC_except_table6680
- GCC_except_table6685
- GCC_except_table6688
- GCC_except_table6913
- GCC_except_table6919
- GCC_except_table6923
- GCC_except_table6927
- GCC_except_table6939
- GCC_except_table6959
- GCC_except_table6968
- GCC_except_table6970
- GCC_except_table6981
- GCC_except_table7026
- GCC_except_table7078
- GCC_except_table7211
- GCC_except_table7517
- GCC_except_table7572
- GCC_except_table7722
- GCC_except_table7729
- GCC_except_table7786
- GCC_except_table7803
- GCC_except_table7821
- GCC_except_table7832
- GCC_except_table7838
- GCC_except_table7848
- GCC_except_table7897
- GCC_except_table7901
- GCC_except_table7903
- GCC_except_table7910
- GCC_except_table7916
- GCC_except_table7948
- GCC_except_table7964
- GCC_except_table7987
- GCC_except_table8012
- GCC_except_table8024
- GCC_except_table8027
- GCC_except_table8028
- GCC_except_table8029
- GCC_except_table8040
- GCC_except_table8043
- GCC_except_table8101
- GCC_except_table8167
- GCC_except_table8191
- GCC_except_table8280
- GCC_except_table8299
- GCC_except_table8321
- GCC_except_table8351
- GCC_except_table8355
- GCC_except_table8511
- GCC_except_table8569
- GCC_except_table8571
- GCC_except_table8755
- GCC_except_table8768
- GCC_except_table8789
- GCC_except_table8812
- GCC_except_table8822
- GCC_except_table8840
- GCC_except_table8841
- GCC_except_table8845
- GCC_except_table8853
- GCC_except_table8909
- GCC_except_table9206
- GCC_except_table9224
- GCC_except_table9378
- GCC_except_table9381
- GCC_except_table9383
- GCC_except_table9385
- GCC_except_table9386
- GCC_except_table9387
- GCC_except_table9418
- GCC_except_table9426
- GCC_except_table9456
- GCC_except_table9482
- GCC_except_table9504
- GCC_except_table9510
- GCC_except_table9582
- GCC_except_table9605
- GCC_except_table9633
- GCC_except_table9645
- GCC_except_table9650
- GCC_except_table9666
- GCC_except_table9768
- GCC_except_table9932
- _get_witness_table 7SwiftUI14GeometryReaderVyAA19_ConditionalContentVyAA08ModifiedF0VyAGyACyAGyAA6HStackVyAA05TupleF0VyAEyAGyAGyAGyAGyAGyAA5ImageVAA18_AspectRatioLayoutVGAA11_ClipEffectVyAA16RoundedRectangleVGGAA06_FrameM0VGAOGAA31AccessibilityAttachmentModifierVGAGyAGyAGyAGyAtA016_BackgroundStyleU0VyAA8MaterialVGGAOGA0_GAXGG_AGyAA6VStackVyAKyAGyAGy5AVKit13AVInfoTabViewV25ScrollableDescriptionView33_6CA406F89E255038964B855E387E9448LLVAXGA0_G_AGyAA6SpacerVAA05_FlexrM0VGA14_26AVInfoTabMetadataStripViewVQPGGA25_GAGyAGyA13_yAA7ForEachVySaySo8UIActionCGSSA16_12ActionButtonA18_LLVGGA0_GAXGSgQPGGA14_015AVInfoTabButtonW0VGGA14_014GlassGroupViewU033_85582C688EDBE270D86ACAB4DC4CB8F7LLVGAA024_SafeAreaRegionsIgnoringM0VGAGyAGyAGyACyA13_yAKyA13_yAKyAGyAGyA19_A0_GAXG_AGyA28_A0_GQPGG_ACyAGyAIyA33_yA36_SSAGyA38_AXGGGA0_GGSgA23_QPGGGAA08_PaddingM0VGA47_GA52_GGGAA4ViewHPyHC
- _symbolic _____y___________y_____y_____yAEyAEyAEyAEy__________G_____y_____GG_____GAGG_____GAEyAEyAEyAEyAJ_____y_____GGAGGAPGAMGG_AEy_____yACyAEyAEy_____AMGAPG_AEy__________G_____QPGGA3_GAEyAEyAZy_____ySaySo8UIActionCGSS_____GGAPGAMGSgQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_HStackLayoutV AA12TupleContentV AA012_ConditionalI0V AA08ModifiedI0V AA5ImageV AA012_AspectRatioG0V AA11_ClipEffectV AA16RoundedRectangleV AA06_FrameG0V AA31AccessibilityAttachmentModifierV AA016_BackgroundStyleV0V AA8MaterialV AA6VStackV 5AVKit09AVInfoTabD0V021ScrollableDescriptionD033_6CA406F89E255038964B855E387E9448LLV AA6SpacerV AA05_FlexsG0V A4_022AVInfoTabMetadataStripD0V AA7ForEachV A6_12ActionButtonA8_LLV
- _symbolic _____y_____yAByAByAByABy__________G_____y_____GG_____GADG_____GAByAByAByAByAG_____y_____GGADGAMGAJGG_ABy_____y_____yAByABy_____AJGAMG_ABy__________G_____QPGGA1_GAByAByAWy_____ySaySo8UIActionCGSS_____GGAMGAJGSgt 7SwiftUI19_ConditionalContentV AA08ModifiedD0V AA5ImageV AA18_AspectRatioLayoutV AA11_ClipEffectV AA16RoundedRectangleV AA06_FrameI0V AA31AccessibilityAttachmentModifierV AA016_BackgroundStyleQ0V AA8MaterialV AA6VStackV AA05TupleD0V 5AVKit13AVInfoTabViewV021ScrollableDescriptionZ033_6CA406F89E255038964B855E387E9448LLV AA6SpacerV AA05_FlexnI0V AZ0xy13MetadataStripZ0V AA7ForEachV A0_12ActionButtonA2_LLV
- _symbolic _____y_____y_____yACyAAyACy_____y_____yAByACyACyACyACyACy__________G_____y_____GG_____GAGG_____GACyACyACyACyAJ_____y_____GGAGGAPGAMGG_ACy_____yAEyACyACy_____AMGAPG_ACy__________G_____QPGGA3_GACyACyAZy_____ySaySo8UIActionCGSS_____GGAPGAMGSgQPGG_____GG_____G_____GACyACyACyAAyAZyAEyAZyAEyACyACyA_APGAMG_ACyA5_APGQPGG_AAyACyADyA9_yA12_SSACyA13_AMGGGAPGGSgA2_QPGGG_____GA21_GA24_GGG 7SwiftUI14GeometryReaderV AA19_ConditionalContentV AA08ModifiedF0V AA6HStackV AA05TupleF0V AA5ImageV AA18_AspectRatioLayoutV AA11_ClipEffectV AA16RoundedRectangleV AA06_FrameM0V AA31AccessibilityAttachmentModifierV AA016_BackgroundStyleU0V AA8MaterialV AA6VStackV 5AVKit13AVInfoTabViewV25ScrollableDescriptionView33_6CA406F89E255038964B855E387E9448LLV AA6SpacerV AA05_FlexrM0V A2_26AVInfoTabMetadataStripViewV AA7ForEachV A4_12ActionButtonA6_LLV A2_015AVInfoTabButtonW0V A2_014GlassGroupViewU033_85582C688EDBE270D86ACAB4DC4CB8F7LLV AA024_SafeAreaRegionsIgnoringM0V AA08_PaddingM0V
- _symbolic _____y_____y_____y_____yAAyAAyAAyAAyAAy__________G_____y_____GG_____GAFG_____GAAyAAyAAyAAyAI_____y_____GGAFGAOGALGG_AAy_____yACyAAyAAy_____ALGAOG_AAy__________G_____QPGGA2_GAAyAAyAYy_____ySaySo8UIActionCGSS_____GGAOGALGSgQPGG_____G 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA012_ConditionalD0V AA5ImageV AA18_AspectRatioLayoutV AA11_ClipEffectV AA16RoundedRectangleV AA06_FrameK0V AA31AccessibilityAttachmentModifierV AA016_BackgroundStyleS0V AA8MaterialV AA6VStackV 5AVKit13AVInfoTabViewV25ScrollableDescriptionView33_6CA406F89E255038964B855E387E9448LLV AA6SpacerV AA05_FlexpK0V A0_0yZ17MetadataStripViewV AA7ForEachV A2_12ActionButtonA4_LLV A0_0yz6ButtonU0V
- _symbolic _____y_____y_____y_____yADyADyADyADy__________G_____y_____GG_____GAFG_____GADyADyADyADyAI_____y_____GGAFGAOGALGG_ADy_____yAByADyADy_____ALGAOG_ADy__________G_____QPGGA2_GADyADyAYy_____ySaySo8UIActionCGSS_____GGAOGALGSgQPGG 7SwiftUI6HStackV AA12TupleContentV AA012_ConditionalE0V AA08ModifiedE0V AA5ImageV AA18_AspectRatioLayoutV AA11_ClipEffectV AA16RoundedRectangleV AA06_FrameK0V AA31AccessibilityAttachmentModifierV AA016_BackgroundStyleS0V AA8MaterialV AA6VStackV 5AVKit13AVInfoTabViewV25ScrollableDescriptionView33_6CA406F89E255038964B855E387E9448LLV AA6SpacerV AA05_FlexpK0V A0_0yZ17MetadataStripViewV AA7ForEachV A2_12ActionButtonA4_LLV
CStrings:
+ "%s Setting up controls view controller and adding to the view hierarchy."
+ "%s playerViewControllerDidStopPictureInPicture"
+ "%s suppressing write; all synthesized ranges are pointer-identical to existing"
+ "-[AVPlayerViewController _setUpControlsViewControllerIfNeeded]"
+ "-[AVPlayerViewController pictureInPictureControllerDidStopPictureInPicture:]"
+ "AX_GO_TO_LIVE"
+ "AX_NEXT_ITEM"
+ "AX_PREVIOUS_ITEM"
+ "AX_SKIP_BACK_SECONDS %ld"
+ "AX_SKIP_FORWARD_SECONDS %ld"
+ "DISPLAY_MODE_OVERFLOW_ACCESSIBILITY_LABEL"
+ "Display Mode Overflow Button"
+ "MULTIVIEW_OVERFLOW_MENU_ITEM_TITLE"
+ "Transport controls frame is smaller than desired during content tab presenting animation. Aux controls will compress and produce a wrong frame that UIKit animates from when controls reappear."
+ "artworkRepresentations"
+ "hasAudio"
+ "hasLegible"
+ "inset.filled.center.rectangle"
+ "playerController.player.currentItem.supplementalMetadata"
+ "segmentType"
+ "videoProperties"
+ "\xf0\xf0\xf0\xf0\xf0\xf0A"
- "\xf0\xf0\xf0\xf0\xf0\xf01"
```
