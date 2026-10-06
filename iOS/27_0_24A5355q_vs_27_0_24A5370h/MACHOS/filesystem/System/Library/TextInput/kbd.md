## kbd

> `/System/Library/TextInput/kbd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd094` | `0xeaf8` | **`+0x1a64`** |
| `__TEXT.__cstring` | `0x14c1` | `0x19e5` | **`+0x524`** |
| `__TEXT.__objc_methname` | `0x318a` | `0x340f` | **`+0x285`** |
| `__TEXT.__objc_stubs` | `0x2600` | `0x2860` | **`+0x260`** |
| `__TEXT.__dlopen_cstrs` | `0x112` | `0x22c` | **`+0x11a`** |
| `__TEXT.__oslogstring` | `0xb05` | `0xbff` | **`+0xfa`** |
| `__DATA.__objc_selrefs` | `0xd80` | `0xe28` | **`+0xa8`** |
| `__DATA_CONST.__cfstring` | `0xa40` | `0xae0` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x648` | `0x6e0` | **`+0x98`** |
| `__TEXT.__objc_methlist` | `0x12a4` | `0x1314` | **`+0x70`** |
| `__TEXT.__objc_methtype` | `0x127e` | `0x12e9` | **`+0x6b`** |
| `__DATA.__bss` | `0x150` | `0x1b8` | **`+0x68`** |
| `__DATA.__data` | `0xb40` | `0xba0` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x760` | `0x7c0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x3c0` | `0x418` | **`+0x58`** |
| `__DATA.__objc_const` | `0x44f8` | `0x4530` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x3b8` | `0x3e8` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x51f` | `0x53c` | **`+0x1d`** |
| `__DATA_CONST.__auth_ptr` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x388` | `0x390` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0xf0` | `0xf8` | **`+0x8`** |
| `__TEXT.__const` | `0xca` | `0xd2` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-3557.12.1.0.0
+3557.15.100.0.0

-  Functions: 359
-  Symbols:   244
-  CStrings:  910
+  Functions: 396
+  Symbols:   252
+  CStrings:  973
Symbols:
+ _NSLocalizedDescriptionKey
+ ___chkstk_darwin
+ __os_feature_enabled_impl
+ _bzero
+ _objc_autorelease
+ _objc_copyWeak
+ _objc_initWeak
+ _proc_pidpath
CStrings:
+ "%s  Dictation Enablement Prompt already being presented, rejecting re-entrant enablement request"
+ "%s  Dictation Enablement Remote Alert Handle dismissed with Error: %@"
+ "%s  Linguistic asset download requested for language '%@' by process '%@' (pid %d)"
+ "-[TIRemoteDataHandle dismissRemoteAlertHandleWithResponse:error:]"
+ "-[TIRemoteDataHandle presentCFUserNotificationDialogForType:completionHandler:]_block_invoke"
+ "-[TIRemoteDataHandle presentSBSRemoteAlertDialogForType:completionHandler:]_block_invoke"
+ "-[TIRemoteDataHandle requestLinguisticAssetsForLanguage:completion:]"
+ "BSAction"
+ "BSActionResponder"
+ "BSActionResponder returned a invalid response."
+ "Class getBSActionClass(void)_block_invoke"
+ "Class getBSActionResponderClass(void)_block_invoke"
+ "Class getRBSProcessIdentityClass(void)_block_invoke"
+ "Class getSBSRemoteAlertActivationContextClass(void)_block_invoke"
+ "Class getSBSRemoteAlertConfigurationContextClass(void)_block_invoke"
+ "Class getSBSRemoteAlertDefinitionClass(void)_block_invoke"
+ "Class getSBSRemoteAlertHandleClass(void)_block_invoke"
+ "Dictation-Enablement-Remote-Scene-Configuration"
+ "NSString *getSBSRemoteAlertHandleInvalidationErrorDomain(void)"
+ "RBSProcessIdentity"
+ "SBSRemoteAlertActivationContext"
+ "SBSRemoteAlertConfigurationContext"
+ "SBSRemoteAlertDefinition"
+ "SBSRemoteAlertHandle"
+ "SBSRemoteAlertHandleInvalidationErrorDomain"
+ "SBSRemoteAlertHandleObserver"
+ "TextInputCore"
+ "activateWithContext:"
+ "com.apple.DictationExperience"
+ "dictation_enablement_response"
+ "dismissRemoteAlertHandleWithResponse:error:"
+ "identityForEmbeddedApplicationIdentifier:"
+ "info"
+ "initWithInfo:responder:"
+ "initWithSceneProvidingProcess:configurationIdentifier:"
+ "integerValue"
+ "newHandleWithDefinition:configurationContext:"
+ "objectForSetting:"
+ "presentCFUserNotificationDialogForType:completionHandler:"
+ "presentSBSRemoteAlertDialogForType:completionHandler:"
+ "q32@0:8@16^@24"
+ "registerObserver:"
+ "remoteAlertHandle:didInvalidateWithError:"
+ "remoteAlertHandleDidActivate:"
+ "remoteAlertHandleDidDeactivate:"
+ "responderWithHandler:"
+ "responseTypeFromActionResponse:error:"
+ "sb_remote_dictation_enablement"
+ "setActions:"
+ "setPreferredSceneDeactivationReason:"
+ "setWithArray:"
+ "softlink:r:path:/System/Library/PrivateFrameworks/BaseBoard.framework/BaseBoard"
+ "softlink:r:path:/System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices"
+ "softlink:r:path:/System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices"
+ "unknown"
+ "unregisterObserver:"
+ "v16@?0@\"BSActionResponse\"8"
+ "v24@0:8@\"SBSRemoteAlertHandle\"16"
+ "v32@0:8@\"SBSRemoteAlertHandle\"16@\"NSError\"24"
+ "v32@0:8q16@24"
+ "void *BaseBoardLibrary(void)"
+ "void *RunningBoardServicesLibrary(void)"
+ "void *SpringBoardServicesLibrary(void)"
```
