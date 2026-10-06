## AppleAVE2FW_H17.im4p

> `Firmware/ave/AppleAVE2FW_H17.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1140b4` | `0x114058` | **`-0x5c`** |
| `__TEXT.__const` | `0x266f4` | `0x26704` | **`+0x10`** |
| `__DATA.__data` | `0x11b0` | `0x11b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA._rtk_patchbay`
- `__TEXT.__chain_starts`
- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ __ZN14CAVCController16PipePrepareParamEPv : 4520 -> 4528
~ __ZN14CAVCController28ProcessDataFromCpusMultiCoreE9SliceType : 14844 -> 14832
~ __ZN15CHEVCController16PipePrepareParamEPv : 8660 -> 8668
~ __ZN15CHEVCController22InitEncodingParametersEPv : 24592 -> 24572
~ __ZN15CHEVCController28ProcessDataFromCpusMultiCoreEv : 13272 -> 13260
~ sub_c48f4 -> sub_c48d8 : 272 -> 268
~ __ZN10CAVEClientC2EPKcP7CObjectP12MappedMemoryPviyjjjjbP14AVE_PIODMACtrl : 3948 -> 3888
~ __Z20AVE_IOP_Config_pandav : 484 -> 488
~ _exp2f : 176 -> 168
~ sub_10a6d4 -> sub_10a674 : 384 -> 388
~ sub_113f74 -> sub_113f18 : 320 -> 328
CStrings:
+ "9013.48.1"
- "9013.45.2"
```
