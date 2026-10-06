## TilesService

> `/System/Library/PrivateFrameworks/CoreLocationTiles.framework/XPCServices/TilesService.xpc/TilesService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xac9` | `0x967` | **`-0x162`** |
| `__TEXT.__gcc_except_tab` | `0x4fc` | `0x4d8` | **`-0x24`** |
| `__DATA_CONST.__const` | `0x378` | `0x398` | **`+0x20`** |
| `__TEXT.__text` | `0x822c` | `0x820c` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x408` | `0x3f8` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3169.4.0.0.0
+3176.0.0.0.0

-  Functions: 182
+  Functions: 183

-  CStrings:  301
+  CStrings:  300
Symbols:
+ _dispatch_async
- __ZNSt3__132__internal_log_hardening_failureEPKc
CStrings:
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__hash_table:1855: libc++ Hardening assertion __p != end() failed: unordered container::erase(iterator) called with a non-dereferenceable iterator\n"
```
