## AccessibilityUIService

> `/System/Library/PrivateFrameworks/AccessibilityUIService.framework/AccessibilityUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fc60` | `0x1ff84` | **`+0x324`** |
| `__TEXT.__oslogstring` | `0x1784` | `0x1a70` | **`+0x2ec`** |
| `__TEXT.__const` | `0x868` | `0x880` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x4b0` | `0x4bc` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x920` | `0x928` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x510` | `0x518` | **`+0x8`** |

### Other Changes

```diff

-3240.9.0.0.0
+3245.7.1.0.0

-  Symbols:   1488
-  CStrings:  222
+  Symbols:   1489
+  CStrings:  228
Symbols:
+ _UIFontTextStyleHeadline
Functions:
~ -[AXUIAlertStyleProvider alertBackgroundSizeForType:] : 776 -> 816
~ -[AXUIAlertStyleProvider alertTextFontForType:] : 396 -> 432
~ -[AXUIAlertStyleProvider alertTextColorForType:] : 128 -> 132
~ -[AXUIDisplayManager addContentViewController:withUserInteractionEnabled:forService:forSceneClientIdentifier:context:userInterfaceStyle:forWindowScene:spatialConfiguration:isModal:completion:] : 992 -> 1272
~ -[AXUIDisplayManager waitForSceneAddContentViewController:withUserInteractionEnabled:forService:forSceneClientIdentifier:context:userInterfaceStyle:forWindowScene:spatialConfiguration:isModal:completion:] : 788 -> 812
~ ___204-[AXUIDisplayManager waitForSceneAddContentViewController:withUserInteractionEnabled:forService:forSceneClientIdentifier:context:userInterfaceStyle:forWindowScene:spatialConfiguration:isModal:completion:]_block_invoke : 112 -> 300
~ -[AXUIDisplayManager _windowSceneDisconnected:forSceneClientIdentifier:] : 440 -> 580
~ -[AXUIDisplayManager saveAddContentViewControllerBlock:forObjectKey:forSceneClientIdentifier:] : 356 -> 388
~ -[AXUIDisplayManager removeAddContentViewControllerBlockForObjectKey:] : 460 -> 588
~ -[AXStyleProviderUIAlert initWithType:text:subtitleText:iconImage:styleProvider:userInfo:] : 6488 -> 6444
~ sub_250cdcd28 -> sub_2546d0064 : 744 -> 752
~ sub_250cdd2d8 -> sub_2546d061c : 688 -> 684
~ sub_250cdf044 -> sub_2546d2384 : 3024 -> 3012
~ sub_250ce02cc -> sub_2546d3600 : 104 -> 96
~ sub_250ce0334 -> sub_2546d3660 : 104 -> 96
CStrings:
+ "AXUIDisplayManager was deallocated before queued addContentViewController for %@ sceneClientIdentifier:%@ could run; completion will never fire."
+ "No attachable scene for contentVC=%p sceneClientIdentifier:%@; queuing."
+ "No queued block found for objectKey: %{public}@; nothing to remove."
+ "Remove block for objectKey: %{public}@ sceneClientIdentifier:%{public}@ queueDepth:%lu"
+ "Running queued addContentViewController for %@ sceneClientIdentifier:%@"
+ "Save block for objectKey: %{public}@ sceneClientIdentifier:%{public}@ queueDepth:%lu"
+ "Tried to add %@ before a scene was connected, queuing for later (sceneClientIdentifier:%@, sceneAlreadyRequested=%d)."
+ "Window scene disconnected while %lu add-block(s) still queued for sceneClientIdentifier:%{public}@"
+ "sceneClientIdentifier:%@ windowScene attachable=%d (activationState=%ld), savedWindowScene attachable=%d (activationState=%ld)"
- "Remove block for objectKey: %@"
- "Save block for objectKey: %@"
- "Tried to add %@ before a scene was connected, queuing for later."
```
