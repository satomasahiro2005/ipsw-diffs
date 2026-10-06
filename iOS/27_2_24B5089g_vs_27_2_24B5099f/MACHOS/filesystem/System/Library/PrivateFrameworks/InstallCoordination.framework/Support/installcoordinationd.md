## installcoordinationd

> `/System/Library/PrivateFrameworks/InstallCoordination.framework/Support/installcoordinationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa03dc` | `0xa0b30` | **`+0x754`** |
| `__TEXT.__oslogstring` | `0xd57c` | `0xd6cc` | **`+0x150`** |
| `__TEXT.__objc_methname` | `0x1007b` | `0x1015b` | **`+0xe0`** |
| `__TEXT.__objc_stubs` | `0xa660` | `0xa6e0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x16a7a` | `0x16ada` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x5a0` | `0x5c8` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x3110` | `0x3130` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x5a8` | `0x5b8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1ae0` | `0x1af0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x1c0` | `0x1d0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xd80` | `0xd88` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2648` | `0x2650` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-849.40.4.0.1
+849.40.7.0.2

-  Functions: 3245
-  Symbols:   638
-  CStrings:  5092
+  Functions: 3249
+  Symbols:   641
+  CStrings:  5102
Symbols:
+ _MobileInstallationEndAppReplacement
+ _MobileInstallationSetAppLaunchProhibited
+ _OBJC_CLASS_$_IXAppInstallCoordinator
+ _OBJC_CLASS_$_IXAppReplacementSourceResolver
- _MobileInstallationSetAppReplacementStatus
CStrings:
+ "%s: Failed to clear the app launch prohibition marker for %@: %@"
+ "%s: Failed to determine what MDM manages, so the app replacement source for %@ can't be resolved: %@"
+ "%s: Failed to resolve app replacement source for %@: %@"
+ "%s: Failed to subscribe to managed app events: %@"
+ "-[IXSCoordinatedAppInstall _finishAppInstallAtURL:result:recordPromise:error:]_block_invoke"
+ "06:08:27"
+ "Failed to push replacement info for %@ to LS: %s"
+ "Sep 26 2026"
+ "initWithIdentity:managedAppBundleIdentifiers:"
+ "managedAppBundleIdentifiersWithError:"
+ "prepareForAppReplacementSourceLookupWithOptions:error:"
+ "resolveAppReplacementSource:replacementRuledOut:replacementCandidate:error:"
- "05:57:49"
- "Sep 12 2026"
```
