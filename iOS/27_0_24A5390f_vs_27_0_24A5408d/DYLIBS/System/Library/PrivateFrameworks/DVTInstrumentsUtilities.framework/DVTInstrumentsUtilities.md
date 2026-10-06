## DVTInstrumentsUtilities

> `/System/Library/PrivateFrameworks/DVTInstrumentsUtilities.framework/DVTInstrumentsUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x31c50` | `0x325ac` | **`+0x95c`** |
| `__AUTH_CONST.__objc_const` | `0x6478` | `0x6360` | **`-0x118`** |
| `__AUTH.__data` | `0xf0` | `0x178` | **`+0x88`** |
| `__TEXT.__cstring` | `0x5d4a` | `0x5cda` | **`-0x70`** |
| `__AUTH_CONST.__const` | `0x1158` | `0x11b8` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x1cd8` | `0x1c88` | **`-0x50`** |
| `__AUTH_CONST.__auth_got` | `0xb70` | `0xbb0` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x284` | `0x2b8` | **`+0x34`** |
| `__TEXT.__swift5_typeref` | `0x313` | `0x343` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x34c` | `0x374` | **`+0x28`** |
| `__DATA.__data` | `0xbd8` | `0xbf8` | **`+0x20`** |
| `__TEXT.__const` | `0x175c` | `0x177c` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2ffc` | `0x2fdc` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x15d` | `0x175` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1468` | `0x1480` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x2b8` | `0x2b0` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x18c8` | `0x18c0` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x150` | `0x148` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x31c` | `0x318` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x3c` | `0x40` | **`+0x4`** |

### Other Changes

```diff

-64578.145.1.0.0
+64578.160.1.0.0

-  Functions: 1523
-  Symbols:   615
-  CStrings:  1287
+  Functions: 1533
+  Symbols:   619
+  CStrings:  1286
Symbols:
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getSingletonMetadata
+ _swift_storeEnumTagSinglePayloadGeneric
- _OBJC_CLASS_$_XRBlockHandledIssueResponder
- _OBJC_METACLASS_$_XRBlockHandledIssueResponder
CStrings:
+ "-[XRStandardIssueResponder handleIssue:type:]"
+ "Debug: %@"
+ "Error: %@"
+ "Info: %@"
+ "Warning: %@"
- "-[XRStandardIssueResponder handleIssue:type:from:]"
- "Debug: %@ originating from %@"
- "Error: %@ originating from %@"
- "Info: %@ originating from %@"
- "KdebugSignpostHelpURL"
- "Warning: %@ originating from %@"
```
