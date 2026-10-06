## batteryintelligenced

> `/usr/libexec/batteryintelligenced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x45ec4` | `0x46fbc` | **`+0x10f8`** |
| `__DATA.__objc_const` | `0x7b90` | `0x7eb0` | **`+0x320`** |
| `__TEXT.__objc_methlist` | `0x33ec` | `0x35c4` | **`+0x1d8`** |
| `__TEXT.__objc_methname` | `0x70ca` | `0x71c9` | **`+0xff`** |
| `__DATA.__objc_data` | `0x12c0` | `0x13b0` | **`+0xf0`** |
| `__DATA_CONST.__objc_arraydata` | `0xd48` | `0xde0` | **`+0x98`** |
| `__TEXT.__objc_classname` | `0x776` | `0x7f6` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0x5460` | `0x54e0` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0xcb8` | `0xd10` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x8d1a` | `0x8d70` | **`+0x56`** |
| `__DATA_CONST.__objc_arrayobj` | `0x510` | `0x558` | **`+0x48`** |
| `__DATA.__objc_selrefs` | `0x1b00` | `0x1b40` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x42c0` | `0x4300` | **`+0x40`** |
| `__TEXT.__cstring` | `0x38f0` | `0x3922` | **`+0x32`** |
| `__DATA_CONST.__objc_classlist` | `0x1e0` | `0x1f8` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x1c0` | `0x1d8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x3a4` | `0x3b0` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x340` | `0x348` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-229.0.0.0.0
+231.40.1.0.0

-  Functions: 1598
+  Functions: 1638

-  CStrings:  2757
+  CStrings:  2770
CStrings:
+ "Could not load battery_analysis_tt80_model_bp4eym645b.mlmodelc in the bundle resource"
+ "battery_analysis_tt80_model_bp4eym645b"
+ "battery_analysis_tt80_model_bp4eym645bInput"
+ "battery_analysis_tt80_model_bp4eym645bOutput"
+ "bp4eym645b"
+ "defaultModelVersionForTarget:"
+ "isCurrentlyDrawingUnlimitedPower"
+ "persistentDomainForName:"
+ "removePersistentDomainForName:"
+ "restorePersistedDefaultsForTesting:"
+ "setPersistentDomain:forName:"
+ "snapshotPersistedDefaultsForTesting"
+ "supportedModelVersionsWithFeatures"
```
