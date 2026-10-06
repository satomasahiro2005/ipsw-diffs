## PanicProcessingSupport

> `/System/Library/PrivateFrameworks/PanicProcessingSupport.framework/PanicProcessingSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcb5c` | `0xc9f8` | **`-0x164`** |
| `__AUTH_CONST.__cfstring` | `0x2180` | `0x20e0` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x15ba` | `0x155a` | **`-0x60`** |
| `__DATA_CONST.__objc_arraydata` | `0x170` | `0x148` | **`-0x28`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x30` | `0x18` | **`-0x18`** |

### Other Changes

```diff

-34.0.0.0.0
+37.0.0.0.0

-  CStrings:  344
+  CStrings:  339
Symbols:
+ -[PanicReport setPlaneMetadata:]
+ _OBJC_IVAR_$_PanicReport._planeMetadata
- -[PanicReport setEnsembleMetadata:]
- _OBJC_IVAR_$_PanicReport._ensembleMetadata
Functions:
~ -[PanicReport setEnsembleMetadata:] -> -[PanicReport setPlaneMetadata:] : 620 -> 264
CStrings:
+ "plane_node"
+ "plane_supervisor"
- "chassisID"
- "ensembleID"
- "ensemble_node"
- "ensemble_supervisor"
- "totalNodeNumber"
- "totalReportNumber"
- "unique_crash_event_id"
```
