## Silex

> `/System/Library/PrivateFrameworks/Silex.framework/Silex`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x118cf8` | `0x118eb4` | **`+0x1bc`** |
| `__AUTH_CONST.__cfstring` | `0x98e0` | `0x9920` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x51c90` | `0x51cc0` | **`+0x30`** |
| `__TEXT.__cstring` | `0xa09c` | `0xa0c5` | **`+0x29`** |
| `__DATA_CONST.__const` | `0x3c30` | `0x3c58` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x1e6fc` | `0x1e70c` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2498` | `0x24a0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1fac` | `0x1fb0` | **`+0x4`** |

### Other Changes

```diff

-5934.3.0.0.0
+5960.0.0.0.0

-  Functions: 8573
-  Symbols:   20676
-  CStrings:  1844
+  Functions: 8575
+  Symbols:   20680
+  CStrings:  1846
Symbols:
+ -[SXLayoutOptions initWithColumnLayout:viewportSize:safeAreaInsets:traitCollection:contentSizeCategory:bundleSubscriptionStatus:channelSubscriptionStatus:testing:viewingLocation:contentScaleFactor:newsletterSubscriptionStatus:offerUpsellScenario:subscriptionActivationEligibility:offerIdentifier:smartInvertColorsEnabled:conditionKeys:tagSubscriptionStatus:]
+ -[SXLayoutOptions safeAreaInsets]
+ OBJC_IVAR_$_SXLayoutOptions._safeAreaInsets
+ ___110-[SXFullscreenCanvasController fullscreenCanvasViewController:willTransitionToSize:withTransitionCoordinator:]_block_invoke_2
+ ___block_descriptor_40_e8_32s_e56_v16?0"<UIViewControllerTransitionCoordinatorContext>"8ls32l8
- -[SXLayoutOptions initWithColumnLayout:viewportSize:traitCollection:contentSizeCategory:bundleSubscriptionStatus:channelSubscriptionStatus:testing:viewingLocation:contentScaleFactor:newsletterSubscriptionStatus:offerUpsellScenario:subscriptionActivationEligibility:offerIdentifier:smartInvertColorsEnabled:conditionKeys:tagSubscriptionStatus:]
CStrings:
+ "  safeAreaInsets: %@; \n"
+ "SafeAreaInsets; "
```
