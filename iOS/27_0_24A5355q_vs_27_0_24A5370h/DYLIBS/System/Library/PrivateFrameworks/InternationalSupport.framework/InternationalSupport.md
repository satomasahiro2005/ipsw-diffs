## InternationalSupport

> `/System/Library/PrivateFrameworks/InternationalSupport.framework/InternationalSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__objc_arraydata` | `0x1aa2d0` | `0x1a9fd0` | **`-0x300`** |
| `__AUTH_CONST.__cfstring` | `0x68f6a0` | `0x68f940` | **`+0x2a0`** |
| `__AUTH_CONST.__objc_dictobj` | `0x2cd8` | `0x2b98` | **`-0x140`** |
| `__TEXT.__cstring` | `0x212a` | `0x21ab` | **`+0x81`** |
| `__TEXT.__text` | `0xa4cc` | `0xa534` | **`+0x68`** |
| `__TEXT.__ustring` | `0x2f9ab8` | `0x2f9a5c` | **`-0x5c`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x1d40` | `0x1d28` | **`-0x18`** |
| `__DATA_CONST.__const` | `0x310` | `0x308` | **`-0x8`** |

### Other Changes

```diff

-121.0.0.0.0
+122.0.0.0.0

-  Symbols:   509
-  CStrings:  215015
+  Symbols:   508
+  CStrings:  215036
Symbols:
+ _KeyboardLanguages
- _KeyboardLanguages_iOS
- _KeyboardLanguages_macOS
Functions:
~ +[NSLocale(InternationalSupportExtensions) matchedLanguagesFromAvailableLanguages:forPreferredLanguages:] : 636 -> 632
~ ___60+[NSLocale(InternationalSupportExtensions) _deviceLanguages]_block_invoke : 404 -> 400
~ -[ISRegionDetector _checkForAliasesOrInvalid:] : 640 -> 632
~ -[ISRegionDetector guessedLanguages] : 660 -> 652
~ -[ISRegionDetector _scanComplete:error:] : 1152 -> 1140
~ ___63+[NSLocale(InternationalSupportExtensions) baseSystemLanguages]_block_invoke : 344 -> 340
~ +[NSLocale(InternationalSupportExtensions) regionsForLanguage:withThreshold:] : 484 -> 492
~ +[NSLocale(InternationalSupportExtensions) relatedLanguagesForLanguage:] : 756 -> 752
~ +[NSLocale(InternationalSupportExtensions) languagesByAddingRelatedLanguagesToLanguages:] : 724 -> 720
~ ___68+[NSLocale(InternationalSupportExtensions) availableSpokenLanguages]_block_invoke : 420 -> 416
~ +[NSLocale(InternationalSupportExtensions) spokenLanguagesForLanguages:includeLanguagesForRegion:] : 876 -> 868
~ -[NSLocale(InternationalSupportExtensions) availableNumberingSystems] : 708 -> 704
~ -[NSLocale(InternationalSupportExtensions) countryCodeTopLevelDomainsUsingPunycode:] : 656 -> 652
~ +[NSLocale(InternationalSupportExtensions) abbreviationsForLanguages:minimizeVariants:] : 1112 -> 1100
~ +[NSLocale(InternationalSupportExtensions) _languagesForRegion:subdivision:withThreshold:] : 1368 -> 1372
~ +[ISLanguageCarousel rankedItemsFromItems:usingSystemLanguages:preferredLanguages:region:] : 1140 -> 1136
~ -[ISLanguageCarousel _itemsWithMergedDuplicates:] : 988 -> 984
~ sub_1ca7b5e44 -> sub_1cb044df8 : 980 -> 1148
~ sub_1ca7b67a8 -> sub_1cb045804 : 220 -> 232
CStrings:
+ "KeyboardLanguages.plist"
+ "acf"
+ "acf-Latn"
+ "bla-Latn"
+ "crj-Cans"
+ "crk-Cans"
+ "crl-Cans"
+ "crm-Cans"
+ "csw-Cans"
+ "cwd-Cans"
+ "fil-Tglg"
+ "fla"
+ "fla-Latn"
+ "gcf"
+ "gcf-Latn"
+ "kgp"
+ "kgp-Latn"
+ "kio"
+ "kio-Latn"
+ "srs"
+ "srs-Latn"
+ "yrl"
+ "yrl-Latn"
+ "ƛ"
+ "ᐁ"
+ "ᐌ"
+ "ᐍ"
+ "ᙷ"
+ "ᜃ"
+ "ᵰ"
+ "Ỹ"
- "KeyboardLanguages-iOS.plist"
- "KeyboardLanguages-macOS.plist"
- "тыва дыл"
- "ᐃᓕᓖᒧᐎᓐ"
- "ᐄᓅ ᐊᔨᒨᓐ"
- "ᐄᔨᔫ ᐊᔨᒨᓐ"
- "ᓀᐦᐃᓇᐍᐏᐣ"
- "ᓀᐦᐃᔭᐍᐏᐣ"
- "ᓀᐦᐃᖬᐍᐏᐣ"
- "ᓱᖽᐧᖿ"
```
