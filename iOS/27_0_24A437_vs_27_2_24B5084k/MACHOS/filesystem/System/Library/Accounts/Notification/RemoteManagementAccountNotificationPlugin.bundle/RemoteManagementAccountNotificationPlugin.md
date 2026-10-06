## RemoteManagementAccountNotificationPlugin

> `/System/Library/Accounts/Notification/RemoteManagementAccountNotificationPlugin.bundle/RemoteManagementAccountNotificationPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e40` | `0x23b8` | **`+0x578`** |
| `__DATA.__objc_const` | `0x788` | `0xb58` | **`+0x3d0`** |
| `__TEXT.__objc_methname` | `0x75f` | `0xa25` | **`+0x2c6`** |
| `__TEXT.__objc_stubs` | `0x560` | `0x6c0` | **`+0x160`** |
| `__DATA.__data` | `0xc0` | `0x1e0` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x374` | `0x474` | **`+0x100`** |
| `__DATA.__objc_data` | `0x2d0` | `0x3c0` | **`+0xf0`** |
| `__TEXT.__objc_methtype` | `0x217` | `0x2d8` | **`+0xc1`** |
| `__TEXT.__objc_classname` | `0x218` | `0x2d5` | **`+0xbd`** |
| `__DATA.__objc_selrefs` | `0x278` | `0x2f8` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0x160` | `0x1c0` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x1a0` | `0x200` | **`+0x60`** |
| `__TEXT.__cstring` | `0x2bd` | `0x309` | **`+0x4c`** |
| `__DATA_CONST.__auth_got` | `0xd8` | `0x108` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x12d` | `0x158` | **`+0x2b`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x60` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x10` | `0x28` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x100` | `0x118` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x138` | `0x148` | **`+0x10`** |
| `__DATA.__objc_ivar` | `—` | `0xc` | **`+0xc`** |
| `__DATA_CONST.__objc_superrefs` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__const` | `0x70` | `0x78` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__const`

### Other Changes

```diff

-624.2.3.0.0
+624.40.12.0.0

+  - /System/Library/PrivateFrameworks/DMCUtilities.framework/DMCUtilities

-  Functions: 65
-  Symbols:   100
-  CStrings:  144
+  Functions: 80
+  Symbols:   114
+  CStrings:  183
Symbols:
+ _OBJC_CLASS_$_DMCDeviceEligibility
+ _OBJC_CLASS_$_RMAccountStatusHandlerSignificanceEvaluator
+ _OBJC_CLASS_$_RMDarwinNotificationPoster
+ _OBJC_CLASS_$_RMUserAccountTypeChecker
+ _OBJC_METACLASS_$_RMAccountStatusHandlerSignificanceEvaluator
+ _OBJC_METACLASS_$_RMDarwinNotificationPoster
+ _OBJC_METACLASS_$_RMUserAccountTypeChecker
+ _RMModelStatusAccountListExchange_ProtocolType_EAS
+ _objc_msgSendSuper2
+ _objc_retain_x22
+ _objc_retain_x23
+ _objc_retain_x5
+ _objc_retain_x8
+ _objc_storeStrong
CStrings:
+ ".cxx_destruct"
+ "@\"<RMAccountChangeSignificanceEvaluating>\""
+ "@\"<RMAccountNotificationPosting>\""
+ "@\"<RMUserAccountTypeChecking>\""
+ "@40@0:8@16@24@32"
+ "B24@0:8@\"NSString\"16"
+ "B32@0:8@\"ACAccount\"16@\"ACAccount\"24"
+ "RMAccountChangeSignificanceEvaluating"
+ "RMAccountNotificationPosting"
+ "RMAccountStatusHandlerSignificanceEvaluator"
+ "RMDarwinNotificationPoster"
+ "RMUserAccountTypeChecker"
+ "RMUserAccountTypeChecking"
+ "T@\"<RMAccountChangeSignificanceEvaluating>\",&,N,V_significanceEvaluator"
+ "T@\"<RMAccountNotificationPosting>\",&,N,V_notifier"
+ "T@\"<RMUserAccountTypeChecking>\",&,N,V_userAccountTypeChecker"
+ "User account %{public}@ of type %{public}@"
+ "_notifier"
+ "_sendUserAccountChangeNotificationIfNeededForAccount:oldAccount:changeType:"
+ "_significanceEvaluator"
+ "_userAccountTypeChecker"
+ "accountType"
+ "added"
+ "changeIsSignificantForAccount:oldAccount:"
+ "com.apple.remotemanagement.status.user-account.notification"
+ "containsObject:"
+ "init"
+ "initWithNotifier:userAccountTypeChecker:significanceEvaluator:"
+ "isUserAccountType:"
+ "notifier"
+ "postAccountStatusDidChangeNotification"
+ "postUserAccountDidChangeNotification"
+ "removed"
+ "setNotifier:"
+ "setSignificanceEvaluator:"
+ "setStatusProtocolType:"
+ "setUserAccountTypeChecker:"
+ "significanceEvaluator"
+ "userAccountTypeChecker"
+ "userAccountTypeIdentifiersForNoninteractiveEnhancedLogCollection"
+ "v24@0:8@16"
- "_changeIsSignificantForAccount:oldAccount:"
- "_postNotification"
```
