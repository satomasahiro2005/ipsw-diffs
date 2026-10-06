## Setup

> `/Applications/Setup.app/Setup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27020c` | `0x27159c` | **`+0x1390`** |
| `__TEXT.__objc_methname` | `0x4150e` | `0x418ce` | **`+0x3c0`** |
| `__TEXT.__objc_stubs` | `0x29ba0` | `0x29da0` | **`+0x200`** |
| `__DATA.__objc_const` | `0x4c430` | `0x4c550` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x1e680` | `0x1e7a0` | **`+0x120`** |
| `__DATA.__objc_selrefs` | `0xcf58` | `0xd008` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0xa418` | `0xa498` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x4b5c` | `0x4bd8` | **`+0x7c`** |
| `__DATA.__data` | `0x8198` | `0x8208` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x15427` | `0x15494` | **`+0x6d`** |
| `__TEXT.__objc_methtype` | `0xcbf7` | `0xcc50` | **`+0x59`** |
| `__DATA_CONST.__const` | `0x9208` | `0x9230` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x2020` | `0x2048` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x6067` | `0x6088` | **`+0x21`** |
| `__TEXT.__auth_stubs` | `0x2a60` | `0x2a80` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x1df0` | `0x1e04` | **`+0x14`** |
| `__DATA_CONST.__auth_got` | `0x1548` | `0x1558` | **`+0x10`** |
| `__TEXT.__cstring` | `0x105a8` | `0x10598` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x8a8` | `0x8b0` | **`+0x8`** |
| `__TEXT.__const` | `0x3c58` | `0x3c50` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x2b60` | `0x2b62` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5403.100.0.0.0
+5405.0.0.0.0

-  Functions: 12810
-  Symbols:   1563
-  CStrings:  15111
+  Functions: 12833
+  Symbols:   1570
+  CStrings:  15146
Symbols:
+ _$s9SiriSetup0aB16EnrollmentStatusO2eeoiySbAC_ACtFZ
+ _$s9SiriSetup0aB16EnrollmentStatusO7successyA2CmFWC
+ _$s9SiriSetup0aB16EnrollmentStatusOMa
+ _$s9SiriSetup0aB16EnrollmentStatusOs23CustomStringConvertibleAAMc
+ _DMCSettingsChangedNotification
+ _OBJC_CLASS_$_UITextSuggestion
+ _kCCSkipKeyDeviceFeaturesTour
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:438: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:446: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:481: libc++ Hardening assertion size() < capacity() failed: We assume that we have enough space to insert an element at the end of the vector\n"
+ "@%@"
+ "AIDAServiceManagerSignInDelegate"
+ "AppStore sign-in finished (success=%d); proceeding with AVK check if pending"
+ "Jun 12 2026"
+ "Siri completion status: %s"
+ "T@\"NSArray\",C,N,V_managedAppleIDDefaultDomains"
+ "T@?,C,N,V_pendingAVKBlock"
+ "TB,N,V_storeSignInCompleted"
+ "Ti,N,V_domainsNotifyToken"
+ "_domainsNotifyToken"
+ "_managedAppleIDDefaultDomains"
+ "_pendingAVKBlock"
+ "_resetStoreSignInState"
+ "_startObservingManagedAppleIDDefaultDomainsChangesIfNeeded"
+ "_storeSignInCompleted"
+ "_suggestionsForInputText:defaultDomains:"
+ "_updateKeyboardSuggestionsForTextField:"
+ "_updateManagedAppleIDDefaultDomains"
+ "_waitForStoreSignInThenPresentAgeAssuranceIfNeededWithCompletion:"
+ "capsule.on.rectangle.liquid.glass"
+ "domainsNotifyToken"
+ "eraseDeviceWithCompletionHandler:"
+ "isORGOEnrolled"
+ "managedAppleIDDefaultDomains"
+ "pendingAVKBlock"
+ "presentUnenrollmentActivityPageIsAppleMAID:isProvisional:"
+ "requestUserConfirmationIsAppleMAID:isProvisionallyEnrolled:completionHandler:"
+ "serviceOwnersManager:didFinishSignInForService:success:error:"
+ "setDomainsNotifyToken:"
+ "setManagedAppleIDDefaultDomains:"
+ "setPendingAVKBlock:"
+ "setSignInDelegate:"
+ "setStoreSignInCompleted:"
+ "setSuggestions:"
+ "storeSignInCompleted"
+ "textInputSuggestionDelegate"
+ "textSuggestionWithInputText:"
+ "v32@0:8B16B20@?<v@?B>24"
+ "v44@0:8@\"AIDAServiceOwnersManager\"16@\"NSString\"24B32@\"NSError\"36"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:418: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:437: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:445: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:480: libc++ Hardening assertion size() < capacity() failed: We assume that we have enough space to insert an element at the end of the vector\n"
- "EXPRESS_FEATURE_STATE_GLASS_FULL_OPAQUE"
- "Jun  3 2026"
- "drop.halffull"
- "requestUserConfirmationIsAppleMAID:completionHandler:"
```
