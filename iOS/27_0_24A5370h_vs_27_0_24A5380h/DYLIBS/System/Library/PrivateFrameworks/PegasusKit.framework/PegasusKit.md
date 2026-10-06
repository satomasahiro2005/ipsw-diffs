## PegasusKit

> `/System/Library/PrivateFrameworks/PegasusKit.framework/PegasusKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe87b8` | `0xeb23c` | **`+0x2a84`** |
| `__DATA_DIRTY.__data` | `0x7298` | `0x74b8` | **`+0x220`** |
| `__DATA.__data` | `0xdb8` | `0xca0` | **`-0x118`** |
| `__AUTH.__data` | `0x250` | `0x178` | **`-0xd8`** |
| `__TEXT.__cstring` | `0x2ae1` | `0x2b91` | **`+0xb0`** |
| `__DATA.__bss` | `0x2520` | `0x24a0` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x1580` | `0x1600` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x2bdf` | `0x2c5f` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x61f4` | `0x626c` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x2b58` | `0x2bd0` | **`+0x78`** |
| `__TEXT.__swift5_typeref` | `0x2dce` | `0x2dac` | **`-0x22`** |
| `__AUTH.__objc_data` | `0x140` | `0x120` | **`-0x20`** |
| `__DATA_DIRTY.__objc_data` | `0x440` | `0x460` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1b20` | `0x1b08` | **`-0x18`** |
| `__DATA.__common` | `0x78` | `0x60` | **`-0x18`** |
| `__DATA_DIRTY.__common` | `0xe8` | `0x100` | **`+0x18`** |
| `__TEXT.__const` | `0x6100` | `0x6110` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x2c48` | `0x2c58` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x2303` | `0x2313` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1d14` | `0x1d20` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x178` | `0x180` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x480` | `0x488` | **`+0x8`** |

### Other Changes

```diff

-3600.56.7.0.0
+3600.56.16.0.0

+  - /usr/lib/swift/libswiftCompression.dylib

+  - /usr/lib/swift/libswiftRegexBuilder.dylib

-  Functions: 5344
+  Functions: 5377

-  CStrings:  524
+  CStrings:  530
Symbols:
+ _OUTLINED_FUNCTION_390
+ _OUTLINED_FUNCTION_391
+ _OUTLINED_FUNCTION_392
+ _OUTLINED_FUNCTION_393
+ _OUTLINED_FUNCTION_394
+ _OUTLINED_FUNCTION_395
+ _OUTLINED_FUNCTION_396
+ ___swift_closure_destructor.304Tm
+ ___swift_get_extra_inhabitant_index.375Tm
+ ___swift_project_boxed_opaque_existential_0Tm
+ ___swift_store_extra_inhabitant_index.376Tm
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCompression_$_PegasusKit
+ _symbolic SS3key_yp5valuet
- ___swift_closure_destructor.306Tm
- ___swift_get_extra_inhabitant_index.379Tm
- ___swift_memcpy24_8
- ___swift_store_extra_inhabitant_index.380Tm
- _get_type_metadata 15Synchronization5MutexVy10PegasusKit26PrivateAccessTokenFetching_pSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDySS10Foundation4DateVGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDySS10PegasusKit35FeedbackReportingURLSessionDelegateC0E14LoggingContext33_B9E1B3F43E9E83D7078019348D2180D0LLVGG noncopyable
- _get_type_metadata 15Synchronization5MutexVyScS12ContinuationVyyyYbc_GG noncopyable
- _get_type_metadata 15Synchronization5MutexVys6ResultOySo17NSHTTPURLResponseC_10Foundation4DataVSgts5Error_pGSgG noncopyable
- _get_type_metadata 15Synchronization6AtomicVySbG noncopyable
- _get_type_metadata RlzCl15Synchronization5MutexVyytG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
- _symbolic _____ySsG s23_ContiguousArrayStorageC
CStrings:
+ "Detected non-default configuration overrides — requests may target a non-production endpoint. Active overrides: %{public}s"
+ "PARAppWhitelistSignature"
+ "PARAppWhitelistSignatureLastModified"
+ "PARDefaultsVersion"
+ "WhitelistUpdateRequiredKey"
+ "download_resources"
```
