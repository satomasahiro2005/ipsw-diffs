## com.apple.FontServices.FontProviderLoader

> `/System/Library/PrivateFrameworks/FontServices.framework/XPCServices/com.apple.FontServices.FontProviderLoader.xpc/com.apple.FontServices.FontProviderLoader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25fc` | `0x2f88` | **`+0x98c`** |
| `__DATA_CONST.__cfstring` | `0x440` | `0x5c0` | **`+0x180`** |
| `__TEXT.__cstring` | `0x491` | `0x603` | **`+0x172`** |
| `__TEXT.__objc_stubs` | `0x9c0` | `0xa20` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x98` | `0xe0` | **`+0x48`** |
| `__TEXT.__objc_methname` | `0xd6b` | `0xd8b` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x460` | `0x470` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x450` | `0x460` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x238` | `0x240` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-169.0.0.0.0
+173.0.0.0.0

-  Functions: 37
-  Symbols:   129
-  CStrings:  244
+  Functions: 39
+  Symbols:   132
+  CStrings:  258
Symbols:
+ _FontProviderAppInfoIsWellFormed
+ _FontProviderFontsInfoIsWellFormed
+ _memchr
CStrings:
+ "FontProviderSubscriptionSupportInfo"
+ "actualPath"
+ "expire"
+ "length"
+ "objectForKeyedSubscript:"
+ "registerFonts received malformed appInfo."
+ "registerFonts received malformed fontsInfo."
+ "registeredFontsInfo received malformed appInfo; dropping the connection."
+ "scheme"
+ "test"
+ "unregisterFonts received malformed appInfo; dropping the connection."
+ "updateAppInfo received malformed appInfo; dropping the connection."
+ "url"
+ "warn"
```
