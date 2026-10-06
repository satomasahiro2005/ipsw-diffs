## Setup

> `/Applications/Setup.app/Setup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__objc_const` | `0x49d40` | `0x496b0` | **`-0x690`** |
| `__TEXT.__text` | `0x24cfc4` | `0x24cb94` | **`-0x430`** |
| `__TEXT.__oslogstring` | `0x14ec2` | `0x1508c` | **`+0x1ca`** |
| `__TEXT.__objc_methlist` | `0x1dd28` | `0x1dc20` | **`-0x108`** |
| `__DATA_CONST.__cfstring` | `0xb540` | `0xb440` | **`-0x100`** |
| `__DATA.__objc_data` | `0xcb68` | `0xcac8` | **`-0xa0`** |
| `__TEXT.__objc_stubs` | `0x29440` | `0x293c0` | **`-0x80`** |
| `__TEXT.__gcc_except_tab` | `0x4ecc` | `0x4e64` | **`-0x68`** |
| `__TEXT.__unwind_info` | `0x9e58` | `0x9e08` | **`-0x50`** |
| `__TEXT.__objc_methtype` | `0xcb1a` | `0xcae2` | **`-0x38`** |
| `__TEXT.__objc_classname` | `0x5c43` | `0x5c0c` | **`-0x37`** |
| `__DATA.__objc_selrefs` | `0xcd20` | `0xcd00` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x8758` | `0x8778` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1c58` | `0x1c38` | **`-0x20`** |
| `__TEXT.__cstring` | `0xfd2e` | `0xfd10` | **`-0x1e`** |
| `__DATA.__data` | `0x7a10` | `0x7a28` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1d58` | `0x1d40` | **`-0x18`** |
| `__TEXT.__const` | `0x3640` | `0x3658` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x11cc` | `0x11e0` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0xe20` | `0xe10` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x40a5e` | `0x40a4e` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x810` | `0x808` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x2792` | `0x2796` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5411.101.0.0.0
+5411.103.0.0.0

-  - /usr/lib/swift/libswiftSpriteKit.dylib

-  Functions: 12357
-  Symbols:   1537
-  CStrings:  14883
+  Functions: 12340
+  Symbols:   1530
+  CStrings:  14880
Symbols:
+ _OBJC_CLASS_$_AMSUISelfieFaceIDSession
- _BYPrivacyPrivacyPaneIdentifier
- _BYPrivacySubscriptionBundleIdentifier
- _OBJC_CLASS_$_AMSAcknowledgePrivacyTask
- _OBJC_CLASS_$_OBCapabilities
- _OBJC_CLASS_$_OBPrivacySplashController
- _OBJC_METACLASS_$_OBPrivacySplashController
- __swift_FORCE_LOAD_$_swiftSpriteKit
- _kMCCCSkipSetupPrivacy
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:438: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:446: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:481: libc++ Hardening assertion size() < capacity() failed: We assume that we have enough space to insert an element at the end of the vector\n"
+ "BuddyMigrationSourceFinishedStringHandler"
+ "Enabling D&U submission for seed build..."
+ "ForceShouldBeginRestore"
+ "ForceSilentRenewFailure"
+ "Forcing shouldBeginRestore due to internal override"
+ "Forcing silent renew to fail due to internal override"
+ "Forcing the software update restore flow to run due to internal override; no backup item will be set!"
+ "Is the multitasking feature applicable: %{bool}d"
+ "Moving on automatically..."
+ "PASSWORD_FIELD"
+ "PearlSplashController: Age verification eligibility check failed: %{public}@"
+ "PearlSplashController: Age verification eligibility: %i"
+ "Sep  4 2026"
+ "Should the multitasking feature flow be shown: %{bool}d"
+ "_cleanupPresentingState"
+ "_fetchAdultAgeVerificationEligibilityWithCompletion:"
+ "_shouldInsertWiFiControllerAsFirstPaneBeforePushingFlowItem:"
+ "_shouldShowContinueButton"
+ "isEligible"
+ "requestRemovalOfExistingApplicationForReason:iTunesStoreID:allowSkip:completionHandler:"
+ "resultWithTimeout:completion:"
+ "setBoolValue:forSetting:"
+ "setShowsAdultAgeVerificationDetail:"
+ "showsAdultAgeVerificationDetail"
+ "v24@?0@\"AMSBoolean\"8@\"NSError\"16"
+ "v44@0:8q16@\"NSNumber\"24B32@?<v@?BB@\"NSError\">36"
+ "v44@0:8q16@24B32@?36"
- "%s isFeatureApplicable: %{bool}d"
- "%s shouldShowFlow: %{bool}d"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:438: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:446: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:481: libc++ Hardening assertion size() < capacity() failed: We assume that we have enough space to insert an element at the end of the vector\n"
- "@\"OBPrivacySplashController\""
- "Aug 13 2026"
- "BuddyPrivacyController"
- "BuddyPrivacySplashController"
- "CTBuddyMigrationSourceFinishedStringProvider"
- "Fade up"
- "Fade up Dark"
- "LEARN_MORE_ELLIPSIS"
- "PrivacyPane"
- "Shake down"
- "Shake down Dark"
- "Shake up"
- "Shake up Dark"
- "THIS_FIELD_REQUIRED"
- "_writeOutCurrentPrivacyVersion"
- "acknowledgementNeededForPrivacyIdentifier:account:"
- "ams_isBundleOwner"
- "combinedController"
- "initWithPrivacyIdentifier:"
- "isDataAndPrivacyBundleEnabled"
- "learnMorePressed:"
- "presenterForPrivacyUnifiedAbout"
- "setDismissHandlerForDefaultButton:"
- "setPresentedFromPrivacyPane:"
- "setPreventOpeningSafari:"
- "setPreventURLDataDetection:"
- "sharedCapabilities"
- "viewDidAppear"
```
