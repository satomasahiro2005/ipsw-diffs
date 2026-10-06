## CarPlayTemplateUIHost

> `/System/Library/CoreServices/CarPlayTemplateUIHost.app/CarPlayTemplateUIHost`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd050` | `0xb280` | **`-0x1dd0`** |
| `__DATA.__objc_const` | `0x3ac8` | `0x3128` | **`-0x9a0`** |
| `__TEXT.__objc_methname` | `0x3e01` | `0x35ad` | **`-0x854`** |
| `__TEXT.__objc_stubs` | `0x2c20` | `0x2680` | **`-0x5a0`** |
| `__TEXT.__objc_methlist` | `0x138c` | `0x110c` | **`-0x280`** |
| `__DATA.__objc_selrefs` | `0xf28` | `0xd20` | **`-0x208`** |
| `__TEXT.__objc_methtype` | `0xd01` | `0xbb2` | **`-0x14f`** |
| `__TEXT.__oslogstring` | `0xd51` | `0xc52` | **`-0xff`** |
| `__DATA.__data` | `0x600` | `0x540` | **`-0xc0`** |
| `__DATA_CONST.__cfstring` | `0x3e0` | `0x320` | **`-0xc0`** |
| `__DATA.__objc_data` | `0x370` | `0x2d0` | **`-0xa0`** |
| `__TEXT.__objc_classname` | `0x322` | `0x29a` | **`-0x88`** |
| `__TEXT.__gcc_except_tab` | `0x2c0` | `0x254` | **`-0x6c`** |
| `__DATA_CONST.__got` | `0x1f0` | `0x1a8` | **`-0x48`** |
| `__TEXT.__unwind_info` | `0x340` | `0x300` | **`-0x40`** |
| `__DATA.__objc_ivar` | `0x144` | `0x10c` | **`-0x38`** |
| `__TEXT.__cstring` | `0x5ce` | `0x5ad` | **`-0x21`** |
| `__DATA_CONST.__objc_classlist` | `0x58` | `0x48` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x80` | `0x70` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x50` | `0x40` | **`-0x10`** |
| `__TEXT.__const` | `0x40` | `0x38` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-574.2.0.0.0
+577.2.0.0.0

-  - /System/Library/PrivateFrameworks/BannerKit.framework/BannerKit

-  Functions: 369
-  Symbols:   138
-  CStrings:  919
+  Functions: 322
+  Symbols:   129
+  CStrings:  800
Symbols:
- _CGRectZero
- _OBJC_CLASS_$_BNSceneSettings
- _OBJC_CLASS_$_CARSessionStatus
- _OBJC_CLASS_$_NSURL
- _OBJC_CLASS_$_UILabel
- _OBJC_CLASS_$_UILayoutGuide
- _UISceneDidEnterBackgroundNotification
- _UISceneWillEnterForegroundNotification
- ___NSArray0__struct
CStrings:
- "1"
- "2"
- "3"
- "@\"CARSessionStatus\""
- "@\"CARTemplateUIDashboardButton\""
- "@\"CARTemplateUIHostInstrumentClusterViewController\""
- "@\"CRSUIClusterWindow\""
- "@\"NSXPCConnection\""
- "@\"UIView\""
- "@\"UIWindow\""
- "Banner scene disconnected: %@"
- "Banner scene entering foreground: %@"
- "CARTemplateUIDashboardButton"
- "CARTemplateUIHostDashboardViewController"
- "CRSUIDashboardFocusableItemProviding"
- "Other scene disconnected: %@"
- "Scene entering foreground for client: %@"
- "T@\"CARSessionStatus\",&,N,V_sessionStatus"
- "T@\"CARTemplateUIDashboardButton\",&,N,V_button1"
- "T@\"CARTemplateUIDashboardButton\",&,N,V_button2"
- "T@\"CARTemplateUIDashboardButton\",&,N,V_button3"
- "T@\"CARTemplateUIHostInstrumentClusterViewController\",&,N,V_instrumentClusterViewController"
- "T@\"CRSUIClusterWindow\",&,N,V_instrumentClusterWindow"
- "T@\"CRSUIDashboardWidgetWindow\",&,N,V_largeDashboardWindow"
- "T@\"CRSUIDashboardWidgetWindow\",&,N,V_smallDashboardWindow"
- "T@\"NSArray\",R,N"
- "T@\"NSXPCConnection\",&,N,V_connection"
- "T@\"UIView\",&,N,V_safeView"
- "T@\"UIWindow\",&,N,V_mainWindow"
- "T@\"UIWindow\",W,N,V_activeWindow"
- "T@\"UIWindowScene\",W,N,V_activeBannerScene"
- "UIApplicationDelegatePrivate"
- "URLWithString:"
- "Unable to find environment for scene: %@"
- "Unexpected scene entering foreground: %@"
- "You are using: %@"
- "_activeBannerScene"
- "_activeWindow"
- "_application:handleSiriTask:"
- "_application:statusBarTouchesEnded:"
- "_button1"
- "_button1Triggered"
- "_button2"
- "_button2Triggered"
- "_button3"
- "_button3Triggered"
- "_connection"
- "_instrumentClusterViewController"
- "_instrumentClusterWindow"
- "_largeDashboardWindow"
- "_mainWindow"
- "_safeView"
- "_sceneDidDidEnterBackground:"
- "_sceneWillEnterForeground:"
- "_sessionStatus"
- "_smallDashboardWindow"
- "activeBannerScene"
- "activeWindow"
- "addLayoutGuide:"
- "addTarget:action:forControlEvents:"
- "application:didFinishLaunchingSuspendedWithOptions:"
- "application:userAcceptedCloudKitShareWithMetadata:"
- "blueColor"
- "button1"
- "button2"
- "button3"
- "buttonWithType:"
- "centerXAnchor"
- "centerYAnchor"
- "connection"
- "constraintEqualToAnchor:constant:"
- "constraintLessThanOrEqualToAnchor:constant:"
- "currentSession"
- "focusableItemFocused:"
- "focusableItemPressed:"
- "focusableItemSelected"
- "initAndWaitUntilSessionUpdated"
- "initWithFrame:"
- "instrumentClusterViewController"
- "instrumentClusterWindow"
- "largeDashboardWindow"
- "mainWindow"
- "maps:"
- "redColor"
- "safeAreaLayoutGuide"
- "safeView"
- "scene: (%@) didUpdateSettings: (%@)"
- "sendActionsForControlEvents:"
- "sessionStatus"
- "setActiveBannerScene:"
- "setActiveWindow:"
- "setBackgroundColor:"
- "setButton1:"
- "setButton2:"
- "setButton3:"
- "setConnection:"
- "setFocusableViews:"
- "setHighlighted:"
- "setInstrumentClusterViewController:"
- "setInstrumentClusterWindow:"
- "setLargeDashboardWindow:"
- "setMainWindow:"
- "setNumberOfLines:"
- "setSafeView:"
- "setSessionStatus:"
- "setSmallDashboardWindow:"
- "setTextAlignment:"
- "setTextColor:"
- "setTintColor:"
- "setTitle:forState:"
- "smallDashboardWindow"
- "suggestUI:"
- "v32@0:8@\"UIApplication\"16@\"AFSiriTask\"24"
- "v32@0:8@\"UIApplication\"16@\"CKShareMetadata\"24"
- "v32@0:8@\"UIApplication\"16@\"NSDictionary\"24"
- "v32@0:8@\"UIApplication\"16@\"UIEvent\"24"
- "viewDidAppear:"
- "whiteColor"
- "yellowColor"
```
