## localizationswitcherd

> `/System/Library/PrivateFrameworks/IntlPreferences.framework/Support/localizationswitcherd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaa3c` | `0xc928` | **`+0x1eec`** |
| `__TEXT.__objc_stubs` | `0x9a0` | `0xac0` | **`+0x120`** |
| `__TEXT.__auth_stubs` | `0xba0` | `0xcb0` | **`+0x110`** |
| `__TEXT.__cstring` | `0x612` | `0x502` | **`-0x110`** |
| `__TEXT.__objc_methname` | `0x9b7` | `0xaa9` | **`+0xf2`** |
| `__DATA_CONST.__auth_got` | `0x5e0` | `0x668` | **`+0x88`** |
| `__TEXT.__swift5_typeref` | `0xdc` | `0x154` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0xaec` | `0xb3c` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x350` | `0x398` | **`+0x48`** |
| `__DATA.__data` | `0x1c0` | `0x1f0` | **`+0x30`** |
| `__TEXT.__const` | `0x142` | `0x162` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x248` | `0x268` | **`+0x20`** |
| `__DATA.__bss` | `0x38` | `0x48` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x180` | `0x188` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`

### Other Changes

```diff

-494.6.0.0.0
+496.0.0.0.0

-  Functions: 143
-  Symbols:   275
-  CStrings:  244
+  Functions: 158
+  Symbols:   293
+  CStrings:  250
Symbols:
+ _$s10Foundation22_convertNSErrorToErrorys0E0_pSo0C0CSgF
+ _$s10Foundation3URLV36_unconditionallyBridgeFromObjectiveCyACSo5NSURLCSgFZ
+ _$s10Foundation4DataV19_bridgeToObjectiveCSo6NSDataCyF
+ _$s10Foundation6LocaleV18preferredLanguagesSaySSGvgZ
+ _$sSS10FoundationE36_unconditionallyBridgeFromObjectiveCySSSo8NSStringCSgFZ
+ _$sSS10FoundationE4data5using20allowLossyConversionAA4DataVSgSSAAE8EncodingV_SbtF
+ _$sSS10FoundationE8EncodingV4utf8ACvgZ
+ _$sSS10FoundationE8EncodingVMa
+ _$sSo13os_log_type_ta0A0E5faultABvgZ
+ _$ss018_bridgeAnyObjectToB0yypyXlSgF
+ _$ss10_HashTableV12previousHole6beforeAB6BucketVAF_tF
+ _$ss38_bridgeAnythingNonVerbatimToObjectiveCyyXlxnlF
+ _OBJC_CLASS_$_NSJSONSerialization
+ _objc_retain_x24
+ _objc_retain_x9
+ _swift_release_x25
+ _swift_retain_x21
+ _swift_unknownObjectRelease
+ _swift_willThrow
- _$s10Foundation17NSLocalizedString_9tableName6bundle5value7commentS2S_SSSgSo8NSBundleCS2StF
CStrings:
+ "IntlPreferences bundle not found — localized strings will not resolve"
+ "JSONObjectWithData:options:error:"
+ "URLForResource:withExtension:"
+ "__swift_objectForKeyedSubscript:"
+ "baseLanguageFromLanguage:"
+ "bundleWithIdentifier:"
+ "doubleValue"
+ "initWithContentsOfURL:"
+ "localizations"
+ "preferredLocalizationsFromArray:forPreferences:"
- "Action to add discovered language. Variable is language name."
- "Description for language discovery follow-up notification. Variable is language name."
- "Notification action"
- "Title for language discovery follow-up. Variable is language name."
```
