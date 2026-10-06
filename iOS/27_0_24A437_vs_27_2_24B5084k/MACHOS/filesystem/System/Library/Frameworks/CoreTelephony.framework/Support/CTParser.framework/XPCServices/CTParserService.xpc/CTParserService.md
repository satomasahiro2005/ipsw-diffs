## CTParserService

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CTParser.framework/XPCServices/CTParserService.xpc/CTParserService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14ad8` | `0x14a24` | **`-0xb4`** |
| `__DATA_CONST.__const` | `0x2568` | `0x2528` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0x1abc` | `0x1ae0` | **`+0x24`** |
| `__TEXT.__auth_stubs` | `0x8b0` | `0x8a0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x460` | `0x458` | **`-0x8`** |
| `__TEXT.__cstring` | `0x5d5` | `0x5cf` | **`-0x6`** |
| `__TEXT.__init_offsets` | `0x90` | `0x8c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__got`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-13487.7.0.0.0
+13494.0.0.0.0

-  Functions: 803
-  Symbols:   339
-  CStrings:  78
+  Functions: 801
+  Symbols:   338
+  CStrings:  77
Symbols:
- _dispatch_once
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/string:1371: libc++ Hardening assertion __pos <= size() failed: string index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/string:1371: libc++ Hardening assertion __pos <= size() failed: string index out of bounds\n"
- "v8@?0"
```
