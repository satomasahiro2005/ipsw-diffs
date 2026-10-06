## FontServices

> `/System/Library/PrivateFrameworks/FontServices.framework/FontServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc330` | `0xd4d8` | **`+0x11a8`** |
| `__TEXT.__cstring` | `0x1a5b` | `0x1d17` | **`+0x2bc`** |
| `__AUTH_CONST.__cfstring` | `0xe80` | `0xfa0` | **`+0x120`** |
| `__DATA_CONST.__const` | `0x6e8` | `0x738` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x6d4` | `0x724` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x5f8` | `0x630` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0xdfc` | `0xe2c` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x900` | `0x928` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x10d8` | `0x10e8` | **`+0x10`** |

### Other Changes

```diff

-169.0.0.0.0
+173.0.0.0.0

-  Functions: 355
-  Symbols:   850
-  CStrings:  188
+  Functions: 366
+  Symbols:   865
+  CStrings:  199
Symbols:
+ +[FSUserFontManager replaceFontDataFromIdentifier:toIdentifier:]
+ -[FontServicesDaemonManager migrateIssuedFontsForIdentifier:toIdentifier:]
+ GCC_except_table37
+ GCC_except_table77
+ _AppReplacementDictionaryByRemovingIdentifier
+ _AppReplacementDictionaryByRenamingIdentifier
+ _AppReplacementIdentifierIsWellFormed
+ _FontProviderAppInfoIsWellFormed
+ _FontProviderFontsInfoIsWellFormed
+ ___64+[FSUserFontManager replaceFontDataFromIdentifier:toIdentifier:]_block_invoke
+ ___64+[FSUserFontManager replaceFontDataFromIdentifier:toIdentifier:]_block_invoke_2
+ ___74-[FontServicesDaemonManager migrateIssuedFontsForIdentifier:toIdentifier:]_block_invoke
+ ___74-[FontServicesDaemonManager migrateIssuedFontsForIdentifier:toIdentifier:]_block_invoke_2
+ ___block_descriptor_40_e8_32r_e17_v16?0"NSError"8lr32l8
+ ___block_descriptor_40_e8_32r_e8_v12?0B8lr32l8
+ _memchr
- GCC_except_table34
CStrings:
+ "+[FSUserFontManager replaceFontDataFromIdentifier:toIdentifier:]_block_invoke"
+ "-[FontServicesDaemonManager migrateIssuedFontsForIdentifier:toIdentifier:]_block_invoke"
+ ".."
+ "App Replacement: -> UserFontManager replaceFontData \"%@\" -> \"%@\""
+ "App Replacement: -> fontservicesd migrateIssuedFonts \"%@\" -> \"%@\""
+ "App Replacement: <- UserFontManager replaceFontData (xpcError %@, migrationError %@)"
+ "App Replacement: <- fontservicesd migrateIssuedFonts (success %d, xpcFailed %d)"
+ "UIFont is unavailable in this process; no system font names"
+ "UIWindow is unavailable in this process; continuing without a scene identifier"
+ "UIWindow is unavailable in this process; requesting fonts without a scene identifier"
+ "actualPath"
```
