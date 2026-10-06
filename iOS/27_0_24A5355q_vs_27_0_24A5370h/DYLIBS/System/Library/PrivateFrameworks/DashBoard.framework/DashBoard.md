## DashBoard

> `/System/Library/PrivateFrameworks/DashBoard.framework/DashBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2dc2b0` | `0x2ed9dc` | **`+0x1172c`** |
| `__AUTH_CONST.__objc_const` | `0x51260` | `0x52850` | **`+0x15f0`** |
| `__TEXT.__oslogstring` | `0x16cfc` | `0x176fc` | **`+0xa00`** |
| `__TEXT.__objc_methlist` | `0x17374` | `0x177bc` | **`+0x448`** |
| `__DATA.__data` | `0x9f90` | `0xa300` | **`+0x370`** |
| `__AUTH.__objc_data` | `0xeb20` | `0xee80` | **`+0x360`** |
| `__TEXT.__swift5_typeref` | `0xb39e` | `0xb6f0` | **`+0x352`** |
| `__TEXT.__eh_frame` | `0x4430` | `0x4718` | **`+0x2e8`** |
| `__TEXT.__unwind_info` | `0x94f8` | `0x9728` | **`+0x230`** |
| `__TEXT.__constg_swiftt` | `0x6d60` | `0x6f60` | **`+0x200`** |
| `__TEXT.__cstring` | `0xd707` | `0xd8f7` | **`+0x1f0`** |
| `__DATA_CONST.__objc_selrefs` | `0xcd80` | `0xcf40` | **`+0x1c0`** |
| `__AUTH_CONST.__const` | `0xc2a8` | `0xc460` | **`+0x1b8`** |
| `__TEXT.__gcc_except_tab` | `0x1ba0` | `0x1a2c` | **`-0x174`** |
| `__TEXT.__swift5_reflstr` | `0x5277` | `0x53e7` | **`+0x170`** |
| `__TEXT.__swift5_capture` | `0x2e3c` | `0x2f68` | **`+0x12c`** |
| `__AUTH.__data` | `0x36e8` | `0x37f8` | **`+0x110`** |
| `__TEXT.__swift5_fieldmd` | `0x41f8` | `0x42f4` | **`+0xfc`** |
| `__DATA.__bss` | `0x8a78` | `0x8998` | **`-0xe0`** |
| `__AUTH_CONST.__auth_got` | `0x34f0` | `0x35b0` | **`+0xc0`** |
| `__DATA_CONST.__got` | `0x2c80` | `0x2d38` | **`+0xb8`** |
| `__AUTH_CONST.__cfstring` | `0x8720` | `0x86a0` | **`-0x80`** |
| `__TEXT.__const` | `0xcd84` | `0xce04` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x3860` | `0x37e8` | **`-0x78`** |
| `__DATA_CONST.__objc_protolist` | `0xac8` | `0xb08` | **`+0x40`** |
| `__AUTH_CONST.__objc_intobj` | `0x318` | `0x348` | **`+0x30`** |
| `__DATA_CONST.__objc_classlist` | `0xb20` | `0xb40` | **`+0x20`** |
| `__DATA_CONST.__objc_protorefs` | `0x510` | `0x530` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x960` | `0x948` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x334` | `0x348` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0x128c` | `0x129c` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x624` | `0x634` | **`+0x10`** |
| `__DATA.__common` | `0x388` | `0x390` | **`+0x8`** |
| `__DATA_CONST.__objc_catlist` | `0xd8` | `0xd0` | **`-0x8`** |
| `__DATA_DIRTY.__bss` | `0x140` | `0x148` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x42c` | `0x424` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x21c` | `0x224` | **`+0x8`** |

### Other Changes

```diff

-571.3.0.0.0
+574.2.0.0.0

