## Silex

> `/System/Library/PrivateFrameworks/Silex.framework/Silex`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x3048` | `0x2f58` | **`-0xf0`** |
| `__DATA_DIRTY.__objc_data` | `0xf0c8` | `0xf1b8` | **`+0xf0`** |
| `__TEXT.__text` | `0x118264` | `0x1182b4` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x2430` | `0x243c` | **`+0xc`** |
| `__DATA.__common` | `0x8` | `—` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xb818` | `0xb820` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0x58` | `0x60` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4ef8` | `0x4f00` | **`+0x8`** |

### Other Changes

```diff

-5920.0.0.0.0
+5923.0.0.0.0
Functions:
~ -[SXBlueprintAnalyzer markersFromBlueprint:components:DOMObjectProvider:cursor:] : 1708 -> 1748
~ __Z42SXJSONObjectPrimitivesIsSupportedPrimitivePKc : 360 -> 364
~ __Z69SXJSONObjectPrimitivesMatchPrimitiveForEncodingAndRetrieveInformationPKcPS0_S1_PPFvvE : 248 -> 264
~ __Z58SXJSONObjectDetermineFunctionSpecificationAndCopyClassNamePKcPS0_PPFvvEPPc : 708 -> 688
~ +[SXCollectionCalculator layoutWithCollectionDisplay:width:numberOfComponents:unitConverter:] : 1144 -> 1148
~ -[SXDateParser dateFromString:] : 792 -> 828
```
