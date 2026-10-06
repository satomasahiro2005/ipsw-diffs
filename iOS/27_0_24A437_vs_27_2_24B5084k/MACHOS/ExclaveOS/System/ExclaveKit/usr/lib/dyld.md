## dyld

> `/System/ExclaveKit/usr/lib/dyld`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c60c` | `0x5c894` | **`+0x288`** |
| `__TEXT.__cstring` | `0xe699` | `0xe6f7` | **`+0x5e`** |
| `__AUTH_CONST.__const` | `0x3ee8` | `0x3f20` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x1ea8` | `0x1ec0` | **`+0x18`** |
| `__TEXT.__const` | `0x1c0a8` | `0x1c0ac` | **`+0x4`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_DIRTY.__all_image_info`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-27062.0.0.0.0
-  Functions: 2756
-  Symbols:   2430
-  CStrings:  1470
+27102.0.0.0.0
+  Functions: 2762
+  Symbols:   2438
+  CStrings:  1475
Symbols:
+ __ZN5dyld44APIs28_dyld_with_active_atlas_PRIVEPvPFvS1_PKvmE
+ __ZN6mach_o12ArchitectureC1EPK11mach_header
+ __ZN6mach_o6PolicyC1ERKNS_6HeaderEbbb
+ __ZN6mach_o6PolicyC2ENS_12ArchitectureENS_19PlatformAndVersionsEjbbb
+ __ZN6mach_o8Platform5Epoch8fall2026E
+ __ZNK6mach_o5Image19maxAuthRebaseOffsetEv
+ __ZNK6mach_o6Header4archEv
+ __ZNK6mach_o6Header8fileTypeEv
+ __ZNK6mach_o6Policy34enforceAuthRebasesPointWithinImageEv
+ __ZNK6mach_o8Platform5epochENS_9Version32E
+ ____ZNK6mach_o5Image19maxAuthRebaseOffsetEv_block_invoke
+ ___memmove_chk
- _OUTLINED_FUNCTION_15
- ___liblibc_stream_error
- _append_char
- _xrt__platform_init_stack
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/ExclaveKit.iPhoneOS.platform/Developer/SDKs/ExclaveKit.iPhoneOS27.2.Internal.sdk/System/ExclaveKit/usr/include/xrt/thread.h"
+ "27102"
+ "__memmove_chk"
+ "_insecure_random_buf"
+ "rebase out of range"
+ "s[0] || s[1]"
+ "src/libc/string/memmove.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/ExclaveKit.iPhoneOS.platform/Developer/SDKs/ExclaveKit.iPhoneOS27.0.Internal.sdk/System/ExclaveKit/usr/include/xrt/thread.h"
- "27062"
```