-  Functions: 15125
-  Symbols:   14229
-  CStrings:  3554
+  Functions: 15314
+  Symbols:   14349
+  CStrings:  3591
Symbols:
+ +[DBDashboardLayoutEngine dockSizeOverride]
+ +[DBIconView platterViewPool]
+ +[DBPlatterViewPoolDelegate sharedInstance]
+ -[DBAppDockViewController _applyResolvedBundleIdentifiers:]
+ -[DBAppDockViewController _buttonForSlot:]
+ -[DBAppDockViewController _firstVisibleAppInList:]
+ -[DBAppDockViewController _prioritizedOtherAppsForApps:]
+ -[DBAppDockViewController _refreshDockButtons]
+ -[DBAppDockViewController _resolveDockBundleIdentifiers]
+ -[DBAppDockViewController _setButton:forSlot:]
+ -[DBAppDockViewController _updateSizeConstraints:forButton:]
+ -[DBAppLinkManager assetLibraryUpdated]
+ -[DBAppLinkManager orderedAppLinkIdentifiers]
+ -[DBAppLinkManager session]
+ -[DBAppLinkManager setOrderedAppLinkIdentifiers:]
+ -[DBAppLinkManager setSession:]
+ -[DBEnvironmentConfiguration showsAppLinksInDock]
+ -[DBIconLabelBackdropView dealloc]
+ -[DBIconLabelBackdropView layoutSubviews]
+ -[DBIconView dropShadowLayer]
+ -[DBIconView lastShadowInterfaceStyle]
+ -[DBIconView setDropShadowLayer:]
+ -[DBIconView setLastShadowInterfaceStyle:]
+ -[DBInstrumentCluster clusterThemeService:getDisplayNameForDriveMode:error:]
+ -[DBLockOutViewController _viewBackgroundColorForMode:]
+ -[DBPlatterViewPoolDelegate recycledViewsContainerProviderForViewMap:]
+ -[DBPlatterViewPoolDelegate viewMap:maxRecycledViewsOfClass:]
+ -[DBRequestContentPunchThroughManager serviceDidFinishGroupUpdate:]
+ -[DBStatusBarViewController assetLibraryUpdated]
+ -[DBWallpaperViewController clientSceneSettingsDidUpdate:]
+ -[DBWallpaperViewController delegate]
+ -[DBWallpaperViewController isReady]
+ -[DBWallpaperViewController setDelegate:]
+ -[DashBoard createWidgetLayoutDataProviderForVehicleID:viewAreas:supportsTouch:]
+ GCC_except_table29
+ GCC_except_table54
+ GCC_except_table63
+ _DBDockSizeOverride.once
+ _DBDockSizeOverride.value
+ _OBJC_CLASS_$_CAFUnitPercent
+ _OBJC_CLASS_$_CAFWirelessChargerStatus
+ _OBJC_CLASS_$_CARScreenInfo
+ _OBJC_CLASS_$_CRSUIWallpaperSceneClientSettings
+ _OBJC_CLASS_$_DBPlatterViewPoolDelegate
+ _OBJC_CLASS_$_SBHReusableViewMap
+ _OBJC_CLASS_$_STStatusBarDataWirelessChargerEntry
+ _OBJC_CLASS_$_STStatusBarDataWirelessChargerGroupEntry
+ _OBJC_CLASS_$__TtC9DashBoard13DBAppDockSlot
+ _OBJC_CLASS_$__TtC9DashBoard22DBIdentifiableLeafIcon
+ _OBJC_IVAR_$_DBAppLinkManager._orderedAppLinkIdentifiers
+ _OBJC_IVAR_$_DBAppLinkManager._session
+ _OBJC_IVAR_$_DBIconView._dropShadowLayer
+ _OBJC_IVAR_$_DBIconView._lastShadowInterfaceStyle
+ _OBJC_IVAR_$_DBWallpaperViewController._delegate
+ _OBJC_IVAR_$_DBWallpaperViewController._isReady
+ _OBJC_METACLASS_$_DBPlatterViewPoolDelegate
+ _OBJC_METACLASS_$_SBLeafIcon
+ _OBJC_METACLASS_$__TtC9DashBoard13DBAppDockSlot
+ _OBJC_METACLASS_$__TtC9DashBoard22DBIdentifiableLeafIcon
+ _OBJC_METACLASS_$__TtC9DashBoardP33_E653F4F4E0CBA17AF900E37FA6F98E4626DBIconImageViewMapDelegate
+ _STStatusBarDataEntryExternalWirelessChargersKey
+ _STUIStatusBarCarPlayTopStatusDriverSideExclusionWidthKey
+ _STUIStatusBarCarPlayTopStatusOppositeDriverAlignedKey
+ __DATA__TtC9DashBoard13DBAppDockSlot
+ __DATA__TtC9DashBoard21DriveModeThemeManager
+ __DATA__TtC9DashBoard22DBIdentifiableLeafIcon
+ __DATA__TtC9DashBoardP33_E653F4F4E0CBA17AF900E37FA6F98E4626DBIconImageViewMapDelegate
+ __INSTANCE_METHODS__TtC9DashBoard13DBAppDockSlot
+ __INSTANCE_METHODS__TtC9DashBoard22DBIdentifiableLeafIcon
+ __INSTANCE_METHODS__TtC9DashBoardP33_E653F4F4E0CBA17AF900E37FA6F98E4626DBIconImageViewMapDelegate
+ __IVARS__TtC9DashBoard13DBAppDockSlot
+ __IVARS__TtC9DashBoard21DriveModeThemeManager
+ __IVARS__TtC9DashBoard22DBIdentifiableLeafIcon
+ __METACLASS_DATA__TtC9DashBoard13DBAppDockSlot
+ __METACLASS_DATA__TtC9DashBoard21DriveModeThemeManager
+ __METACLASS_DATA__TtC9DashBoard22DBIdentifiableLeafIcon
+ __METACLASS_DATA__TtC9DashBoardP33_E653F4F4E0CBA17AF900E37FA6F98E4626DBIconImageViewMapDelegate
+ __OBJC_$_CLASS_METHODS_DBPlatterViewPoolDelegate
+ __OBJC_$_CLASS_METHODS__TtC9DashBoard13DBAppDockSlot(DashBoard)
+ __OBJC_$_CLASS_METHODS__TtC9DashBoard22DBIdentifiableLeafIcon(DashBoard)
+ __OBJC_$_INSTANCE_METHODS_DBPlatterViewPoolDelegate
+ __OBJC_$_INSTANCE_METHODS__TtC9DashBoard14DBAssetLibrary(DashBoard|DashBoard1|DashBoard2|DashBoard3)
+ __OBJC_$_INSTANCE_METHODS__TtC9DashBoard29DBWallpaperRootViewController(DashBoard|DashBoard1|DashBoard2|DashBoard3|DashBoard4)
+ __OBJC_$_INSTANCE_METHODS__TtCE9DashBoardCSo26DBStatusBarDataBroadcaster18VehicleStateSource(DashBoard|DashBoard1|DashBoard2|DashBoard3|DashBoard4|DashBoard5|DashBoard6|DashBoard7|DashBoard8|DashBoard9|DashBoard10)
+ __OBJC_$_PROP_LIST_DBPlatterViewPoolDelegate
+ __OBJC_$_PROP_LIST_SBHReusableView
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CAFWirelessChargerStatusObserver
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_DBWallpaperViewControllerDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SBHReusableView
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SBHReusableViewMapDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SBHReusableView
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SBHReusableViewMapDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CAFWirelessChargerStatusObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_DBWallpaperViewControllerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SBHReusableView
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SBHReusableViewMapDelegate
+ __OBJC_$_PROTOCOL_REFS_CAFWirelessChargerStatusObserver
+ __OBJC_$_PROTOCOL_REFS_DBWallpaperViewControllerDelegate
+ __OBJC_$_PROTOCOL_REFS_SBHReusableView
+ __OBJC_$_PROTOCOL_REFS_SBHReusableViewMapDelegate
+ __OBJC_CLASS_PROTOCOLS_$_DBPlatterViewPoolDelegate
+ __OBJC_CLASS_PROTOCOLS_$__TtC9DashBoard29DBWallpaperRootViewController(DashBoard|DashBoard1|DashBoard2|DashBoard3|DashBoard4)
+ __OBJC_CLASS_PROTOCOLS_$__TtCE9DashBoardCSo26DBStatusBarDataBroadcaster18VehicleStateSource(DashBoard|DashBoard1|DashBoard2|DashBoard3|DashBoard4|DashBoard5|DashBoard6|DashBoard7|DashBoard8|DashBoard9|DashBoard10)
+ __OBJC_CLASS_RO_$_DBPlatterViewPoolDelegate
+ __OBJC_LABEL_PROTOCOL_$_CAFWirelessChargerStatusObserver
+ __OBJC_LABEL_PROTOCOL_$_DBWallpaperViewControllerDelegate
+ __OBJC_LABEL_PROTOCOL_$_SBHReusableView
+ __OBJC_LABEL_PROTOCOL_$_SBHReusableViewMapDelegate
+ __OBJC_METACLASS_RO_$_DBPlatterViewPoolDelegate
+ __OBJC_PROTOCOL_$_CAFWirelessChargerStatusObserver
+ __OBJC_PROTOCOL_$_DBWallpaperViewControllerDelegate
+ __OBJC_PROTOCOL_$_SBHReusableView
+ __OBJC_PROTOCOL_$_SBHReusableViewMapDelegate
+ __PROPERTIES__TtC9DashBoard13DBAppDockSlot
+ __PROPERTIES__TtC9DashBoard22DBIdentifiableLeafIcon
+ __PROTOCOLS__TtC9DashBoard22DBDashboardPlatterView
+ __PROTOCOLS__TtC9DashBoardP33_E653F4F4E0CBA17AF900E37FA6F98E4626DBIconImageViewMapDelegate
+ ___29+[DBIconView platterViewPool]_block_invoke
+ ___39-[DBAppLinkManager assetLibraryUpdated]_block_invoke
+ ___43+[DBPlatterViewPoolDelegate sharedInstance]_block_invoke
+ ___55-[DBLockOutViewController _viewBackgroundColorForMode:]_block_invoke
+ ___58-[DBWallpaperViewController clientSceneSettingsDidUpdate:]_block_invoke
+ ___59-[DBAppDockViewController _applyResolvedBundleIdentifiers:]_block_invoke
+ ___67-[DBRequestContentPunchThroughManager serviceDidFinishGroupUpdate:]_block_invoke
+ ___DBDockSizeOverride_block_invoke
+ ___swift_closure_destructor.14Tm
+ ___swift_closure_destructor.50Tm
+ ___swift_closure_destructor.71Tm
+ __swift_implicitisolationactor_to_executor_cast
+ _associated conformance 9DashBoard35DriveModeThemeConfigurationOverrideV10CodingKeys33_C4113CE20A3055B4D54FED8A06E91340LLOSHAASQ
+ _associated conformance 9DashBoard35DriveModeThemeConfigurationOverrideV10CodingKeys33_C4113CE20A3055B4D54FED8A06E91340LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 9DashBoard35DriveModeThemeConfigurationOverrideV10CodingKeys33_C4113CE20A3055B4D54FED8A06E91340LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _platterViewPool.onceToken
+ _platterViewPool.pool
+ _sharedInstance.delegate
+ _swift_retain_x9
+ _symbolic SDy_____y_____SSGAAy_____SSGG 14CarPlayAssetUI11TaggedValueV AA12DriveModeTagO AA6LayoutV
+ _symbolic SaySo24CAFWirelessChargerStatusCG
+ _symbolic SaySo39DBTodayViewSynchronizedAnimationManagerCGSg
+ _symbolic Si6offset______Sg7elementt 13CarAssetUtils19CAUVehicleLayoutKeyO
+ _symbolic So10SBLeafIconC
+ _symbolic So16DBAppLinkManagerCSgXw
+ _symbolic So16DBAppLinkManagerCSgXwz_Xx
+ _symbolic So18SBHReusableViewMapCy_____GSg 9DashBoard15DBIconImageViewC
+ _symbolic So21CPUIDimmingEffectViewCSg
+ _symbolic _____ 9DashBoard13DBAppDockSlotC
+ _symbolic _____ 9DashBoard21DriveModeThemeManagerC
+ _symbolic _____ 9DashBoard22DBIdentifiableLeafIconC
+ _symbolic _____ 9DashBoard26DBIconImageViewMapDelegate07_E653F4I24E0CBA17AF900E37FA6F98E46LLC
+ _symbolic _____ 9DashBoard27CAFDefaultDriveModeProducerV
+ _symbolic _____ 9DashBoard35DriveModeThemeConfigurationOverrideV10CodingKeys33_C4113CE20A3055B4D54FED8A06E91340LLO
+ _symbolic _____ So17DBAppDockCategoryV
+ _symbolic _____Sg 13CarAssetUtils19CAUVehicleLayoutKeyO
+ _symbolic _____Sg 13CarAssetUtils21CAUAppUIConfigurationV17AppsConfigurationV
+ _symbolic _____Sg 13CarAssetUtils21CAUAppUIConfigurationV22WallpaperConfigurationV
+ _symbolic _____Sg 13CarAssetUtils23CAUFeatureConfigurationV0A7PlayAppV12TopStatusBarV
+ _symbolic _____Sg 9DashBoard21DriveModeThemeManagerC
+ _symbolic _____Sg So17OS_dispatch_queueC8DispatchE16SchedulerOptionsV
+ _symbolic _____Sg3key_SaySo24CAFWirelessChargerStatusCG5valuet 13CarAssetUtils19CAUVehicleLayoutKeyO
+ _symbolic _____SgXw 9DashBoard21DriveModeThemeManagerC
+ _symbolic _____SgXw 9DashBoard29DBWallpaperRootViewControllerC
+ _symbolic _____SgXwz_Xx 9DashBoard21DriveModeThemeManagerC
+ _symbolic _____SgXwz_Xx 9DashBoard29DBWallpaperRootViewControllerC
+ _symbolic _____Sg_ABt 13CarAssetUtils19CAUVehicleLayoutKeyO
+ _symbolic _____Sg_Sbytt 14CarPlayAssetUI19RequestContentModelO
+ _symbolic _____XDXMT 9DashBoard21DriveModeThemeManagerC
+ _symbolic _____ySb_Sbt_____G 7Combine12AnyPublisherV s5NeverO
+ _symbolic _____ySb_____G 7Combine19CurrentValueSubjectC s5NeverO
+ _symbolic _____ySo14CAFUnitPercentCG 10Foundation11MeasurementV
+ _symbolic _____ySo14CAFUnitPercentCGSg 10Foundation11MeasurementV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 9DashBoard35DriveModeThemeConfigurationOverrideV10CodingKeys33_C4113CE20A3055B4D54FED8A06E91340LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 9DashBoard35DriveModeThemeConfigurationOverrideV10CodingKeys33_C4113CE20A3055B4D54FED8A06E91340LLO
+ _symbolic _____y_____SSG_AAy_____SSGt 14CarPlayAssetUI11TaggedValueV AA12DriveModeTagO AA6LayoutV
+ _symbolic _____y_____SgG s11_SetStorageC 13CarAssetUtils19CAUVehicleLayoutKeyO
+ _symbolic _____y_____SgG s23_ContiguousArrayStorageC 13CarAssetUtils19CAUVehicleLayoutKeyO
+ _symbolic _____y_____SgSaySo24CAFWirelessChargerStatusCGG s18_DictionaryStorageC 13CarAssetUtils19CAUVehicleLayoutKeyO
+ _symbolic _____y_____Sg_Sbytt_____G 7Combine12AnyPublisherV 14CarPlayAssetUI19RequestContentModelO s5NeverO
+ _symbolic _____y______ySb_Sbt_____GG 7Combine10PublishersO6FilterV AA12AnyPublisherV s5NeverO
+ _symbolic _____y______ySo13CAFDriveStateC_____GSSSgG 7Combine10PublishersO10CompactMapV AA12AnyPublisherV s5NeverO
+ _symbolic _____y______ySo13CAFDriveStateC_____G_____y_____SSGSgG 7Combine10PublishersO10CompactMapV AA12AnyPublisherV s5NeverO 14CarPlayAssetUI11TaggedValueV AJ12DriveModeTagO
+ _symbolic _____y______y_AAy______y__________GSbGGytG 7Combine10PublishersO3MapV AC16RemoveDuplicatesV AA12AnyPublisherV So16CAFChargingStateV s5NeverO
+ _symbolic _____y______y_SayytG_____G_____y______y_AFy______y_____ADGSbGGytGG 7Combine10PublishersO11ConcatenateV AC8SequenceV s5NeverO AC3MapV AC16RemoveDuplicatesV AA12AnyPublisherV So16CAFChargingStateV
+ _symbolic _____y______y_____Sg_GACG 7Combine10PublishersO10CompactMapV AA9PublishedV9PublisherV 13CarAssetUtils15CAUAssetLibraryC
+ _symbolic _____y______y_____Sg_Sbytt_____GSo9NSRunLoopCG 7Combine10PublishersO8DebounceV AA12AnyPublisherV 14CarPlayAssetUI19RequestContentModelO s5NeverO
+ _symbolic _____y______y_____Sg_____GABySbAEG_____y______y_SayytGAEG_____y______y_ALy_ABy_____AEGSbGGytGGG 7Combine10PublishersO0A7Latest3V AA12AnyPublisherV 14CarPlayAssetUI19RequestContentModelO s5NeverO AC11ConcatenateV AC8SequenceV AC3MapV AC16RemoveDuplicatesV So16CAFChargingStateV
+ _symbolic _____y______y__________GSbG 7Combine10PublishersO3MapV AA12AnyPublisherV So16CAFChargingStateV s5NeverO
+ _symbolic _____y______y______ySb_GGSo17OS_dispatch_queueCG 7Combine10PublishersO8DebounceV AC4DropV AA9PublishedV9PublisherV
+ _symbolic _____y______y______ySb_Sbt_____GGSbG 7Combine10PublishersO3MapV AC6FilterV AA12AnyPublisherV s5NeverO
+ _symbolic _____y______y______ySb_____GG_____ySbADGG 7Combine10PublishersO0A6LatestV AC15MakeConnectableV AA12AnyPublisherV s5NeverO AA19CurrentValueSubjectC
+ _symbolic _____y______y______ySo13CAFDriveStateC_____G_____y_____SSGSgGG 7Combine10PublishersO16RemoveDuplicatesV AC10CompactMapV AA12AnyPublisherV s5NeverO 14CarPlayAssetUI11TaggedValueV AL12DriveModeTagO
+ _symbolic _____y______y______y_____Sg_GADGG 7Combine10PublishersO5FirstV AC10CompactMapV AA9PublishedV9PublisherV 13CarAssetUtils15CAUAssetLibraryC
+ _symbolic _____y______y______y_____Sg_Sbytt_____GSo9NSRunLoopCGG 7Combine10PublishersO6FilterV AC8DebounceV AA12AnyPublisherV 14CarPlayAssetUI19RequestContentModelO s5NeverO
+ _symbolic _____y______y______y__________GSbGG 7Combine10PublishersO16RemoveDuplicatesV AC3MapV AA12AnyPublisherV So16CAFChargingStateV s5NeverO
+ _symbolic _____y______y______y______ySb_Sbt_____GGSbGG 7Combine10PublishersO16RemoveDuplicatesV AC3MapV AC6FilterV AA12AnyPublisherV s5NeverO
+ _symbolic _____y______y______y______ySb_____GG_____ySbAEGGSbG 7Combine10PublishersO3MapV AC0A6LatestV AC15MakeConnectableV AA12AnyPublisherV s5NeverO AA19CurrentValueSubjectC
+ _symbolic _____y______y______y______y_____Sg_GAEGGSo9NSRunLoopCG 7Combine10PublishersO9ReceiveOnV AC5FirstV AC10CompactMapV AA9PublishedV9PublisherV 13CarAssetUtils15CAUAssetLibraryC
+ _symbolic _____y______y______y______y_____Sg_Sbytt_____GSo9NSRunLoopCGGAFG 7Combine10PublishersO3MapV AC6FilterV AC8DebounceV AA12AnyPublisherV 14CarPlayAssetUI19RequestContentModelO s5NeverO
+ _symbolic _____y______y______y______y__________GSbGGADySbAFGG 7Combine10PublishersO0A6LatestV AC16RemoveDuplicatesV AC3MapV AA12AnyPublisherV So16CAFChargingStateV s5NeverO
+ _symbolic _____y_____y_____SSGABy_____SSGG s18_DictionaryStorageC 14CarPlayAssetUI11TaggedValueV AC12DriveModeTagO AC6LayoutV
+ _symbolic _____y_____y_____SSGSg_____G 7Combine12AnyPublisherV 14CarPlayAssetUI11TaggedValueV AD12DriveModeTagO s5NeverO
+ _type_layout_string 9DashBoard27CAFDefaultDriveModeProducerV
- -[DBAppDockViewController _generateOrderedAppItems]
- -[DBAppDockViewController _updateAudioButtonSizeConstraints]
- -[DBAppDockViewController _updateCommunicationButtonSizeConstraints]
- -[DBAppDockViewController _updateNavigationButtonSizeConstraints]
- -[DBAppDockViewController _updateOtherButtonSizeConstraints]
- -[DBAppDockViewController orderedAppItems]
- -[DBAppDockViewController setOrderedAppItems:]
- -[DBDisplayManager _setCornerMaskImageIfNecessaryForPrimaryDisplayConfiguration:]
- -[DBIconView dropShadowView]
- -[DBIconView setDropShadowView:]
- -[DashBoard createWidgetLayoutDataProviderForVehicleID:viewAreas:]
- GCC_except_table44
- GCC_except_table62
- _CRSWidgetCalmModeDefault
- _OBJC_IVAR_$_DBAppDockViewController._orderedAppItems
- _OBJC_IVAR_$_DBIconView._dropShadowView
- __CATEGORY_INSTANCE_METHODS_SBLeafIcon_$_DashBoard
- __CATEGORY_SBLeafIcon_$_DashBoard
- __DATA__TtC9DashBoardP33_2F69B94F231272623535798A4DF9928026BackgroundGlassCoordinator
- __IVARS__TtC9DashBoardP33_2F69B94F231272623535798A4DF9928026BackgroundGlassCoordinator
- __METACLASS_DATA__TtC9DashBoardP33_2F69B94F231272623535798A4DF9928026BackgroundGlassCoordinator
- __OBJC_$_INSTANCE_METHODS__TtC9DashBoard14DBAssetLibrary(DashBoard|DashBoard1)
- __OBJC_$_INSTANCE_METHODS__TtC9DashBoard29DBWallpaperRootViewController(DashBoard|DashBoard1|DashBoard2)
- __OBJC_$_INSTANCE_METHODS__TtCE9DashBoardCSo26DBStatusBarDataBroadcaster18VehicleStateSource(DashBoard|DashBoard1|DashBoard2|DashBoard3|DashBoard4|DashBoard5|DashBoard6|DashBoard7|DashBoard8|DashBoard9)
- __OBJC_CLASS_PROTOCOLS_$__TtC9DashBoard29DBWallpaperRootViewController(DashBoard|DashBoard1|DashBoard2)
- __OBJC_CLASS_PROTOCOLS_$__TtCE9DashBoardCSo26DBStatusBarDataBroadcaster18VehicleStateSource(DashBoard|DashBoard1|DashBoard2|DashBoard3|DashBoard4|DashBoard5|DashBoard6|DashBoard7|DashBoard8|DashBoard9)
- ___51-[DBAppDockViewController _generateOrderedAppItems]_block_invoke
- ___51-[DBAppDockViewController _generateOrderedAppItems]_block_invoke_2
- ___51-[DBAppDockViewController _generateOrderedAppItems]_block_invoke_3
- ___51-[DBAppDockViewController _generateOrderedAppItems]_block_invoke_4
- ___60-[DBLockOutViewController initWithEnvironmentConfiguration:]_block_invoke
- ___81-[DBDisplayManager _setCornerMaskImageIfNecessaryForPrimaryDisplayConfiguration:]_block_invoke
- ___82-[DBRequestContentPunchThroughManager requestTemporaryContentService:didUpdateOn:]_block_invoke
- ___99-[DBRequestContentPunchThroughManager requestTemporaryContentService:didUpdateTemporaryContentURL:]_block_invoke
- ___block_descriptor_40_e8_32s_e30_B32?0"DBApplication"8Q16^B24ls32l8
- ___block_descriptor_48_e8_32s_e27_v16?0"<UIMutableTraits>"8ls32l8
- ___block_descriptor_49_e8_32s40w_e5_v8?0lw40l8s32l8
- ___swift_closure_destructor.18Tm
- ___swift_closure_destructor.68Tm
- ___swift_memcpy9_8
- _associated conformance 9DashBoard15BackgroundGlass33_2F69B94F231272623535798A4DF99280LLV7SwiftUI4ViewAA4BodyAeFP_AeF
- _associated conformance 9DashBoard35DriveModeThemeConfigurationOverrideV10CodingKeys33_8E11141C46C850AB2783A04DF7234313LLOSHAASQ
- _associated conformance 9DashBoard35DriveModeThemeConfigurationOverrideV10CodingKeys33_8E11141C46C850AB2783A04DF7234313LLOs0H3KeyAAs23CustomStringConvertible
- _associated conformance 9DashBoard35DriveModeThemeConfigurationOverrideV10CodingKeys33_8E11141C46C850AB2783A04DF7234313LLOs0H3KeyAAs28CustomDebugStringConvertible
- _get_enum_tag_for_layout_string 7SwiftUI11EnvironmentV7ContentOy9DashBoard26BackgroundGlassCoordinator33_2F69B94F231272623535798A4DF99280LLC_G
- _get_witness_table 7SwiftUI5GroupVyAA4ViewPAAE12_glassEffect_2inQrAA6_GlassV_qd__tAA5ShapeRd__lFQOyAA15ModifiedContentVyAA5ColorVAA01_kI8ModifierVyAA03AnyI0VGG_ARQo_SgGAaDHPAvaDHpqd0__AaDHD3_AUHO_HC_HC
- _symbolic So10CAFAppLinkC
- _symbolic So21CPUIDimmingEffectViewC
- _symbolic So23CAFSymbolImageWithColorC
- _symbolic _____ 9DashBoard15BackgroundGlass33_2F69B94F231272623535798A4DF99280LLV
- _symbolic _____ 9DashBoard26BackgroundGlassCoordinator33_2F69B94F231272623535798A4DF99280LLC
- _symbolic _____ 9DashBoard35DriveModeThemeConfigurationOverrideV10CodingKeys33_8E11141C46C850AB2783A04DF7234313LLO
- _symbolic _____Sg 13CarAssetUtils22CAUAssetLibraryManagerC
- _symbolic _____Sg 9DashBoard25DBDriveModeCommandHandlerV
- _symbolic _____Sg 9DashBoard34DriveModeThemeConfigurationManagerC
- _symbolic _____Sg_Sbt 14CarPlayAssetUI19RequestContentModelO
- _symbolic _____y_____G 7SwiftUI11EnvironmentV 9DashBoard26BackgroundGlassCoordinator33_2F69B94F231272623535798A4DF99280LLC
- _symbolic _____y_____G 7SwiftUI21_ContentShapeModifierV AA03AnyD0V
- _symbolic _____y_____G s22KeyedDecodingContainerV 9DashBoard35DriveModeThemeConfigurationOverrideV10CodingKeys33_8E11141C46C850AB2783A04DF7234313LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 9DashBoard35DriveModeThemeConfigurationOverrideV10CodingKeys33_8E11141C46C850AB2783A04DF7234313LLO
- _symbolic _____y_____Sg_Sbt_____G 7Combine12AnyPublisherV 14CarPlayAssetUI19RequestContentModelO s5NeverO
- _symbolic _____y______Sbt_____G 7Combine12AnyPublisherV So16CAFChargingStateV s5NeverO
- _symbolic _____y___________Qo_ 7SwiftUI4ViewPAAE11environmentyQrqd__SgRld__C11Observation10ObservableRd__lFQO 9DashBoard15BackgroundGlass33_2F69B94F231272623535798A4DF99280LLV AH0iJ11CoordinatorAJLLC
- _symbolic _____y__________y_____GG 7SwiftUI15ModifiedContentV AA5ColorV AA01_D13ShapeModifierV AA03AnyF0V
- _symbolic _____y______ySo13CAFDriveStateC_____GSSG 7Combine10PublishersO10CompactMapV AA12AnyPublisherV s5NeverO
- _symbolic _____y______y_____Sg_Sbt_____GSo9NSRunLoopCG 7Combine10PublishersO8DebounceV AA12AnyPublisherV 14CarPlayAssetUI19RequestContentModelO s5NeverO
- _symbolic _____y______y_____Sg_____G_____y_ABySbAEGGG 7Combine10PublishersO0A6LatestV AA12AnyPublisherV 14CarPlayAssetUI19RequestContentModelO s5NeverO AC15MakeConnectableV
- _symbolic _____y______y______Sbt_____GG 7Combine10PublishersO6FilterV AA12AnyPublisherV So16CAFChargingStateV s5NeverO
- _symbolic _____y______y__________G_____y_ABySbADGGG 7Combine10PublishersO0A6LatestV AA12AnyPublisherV So16CAFChargingStateV s5NeverO AC15MakeConnectableV
- _symbolic _____y______y______ySo13CAFDriveStateC_____GSSGG 7Combine10PublishersO16RemoveDuplicatesV AC10CompactMapV AA12AnyPublisherV s5NeverO
- _symbolic _____y______y______y_____Sg_Sbt_____GSo9NSRunLoopCGG 7Combine10PublishersO6FilterV AC8DebounceV AA12AnyPublisherV 14CarPlayAssetUI19RequestContentModelO s5NeverO
- _symbolic _____y______y______y______Sbt_____GGADG 7Combine10PublishersO3MapV AC6FilterV AA12AnyPublisherV So16CAFChargingStateV s5NeverO
- _symbolic _____y______y______y______Sbt_____GGSbG 7Combine10PublishersO3MapV AC6FilterV AA12AnyPublisherV So16CAFChargingStateV s5NeverO
- _symbolic _____y______y______y______y_____Sg_Sbt_____GSo9NSRunLoopCGGAFG 7Combine10PublishersO3MapV AC6FilterV AC8DebounceV AA12AnyPublisherV 14CarPlayAssetUI19RequestContentModelO s5NeverO
- _symbolic _____y______y______y______y______Sbt_____GGSbGG 7Combine10PublishersO16RemoveDuplicatesV AC3MapV AC6FilterV AA12AnyPublisherV So16CAFChargingStateV s5NeverO
- _symbolic _____y______y______y______y______y_____Sg_Sbt_____GSo9NSRunLoopCGGAGGG 7Combine10PublishersO16RemoveDuplicatesV AC3MapV AC6FilterV AC8DebounceV AA12AnyPublisherV 14CarPlayAssetUI19RequestContentModelO s5NeverO
- _symbolic _____y_____y___________Qo_G 7SwiftUI14_UIHostingViewC AA0D0PAAE11environmentyQrqd__SgRld__C11Observation10ObservableRd__lFQO 9DashBoard15BackgroundGlass33_2F69B94F231272623535798A4DF99280LLV AJ0jK11CoordinatorALLLC
- _symbolic _____y_____y__________y_____GG_ADQo_ 7SwiftUI4ViewPAAE12_glassEffect_2inQrAA6_GlassV_qd__tAA5ShapeRd__lFQO AA15ModifiedContentV AA5ColorV AA01_jH8ModifierV AA03AnyH0V
- _symbolic _____y_____y__________y_____GG_ADQo_Sg 7SwiftUI4ViewPAAE12_glassEffect_2inQrAA6_GlassV_qd__tAA5ShapeRd__lFQO AA15ModifiedContentV AA5ColorV AA01_jH8ModifierV AA03AnyH0V
- _symbolic _____y_____y_____y__________y_____GG_AEQo_SgG 7SwiftUI5GroupV AA4ViewPAAE12_glassEffect_2inQrAA6_GlassV_qd__tAA5ShapeRd__lFQO AA15ModifiedContentV AA5ColorV AA01_kI8ModifierV AA03AnyI0V
- _type_layout_string 9DashBoard15BackgroundGlass33_2F69B94F231272623535798A4DF99280LLV
CStrings:
+ "!\xb1"
+ "%s assets=%@ topStatusBarOppositeDriverAligned=%@"
+ "%s deferring TopBar creation until featureConfiguration resolves"
+ "%s wirelessChargerPriorities=%s"
+ "%s: %@ added, %@ removed, %@ changed%s"
+ "%s: AppLink order changed, requesting library refresh."
+ "%s: Received changing %@"
+ "%s: snapshot identical to previous"
+ "%{public}@ wallpaper became ready"
+ ", order changed"
+ "Adding charging widget from DCA zones"
+ "Bad payload for driveModeDynamicAssignmentChange"
+ "Cluster visible changed to %{bool,public}d"
+ "DBAssetLibrary slimAssetLibrary first available"
+ "DBAssetLibrary: No asset library available for wallpaper readiness check"
+ "DBAssetLibrary: wallpaper_readiness_option_enabled = %{bool}d"
+ "DBWallpaperRootViewController: Updating wallpaper readiness enabled from %{public}@ to %{public}@"
+ "DashBoard.DBAppDockSlot"
+ "DashBoard.DBIdentifiableLeafIcon"
+ "DriveModeThemeManager: Asset library loaded, updating feature flag to %{bool}d"
+ "DriveModeThemeManager: Drive mode theme association is disabled, returning nil theme data"
+ "DriveModeThemeManager: Handle DriveModeChange change %{public}s."
+ "DriveModeThemeManager: Initialized"
+ "DriveModeThemeManager: Resolved layout %s for drive mode %s"
+ "DriveModeThemeManager: Updated dynamic assignments with %ld assignments"
+ "Empty drive mode string in dynamic assignment mapping"
+ "Empty layout ID string in dynamic assignment mapping for drive mode '%{public}s'"
+ "Failed to seed default drive mode theme linked state: %s"
+ "Ignoring AppLink bundle identifier in dock because priority apps are kept in dock."
+ "Missing driveModeToLayoutIdAssignments in driveModeDynamicAssignmentChange payload: %s"
+ "No persisted drive mode theme linked state; using package default %{bool,public}d"
+ "Prioritized other apps: %@"
+ "Received default drive mode: %s"
+ "Received drive mode to layout ID assignments from Lua: %s"
+ "Refusing to return widget state without viewAreas for vehicle ID: %{public}s"
+ "Refusing to set widget state smaller than viewArea requires (state: %{public}ldx%{public}ld, required: %{public}ldx%{public}ld) for vehicle ID: %{public}s"
+ "Removing charging widget from DCA zones"
+ "Resolved app dock items: %@"
+ "Resolved communication app dock item to AppLink %@"
+ "Seeding drive mode theme linked state from package default: %{bool,public}d"
+ "Setting up drive mode observation using provided publisher"
+ "Skipping default widget state load: no view areas yet for vehicle ID: %{public}s"
+ "Skipping setting identical widget state for vehicle ID: %{public}s from source: %{public}s"
+ "Unable to process layout update for layout: %s"
+ "Updated feature enabled flag to %{bool}d"
+ "[DBRequestContentPunchThroughManager] Registering for service: %@"
+ "[DBRequestContentPunchThroughManager] _updatePunchThroughIfNecessary: Dismissing PT zone=%{public}@: %@ (on=%d, url=%@)"
+ "[DBRequestContentPunchThroughManager] _updatePunchThroughIfNecessary: Received ASC ON zone=%{public}@: %@"
+ "[DBRequestContentPunchThroughManager] _updatePunchThroughIfNecessary: Requesting PT %@ on zone %@."
+ "[DBRequestContentPunchThroughManager] _updatePunchThroughIfNecessary: assets not ready for %@ on zone %@; awaiting assetLibraryUpdated"
+ "[DBRequestContentPunchThroughManager] _updateRequestContentForDismissedPT: No matching active service found for PT: %@ on zone: %@."
+ "[DBRequestContentPunchThroughManager] _updateRequestContentForDismissedPT: Setting RequestTemporaryContent OFF: %@ on zone: %@."
+ "[DBRequestContentPunchThroughManager] _updateRequestContentForDismissedPT: iOS dismissing PT %@ on zone %@."
+ "[DBRequestContentPunchThroughManager] _updateRequestContentForPresentedPT: Not setting RequestTemporaryContent. PT is already visible: %@ on zone: %@."
+ "[DBRequestContentPunchThroughManager] _updateRequestContentForPresentedPT: Sending TemporaryContentChanged command ON on %@: %@ url: %@."
+ "[DBRequestContentPunchThroughManager] _updateRequestContentForPresentedPT: Setting RequestTemporaryContent ON on %@: %@ url: %@."
+ "[DBRequestContentPunchThroughManager] _updateRequestContentForPresentedPT: Timer expired, clearing suppression for zone %@. Re-evaluating service state."
+ "[DBRequestContentPunchThroughManager] assetLibraryUpdated: replaying services"
+ "[DBRequestContentPunchThroughManager] serviceDidFinishGroupUpdate: Processing OEM change zone=%{public}@ on=%d url=%@"
+ "[DBRequestContentPunchThroughManager] serviceDidFinishGroupUpdate: Suppressed during iOS write zone=%{public}@"
+ "[SplitContent] didSetViewArea: re-derived theme systemUILayout. primaryContentFrame=%{public}@ primaryContentSafeAreaInsets={%.0f,%.0f,%.0f,%.0f}"
+ "appLinkManager(_:didChangeAppLinks:)"
+ "appLinkManagerDidChangeAppLinkOrder(_:)"
+ "assetLibraryUpdated: no AppLinks tracked, nothing to refresh"
+ "assetLibraryUpdated: refreshing %@ AppLink icon(s)"
+ "broadcastWirelessChargerStatuses()"
+ "driveModeToLayoutIdAssignments"
+ "init(leafIdentifier:applicationBundleID:)"
+ "isDriveModeThemeAssociationEnabled: feature flag is disabled"
+ "wirelessChargerEntriesByRelativePriority"
- "!\xc1"
- "%s: notifying observers not needed"
- "%s: notifying observers. %@ applink(s) added, %@ applink(s) removed"
- "(BackgroundGlassCoordinator in _2F69B94F231272623535798A4DF99280)"
- "B32@?0@\"DBApplication\"8Q16^B24"
- "Campo"
- "DBRequestContentPunchThroughManager: registering for service: %@"
- "IntelligenceFlow"
- "Main screen is requesting corner masks."
- "Received default drive mode string: %s"
- "Setting up CAF default drive mode observation using provided carObservable"
- "Unable to process lauyout update for layout: %s"
- "_updatePunchThroughIfNecessary: Dismissing PT zone=%{public}@: %@ (on=%d, url=%@)"
- "_updatePunchThroughIfNecessary: Received ASC ON zone=%{public}@: %@"
- "_updatePunchThroughIfNecessary: Requesting PT %@ on zone %@."
- "_updatePunchThroughIfNecessary: assets not ready for %@ on zone %@; awaiting assetLibraryUpdated"
- "_updateRequestContentForDismissedPT: No matching active service found for PT: %@ on zone: %@."
- "_updateRequestContentForDismissedPT: Setting RequestTemporaryContent OFF: %@ on zone: %@."
- "_updateRequestContentForDismissedPT: iOS dismissing PT %@ on zone %@."
- "_updateRequestContentForPresentedPT: Not setting RequestTemporaryContent. PT is already visible: %@ on zone: %@."
- "_updateRequestContentForPresentedPT: Setting RequestTemporaryContent ON on %@: %@."
- "_updateRequestContentForPresentedPT: Suppressing observer callbacks for zone %@."
- "_updateRequestContentForPresentedPT: Timer expired, clearing suppression for zone %@. Re-evaluating service state."
- "assetLibraryUpdated: replaying services"
- "didUpdateOn: Processing OEM change zone=%{public}@ on=%d"
- "didUpdateOn: Suppressed during iOS write zone=%{public}@ on=%d"
- "didUpdateTemporaryContentURL: Processing OEM change zone=%{public}@: %@"
- "didUpdateTemporaryContentURL: Suppressed during iOS write zone=%{public}@: %@"
- "isDriveModeThemeAssociationEnabled: assetLibraryManager or assetLibrary is nil"
- "isDriveModeThemeAssociationEnabled: feature flag is disabled in settingsUIConfiguration"
- "isDriveModeThemeAssociationEnabled: settingsUIConfiguration is nil"
- "prioritized app. index=%{public}ld, id=%{private}@"
- "will prioritize some apps in dock."
```
