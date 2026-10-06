## WebInspector

> `/System/Library/PrivateFrameworks/WebInspector.framework/WebInspector`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5df48` | `0x5dfbc` | **`+0x74`** |

### Other Changes

```diff

-7625.1.18.10.4
+7625.1.20.10.3
Symbols:
+ __ZNSt3__110unique_ptrIN9Inspector33ObjCInspectorCSSBackendDispatcherENS_14default_deleteIS2_EEE5resetB9sqn220106EPS2_
+ __ZNSt3__110unique_ptrIN9Inspector33ObjCInspectorDOMBackendDispatcherENS_14default_deleteIS2_EEE5resetB9sqn220106EPS2_
+ __ZNSt3__110unique_ptrIN9Inspector34ObjCInspectorPageBackendDispatcherENS_14default_deleteIS2_EEE5resetB9sqn220106EPS2_
+ __ZNSt3__110unique_ptrIN9Inspector37ObjCInspectorNetworkBackendDispatcherENS_14default_deleteIS2_EEE5resetB9sqn220106EPS2_
+ __ZNSt3__110unique_ptrIN9Inspector40ObjCInspectorDOMStorageBackendDispatcherENS_14default_deleteIS2_EEE5resetB9sqn220106EPS2_
+ __ZNSt3__123__lower_bound_bisectingB9sqn220106INS_17_ClassicAlgPolicyEPKNS_4pairIN3WTF28ComparableASCIISubsetLiteralILNS3_11ASCIISubsetE0EEE22RWIProtocolCSSPseudoIdEENS3_20ComparableStringViewENS_10__identityEZNKS3_14SortedArrayMapIS8_Lm28EE6tryGetINS3_6StringEEEPKS7_RKT_EUlRSJ_RT0_E_EESN_SN_RKT1_NS_15iterator_traitsISN_E15difference_typeERT3_RT2_
+ __ZNSt3__127__throw_bad_optional_accessB9sqn220106Ev
+ __ZNSt3__16vectorIhNS_9allocatorIhEEE11__vallocateB9sqn220106Em
+ __ZNSt3__16vectorIhNS_9allocatorIhEEE20__throw_length_errorB9sqn220106Ev
+ __ZNSt3__16vectorIhNS_9allocatorIhEEEC2B9sqn220106Em
- __ZNSt3__110unique_ptrIN9Inspector33ObjCInspectorCSSBackendDispatcherENS_14default_deleteIS2_EEE5resetB9sqn220100EPS2_
- __ZNSt3__110unique_ptrIN9Inspector33ObjCInspectorDOMBackendDispatcherENS_14default_deleteIS2_EEE5resetB9sqn220100EPS2_
- __ZNSt3__110unique_ptrIN9Inspector34ObjCInspectorPageBackendDispatcherENS_14default_deleteIS2_EEE5resetB9sqn220100EPS2_
- __ZNSt3__110unique_ptrIN9Inspector37ObjCInspectorNetworkBackendDispatcherENS_14default_deleteIS2_EEE5resetB9sqn220100EPS2_
- __ZNSt3__110unique_ptrIN9Inspector40ObjCInspectorDOMStorageBackendDispatcherENS_14default_deleteIS2_EEE5resetB9sqn220100EPS2_
- __ZNSt3__123__lower_bound_bisectingB9sqn220100INS_17_ClassicAlgPolicyEPKNS_4pairIN3WTF28ComparableASCIISubsetLiteralILNS3_11ASCIISubsetE0EEE22RWIProtocolCSSPseudoIdEENS3_20ComparableStringViewENS_10__identityEZNKS3_14SortedArrayMapIS8_Lm28EE6tryGetINS3_6StringEEEPKS7_RKT_EUlRSJ_RT0_E_EESN_SN_RKT1_NS_15iterator_traitsISN_E15difference_typeERT3_RT2_
- __ZNSt3__127__throw_bad_optional_accessB9sqn220100Ev
- __ZNSt3__16vectorIhNS_9allocatorIhEEE11__vallocateB9sqn220100Em
- __ZNSt3__16vectorIhNS_9allocatorIhEEE20__throw_length_errorB9sqn220100Ev
- __ZNSt3__16vectorIhNS_9allocatorIhEEEC2B9sqn220100Em
Functions:
~ -[_RWIApplicationInfo updateFromListing:] : 1080 -> 1076
~ +[RWIDriverState isValidPayload:] : 532 -> 528
~ +[RWIDriverState decodeFromPayload:] : 484 -> 480
~ __ZN9Inspector17toJSONObjectArrayEP7NSArray : 648 -> 644
~ __ZN9Inspector17toJSONStringArrayEP7NSArray : 668 -> 664
~ __ZN9Inspector18toJSONIntegerArrayEP7NSArray : 588 -> 584
~ __ZN9Inspector17toJSONDoubleArrayEP7NSArray : 588 -> 584
~ __ZN9Inspector22toJSONStringArrayArrayEP7NSArray : 644 -> 640
~ ____ZN9Inspector33ObjCInspectorCSSBackendDispatcher23getMatchedStylesForNodeEliONSt3__18optionalIbEES4__block_invoke_2 : 2076 -> 2064
~ ____ZN9Inspector33ObjCInspectorCSSBackendDispatcher23getComputedStyleForNodeEli_block_invoke_2 : 824 -> 820
~ ____ZN9Inspector33ObjCInspectorCSSBackendDispatcher17getAllStyleSheetsEl_block_invoke_2 : 824 -> 820
~ ____ZN9Inspector33ObjCInspectorCSSBackendDispatcher25getSupportedCSSPropertiesEl_block_invoke_2 : 824 -> 820
~ __ZN9Inspector33ObjCInspectorCSSBackendDispatcher31setLayoutContextTypeChangedModeElRKN3WTF6StringE : 488 -> 504
~ ____ZN9Inspector33ObjCInspectorDOMBackendDispatcher22getDataBindingsForNodeEli_block_invoke_2 : 824 -> 820
~ ____ZN9Inspector33ObjCInspectorDOMBackendDispatcher24getEventListenersForNodeEliONSt3__18optionalIbEE_block_invoke_2 : 824 -> 820
~ __ZN9Inspector37ObjCInspectorNetworkBackendDispatcher15addInterceptionElRKN3WTF6StringES4_ONSt3__18optionalIbEES8_ : 744 -> 760
~ __ZN9Inspector37ObjCInspectorNetworkBackendDispatcher18removeInterceptionElRKN3WTF6StringES4_ONSt3__18optionalIbEES8_ : 744 -> 760
~ __ZN9Inspector37ObjCInspectorNetworkBackendDispatcher17interceptContinueElRKN3WTF6StringES4_ : 656 -> 672
~ __ZN9Inspector37ObjCInspectorNetworkBackendDispatcher25interceptRequestWithErrorElRKN3WTF6StringES4_ : 656 -> 672
~ __ZN9Inspector34ObjCInspectorPageBackendDispatcher15overrideSettingElRKN3WTF6StringEONSt3__18optionalIbEE : 528 -> 544
~ __ZN9Inspector34ObjCInspectorPageBackendDispatcher22overrideUserPreferenceElRKN3WTF6StringES4_ : 652 -> 676
~ ____ZN9Inspector34ObjCInspectorPageBackendDispatcher10getCookiesEl_block_invoke_2 : 824 -> 820
~ ____ZN9Inspector34ObjCInspectorPageBackendDispatcher16searchInResourceElRKN3WTF6StringES4_S4_ONSt3__18optionalIbEES8_S4__block_invoke_2 : 824 -> 820
~ ____ZN9Inspector34ObjCInspectorPageBackendDispatcher17searchInResourcesElRKN3WTF6StringEONSt3__18optionalIbEES8__block_invoke_2 : 824 -> 820
~ __ZN9Inspector34ObjCInspectorPageBackendDispatcher12snapshotRectEliiiiRKN3WTF6StringE : 532 -> 544
~ __ZN3WTF9HashTableINS_6StringENS_12KeyValuePairIS1_NS_3RefINS_8JSONImpl5ValueENS_12RawPtrTraitsIS5_EENS_21DefaultRefDerefTraitsIS5_EEEEEENS_24KeyValuePairKeyExtractorISB_EENS_11DefaultHashIS1_EENS_7HashMapIS1_SA_SF_NS_10HashTraitsIS1_EENSH_ISA_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE1ENS_10FastMallocEE18KeyValuePairTraitsESI_SM_E6rehashENS_7CheckedIjNS_15CrashOnOverflowEEEPSB_ : 420 -> 436
~ __ZN3WTFeqENS_10StringViewENS_12ASCIILiteralE : 868 -> 860
~ -[RWIProtocolDOMDomainEventDispatcher setChildNodesWithParentId:nodes:] : 1384 -> 1380
~ -[RWIProtocolPageDomainEventDispatcher defaultUserPreferencesDidChangeWithPreferences:] : 1316 -> 1312
~ -[RWIProtocolCSSPseudoIdMatches initWithPseudoId:matches:] : 596 -> 592
~ -[RWIProtocolCSSPseudoIdMatches setMatches:] : 568 -> 548
~ -[RWIProtocolCSSInheritedStyleEntry initWithMatchedCSSRules:] : 576 -> 572
~ -[RWIProtocolCSSInheritedStyleEntry setMatchedCSSRules:] : 568 -> 548
~ -[RWIProtocolCSSSelectorList initWithSelectors:text:] : 664 -> 660
~ -[RWIProtocolCSSSelectorList setSelectors:] : 568 -> 548
~ -[RWIProtocolCSSStyleSheetHeader origin] : 244 -> 260
~ -[RWIProtocolCSSStyleSheetBody initWithStyleSheetId:rules:] : 672 -> 668
~ -[RWIProtocolCSSStyleSheetBody setRules:] : 568 -> 548
~ -[RWIProtocolCSSRule origin] : 244 -> 260
~ -[RWIProtocolCSSRule setGroupings:] : 568 -> 548
~ -[RWIProtocolCSSStyle initWithCssProperties:shorthandEntries:] : 924 -> 916
~ -[RWIProtocolCSSStyle setCssProperties:] : 568 -> 548
~ -[RWIProtocolCSSStyle setShorthandEntries:] : 568 -> 548
~ -[RWIProtocolCSSProperty status] : 244 -> 260
~ -[RWIProtocolCSSGrouping type] : 244 -> 260
~ -[RWIProtocolCSSFont initWithDisplayName:variationAxes:] : 672 -> 668
~ -[RWIProtocolCSSFont setVariationAxes:] : 568 -> 548
~ -[RWIProtocolConsoleChannel source] : 244 -> 260
~ -[RWIProtocolConsoleChannel level] : 244 -> 260
~ -[RWIProtocolConsoleMessage source] : 244 -> 260
~ -[RWIProtocolConsoleMessage level] : 244 -> 260
~ -[RWIProtocolConsoleMessage type] : 244 -> 260
~ -[RWIProtocolConsoleMessage setParameters:] : 568 -> 548
~ -[RWIProtocolConsoleStackTrace initWithCallFrames:] : 576 -> 572
~ -[RWIProtocolConsoleStackTrace setCallFrames:] : 568 -> 548
~ -[RWIProtocolDOMNode setChildren:] : 568 -> 548
~ -[RWIProtocolDOMNode pseudoType] : 244 -> 260
~ -[RWIProtocolDOMNode shadowRootType] : 244 -> 260
~ -[RWIProtocolDOMNode customElementState] : 244 -> 260
~ -[RWIProtocolDOMNode setShadowRoots:] : 568 -> 548
~ -[RWIProtocolDOMNode setPseudoElements:] : 568 -> 548
~ -[RWIProtocolDOMAccessibilityProperties checked] : 244 -> 260
~ -[RWIProtocolDOMAccessibilityProperties current] : 244 -> 260
~ -[RWIProtocolDOMAccessibilityProperties invalid] : 244 -> 260
~ -[RWIProtocolDOMAccessibilityProperties liveRegionStatus] : 244 -> 260
~ -[RWIProtocolDOMAccessibilityProperties switchState] : 244 -> 260
~ -[RWIProtocolDOMImmersiveVideoMetadata kind] : 244 -> 260
~ -[RWIProtocolDebuggerBreakpointAction type] : 244 -> 260
~ -[RWIProtocolDebuggerBreakpointOptions setActions:] : 568 -> 548
~ -[RWIProtocolDebuggerFunctionDetails setScopeChain:] : 568 -> 548
~ -[RWIProtocolDebuggerCallFrame initWithCallFrameId:functionName:location:scopeChain:thisObject:isTailDeleted:] : 956 -> 952
~ -[RWIProtocolDebuggerCallFrame setScopeChain:] : 568 -> 548
~ -[RWIProtocolDebuggerScope type] : 244 -> 260
~ -[RWIProtocolNetworkRequest referrerPolicy] : 244 -> 260
~ -[RWIProtocolNetworkResponse source] : 244 -> 260
~ -[RWIProtocolNetworkMetrics priority] : 244 -> 260
~ -[RWIProtocolNetworkCachedResource type] : 244 -> 260
~ -[RWIProtocolNetworkInitiator type] : 244 -> 260
~ -[RWIProtocolPageUserPreference name] : 244 -> 260
~ -[RWIProtocolPageUserPreference value] : 244 -> 260
~ -[RWIProtocolPageFrameResource type] : 244 -> 260
~ -[RWIProtocolPageFrameResourceTree initWithFrame:resources:] : 672 -> 668
~ -[RWIProtocolPageFrameResourceTree setChildFrames:] : 568 -> 548
~ -[RWIProtocolPageFrameResourceTree setResources:] : 568 -> 548
~ -[RWIProtocolPageCookie sameSite] : 244 -> 260
~ -[RWIProtocolRuntimeRemoteObject type] : 244 -> 260
~ -[RWIProtocolRuntimeRemoteObject subtype] : 244 -> 260
~ -[RWIProtocolRuntimeObjectPreview type] : 244 -> 260
~ -[RWIProtocolRuntimeObjectPreview subtype] : 244 -> 260
~ -[RWIProtocolRuntimeObjectPreview setProperties:] : 568 -> 548
~ -[RWIProtocolRuntimeObjectPreview setEntries:] : 568 -> 548
~ -[RWIProtocolRuntimePropertyPreview type] : 244 -> 260
~ -[RWIProtocolRuntimePropertyPreview subtype] : 244 -> 260
~ -[RWIProtocolRuntimeExecutionContextDescription type] : 244 -> 260
~ -[RWIProtocolRuntimeTypeDescription setStructures:] : 568 -> 548
~ -[RWIRelay _allApplicationDetails] : 400 -> 396
~ -[RWIRelay _allDriverDetails] : 400 -> 396
~ -[RWIRelay _reportCurrentStateToAllClients] : 252 -> 248
~ -[RWIRelay _rpc_forwardSocketSetup:] : 712 -> 708
~ -[RWIRelay _rpc_forwardAutomaticInspectionConfiguration:] : 576 -> 572
~ -[RWIRelay _applicationUpdated:] : 464 -> 460
~ -[RWIRelay _applicationConnected:] : 556 -> 552
~ -[RWIRelay _applicationDisconnected:] : 500 -> 496
~ -[RWIRelay clientConnectionDidClose:] : 752 -> 744
~ -[RWIRelay _driverConnected:] : 512 -> 508
~ -[RWIRelay _driverUpdated:] : 472 -> 468
~ -[RWIRelay _driverDisconnected:] : 508 -> 504
~ -[RWIRelay _receivedListingMessage:connection:] : 896 -> 892
~ -[RWIRelayDelegateIOS _processMonitorPredicatesForConnectedApplications] : 432 -> 428
~ -[RWIRelayDelegateIOS _updateDeviceIdlePrevention] : 460 -> 456
~ __ZN3WTF9HashTableINS_6StringENS_12KeyValuePairIS1_PN9Inspector29SupplementalBackendDispatcherEEENS_24KeyValuePairKeyExtractorIS6_EENS_11DefaultHashIS1_EENS_7HashMapIS1_S5_SA_NS_10HashTraitsIS1_EENSC_IS5_EENS_15HashTableTraitsELNS_17ShouldValidateKeyE0ENS_10FastMallocEE18KeyValuePairTraitsESD_SH_E15deallocateTableEPS6_.cold.1 : 96 -> 104
```
