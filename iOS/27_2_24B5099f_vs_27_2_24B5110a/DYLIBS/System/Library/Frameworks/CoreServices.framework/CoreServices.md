## CoreServices

> `/System/Library/Frameworks/CoreServices.framework/CoreServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cdd7c` | `0x1cde80` | **`+0x104`** |
| `__TEXT.__cstring` | `0x2944b` | `0x294e8` | **`+0x9d`** |
| `__AUTH_CONST.__cfstring` | `0x17d20` | `0x17d60` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x3be8` | `0x3c00` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1968` | `0x1970` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x2a28c` | `0x2a294` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xc790` | `0xc798` | **`+0x8`** |

### Other Changes

```diff

-1517.1.11.0.0
+1517.1.12.0.0

-  Functions: 9609
-  Symbols:   14307
-  CStrings:  6114
+  Functions: 9610
+  Symbols:   14309
+  CStrings:  6120
Symbols:
+ __ZN14LaunchServicesL31bbtm2DescriptionFlavorAvailableEv
+ _os_variant_has_internal_content
Functions:
~ __ZL17_LSRegisterPluginP11_LSDatabaseP13LSInstallInfoRK12LSPluginInfoPK14__CFDictionaryPK10__CFStringSB_S8_jPj : 4624 -> 4640
~ __ZL21UTTypeDescriptionKeysv : 128 -> 136
~ __UTTypeAddWithDeclarationDictionary : 3600 -> 3744
+ __ZN14LaunchServicesL31bbtm2DescriptionFlavorAvailableEv
~ ____ZN14LaunchServicesL35UTTypeEnumerateFlavoredDisplayNamesIZNS_L54UTTypeEnumerateAvailableAndPresentFlavoredDisplayNamesIZL30_UTGetLocalizedDescriptionImplPK16UTTypeSearchInfoE3$_0EEvP11_LSDatabasePK11_UTTypeDataRKT_EUljRKNS_23UTTypeDisplayNameFlavorEPhE_EEvS7_SA_SD__block_invoke : 100 -> 124
CStrings:
+ "#BreadBoardTestMode2"
+ "BreadBoard"
+ "TestMode2"
+ "UTTypeBreadBoardTestMode2Description"
+ "com.apple.Home.HomeExtension"
+ "com.apple.LaunchServices.UTTypeDisplayNameFlavor"
```
