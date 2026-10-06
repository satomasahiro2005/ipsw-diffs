## LocalAuthenticationUIService

> `/Applications/LocalAuthenticationUIService.app/LocalAuthenticationUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6c160` | `0x6c8e0` | **`+0x780`** |
| `__TEXT.__objc_methname` | `0x9565` | `0x9785` | **`+0x220`** |
| `__TEXT.__objc_stubs` | `0x6d40` | `0x6ec0` | **`+0x180`** |
| `__DATA.__objc_const` | `0xc080` | `0xc150` | **`+0xd0`** |
| `__TEXT.__objc_methlist` | `0x3a30` | `0x3ad8` | **`+0xa8`** |
| `__DATA.__objc_selrefs` | `0x24c0` | `0x2540` | **`+0x80`** |
| `__DATA_CONST.__got` | `0xaf8` | `0xb10` | **`+0x18`** |
| `__TEXT.__cstring` | `0x157e` | `0x158e` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1c08` | `0x1c18` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x328` | `0x334` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2319.0.33.0.1
+2319.0.46.0.0

-  Functions: 2646
-  Symbols:   7846
-  CStrings:  2343
+  Functions: 2656
+  Symbols:   7875
+  CStrings:  2362
Symbols:
+ -[TouchIdAlertController .cxx_destruct]
+ -[TouchIdAlertController _headerContentViewControllerWithContentView:]
+ -[TouchIdAlertController _legacyHeaderContentView]
+ -[TouchIdAlertController _modernHeaderViewController]
+ -[TouchIdAlertController _rebuildHeaderContentViewController]
+ -[TouchIdAlertController callerBundleIdentifier]
+ -[TouchIdAlertController callerIconPath]
+ -[TouchIdAlertController sensorActive]
+ -[TouchIdAlertController setCallerBundleIdentifier:]
+ -[TouchIdAlertController setCallerIconPath:]
+ -[TouchIdAlertController setSensorActive:]
+ -[TouchIdViewController _authenticationSubtitle]
+ -[TouchIdViewController _authenticationTitle]
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/LocalAuthenticationUI/install/TempContent/Objects/CoreAuthentication.build/LocalAuthenticationUIService.build/Objects-normal/arm64e/PasscodeContentViewControllerFullScreen-263c36d2fc7cbb0918eeb0aa5a6625a4.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/LocalAuthenticationUI/install/TempContent/Objects/CoreAuthentication.build/LocalAuthenticationUIService.build/Objects-normal/arm64e/PinViewController-0f52c3f2d9cc8c0119198a3ce6d96a15.o
+ OBJC_IVAR_$_TouchIdAlertController._callerBundleIdentifier
+ OBJC_IVAR_$_TouchIdAlertController._callerIconPath
+ OBJC_IVAR_$_TouchIdAlertController._sensorActive
+ _OBJC_CLASS_$_LACUIIconConfiguration
+ _OBJC_CLASS_$_LACUIIconWithBadgeViewController
+ _OBJC_CLASS_$_LACUILocalization
+ __OBJC_$_INSTANCE_VARIABLES_TouchIdAlertController
+ __OBJC_$_PROP_LIST_TouchIdAlertController
+ ___47-[TouchIdViewController _handleBiometryNoMatch]_block_invoke_2
+ _objc_msgSend$_authenticationSubtitle
+ _objc_msgSend$_authenticationTitle
+ _objc_msgSend$_headerContentViewControllerWithContentView:
+ _objc_msgSend$_legacyHeaderContentView
+ _objc_msgSend$_modernHeaderViewController
+ _objc_msgSend$_rebuildHeaderContentViewController
+ _objc_msgSend$imageForPath:bundleIdentifier:
+ _objc_msgSend$initWithIconConfiguration:badgeConfiguration:
+ _objc_msgSend$initWithType:isActive:
+ _objc_msgSend$setCallerBundleIdentifier:
+ _objc_msgSend$setCallerIconPath:
+ _objc_msgSend$setSensorActive:
+ _objc_msgSend$touchIdToAllowThisWithCallerName:
- -[TouchIdAlertController _setupHeaderContentViewController]
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/LocalAuthenticationUI/install/TempContent/Objects/CoreAuthentication.build/LocalAuthenticationUIService.build/Objects-normal/arm64e/PasscodeContentViewControllerFullScreen-a7eb3f96f0ffa9fa5633f6ba7b090412.o
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/LocalAuthenticationUI/install/TempContent/Objects/CoreAuthentication.build/LocalAuthenticationUIService.build/Objects-normal/arm64e/PinViewController-dee098465da46377d5a767004913f717.o
- GCC_except_table11
- ___59-[TouchIdAlertController _setupHeaderContentViewController]_block_invoke
- ___59-[TouchIdAlertController _setupHeaderContentViewController]_block_invoke_2
- ___59-[TouchIdAlertController _setupHeaderContentViewController]_block_invoke_3
- _objc_msgSend$_setupHeaderContentViewController
CStrings:
+ "T@\"NSString\",&,N,V_callerBundleIdentifier"
+ "T@\"NSString\",&,N,V_callerIconPath"
+ "TB,N,V_sensorActive"
+ "_callerBundleIdentifier"
+ "_headerContentViewControllerWithContentView:"
+ "_legacyHeaderContentView"
+ "_modernHeaderViewController"
+ "_rebuildHeaderContentViewController"
+ "_sensorActive"
+ "callerBundleIdentifier"
+ "grammarCheckingType"
+ "imageForPath:bundleIdentifier:"
+ "initWithIconConfiguration:badgeConfiguration:"
+ "initWithType:isActive:"
+ "sensorActive"
+ "setCallerBundleIdentifier:"
+ "setCallerIconPath:"
+ "setGrammarCheckingType:"
+ "setSensorActive:"
+ "touchIdToAllowThisWithCallerName:"
- "_setupHeaderContentViewController"
```
