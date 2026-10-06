## InstalledContentLibrary

> `/System/Library/PrivateFrameworks/InstalledContentLibrary.framework/InstalledContentLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xce76c` | `0xcee78` | **`+0x70c`** |
| `__AUTH_CONST.__objc_const` | `0xa740` | `0xa7d0` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x5b94` | `0x5be4` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0xd460` | `0xd4a0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x19c8` | `0x19f0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x30a8` | `0x30c0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x5c0` | `0x5cc` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0xc08` | `0xc10` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xde0` | `0xde8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1673.0.0.0.0
+1674.2.1.0.0

-  Functions: 2402
-  Symbols:   3825
-  CStrings:  2260
+  Functions: 2412
+  Symbols:   3840
+  CStrings:  2262
Symbols:
+ -[ICLPlaceholderRecord installBuildVersion]
+ -[ICLPlaceholderRecord originalInstallDate]
+ -[ICLPlaceholderRecord setInstallBuildVersion:]
+ -[ICLPlaceholderRecord setOriginalInstallDate:]
+ -[MIExecutableBundle getHasExecutableSliceForArchSupportingPAC:withError:]
+ -[MIMachOImageSlice initWithCPUType:cpuSubtype:platform:sdkVersion:minOSVersion:supportsPAC:]
+ -[MIMachOImageSlice setSupportsPAC:]
+ -[MIMachOImageSlice supportsPAC]
+ GCC_except_table22
+ GCC_except_table76
+ GCC_except_table95
+ _MIMachOHasRunnableSliceSupportingPAC
+ _OBJC_IVAR_$_ICLPlaceholderRecord._installBuildVersion
+ _OBJC_IVAR_$_ICLPlaceholderRecord._originalInstallDate
+ _OBJC_IVAR_$_MIMachOImageSlice._supportsPAC
+ __CopyRunnableArchNames
+ __CopyRunnablePlatforms
+ ___block_descriptor_40_e8_32s_e23_B32?0i8i12I16I20I24B28ls32l8
+ ___block_descriptor_57_e8_32bs40r_e14_v20?0I8I12I16lr40l8s32l8
+ _macho_supports_pointer_authentication
- -[MIMachOImageSlice initWithCPUType:cpuSubtype:platform:sdkVersion:minOSVersion:]
- GCC_except_table75
- GCC_except_table94
- ___block_descriptor_40_e8_32s_e20_B28?0i8i12I16I20I24ls32l8
- ___block_descriptor_56_e8_32bs40r_e14_v20?0I8I12I16lr40l8s32l8
CStrings:
+ "#)"
+ "B32@?0i8i12I16I20I24B28"
+ "InstallBuildVersion"
+ "OriginalInstallDate"
+ "The executable at \"%s\" does not contain code for any platform and CPU architecture combination that is runnable on this device. The executable has code for these platforms and architectures: %@. This device can run code for these platforms: %@"
- "#'"
- "B28@?0i8i12I16I20I24"
- "The executable at \"%s\" does not contain code for any platform and CPU architecture combination that is runnable on this device. The executable has code for these platforms and architectures: %@. This device can run code for these architectures: %@. This device can run code for these platforms: %@"
```
