## CoreLocationNumberedMapCalloutPromptPlugin

> `/System/Library/Frameworks/CoreLocation.framework/PlugIns/CoreLocationNumberedMapCalloutPromptPlugin.appex/CoreLocationNumberedMapCalloutPromptPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x36b` | `0x238` | **`-0x133`** |
| `__TEXT.__text` | `0x7a2c` | `0x7a04` | **`-0x28`** |
| `__TEXT.__auth_stubs` | `0x450` | `0x440` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x238` | `0x230` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3169.4.0.0.0
+3176.0.0.0.0

-  Symbols:   138
-  CStrings:  443
+  Symbols:   137
+  CStrings:  442
Symbols:
- __ZNSt3__132__internal_log_hardening_failureEPKc
Functions:
~ sub_100004bdc : 2512 -> 2500
~ sub_100006ae8 -> sub_100006adc : 980 -> 952
CStrings:
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
```
