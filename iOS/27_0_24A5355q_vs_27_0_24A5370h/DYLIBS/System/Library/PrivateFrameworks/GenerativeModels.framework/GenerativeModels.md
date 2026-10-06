## GenerativeModels

> `/System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc731c` | `0xcc3d0` | **`+0x50b4`** |
| `__TEXT.__oslogstring` | `0x2823` | `0x2e63` | **`+0x640`** |
| `__DATA.__bss` | `0xc080` | `0xc500` | **`+0x480`** |
| `__TEXT.__const` | `0xaf94` | `0xb354` | **`+0x3c0`** |
| `__AUTH_CONST.__const` | `0x7bb0` | `0x7eb0` | **`+0x300`** |
| `__TEXT.__cstring` | `0x25f3` | `0x27b3` | **`+0x1c0`** |
| `__TEXT.__eh_frame` | `0x4d9c` | `0x4f1c` | **`+0x180`** |
| `__TEXT.__swift5_reflstr` | `0x21c8` | `0x2348` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x3008` | `0x3160` | **`+0x158`** |
| `__TEXT.__swift5_fieldmd` | `0x2844` | `0x2984` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0x2de8` | `0x2ed2` | **`+0xea`** |
| `__TEXT.__constg_swiftt` | `0x2070` | `0x211c` | **`+0xac`** |
| `__DATA.__data` | `0x19f8` | `0x1a98` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0xd98` | `0xdf8` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x1688` | `0x16c0` | **`+0x38`** |
| `__TEXT.__swift5_proto` | `0x918` | `0x93c` | **`+0x24`** |
| `__AUTH_CONST.__objc_const` | `0xb68` | `0xb88` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x460` | `0x478` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x34c` | `0x360` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x410` | `0x420` | **`+0x10`** |
| `__AUTH.__objc_data` | `0x558` | `0x560` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xa50` | `0xa58` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x15e8` | `0x15f0` | **`+0x8`** |

### Other Changes

```diff

-279.0.15.0.0
+284.0.7.0.0

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 5666
-  Symbols:   242
-  CStrings:  450
+  Functions: 5807
+  Symbols:   248
+  CStrings:  474
Symbols:
+ _CFPreferencesCopyValue
+ _MGGetBoolAnswer
+ _MobileGestalt_copy_regionCode_obj
+ _MobileGestalt_get_current_device
+ _getpwuid
+ _kCFPreferencesCurrentHost
CStrings:
+ "AvailabilityClient._isUseCaseAccessNotGrantedSecureForAnyUser(_:_:)"
+ "DeviceSupportsInstructionFollowingPruningModels"
+ "Enhanced Siri restricted (only app install pending)"
+ "Enhanced Siri unavailable — not eligible to install"
+ "Setting GMOptIn.isOptedIn to %{bool}d from %s %s."
+ "com.apple.gms.enhancedSiri.unifiedReasons"
+ "indexingInProgress"
+ "isSensitiveRegionForEnhancedSiri returning: %{bool,public}d for region: %{private}s"
+ "isUseCaseAccessNotGrantedSecure: failing closed; %{public}s is strict-asset-availability and not yet initialized by CSF"
+ "isUseCaseAccessNotGrantedSecure: returning %{bool,public}d; forcedWaitlistStatus=%{public}s"
+ "isUseCaseAccessNotGrantedSecure: returning granted (false); no pendingEnrollment for any of %{public}s"
+ "isUseCaseAccessNotGrantedSecure: returning granted (false); secure unifiedReasons is nil"
+ "isUseCaseAccessNotGrantedSecure: returning notGranted (true); pendingEnrollment present for %{public}s"
+ "isUseCaseAccessNotGrantedSecure: user=%{public}u -> %{bool,public}d"
+ "isUseCaseAccessNotGrantedSecure: user=%{public}u, input=%{public}s, initializedUseCases=%{public}s"
+ "isUseCaseAccessNotGrantedSecureForAnyUser: input=%{public}s"
+ "isUseCaseAccessNotGrantedSecureForAnyUser: iterating %{public}ld user(s)=%{public}s"
+ "isUseCaseAccessNotGrantedSecureForAnyUser: no users visible; failing closed (returning true)"
+ "isUseCaseAccessNotGrantedSecureForAnyUser: per-user override for user %{public}u -> notGranted=%{bool,public}d"
+ "isUseCaseAccessNotGrantedSecureForAnyUser: returning false; user %{public}u is past the waitlist"
+ "isUseCaseAccessNotGrantedSecureForAnyUser: returning false; vmHostAvailability=true for user %{public}u (treated as access granted)"
+ "isUseCaseAccessNotGrantedSecureForAnyUser: returning true; every user (%{public}ld) has access not granted"
+ "isUseCaseAccessNotGrantedSecureForAnyUser: user=%{public}u -> %{bool,public}d"
+ "restricted with other blocking reasons (toolbox, asset)"
+ "useCaseDoesNotSupportCurrentDevice"
- "Setting GMOptIn.isOptedIn to %{bool}d from %s %s. Note: isOptedIn getter always returns true (auto opt-in)."
```
