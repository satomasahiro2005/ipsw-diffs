## installd

> `/usr/libexec/installd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x70f48` | `0x70dfc` | **`-0x14c`** |
| `__TEXT.__cstring` | `0x18723` | `0x18813` | **`+0xf0`** |
| `__TEXT.__objc_methname` | `0xd567` | `0xd5c7` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x3c00` | `0x3bb0` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x1638` | `0x1610` | **`-0x28`** |
| `__DATA_CONST.__cfstring` | `0xa620` | `0xa600` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x8fe0` | `0x9000` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x390c` | `0x391c` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x28d8` | `0x28e0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x14f8` | `0x14f0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1673.0.0.0.0
+1674.2.1.0.0
Symbols:
+ _MIMachOFileImageSlices
+ _MIMachOHasRunnableSliceSupportingPAC
- _MGGetBoolAnswer
- _MIMachOFileIterateImageVersions
Functions:
~ sub_100050aa8 : 2720 -> 472
~ sub_100051548 -> sub_100050c80 : 16 -> 2084
~ sub_100051558 -> sub_1000514a4 : 8 -> 16
~ sub_100051560 -> sub_1000514b4 : 456 -> 8
~ sub_100051728 -> sub_1000514bc : 52 -> 340
CStrings:
+ "\"%@\" is not built for an architecture that both supports pointer authentication and that is runnable on this device. A runnable architecture supporting pointer authentication (eg. arm64e, or newer) is required for all components of a browser app."
+ "%@ has both the \"%@\" entitlement and the \"%@\" entitlement. Only one of these entitlements can be present at a time. Remove one of these entitlements to allow this app to be installed."
+ "%@ has the \"%@\" entitlement, so it cannot also have the \"%@\" entitlement. Apps that have embedded browser engines may not be default web browsers. Remove one of these entitlements to allow this app to be installed."
+ "+[MIInstallableBundle _requireHasExecutableSliceForArchSupportingPACForBundles:error:]"
+ "Skipping PAC architecture requirement for %@ and all of its contained executables because it is signed for development or testing."
+ "_requireHasExecutableSliceForArchSupportingPACForBundles:error:"
+ "getHasExecutableSliceForArchSupportingPAC:withError:"
- "\"%@\" is not built for the ARM64e architecture. The ARM64e architecture is required for all components of a browser app."
- "%@ has both the \"%@\" entitlement and the \"%@\" entitlement. Only one of these entitlements may be present at a time. Remove one of these entitlements to allow this app to be installed."
- "%@ has the \"%@\" entitlement so it may not also have the \"%@\" entitlement. Remove one of these entitlements to allow this app to be installed."
- "B28@?0i8i12I16I20I24"
- "Skipping ARM64e architecture requirement for %@ and all of its contained executables because it is signed for development or testing."
- "hasExecutableSliceForCPUType:subtype:error:"
- "li+w2foswFu0srn5UxdOug"
```
