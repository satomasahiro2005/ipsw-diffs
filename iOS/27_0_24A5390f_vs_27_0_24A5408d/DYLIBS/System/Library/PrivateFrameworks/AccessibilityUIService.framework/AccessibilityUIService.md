## AccessibilityUIService

> `/System/Library/PrivateFrameworks/AccessibilityUIService.framework/AccessibilityUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x13c4` | `0x16eb` | **`+0x327`** |
| `__TEXT.__text` | `0x1f380` | `0x1f61c` | **`+0x29c`** |
| `__TEXT.__unwind_info` | `0x8b0` | `0x8a0` | **`-0x10`** |
| `__TEXT.__const` | `0x850` | `0x858` | **`+0x8`** |

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

+  - /System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices

-  CStrings:  216
+  CStrings:  220
Symbols:
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
- ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
Functions:
~ -[AXUIServiceManager _extractAndHandleRegistration:clientIdentifier:messageIdentifier:context:error:] : 352 -> 476
~ -[AXUIServiceEntitlementChecker serviceCanProcessMessageWithIdentifier:fromClientWithConnection:possibleRequiredEntitlements:needsToRequireEntitlements:] : 1156 -> 1184
~ -[AXUIDisplayManager _sceneIsAttachable:] : 52 -> 140
~ -[AXUIDisplayManager _removeContentViewController:forService:completion:] : 468 -> 488
~ ___73-[AXUIDisplayManager _removeContentViewController:forService:completion:]_block_invoke : 836 -> 896
~ -[AXUIAssertionManager invalidateAssertionIfNeeded] : 140 -> 252
~ ___51-[AXUIAssertionManager invalidateAssertionIfNeeded]_block_invoke : 256 -> 348
~ -[AXUIAssertionManager invalidateAssertionUIIfNeeded] : 140 -> 252
~ ___53-[AXUIAssertionManager invalidateAssertionUIIfNeeded]_block_invoke : 392 -> 424
CStrings:
+ "Can't invalidate Background Assertion, %lu services are still registered: %@. This timer is not automatically rescheduled — invalidation will not be retried until the next call to acquireAssertionIfNeeded/invalidateAssertionIfNeeded."
+ "Can't invalidate UI Assertion, still clients with UI assertion %@. This timer is not automatically rescheduled — invalidation will not be retried until the next call to acquireAssertionUIIfNeeded/invalidateAssertionUIIfNeeded."
+ "First registration for client %@ serviceBundleName=%@, triggered by message identifier %lu from pid %d"
+ "_removeContentViewController for service %@: isLastVCInWindow=%d requestedSceneDestruction=%d (if NO, the scene for this service's content view controller remains alive)"
+ "invalidateAssertionIfNeeded scheduling timer, current assertionBackground: %@"
+ "invalidateAssertionIfNeeded timer fired, assertionBackground: %@"
+ "invalidateAssertionUIIfNeeded scheduling timer, current assertionUI: %@"
+ "invalidateAssertionUIIfNeeded timer fired, assertionUI: %@"
- "Can't invalidate Background Assertion, still services are registered"
- "Can't invalidate UI Assertion, still clients with UI assertion %@"
- "invalidateAssertionIfNeeded timer"
- "invalidateAssertionUIIfNeeded timer"
```
