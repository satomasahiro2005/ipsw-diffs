## FamilyOutOfProcessUIExtension

> `/Applications/FamilyExtensionHost.app/Extensions/FamilyOutOfProcessUIExtension.appex/FamilyOutOfProcessUIExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fce4` | `0x2924c` | **`+0x9568`** |
| `__TEXT.__eh_frame` | `0x11e0` | `0x1c90` | **`+0xab0`** |
| `__TEXT.__auth_stubs` | `0x1730` | `0x1c30` | **`+0x500`** |
| `__TEXT.__unwind_info` | `0x8c0` | `0xb60` | **`+0x2a0`** |
| `__DATA_CONST.__auth_got` | `0xba0` | `0xe20` | **`+0x280`** |
| `__TEXT.__cstring` | `0xd82` | `0xf87` | **`+0x205`** |
| `__TEXT.__swift5_typeref` | `0xcfb` | `0xedb` | **`+0x1e0`** |
| `__TEXT.__const` | `0x11e0` | `0x13b0` | **`+0x1d0`** |
| `__DATA_CONST.__const` | `0xc58` | `0xe18` | **`+0x1c0`** |
| `__TEXT.__oslogstring` | `0x4c7` | `0x627` | **`+0x160`** |
| `__DATA.__data` | `0xcd0` | `0xe10` | **`+0x140`** |
| `__DATA.__bss` | `0x1090` | `0x11b8` | **`+0x128`** |
| `__DATA_CONST.__got` | `0x3b8` | `0x4d8` | **`+0x120`** |
| `__TEXT.__constg_swiftt` | `0x69c` | `0x760` | **`+0xc4`** |
| `__DATA.__objc_const` | `0x1838` | `0x1780` | **`-0xb8`** |
| `__TEXT.__swift_as_cont` | `0xf0` | `0x188` | **`+0x98`** |
| `__TEXT.__objc_stubs` | `0xe60` | `0xee0` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x42c` | `0x49c` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x564` | `0x5c8` | **`+0x64`** |
| `__TEXT.__objc_methname` | `0x1f0e` | `0x1f6e` | **`+0x60`** |
| `__DATA_CONST.__auth_ptr` | `0x4a0` | `0x4f8` | **`+0x58`** |
| `__TEXT.__objc_classname` | `0x2ff` | `0x2af` | **`-0x50`** |
| `__TEXT.__objc_methtype` | `0xab7` | `0xaf7` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x63b` | `0x67b` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x74` | `0xac` | **`+0x38`** |
| `__TEXT.__swift_as_entry` | `0x54` | `0x84` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x740` | `0x760` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x178` | `0x190` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x38` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x84` | `0x8c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x58` | `0x5c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-291.125.7.0.0
+291.125.10.0.0
+  - /System/Library/Frameworks/Accounts.framework/Accounts

-  - /System/Library/PrivateFrameworks/AAAFoundationSwift.framework/AAAFoundationSwift
+  - /System/Library/PrivateFrameworks/AAAFoundationUI.framework/AAAFoundationUI

-  Functions: 603
-  Symbols:   214
-  CStrings:  461
+  Functions: 719
+  Symbols:   231
+  CStrings:  490
Symbols:
+ _OBJC_CLASS_$_ACAccountStore
+ _OBJC_CLASS_$_NSError
+ _OBJC_CLASS_$_NSXPCConnection
+ ___stack_chk_fail
+ ___stack_chk_guard
+ __availability_version_check
+ _dispatch_once_f
+ _dlsym
+ _fclose
+ _fopen
+ _fread
+ _free
+ _fseek
+ _ftell
+ _malloc
+ _objc_retain_x27
+ _rewind
+ _sscanf
+ _swift_bridgeObjectRetain_n
+ _swift_dynamicCast
+ _swift_release_x23
+ _swift_task_future_wait_throwing
- _OBJC_CLASS_$__TtCs12_SwiftObject
- _OBJC_METACLASS_$__TtCs12_SwiftObject
- _objc_retain_x28
- _swift_deallocClassInstance
- _swift_retain_x27
CStrings:
+ "%d.%d.%d"
+ "/System/Library/CoreServices/SystemVersion.plist"
+ "CFDataCreateWithBytesNoCopy"
+ "CFDictionaryGetValue"
+ "CFGetTypeID"
+ "CFPropertyListCreateFromXMLData"
+ "CFPropertyListCreateWithData"
+ "CFRelease"
+ "CFStringCreateWithCStringNoCopy"
+ "CFStringGetCString"
+ "CFStringGetTypeID"
+ "EntryView task ran with nil requestModel, waiting for scene context"
+ "Failed to terminate extension: %s"
+ "Non-UI: applyScreentimeSettings rejected, missing %s"
+ "Non-UI: getUserAge rejected, missing %s"
+ "Non-UI: rejecting connection, missing %s"
+ "Non-UI: shouldPromptAgeRange rejected, missing %s"
+ "ProductVersion"
+ "View.task @ FamilyOutOfProcessUIExtension/FamilyOutOfProcessUIExtension.swift:"
+ "aa_altDSID"
+ "aa_primaryAppleAccountWithCompletion:"
+ "boolValue"
+ "cachedAgeRangeResponseWith:userAgeOverride:bundleID:attestedAtOverrideInDays:completion:"
+ "code"
+ "com.apple.developer.declared-age-range"
+ "com.apple.family.ageRange"
+ "com.apple.private.ageRange"
+ "com.apple.private.familycircle"
+ "defaultStore"
+ "initWithInteger:"
+ "kCFAllocatorNull"
+ "r"
+ "removingNonSecureCodingValues"
+ "v24@?0@\"ACAccount\"8@\"NSError\"16"
+ "v24@?0@\"FAAgeRangeResponse\"8@\"NSError\"16"
+ "valueForEntitlement:"
- "_TtC29FamilyOutOfProcessUIExtension29FamilyOutOfProcessUIExtension"
- "ageGates"
- "ageRangeController"
- "attestedAtOverrideInDays"
- "entryPoint"
- "requestType"
- "userAgeOverride"
```
