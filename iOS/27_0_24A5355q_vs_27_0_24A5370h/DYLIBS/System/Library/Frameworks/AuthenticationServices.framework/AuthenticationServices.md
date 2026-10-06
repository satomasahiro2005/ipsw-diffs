## AuthenticationServices

> `/System/Library/Frameworks/AuthenticationServices.framework/AuthenticationServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x142f70` | `0x143894` | **`+0x924`** |
| `__TEXT.__eh_frame` | `0x6ca4` | `0x6edc` | **`+0x238`** |
| `__AUTH_CONST.__objc_const` | `0x104f8` | `0x10370` | **`-0x188`** |
| `__TEXT.__swift5_typeref` | `0x31b8` | `0x328e` | **`+0xd6`** |
| `__TEXT.__objc_methlist` | `0x818c` | `0x80ec` | **`-0xa0`** |
| `__AUTH_CONST.__const` | `0x9b60` | `0x9bf8` | **`+0x98`** |
| `__TEXT.__cstring` | `0xb4e8` | `0xb578` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x5d00` | `0x5d90` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0xe54` | `0xea8` | **`+0x54`** |
| `__AUTH.__objc_data` | `0x3d58` | `0x3d08` | **`-0x50`** |
| `__TEXT.__const` | `0x13f24` | `0x13f74` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x349b` | `0x34eb` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x1a70` | `0x1a38` | **`-0x38`** |
| `__AUTH_CONST.__cfstring` | `0x4560` | `0x4580` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x2ac` | `0x2cc` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x4ec` | `0x508` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x16b8` | `0x16d0` | **`+0x18`** |
| `__DATA.__data` | `0x3928` | `0x3940` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x4d00` | `0x4ce8` | **`-0x18`** |
| `__TEXT.__swift_as_entry` | `0x23c` | `0x250` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x10b8` | `0x10a8` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x12ac` | `0x12bc` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x708` | `0x700` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x5b8` | `0x5b0` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0xf8` | `0x100` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x360` | `0x358` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x22c4` | `0x22cc` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__ustring`

### Other Changes

