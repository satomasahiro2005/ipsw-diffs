## HybridDatabaseTokenizer

> `/System/Library/PrivateFrameworks/HybridDatabaseTokenizer.framework/HybridDatabaseTokenizer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x51a` | `0x60` | **`-0x4ba`** |
| `__TEXT.__text` | `0x271c` | `0x2a4c` | **`+0x330`** |
| `__AUTH_CONST.__const` | `0x118` | `0x228` | **`+0x110`** |
| `__TEXT.__const` | `0x90` | `0x120` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x3c` | `0xa4` | **`+0x68`** |
| `__TEXT.__constg_swiftt` | `0x7a` | `0xb2` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0x168` | `0x1a0` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0xa` | `0x42` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x22` | `0x52` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x1ba` | `0x18e` | **`-0x2c`** |
| `__AUTH_CONST.__auth_got` | `0x1b8` | `0x1a8` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x1a4` | `0x1ac` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x4` | `0xc` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x188` | `0x190` | **`+0x8`** |

### Other Changes

```diff

-44.0.1.0.0
+46.0.1.0.0

-  Functions: 54
-  Symbols:   67
-  CStrings:  15
+  Functions: 68
+  Symbols:   66
+  CStrings:  11
Symbols:
+ _objc_autoreleaseReturnValue
+ _objc_release_x21
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initWithCopy
+ _swift_cvw_initializeBufferWithCopyOfBuffer
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC1ERKS5_
- __ZNSt3__132__internal_log_hardening_failureEPKc
- _objc_release_x24
- _objc_release_x26
- _objc_release_x28
- _objc_retain_x22
- _objc_retain_x8
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "HDBTokenizer: segment: failed to extract UTF-8 bytes (length %llu)"
+ "HDBTokenizer: segment: sanitized input still failed UTF-8 decode (original %zu bytes)"
+ "HDBTokenizer: segment: token normalization failed"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:442: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/string:1362: libc++ Hardening assertion __pos <= size() failed: string index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/string:1371: libc++ Hardening assertion __pos <= size() failed: string index out of bounds\n"
- "HDBTokenizer: Latin-ASCII transform failed (%llu UTF-16 code units)"
- "HDBTokenizer: failed to extract UTF-8 bytes for normalized string of length %llu"
- "HDBTokenizer: sanitized input still failed UTF-8 decode (original %zu bytes, sanitized %zu bytes)"
```
