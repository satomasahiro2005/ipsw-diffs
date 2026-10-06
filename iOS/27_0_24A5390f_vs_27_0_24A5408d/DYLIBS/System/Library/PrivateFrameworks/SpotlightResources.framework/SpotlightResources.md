## SpotlightResources

> `/System/Library/PrivateFrameworks/SpotlightResources.framework/SpotlightResources`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29f40` | `0x2a018` | **`+0xd8`** |
| `__TEXT.__unwind_info` | `0x9c0` | `0x9e8` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x45e0` | `0x4600` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x24ec` | `0x2506` | **`+0x1a`** |
| `__TEXT.__const` | `0x128` | `0x138` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1108` | `0x1110` | **`+0x8`** |
| `__TEXT.__cstring` | `0x22fc` | `0x2304` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1628` | `0x1630` | **`+0x8`** |

### Other Changes

```diff

-2454.100.0.0.0
+2459.102.0.0.0

-  Functions: 820
-  Symbols:   1332
-  CStrings:  875
+  Functions: 821
+  Symbols:   1333
+  CStrings:  876
Symbols:
+ +[SRResourcesManager trialSpotlightUITreatmentID]
CStrings:
+ ".xctest"
+ "Before loading namespace %@: _hasActiveExperiment = %@ (treatmentID: %s), _hasRollout = %@, _hasOverride = %@"
+ "ns:%s, exp:%d, trt:%s, ro:%d, over:%d"
- "Before loading namespace %@: _hasActiveExperiment = %@, _hasRollout = %@, _hasOverride = %@"
- "ns:%s, exp:%d, ro:%d, over:%d"
```
