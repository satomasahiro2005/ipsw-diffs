## MXI

> `/System/Library/PrivateFrameworks/MXI.framework/MXI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x50d64` | `0x4f844` | **`-0x1520`** |
| `__TEXT.__cstring` | `0xbdca` | `0xb7ce` | **`-0x5fc`** |
| `__AUTH.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x500` | `0x550` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x764c` | `0x765c` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x488` | `0x480` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xe08` | `0xe00` | **`-0x8`** |

### Other Changes

```diff

-  Functions: 859
-  Symbols:   493
-  CStrings:  1169
+  Functions: 858
+  Symbols:   492
+  CStrings:  1164
Symbols:
- __ZNSt3__132__internal_log_hardening_failureEPKc
CStrings:
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:442: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/array:284: libc++ Hardening assertion __n < _Size failed: out-of-bounds access in std::array<T, N>\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/deque:2199: libc++ Hardening assertion !empty() failed: deque::pop_front called on an empty deque\n"
```
