## CIVisionFilters

> `/System/Library/CoreImage/CIVisionFilters.cifilter/CIVisionFilters`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b14` | `0x1de0` | **`+0x2cc`** |
| `__TEXT.__objc_stubs` | `0x360` | `0x460` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x380` | `0x431` | **`+0xb1`** |
| `__TEXT.__gcc_except_tab` | `0x138` | `0x1c0` | **`+0x88`** |
| `__DATA_CONST.__cfstring` | `0x240` | `0x2a0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x29a` | `0x2ec` | **`+0x52`** |
| `__DATA.__objc_selrefs` | `0x138` | `0x178` | **`+0x40`** |
| `__DATA_CONST.__objc_dictobj` | `0xa0` | `0xc8` | **`+0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0x40` | `0x50` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1653.0.0.120.2
+1657.0.0.0.0

-  CStrings:  77
+  CStrings:  88
Symbols:
+ _objc_enumerationMutation
- _objc_retain_x19
Functions:
~ sub_1510 : 704 -> 1396
~ sub_17d0 -> sub_1a84 : 148 -> 172
CStrings:
+ "Couldn't get the saliency map observation"
+ "MLNeuralEngineComputeDevice"
+ "Paravirtual"
+ "containsString:"
+ "countByEnumeratingWithState:objects:count:"
+ "device"
+ "isEqual:"
+ "metalCommandBuffer"
+ "name"
+ "setComputeDevice:forComputeStage:"
+ "supportedComputeStageDevicesAndReturnError:"
```
