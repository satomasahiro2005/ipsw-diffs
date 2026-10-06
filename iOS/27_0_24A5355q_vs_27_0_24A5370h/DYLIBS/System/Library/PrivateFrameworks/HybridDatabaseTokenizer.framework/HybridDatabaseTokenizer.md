## HybridDatabaseTokenizer

> `/System/Library/PrivateFrameworks/HybridDatabaseTokenizer.framework/HybridDatabaseTokenizer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b78` | `0x271c` | **`-0x45c`** |
| `__TEXT.__cstring` | `0x2bd` | `0x51a` | **`+0x25d`** |
| `__TEXT.__gcc_except_tab` | `0x240` | `0x1a4` | **`-0x9c`** |
| `__TEXT.__oslogstring` | `0x1e4` | `0x1ba` | **`-0x2a`** |
| `__TEXT.__unwind_info` | `0x1a0` | `0x188` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1a8` | `0x1b8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x60` | `0x50` | **`-0x10`** |
| `__TEXT.__const` | `0x98` | `0x90` | **`-0x8`** |

### Other Changes

```diff

-40.0.0.0.0
+44.0.1.0.0

-  Functions: 59
-  Symbols:   65
-  CStrings:  13
+  Functions: 54
+  Symbols:   67
+  CStrings:  15
Symbols:
+ _memchr
+ _objc_release_x26
+ _objc_release_x28
+ _objc_retain_x22
- _objc_release_x25
- _objc_retain_x12
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:442: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/string:1362: libc++ Hardening assertion __pos <= size() failed: string index out of bounds\n"
+ "HDBTokenizer: failed to extract UTF-8 bytes for normalized string of length %llu"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:413: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "HDBTokenizer: failed to extract UTF-8 bytes for token at UTF-16 range [%llu, %llu) within normalized string of length %llu"
```
