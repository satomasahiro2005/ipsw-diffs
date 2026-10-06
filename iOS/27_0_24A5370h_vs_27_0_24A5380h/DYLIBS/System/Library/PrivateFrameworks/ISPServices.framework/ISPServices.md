## ISPServices

> `/System/Library/PrivateFrameworks/ISPServices.framework/ISPServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf05c` | `0xf0d0` | **`+0x74`** |
| `__TEXT.__cstring` | `0x6087` | `0x60ae` | **`+0x27`** |

### Other Changes

```diff

-20.50.6.0.0
+20.55.3.0.0

-  CStrings:  1417
+  CStrings:  1420
Functions:
~ __ZN3ISP23CreateFormattedMetadataERK19sCIspMetaDataShared : 44792 -> 44884
~ sub_280940d98 -> sub_285155df4 : 352 -> 368
~ __ZN3ISP36ISPCreateFrameMetaDataAsCFDictionaryEPK19sCIspMetaDataShared : 308 -> 316
CStrings:
+ "Shared VA Stats"
+ "tgtEstMax"
+ "tgtEstStddev"
```
