## SpotlightUIServices

> `/System/Library/PrivateFrameworks/SpotlightUIServices.framework/SpotlightUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x52f1c` | `0x539d4` | **`+0xab8`** |
| `__AUTH.__objc_data` | `0xa20` | `0x860` | **`-0x1c0`** |
| `__DATA_DIRTY.__objc_data` | `0x1a58` | `0x1c18` | **`+0x1c0`** |
| `__TEXT.__oslogstring` | `0x85b` | `0xa1b` | **`+0x1c0`** |
| `__DATA_DIRTY.__data` | `0x280` | `0x2e0` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x28e0` | `0x2920` | **`+0x40`** |
| `__DATA.__data` | `0x218` | `0x1e0` | **`-0x38`** |
| `__TEXT.__const` | `0xbf4` | `0xc24` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x4d00` | `0x4d30` | **`+0x30`** |
| `__AUTH.__data` | `0x1b0` | `0x188` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e38` | `0x2e60` | **`+0x28`** |
| `__DATA.__bss` | `0xab0` | `0xa90` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x1c8` | `0x1e8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2520` | `0x2540` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x13f8` | `0x1418` | **`+0x20`** |
| `__DATA.__common` | `0x28` | `0x10` | **`-0x18`** |
| `__DATA_DIRTY.__common` | `0x10` | `0x28` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xb40` | `0xb48` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x14d8` | `0x14e0` | **`+0x8`** |

### Other Changes

```diff

-235.3.100.0.0
+236.0.4.100.0

-  Functions: 2171
-  Symbols:   3558
-  CStrings:  449
+  Functions: 2175
+  Symbols:   3563
+  CStrings:  458
Symbols:
+ +[SPUISAskSiriResultBuilder syntheticAskSiriResultForQueryContext:]
+ +[SPUISUtilities elevatedResultShouldInvokeSiri:]
+ +[SPUISUtilities isFirstSectionElevatable:]
+ +[SPUISUtilities splitSections:forElevation:elevatedSections:regularSections:]
+ _objc_autorelease
CStrings:
+ "(nil)"
+ "SearchInAppSectionBuilder: building — askSiriResult=%@ searchInAppInfo=%lu hiddenBundles=%lu"
+ "SearchInAppSectionBuilder: shouldSkipSection=YES (entities=%lu, SSShowSearchInApps=%d)"
+ "SectionBuilder input: bundle=%@ resultCount=%lu"
+ "SectionBuilder output: bundle=%@ resultCount=%lu"
+ "SectionBuilder: DROPPED empty section bundle=%@"
+ "SectionBuilder: output sectionCount=%lu"
+ "SectionBuilder: renderState=%ld askSiriResult=%@ searchInAppInfo=%lu inputSectionCount=%lu"
+ "com.apple.parsec.itunes.iosSoftware"
```
