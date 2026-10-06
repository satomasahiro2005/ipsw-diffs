## SilexWeb

> `/System/Library/PrivateFrameworks/SilexWeb.framework/SilexWeb`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x186bc` | `0x189cc` | **`+0x310`** |
| `__AUTH_CONST.__objc_const` | `0x9bd0` | `0x9e10` | **`+0x240`** |
| `__AUTH_CONST.__cfstring` | `0x19c0` | `0x1ae0` | **`+0x120`** |
| `__TEXT.__cstring` | `0x1d35` | `0x1e2d` | **`+0xf8`** |
| `__TEXT.__objc_methlist` | `0x34fc` | `0x358c` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x1628` | `0x1680` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x460` | `0x4b0` | **`+0x50`** |
| `__DATA.__objc_ivar` | `0x460` | `0x480` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x878` | `0x890` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x490` | `0x498` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x2f8` | `0x300` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x270` | `0x278` | **`+0x8`** |

### Other Changes

```diff

-5920.0.0.0.0
+5923.0.0.0.0

-  Functions: 920
-  Symbols:   2541
-  CStrings:  266
+  Functions: 933
+  Symbols:   2569
+  CStrings:  275
Symbols:
+ -[SWInspection documentSummary]
+ -[SWInspectionDocumentSummary bodyChildCount]
+ -[SWInspectionDocumentSummary bodyHeight]
+ -[SWInspectionDocumentSummary bodyWidth]
+ -[SWInspectionDocumentSummary descendantCount]
+ -[SWInspectionDocumentSummary htmlByteLength]
+ -[SWInspectionDocumentSummary initWithObject:]
+ -[SWInspectionDocumentSummary isBlank]
+ -[SWInspectionDocumentSummary loggingDescription]
+ -[SWInspectionDocumentSummary mediaElementCount]
+ -[SWInspectionDocumentSummary visibleTextLength]
+ _OBJC_CLASS_$_SWInspectionDocumentSummary
+ _OBJC_IVAR_$_SWInspection._documentSummary
+ _OBJC_IVAR_$_SWInspectionDocumentSummary._bodyChildCount
+ _OBJC_IVAR_$_SWInspectionDocumentSummary._bodyHeight
+ _OBJC_IVAR_$_SWInspectionDocumentSummary._bodyWidth
+ _OBJC_IVAR_$_SWInspectionDocumentSummary._descendantCount
+ _OBJC_IVAR_$_SWInspectionDocumentSummary._htmlByteLength
+ _OBJC_IVAR_$_SWInspectionDocumentSummary._mediaElementCount
+ _OBJC_IVAR_$_SWInspectionDocumentSummary._visibleTextLength
+ _OBJC_METACLASS_$_SWInspectionDocumentSummary
+ _SWInspectionFloatValue
+ _SWInspectionIntegerValue
+ __OBJC_$_INSTANCE_METHODS_SWInspectionDocumentSummary
+ __OBJC_$_INSTANCE_VARIABLES_SWInspectionDocumentSummary
+ __OBJC_$_PROP_LIST_SWInspectionDocumentSummary
+ __OBJC_CLASS_RO_$_SWInspectionDocumentSummary
+ __OBJC_METACLASS_RO_$_SWInspectionDocumentSummary
CStrings:
+ "bodyChildCount"
+ "bodyHeight"
+ "bodyWidth"
+ "bodyWidth=%g,bodyHeight=%g,bodyChildCount=%ld,descendantCount=%ld,visibleTextLength=%ld,mediaElementCount=%ld,htmlByteLength=%ld"
+ "descendantCount"
+ "documentSummary"
+ "htmlByteLength"
+ "mediaElementCount"
+ "visibleTextLength"
```
