## UIKitCore

> `/System/Library/PrivateFrameworks/UIKitCore.framework/UIKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bdc124` | `0x1bdbb64` | **`-0x5c0`** |
| `__AUTH_CONST.__objc_const` | `0x27b350` | `0x27b410` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x1026f3` | `0x102637` | **`-0xbc`** |
| `__TEXT.__objc_methlist` | `0x1a0db8` | `0x1a0e68` | **`+0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0x962e0` | `0x96380` | **`+0xa0`** |
| `__DATA.__bss` | `0x3ebe8` | `0x3eb50` | **`-0x98`** |
| `__AUTH_CONST.__cfstring` | `0xb3ce0` | `0xb3c60` | **`-0x80`** |
| `__TEXT.__oslogstring` | `0x56795` | `0x56735` | **`-0x60`** |
| `__AUTH_CONST.__const` | `0x5cbc0` | `0x5cc00` | **`+0x40`** |
| `__DATA_DIRTY.__bss` | `0x166a8` | `0x166d8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x3eda8` | `0x3edd0` | **`+0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0x4248` | `0x4220` | **`-0x28`** |
| `__DATA.__objc_ivar` | `0x11cf8` | `0x11d14` | **`+0x1c`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x2e50` | `0x2e38` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x9140` | `0x9158` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x8680` | `0x8670` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x72678` | `0x72680` | **`+0x8`** |
| `__DATA_DIRTY.__objc_ivar` | `0x8974` | `0x8970` | **`-0x4`** |

### Other Changes

```diff

-9127.1.13.1.106
+9127.1.13.1.110

-  Functions: 182113
-  Symbols:   229440
-  CStrings:  33937
+  Functions: 182131
+  Symbols:   229451
+  CStrings:  33932
Symbols:
+ +[UIListContentConfiguration _defaultConfigurationForFixedStyle:state:traitCollection:]
+ -[UICollectionViewCell _didPerformConfigurationStateUpdate]
+ -[UICollectionViewListCell _didPerformConfigurationStateUpdate]
+ -[UITableViewCell _didPerformConfigurationStateUpdate]
+ -[UIWebClip connection:didFailWithError:]
+ -[UIWebClip connection:didReceiveData:]
+ -[UIWebClip connection:didReceiveResponse:]
+ -[UIWebClip connectionDidFinishLoading:]
+ -[UIWebClip requestCustomIconUpdate]
+ -[UIWebClip requestCustomLandscapeStartupImageUpdate]
+ -[UIWebClip requestCustomPortraitStartupImageUpdate]
+ -[UIWebClip stopLoadingCustomIcon]
+ -[UIWebClip stopLoadingStartupImage]
+ -[UIWebClip stopLoadingStartupLandscapeImage]
+ -[UIWebClip tryLoadingNextCustomIcon]
+ GCC_except_table1032
+ GCC_except_table1033
+ GCC_except_table1036
+ GCC_except_table1138
+ GCC_except_table1141
+ GCC_except_table1145
+ GCC_except_table1146
+ GCC_except_table1150
+ GCC_except_table1157
+ GCC_except_table280
+ GCC_except_table433
+ GCC_except_table434
+ GCC_except_table458
+ GCC_except_table478
+ GCC_except_table490
+ GCC_except_table504
+ GCC_except_table505
+ GCC_except_table510
+ GCC_except_table541
+ GCC_except_table546
+ GCC_except_table698
+ GCC_except_table704
+ GCC_except_table734
+ GCC_except_table780
+ GCC_except_table788
+ GCC_except_table804
+ _OBJC_CLASS_$_FBSDeviceEmulationConfiguration
+ _OBJC_CLASS_$_NSHTTPURLResponse
+ _OBJC_CLASS_$_NSURLConnection
+ _OBJC_IVAR_$_UICollectionViewCell._collectionCellFlags
+ _OBJC_IVAR_$_UIWebClip._customIconData
+ _OBJC_IVAR_$_UIWebClip._customStartupImageData
+ _OBJC_IVAR_$_UIWebClip._customStartupLandscapeImageData
+ _OBJC_IVAR_$_UIWebClip._iconConnection
+ _OBJC_IVAR_$_UIWebClip._startupImageConnection
+ _OBJC_IVAR_$_UIWebClip._startupLandscapeImageConnection
+ __UIApplicationProcessIsTVRemote
+ ___67-[_UIScreenComplexBoundingPathUtilities _loadBitmapForScreen:type:]_block_invoke
+ ____UIApplicationProcessIsTVRemote_block_invoke
+ ____alwaysIgnoreHIDEdgeFlags_block_invoke
+ ___block_descriptor_56_e8_32s_e28_B24?0{_UIIntegralPoint=qq}8ls32l8
+ __panGestureStart:.__s_category
+ _activeKeyboard
- GCC_except_table1029
- GCC_except_table1030
- GCC_except_table1034
- GCC_except_table1136
- GCC_except_table1139
- GCC_except_table1143
- GCC_except_table1148
- GCC_except_table1155
- GCC_except_table278
- GCC_except_table431
- GCC_except_table432
- GCC_except_table456
- GCC_except_table502
- GCC_except_table503
- GCC_except_table527
- GCC_except_table539
- GCC_except_table544
- GCC_except_table559
- GCC_except_table640
- GCC_except_table641
- GCC_except_table696
- GCC_except_table702
- GCC_except_table732
- GCC_except_table778
- GCC_except_table786
- GCC_except_table802
- __UIKBHTVerifyFrameworkDepth
- __verifyClient.didReport
- _acceptAutocorrection._UIKBHT_hit
- _activeKeyboardSceneDelegate._UIKBHT_hit
- _addSubview:._UIKBHT_hit
- _autocorrectionController._UIKBHT_hit
- _candidateController._UIKBHT_hit
- _candidateViewController._UIKBHT_hit
- _compatibilityViewController._UIKBHT_hit
- _hitTest:withEvent:.onceToken
- _inlineTextCompletionController._UIKBHT_hit
- _inputManager._UIKBHT_hit
- _predictionViewController._UIKBHT_hit
- _predictiveViewController._UIKBHT_hit
- _remoteKeyboardWindowForScene:create:._UIKBHT_hit
- _remoteTextInputPartner._UIKBHT_hit
- _rootViewController._UIKBHT_hit
- _sharedInstance._UIKBHT_hit
- _strncmp
- _thread_stack_pcs
- _window._UIKBHT_hit
CStrings:
+ "B24@?0{_UIIntegralPoint=qq}8"
+ "FeedbackFCSBehavior"
+ "com.apple.TVRemoteApp"
- "%{public}@ Called into an unapproved SPI."
- "/System/Library/"
- "Attempting to retrieve sensitivity information without a touchpad."
- "Unknown UIKeyboardViewController client (bundleID=%@)"
- "Verify UIKeyboardViewController client (bundleID=%@, isKnown=%s)"
- "com.apple.ContactsUI.MonogramPosterExtension"
- "com.apple.QuickboardViewService"
- "keyboard_spi_caller_verification"
```
