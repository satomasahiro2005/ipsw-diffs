## libGSFont.dylib

> `/System/Library/PrivateFrameworks/FontServices.framework/libGSFont.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x896c` | `0x96d8` | **`+0xd6c`** |
| `__AUTH_CONST.__cfstring` | `0xd20` | `0xe00` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x15d` | `0x1cd` | **`+0x70`** |
| `__TEXT.__cstring` | `0x8e5` | `0x942` | **`+0x5d`** |
| `__AUTH_CONST.__auth_got` | `0x598` | `0x5c0` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x2b0` | `0x2d0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x288` | `0x2a8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x278` | `0x288` | **`+0x10`** |

### Other Changes

```diff

-169.0.0.0.0
+173.0.0.0.0

-  Functions: 149
-  Symbols:   433
-  CStrings:  128
+  Functions: 158
+  Symbols:   454
+  CStrings:  138
Symbols:
+ _AppReplacementDictionaryByRemovingIdentifier
+ _AppReplacementDictionaryByRenamingIdentifier
+ _AppReplacementIdentifierIsWellFormed
+ _FontProviderAppInfoIsWellFormed
+ _FontProviderFontsInfoIsWellFormed
+ _OBJC_CLASS_$_NSArray
+ _OUTLINED_FUNCTION_3
+ ___PathMayBeRegisteredAsFontFile_block_invoke
+ ___block_descriptor_33_e18_B16?0"NSString"8l
+ __kCTFontFamilyNameAttribute
+ __kCTFontIgnoreURLLocationAttribute
+ __kCTFontNameAttribute
+ __kCTFontRegistrationUserInfo
+ __kCTFontURLAttribute
+ _kFontProviderInfoParameterIndexesKey
+ _kFontProviderSandboxExtension
+ _memchr
+ _objc_opt_class
+ _objc_release_x28
+ _objc_retainBlock
+ _realpath$DARWIN_EXTSN
CStrings:
+ ".."
+ "B16@?0@\"NSString\"8"
+ "FontProviderSubscriptionSupportInfo"
+ "GSFont: refusing to register invalid path."
+ "GSFont: refusing to register path outside the permitted directories."
+ "actualPath"
+ "expire"
+ "scheme"
+ "test"
+ "warn"
```
