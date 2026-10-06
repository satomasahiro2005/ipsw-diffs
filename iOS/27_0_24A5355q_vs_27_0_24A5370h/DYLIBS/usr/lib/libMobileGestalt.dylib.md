## libMobileGestalt.dylib

> `/usr/lib/libMobileGestalt.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__const` | `0x27cd0` | `0x2f440` | **`+0x7770`** |
| `__TEXT.__text` | `0x67c4c` | `0x6b588` | **`+0x393c`** |
| `__TEXT.__const` | `0x8a98` | `0xa088` | **`+0x15f0`** |
| `__TEXT.__constg_swiftt` | `0x444` | `0x544` | **`+0x100`** |
| `__DATA.__bss` | `0xd10` | `0xe00` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x2230` | `0x22f8` | **`+0xc8`** |
| `__TEXT.__oslogstring` | `0x4019` | `0x3f54` | **`-0xc5`** |
| `__TEXT.__eh_frame` | `0x2cc` | `0x37c` | **`+0xb0`** |
| `__TEXT.__swift5_fieldmd` | `0x338` | `0x3c4` | **`+0x8c`** |
| `__AUTH_CONST.__cfstring` | `0x13160` | `0x130e0` | **`-0x80`** |
| `__DATA_CONST.__const` | `0x1680` | `0x1620` | **`-0x60`** |
| `__TEXT.__swift5_typeref` | `0x31d` | `0x37d` | **`+0x60`** |
| `__TEXT.__dlopen_cstrs` | `0x102` | `0xa6` | **`-0x5c`** |
| `__AUTH.__data` | `0x128` | `0x180` | **`+0x58`** |
| `__TEXT.__cstring` | `0x176ff` | `0x176bd` | **`-0x42`** |
| `__DATA.__data` | `0x2f0` | `0x320` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x212` | `0x23d` | **`+0x2b`** |
| `__DATA_CONST.__got` | `0x1a0` | `0x1c8` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x6c` | `0x8c` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xa50` | `0xa38` | **`-0x18`** |
| `__TEXT.__swift5_assocty` | `0x150` | `0x168` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0xa8` | `0xbc` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x198` | `0x190` | **`-0x8`** |
| `__DATA_DIRTY.__bss` | `0x1e18` | `0x1e20` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x130` | `0x128` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_types2` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x14` | `0x18` | **`+0x4`** |

### Other Changes

```diff

-1608.0.0.0.0
+1618.0.0.0.0

-  Functions: 3527
-  Symbols:   1517
-  CStrings:  3852
+  Functions: 3603
+  Symbols:   1507
+  CStrings:  3848
Symbols:
+ _MobileGestalt_copy_image4SecureBootKeyScheme
+ _MobileGestalt_copy_image4SecureBootKeyScheme_obj
+ _MobileGestalt_get_postQuantumCryptographyEnforced
+ ___memmove_chk
+ _swift_cvw_enumFn_getEnumTag
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_release_x8
- _CFAllocatorAllocateTyped
- _CFAllocatorCreate
- _CFStringAppend
- _CFStringCreateWithCStringNoCopy
- _CFURLCopyFileSystemPath
- _CFURLCreateWithFileSystemPath
- _CFURLGetFileSystemRepresentation
- ___strlcpy_chk
- __os_assumes_log
- _abort_report_np
- _asl_log
- _dlerror
- _fileno
- _fread
- _mmap
- _munmap
- _objc_release_x25
CStrings:
+ "%s: Invalid data digest input"
+ "%s: Invalid data digest length: %ld"
+ "%s: fdrDecode->dataImg4.payload_hashed is false"
+ "%s: kAMFDRDecodeOptionManifestOnly, kAMFDRDecodeOptionSubCCOnly, kAMFDRDecodeOptionDataDigestOnly needs to be exclusive to each other"
+ "%s: trust evaluation on customized payload format requires a reStitchManifest"
+ "138AE3E6-173D-41C6-AA19-29B1F0769A69"
+ "AppleBatteryAuth"
+ "HBG+hj/Oz89PjVgn93Jd8A"
+ "Image4SecureBootKeyScheme"
+ "J2+oJRiGdbAzTi6U5nhqdQ"
+ "No pqc-validation-flags available, PQC not supported"
+ "PostQuantumCryptographyEnforced"
+ "_Img4DecodeInitDummyPayloadForDataDigest"
+ "compute-controller"
+ "compute-node"
+ "compute-packet-bridge"
+ "compute-packet-bridge-impersonate"
+ "hybridscheme3"
+ "pqc-validation-flags"
+ "secureboot-key-scheme"
- "%s: "
- "%s: cannot set kAMFDRDecodeOptionManifestOnly and kAMFDRDecodeOptionSubCCOnly at the same time"
- "%s: fdrDecode->sealingManifestImg4.payload_hashed is false"
- "%s: trust evaluation on subCC requires a reStitchManifest"
- "/System/Library/Caches/apticket.der"
- "4751DC85-CF2F-4D64-AC6E-646B328C0EFE"
- "AMSupportCopyPreserveFileURL failed."
- "AMSupportPlatformOpenFileStreamWithURL"
- "Failed to create iterator: %s "
- "_AMSupportCreateDataFromFileURLInternal"
- "entitlement is NULL"
- "failed to convert url to file system representation"
- "failed to create path URL"
- "failed to decode APTicket"
- "failed to format log message"
- "failed to get entitlement string"
- "failed to locate AP ticket: %ld"
- "failed to obtain APTicket"
- "failed to read AP ticket: %d"
- "invalid entitlement length"
- "lookupPathForPersonalizedData"
- "rb"
- "softlink:o:path:/System/Library/PrivateFrameworks/MSUDataAccessor.framework/MSUDataAccessor"
- "~%d"
```