```diff

-625.1.18.10.4
+625.1.20.10.3

-  - /usr/lib/swift/libswiftMLCompute.dylib

-  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Functions: 8175
-  Symbols:   6591
-  CStrings:  1347
+  Functions: 8196
+  Symbols:   6564
+  CStrings:  1352
Symbols:
+ -[ASAuthorizationController proxyShouldIgnoreSilentRequestRequirements]
+ -[ASAuthorizationController setProxyShouldIgnoreSilentRequestRequirements:]
+ -[ASCredentialRequestContainerViewController _updateSheetPresentation]
+ -[_ASAgentPeriodicMaintenanceActivity initRegisteringActivityHandler:pccLimitChecker:securityRecommendationsBiomeDonor:]
+ -[_ASAgentPeriodicMaintenanceActivity securityRecommendationsBiomeDonor]
+ -[_ASAgentPeriodicMaintenanceActivity setSecurityRecommendationsBiomeDonor:]
+ _OBJC_CLASS_$_UISheetPresentationControllerDetent
+ _OBJC_CLASS_$_WBSPasswordWarning
+ _OBJC_IVAR_$_ASAuthorizationController._proxyShouldIgnoreSilentRequestRequirements
+ _OBJC_IVAR_$__ASAgentPeriodicMaintenanceActivity._securityRecommendationsBiomeDonor
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_WBSHistoricalHighLevelDomainsProvider
+ __OBJC_$_PROTOCOL_METHOD_TYPES_WBSHistoricalHighLevelDomainsProvider
+ __OBJC_LABEL_PROTOCOL_$_WBSHistoricalHighLevelDomainsProvider
+ __OBJC_PROTOCOL_$_WBSHistoricalHighLevelDomainsProvider
+ ___70-[ASCredentialRequestContainerViewController _updateSheetPresentation]_block_invoke
+ ___73-[_ASAgentPeriodicMaintenanceActivity _runActivityWithCompletionHandler:]_block_invoke_6
+ ___block_descriptor_40_e64_d16?0"<UISheetPresentationControllerDetentResolutionContext>"8l
+ ___swift_closure_destructor.25Tm
+ ___swift_closure_destructor.94Tm
+ _flat unique So37WBSHistoricalHighLevelDomainsProvider_p
+ _swift_unknownObjectRetain_n
+ _symbolic SccySaySo18WBSPasswordWarningCG______pG s5ErrorP
+ _symbolic So25WBSPasswordWarningManagerC
+ _symbolic ______pSg So37WBSHistoricalHighLevelDomainsProviderP
+ _symbolic _____ySo25WBSPasswordWarningManagerCG 10SafariCore7WBSLazyC
+ _symbolic _____y______pG 10SafariCore7WBSLazyC 022AuthenticationServicesB029ASCredentialProvidersProviderP
+ _symbolic _____y______pG 10SafariCore7WBSLazyC 22AuthenticationServices039ASAutoFillCredentialProviderInformationI0P
+ _symbolic _____y______pG 10SafariCore7WBSLazyC 22AuthenticationServices27ASApplicationRecordResolverP
+ _symbolic _____y______pG 10SafariCore7WBSLazyC 22AuthenticationServices35ASAccountUpgradeInformationProviderP
+ _symbolic _____y______pG 10SafariCore7WBSLazyC 22AuthenticationServices35ASPasswordCredentialActionsProviderP
- -[ASCredentialRequestContainerViewController animationControllerForDismissedController:]
- -[ASCredentialRequestContainerViewController animationControllerForPresentedController:presentingController:sourceController:]
- -[ASCredentialRequestContainerViewController viewWillAppear:]
- -[ASCredentialRequestContainerViewController viewWillDisappear:]
- -[ASCredentialRequestContainerViewControllerAnimator _viewControllerForTransitionContext:]
- -[ASCredentialRequestContainerViewControllerAnimator animateTransition:]
- -[ASCredentialRequestContainerViewControllerAnimator initWithPresenting:]
- -[ASCredentialRequestContainerViewControllerAnimator init]
- -[ASCredentialRequestContainerViewControllerAnimator isPresenting]
- -[ASCredentialRequestContainerViewControllerAnimator transitionDuration:]
- -[_ASAgentPeriodicMaintenanceActivity initRegisteringActivityHandler:pccLimitChecker:]
- _CGRectEqualToRect
- _OBJC_CLASS_$_ASCredentialRequestContainerViewControllerAnimator
- _OBJC_IVAR_$_ASCredentialRequestContainerViewController._sheetContainerView
- _OBJC_IVAR_$_ASCredentialRequestContainerViewController._sheetHeightConstraint
- _OBJC_IVAR_$_ASCredentialRequestContainerViewController._sheetPresentedConstraint
- _OBJC_IVAR_$_ASCredentialRequestContainerViewControllerAnimator._presenting
- _OBJC_METACLASS_$_ASCredentialRequestContainerViewControllerAnimator
- _UITransitionContextFromViewControllerKey
- _UITransitionContextFromViewKey
- _UITransitionContextToViewControllerKey
- _UITransitionContextToViewKey
- __OBJC_$_INSTANCE_METHODS_ASCredentialRequestContainerViewControllerAnimator
- __OBJC_$_INSTANCE_VARIABLES_ASCredentialRequestContainerViewControllerAnimator
- __OBJC_$_PROP_LIST_ASCredentialRequestContainerViewControllerAnimator
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_UIViewControllerAnimatedTransitioning
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_UIViewControllerTransitioningDelegate
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_UIViewControllerAnimatedTransitioning
- __OBJC_$_PROTOCOL_METHOD_TYPES_UIViewControllerAnimatedTransitioning
- __OBJC_$_PROTOCOL_METHOD_TYPES_UIViewControllerTransitioningDelegate
- __OBJC_$_PROTOCOL_REFS_UIViewControllerAnimatedTransitioning
- __OBJC_$_PROTOCOL_REFS_UIViewControllerTransitioningDelegate
- __OBJC_CLASS_PROTOCOLS_$_ASCredentialRequestContainerViewControllerAnimator
- __OBJC_CLASS_RO_$_ASCredentialRequestContainerViewControllerAnimator
- __OBJC_LABEL_PROTOCOL_$_UIViewControllerAnimatedTransitioning
- __OBJC_LABEL_PROTOCOL_$_UIViewControllerTransitioningDelegate
- __OBJC_METACLASS_RO_$_ASCredentialRequestContainerViewControllerAnimator
- __OBJC_PROTOCOL_$_UIViewControllerAnimatedTransitioning
- __OBJC_PROTOCOL_$_UIViewControllerTransitioningDelegate
- ___100-[ASCredentialRequestContainerViewController preferredContentSizeDidChangeForChildContentContainer:]_block_invoke_2
- ___100-[ASCredentialRequestContainerViewController preferredContentSizeDidChangeForChildContentContainer:]_block_invoke_3
- ___61-[ASCredentialRequestContainerViewController viewWillAppear:]_block_invoke
- ___64-[ASCredentialRequestContainerViewController viewWillDisappear:]_block_invoke
- ___72-[ASCredentialRequestContainerViewControllerAnimator animateTransition:]_block_invoke
- ___72-[ASCredentialRequestContainerViewControllerAnimator animateTransition:]_block_invoke_2
- ___72-[ASCredentialRequestContainerViewControllerAnimator animateTransition:]_block_invoke_3
- ___block_descriptor_32_e56_v16?0"<UIViewControllerTransitionCoordinatorContext>"8l
- ___block_descriptor_48_e8_32s40bs_e56_v16?0"<UIViewControllerTransitionCoordinatorContext>"8ls32l8s40l8
- ___swift_closure_destructor.23Tm
- ___swift_closure_destructor.95Tm
- __swift_FORCE_LOAD_$_swiftMLCompute
- __swift_FORCE_LOAD_$_swiftMLCompute_$_AuthenticationServices
- __swift_FORCE_LOAD_$_swiftNaturalLanguage
- __swift_FORCE_LOAD_$_swiftNaturalLanguage_$_AuthenticationServices
- _symbolic ______pSg 22AuthenticationServices039ASAutoFillCredentialProviderInformationF0P
- _symbolic ______pSg 22AuthenticationServices35ASAccountUpgradeInformationProviderP
- _symbolic ______pSg 22AuthenticationServices35ASPasswordCredentialActionsProviderP
CStrings:
+ "%@ and %@ will have access to the passwords and passkeys you’ve shared, as well as any you share later.\n\nYou can send a message to let them know they’ve been invited. They can still accept your invitation if you don’t send a message."
+ "%@ will have access to the passwords and passkeys you’ve shared, as well as any you share later.\n\nYou can send a message to let them know they’ve been invited. They can still accept your invitation if you don’t send a message."
+ "%@, %@, and %@ will have access to the passwords and passkeys you’ve shared, as well as any you share later.\n\nYou can send a message to let them know they’ve been invited. They can still accept your invitation if you don’t send a message."
+ "ASCredentialRequestContentDetent"
+ "Failed to fetch warnings: %{public}s"
+ "No warnings to report"
+ "WBSSecurityRecommendationsBiomeDonationLastDate"
+ "d16@?0@\"<UISheetPresentationControllerDetentResolutionContext>\"8"
- "%@ and %@ will have access to the passwords and passkeys you’ve shared, as well as any you share later.\n\nYou can send a message to let them know they‘ve been invited. They can still accept your invitation if you don‘t send a message."
- "%@ will have access to the passwords and passkeys you’ve shared, as well as any you share later.\n\nYou can send a message to let them know they‘ve been invited. They can still accept your invitation if you don‘t send a message."
- "%@, %@, and %@ will have access to the passwords and passkeys you’ve shared, as well as any you share later.\n\nYou can send a message to let them know they‘ve been invited. They can still accept your invitation if you don‘t send a message."
```
