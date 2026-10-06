## ColorSync

> `/System/Library/Frameworks/ColorSync.framework/ColorSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x688bc` | `0x68ab4` | **`+0x1f8`** |
| `__TEXT.__cstring` | `0x710f` | `0x7144` | **`+0x35`** |

### Other Changes

```diff

-3926.0.0.0.0
+3929.0.0.0.0

-  CStrings:  904
+  CStrings:  905
Symbols:
+ __ZL22cdr_constrain_headroomPK14__CFDictionaryfRfbPKc
- __ZL22cdr_constrain_headroomPK14__CFDictionaryfRfPKc
Functions:
~ __ZN17ConversionManager27AddFlexLuminanceToneMappingEPK14__CFDictionaryP22ColorSyncLuminanceInfo : 1816 -> 1820
~ _verified_uint8_from_dictionary : 160 -> 232
~ __ZN23CMMFloatBitNChanEncoder8DoEncodeER12CMMFloatBitsP14CMMRuntimeInfoPmS4_ : 592 -> 780
~ __ZN23CMMFloatBitNChanDecoder8DoDecodeERK12CMMFloatBitsP14CMMRuntimeInfom : 496 -> 660
~ __ZL22cdr_constrain_headroomPK14__CFDictionaryfRfPKc -> __ZL22cdr_constrain_headroomPK14__CFDictionaryfRfbPKc : 752 -> 772
~ __ZN17ConversionManager22AddHAGCurveToneMappingEPK14__CFDictionaryf : 2384 -> 2440
CStrings:
+ "Value for %@ is expected to be of kCFNumberSInt8Type"
```
