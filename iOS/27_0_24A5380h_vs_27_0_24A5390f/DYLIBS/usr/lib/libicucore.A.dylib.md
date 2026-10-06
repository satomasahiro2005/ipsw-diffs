## libicucore.A.dylib

> `/usr/lib/libicucore.A.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26a990` | `0x26a8fc` | **`-0x94`** |
| `__TEXT.__cstring` | `0xa17e` | `0xa179` | **`-0x5`** |

### Other Changes

```diff

-78128.0.0.0.0
+78131.0.0.0.0

-  CStrings:  4170
+  CStrings:  4169
Functions:
~ __ZNK3icu16SimpleDateFormat9subFormatERNS_13UnicodeStringEDsi15UDisplayContextiDsRNS_20FieldPositionHandlerERNS_8CalendarER10UErrorCode : 6832 -> 6804
~ __ZN3icu16SimpleDateFormat22getPatternForTimeStyleENS_10DateFormat6EStyleERKNS_6LocaleEP15UResourceBundleRNS_13UnicodeStringER10UErrorCode : 840 -> 804
~ __ZN3icu24DateTimePatternGenerator24localeUsesLongDayPeriodsERKNS_6LocaleE : 388 -> 292
~ sub_18f6c4c88 -> sub_18f827be8 : 80 -> 92
CStrings:
- "ldpn"
```
