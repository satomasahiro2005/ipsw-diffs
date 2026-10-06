## PreviewShellKit

> `/System/Library/PrivateFrameworks/PreviewShellKit.framework/PreviewShellKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xed4e8` | `0xeecc0` | **`+0x17d8`** |
| `__TEXT.__const` | `0xb034` | `0xb3a4` | **`+0x370`** |
| `__TEXT.__cstring` | `0x4514` | `0x47f4` | **`+0x2e0`** |
| `__DATA.__bss` | `0xa410` | `0xa610` | **`+0x200`** |
| `__AUTH_CONST.__auth_got` | `0x1fb0` | `0x2060` | **`+0xb0`** |
| `__AUTH_CONST.__const` | `0x6e98` | `0x6f18` | **`+0x80`** |
| `__DATA.__data` | `0x35e0` | `0x3660` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x3b30` | `0x3b98` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0x4fc6` | `0x5012` | **`+0x4c`** |
| `__TEXT.__eh_frame` | `0x83fc` | `0x843c` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xc50` | `0xc80` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x2f1c` | `0x2f40` | **`+0x24`** |
| `__TEXT.__swift_as_cont` | `0x5b8` | `0x5d8` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x22c0` | `0x22dc` | **`+0x1c`** |
| `__DATA.__common` | `0x40` | `0x58` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x560` | `0x570` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1849` | `0x1859` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x308` | `0x30c` | **`+0x4`** |

### Other Changes

```diff

-24.0.31.0.0
+24.0.35.0.0

+  - /usr/lib/swift/libswiftRegexBuilder.dylib

+  - /usr/lib/swift/libswift_StringProcessing.dylib

-  Functions: 4523
-  Symbols:   1828
-  CStrings:  487
+  Functions: 4559
+  Symbols:   1838
+  CStrings:  493
Symbols:
+ ___unnamed_27
+ _associated conformance 15PreviewShellKit22PreviewsJITLinkerState33_AB1E9DAC1E01E07B41F82BB236A927B7LLV29FileInRestrictedLocationErrorV0D12FoundationOS013HumanReadableU0AA0V009LocalizedU0
+ _associated conformance 15PreviewShellKit22PreviewsJITLinkerState33_AB1E9DAC1E01E07B41F82BB236A927B7LLV29FileInRestrictedLocationErrorV0D12FoundationOS013HumanReadableU0AAs23CustomStringConvertible
+ _associated conformance 15PreviewShellKit22PreviewsJITLinkerState33_AB1E9DAC1E01E07B41F82BB236A927B7LLV29FileInRestrictedLocationErrorV10Foundation09LocalizedU0AAs0U0
+ _symbolic _____ 15PreviewShellKit22PreviewsJITLinkerState33_AB1E9DAC1E01E07B41F82BB236A927B7LLV29FileInRestrictedLocationErrorV
+ _symbolic _____Sg 17_StringProcessing23RegexRepetitionBehaviorV
+ _symbolic _____Sg 19PreviewsMessagingOS19RenderedDisplayInfoV
+ _symbolic _____ySsG 12RegexBuilder8ChoiceOfV
+ _symbolic _____ySsG 12RegexBuilder9OneOrMoreV
+ _symbolic _____ySsG 17_StringProcessing5RegexV
+ _type_layout_string 15PreviewShellKit22PreviewsJITLinkerState33_AB1E9DAC1E01E07B41F82BB236A927B7LLV29FileInRestrictedLocationErrorV
- ___unnamed_26
CStrings:
+ "/Build/Intermediates.noindex/"
+ "/Build/Products/"
+ "A file required for previews appears to be in a location macOS may restrict access to (such as Desktop, Downloads, or Documents). Try moving your project or its build output to a folder outside of Desktop, Downloads, and Documents, then try again."
+ "A file required for previews may be in a restricted location"
+ "DerivedData folder may be in a restricted location"
+ "Your DerivedData folder appears to be in a location macOS may restrict access to (such as Desktop, Downloads, or Documents). Try changing DerivedData to “Default” or a folder outside of Desktop, Downloads, and Documents in Xcode → Settings → Locations, then try again."
```
