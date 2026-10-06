## AppleAccount

> `/System/Library/PrivateFrameworks/AppleAccount.framework/AppleAccount`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a7d24` | `0x1a8e0c` | **`+0x10e8`** |
| `__TEXT.__oslogstring` | `0x137fd` | `0x138ed` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0xd5e0` | `0xd620` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x3f50` | `0x3f80` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x15ea` | `0x161a` | **`+0x30`** |
| `__DATA.__data` | `0x40f4` | `0x4114` | **`+0x20`** |
| `__TEXT.__cstring` | `0x11452` | `0x11472` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x64e8` | `0x6500` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xb5b4` | `0xb5c4` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x5270` | `0x5278` | **`+0x8`** |

### Other Changes

```diff

-1063.1.0.0.0
+1064.0.0.0.0

-  Functions: 9142
-  Symbols:   10003
-  CStrings:  3725
+  Functions: 9148
+  Symbols:   10007
+  CStrings:  3731
Symbols:
+ +[AAUrlBagHelper deviceListCacheEnabledWithCompletion:]
+ _AATermsEntryTVOSSLA
+ __AAUrlBagDeviceListCacheEnabledKey
+ ___55+[AAUrlBagHelper deviceListCacheEnabledWithCompletion:]_block_invoke
CStrings:
+ "Device list cache: Failed to fetch config from URL bag: %@"
+ "Device list cache: Returning deviceListCacheEnabled from urlbag: %@"
+ "Device list cache: Unexpected config value type: %@"
+ "Device list cache: key absent in URL bag, defaulting to NO"
+ "deviceListCacheEnabled"
+ "tvOS"
```
