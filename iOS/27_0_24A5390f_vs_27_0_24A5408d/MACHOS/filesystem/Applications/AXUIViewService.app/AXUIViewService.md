## AXUIViewService

> `/Applications/AXUIViewService.app/AXUIViewService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdc5c` | `0xe95c` | **`+0xd00`** |
| `__TEXT.__objc_methname` | `0x4ffb` | `0x55b8` | **`+0x5bd`** |
| `__DATA.__objc_const` | `0x23a8` | `0x27e8` | **`+0x440`** |
| `__TEXT.__objc_stubs` | `0x30a0` | `0x33c0` | **`+0x320`** |
| `__TEXT.__objc_methlist` | `0x197c` | `0x1c54` | **`+0x2d8`** |
| `__TEXT.__objc_methtype` | `0x1cf8` | `0x1fa7` | **`+0x2af`** |
| `__DATA.__objc_selrefs` | `0x13f0` | `0x1530` | **`+0x140`** |
| `__DATA.__objc_data` | `0x6e0` | `0x7d0` | **`+0xf0`** |
| `__DATA.__data` | `0x660` | `0x720` | **`+0xc0`** |
| `__TEXT.__objc_classname` | `0x4bd` | `0x565` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0x470` | `0x4d8` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x5c6` | `0x629` | **`+0x63`** |
| `__TEXT.__gcc_except_tab` | `0x2a8` | `0x2ec` | **`+0x44`** |
| `__DATA_CONST.__const` | `0x590` | `0x5d0` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x660` | `0x690` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x980` | `0x9a0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x340` | `0x358` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x2e0` | `0x2f8` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0xb0` | `0xc8` | **`+0x18`** |
| `__TEXT.__cstring` | `0x99b` | `0x9b3` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xf8` | `0x108` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x88` | `0x98` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x90` | `0xa0` | **`+0x10`** |
| `__DATA_CONST.__objc_catlist` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__const` | `0x68` | `0x70` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  Functions: 353
-  Symbols:   219
-  CStrings:  1124
+  Functions: 391
+  Symbols:   224
+  CStrings:  1196
Symbols:
+ _AXLogUIViewService
+ _OBJC_CLASS_$_UIWindow
+ _OBJC_CLASS_$_UIWindowScene
+ _objc_getAssociatedObject
+ _objc_setAssociatedObject
CStrings:
+ "@\"NSUserActivity\"24@0:8@\"UIScene\"16"
+ "@\"SBSUIRemoteAlertScene\""
+ "@\"UISceneWindowingControlStyle\"24@0:8@\"UIWindowScene\"16"
+ "AXSceneHosting"
+ "AXUIViewServiceRemoteAlertHostProxy"
+ "AXUIViewServiceRemoteAlertSceneDelegate"
+ "AXVSRemoteAlertContainerViewController"
+ "Q24@0:8@\"UIWindowScene\"16"
+ "Q24@0:8@16"
+ "SBSUIRemoteAlertScene"
+ "T@\"AXUIViewServiceRemoteAlertHostProxy\",&,N,Sax_setSceneHostProxy:"
+ "T@\"SBSUIRemoteAlertScene\",W,N,V_remoteAlertScene"
+ "T@\"UIViewController\",&,N,V_contentViewController"
+ "UISceneDelegate"
+ "UIWindowSceneDelegate"
+ "[AXUIViewServiceRemoteAlert] No content for configurationIdentifier=%{public}@ userInfo=%{public}@"
+ "_contentViewController"
+ "_invalidateScene"
+ "_onboardingContentViewControllerForUserInfo:"
+ "_remoteAlertScene"
+ "_rootViewControllerForScene:"
+ "activationContext"
+ "ax_sceneHostProxy"
+ "ax_setSceneHostProxy:"
+ "configurationContext"
+ "configurationIdentifier"
+ "contentViewController"
+ "initWithRemoteAlertScene:"
+ "initWithWindowScene:"
+ "makeKeyAndVisible"
+ "preferredWindowingControlStyleForScene:"
+ "presentedViewController"
+ "remoteAlertScene"
+ "scene:continueUserActivity:"
+ "scene:didFailToContinueUserActivityWithType:error:"
+ "scene:didUpdateUserActivity:"
+ "scene:openURLContexts:"
+ "scene:restoreInteractionStateWithUserActivity:"
+ "scene:willConnectToSession:options:"
+ "scene:willContinueUserActivityWithType:"
+ "sceneDidBecomeActive:"
+ "sceneDidDisconnect:"
+ "sceneDidEnterBackground:"
+ "sceneWillEnterForeground:"
+ "sceneWillResignActive:"
+ "setAllowsAlertStacking:"
+ "setContentOverlaysStatusBar:animationSettings:"
+ "setContentViewController:"
+ "setDesiredHardwareButtonEvents:"
+ "setOrientationChangedEventsDisabled:"
+ "setRemoteAlertScene:"
+ "setWallpaperStyle:animationSettings:"
+ "stateRestorationActivityForScene:"
+ "supportedInterfaceOrientationsForWindowScene:"
+ "v24@0:8@\"UIScene\"16"
+ "v24@0:8Q16"
+ "v28@0:8B16d20"
+ "v32@0:8@\"UIScene\"16@\"NSSet\"24"
+ "v32@0:8@\"UIScene\"16@\"NSString\"24"
+ "v32@0:8@\"UIScene\"16@\"NSUserActivity\"24"
+ "v32@0:8@\"UIWindowScene\"16@\"CKShareMetadata\"24"
+ "v32@0:8@\"UIWindowScene\"16@\"UIWindowSceneGeometry\"24"
+ "v32@0:8q16d24"
+ "v40@0:8@\"UIScene\"16@\"NSString\"24@\"NSError\"32"
+ "v40@0:8@\"UIScene\"16@\"UISceneSession\"24@\"UISceneConnectionOptions\"32"
+ "v40@0:8@\"UIWindowScene\"16@\"UIApplicationShortcutItem\"24@?<v@?B>32"
+ "v48@0:8@\"UIWindowScene\"16@\"<UICoordinateSpace>\"24q32@\"UITraitCollection\"40"
+ "v48@0:8@16@24q32@40"
+ "windowScene:didUpdateCoordinateSpace:interfaceOrientation:traitCollection:"
+ "windowScene:didUpdateEffectiveGeometry:"
+ "windowScene:performActionForShortcutItem:completionHandler:"
+ "windowScene:userDidAcceptCloudKitShareWithMetadata:"
```
