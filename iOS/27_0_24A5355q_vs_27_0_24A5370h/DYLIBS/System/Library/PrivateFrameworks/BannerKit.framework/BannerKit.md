## BannerKit

> `/System/Library/PrivateFrameworks/BannerKit.framework/BannerKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d57c` | `0x2d4b4` | **`-0xc8`** |

### Other Changes

```diff

-163.0.1.0.0
+165.0.0.0.0
Functions:
~ -[BNContentViewController canBecomeFirstResponder] : 284 -> 280
~ -[BNContentViewController _handlePan:] : 2124 -> 2112
~ -[BNContentViewController becomeFirstResponder] : 284 -> 280
~ -[BNBannerController setSuspended:forReason:revokingCurrent:error:] : 704 -> 700
~ -[BNPenderQueue isSuspended] : 376 -> 372
~ -[BNTieredArray allObjects] : 388 -> 384
~ -[BNPenderQueue peekPresentable] : 380 -> 376
~ -[BNBannerController _revokePresentablesWithIdentification:reason:options:animated:userInfo:error:] : 1072 -> 1068
~ -[BNContentViewController _dismissPresentablesWithIdentification:reason:animated:userInfo:] : 340 -> 336
~ -[BNContentViewController _presentablesWithIdentification:requiringUniqueMatch:] : 368 -> 364
~ -[BNBannerSourceListener _removeUnpreparedPresentablesWithIdentification:] : 628 -> 624
~ _BNPresentableDescription : 656 -> 652
~ ___76-[BNContentViewController _dismissPresentable:withReason:animated:userInfo:]_block_invoke : 1032 -> 1028
~ -[BNBannerSourceListenerPresentableViewController(SubclassUtilities) _enumerateObserversRespondingToSelector:usingBlock:] : 336 -> 332
~ -[BNContentViewController _postLayoutChangeForVisibleNotifications] : 700 -> 696
~ -[BNBannerController _resumeForResponsiblePresentableIfNecessaryWithIdentification:] : 332 -> 328
~ -[BNBannerController _resumeForResponsiblePresentableIfNecessary:] : 392 -> 388
~ -[NSArray(BNPresentableIdentifyingAdditions) bn_identificationsForPresentables] : 380 -> 376
~ -[BNTieredArray count] : 260 -> 256
~ -[BNBannerSourceListener _removePresentableWithIdentification:requiringUniqueMatch:] : 364 -> 360
~ _BNInterfaceOrientationFromTransform : 204 -> 196
~ -[BNPresentableQueue _pullPresentablesPassingTest:] : 928 -> 932
~ -[_BNPresentableContext _enumerateObserversRespondingToSelector:usingBlock:] : 324 -> 320
~ -[BNBannerSourceListener invalidate] : 628 -> 616
~ -[BNBannerSourceListener layoutDescriptionDidChange:] : 720 -> 716
~ -[BNBannerSourceListener _isPresentableWithIdentificationWaitingToBeMadeReady:] : 360 -> 356
~ -[BNBannerSourceListener _presentablesWithIdentification:requiringUniqueMatch:] : 516 -> 512
~ -[BNBannerClientContainerViewController _respondToActions:forFBSScene:inUIScene:fromTransitionContext:] : 564 -> 560
~ -[BNContentViewController resignFirstResponder] : 284 -> 280
~ -[BNContentViewController viewWillAppear:] : 320 -> 316
~ -[BNContentViewController viewDidAppear:] : 324 -> 320
~ -[BNContentViewController viewWillDisappear:] : 320 -> 316
~ -[BNContentViewController viewDidDisappear:] : 324 -> 320
~ -[BNContentViewController shouldAutorotate] : 288 -> 284
~ -[BNContentViewController _updateFrameForChildContentContainer:minimumTopInsetUpdate:] : 1568 -> 1564
~ ___78-[BNContentViewController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke : 776 -> 772
~ -[BNContentViewController presentPresentable:withOptions:reason:animated:userInfo:] : 2620 -> 2616
~ ___83-[BNContentViewController presentPresentable:withOptions:reason:animated:userInfo:]_block_invoke_2 : 1236 -> 1228
~ ___96-[BNContentViewController _morphFromPresentable:toPresentable:withOptions:userInfo:stateChange:]_block_invoke : 992 -> 988
~ -[BNContentViewController gestureRecognizer:shouldReceiveTouch:] : 572 -> 568
~ -[BNContentViewController _presentableForGestureInView:] : 360 -> 356
~ -[BNBannerMorphTransitionAnimator _shadowViewForViewController:] : 368 -> 364
~ -[BNBannerMorphTransitionAnimator _contentViewForViewController:] : 444 -> 440
~ -[BNPenderQueue activeSuspensionReasons] : 560 -> 556
~ -[UIView(BannerKitAdditions) bn_existingGaussianBlurFilter] : 312 -> 308
~ -[BNBannerHostMonitorListener _notifyObserversWithBlock:] : 292 -> 288
```
