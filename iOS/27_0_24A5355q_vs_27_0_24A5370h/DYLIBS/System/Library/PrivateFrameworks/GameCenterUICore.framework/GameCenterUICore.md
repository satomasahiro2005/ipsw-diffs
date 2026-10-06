## GameCenterUICore

> `/System/Library/PrivateFrameworks/GameCenterUICore.framework/GameCenterUICore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34518` | `0x344d4` | **`-0x44`** |
| `__TEXT.__unwind_info` | `0xd20` | `0xd18` | **`-0x8`** |

### Other Changes

```diff

-821.0.13.1.2
+821.0.16.0.0
Functions:
~ -[GKLocalPlayerAuthenticator _handleEditedAuthResponse:error:handler:] : 2484 -> 2476
~ -[GKLocalPlayerAuthenticator remoteUIControllerDidDismiss:] : 860 -> 856
~ -[GKConditionBrush drawInRect:withContext:input:] : 196 -> 192
~ -[GKConditionBrush sizeForInput:] : 140 -> 136
~ -[GKBrushList drawInRect:withContext:input:] : 460 -> 456
~ ___69-[UIViewController(GKAdditions) _gkSetContentsNeedUpdateWithHandler:]_block_invoke.68 -> ___69-[UIViewController(GKAdditions) _gkSetContentsNeedUpdateWithHandler:]_block_invoke.83 : 248 -> 244
~ -[UITabBarController(GKAdditions) _gkForceNextContentUpdate] : 276 -> 272
~ -[UITabBarController(GKAdditions) _gkRefreshContentsForDataType:userInfo:] : 304 -> 300
~ ___74-[UISplitViewController(GKAdditions) _gkSetContentsNeedUpdateWithHandler:]_block_invoke : 468 -> 464
~ -[UISplitViewController(GKAdditions) _gkResetContents] : 240 -> 236
~ -[UISplitViewController(GKAdditions) _gkForceNextContentUpdate] : 276 -> 272
~ _GKRectsCenterYInRect : 168 -> 180
~ _GKRectsCenterXInRect : 184 -> 180
~ -[GKImageColorPalette generateHSVMapWithContext:] : 584 -> 572
~ -[GKImageColorPalette printHistogram:ofSize:] : 108 -> 104
~ -[GKImageColorPalette findBrightColors] : 304 -> 300
~ ___82-[NSString(GKTextStyle) _gkAttributedStringByApplyingStylesForTags:untaggedStyle:]_block_invoke_3 : 380 -> 372
```
