## CTParserService

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CTParser.framework/XPCServices/CTParserService.xpc/CTParserService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14b88` | `0x14b28` | **`-0x60`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-13466.3.0.0.0
+13473.1.0.0.0
Functions:
~ __ZNK15CTParserXPCData8describeEv : 852 -> 848
~ __ZN5boost7archive17archive_exceptionC1ENS1_14exception_codeEPKcS4_ : 1680 -> 1588
~ sub_1000128e8 -> sub_100012888 : 960 -> 956
~ sub_100013998 -> sub_100013934 : 124 -> 128
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:418: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
```
