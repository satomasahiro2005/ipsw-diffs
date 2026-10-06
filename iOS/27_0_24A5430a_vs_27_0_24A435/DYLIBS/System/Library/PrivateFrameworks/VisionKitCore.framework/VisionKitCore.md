## VisionKitCore

> `/System/Library/PrivateFrameworks/VisionKitCore.framework/VisionKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x31200` | `0x31338` | **`+0x138`** |
| `__TEXT.__text` | `0xe7604` | `0xe7638` | **`+0x34`** |
| `__AUTH_CONST.__auth_got` | `0x1090` | `0x1088` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x98a8` | `0x98b0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1063c` | `0x10644` | **`+0x8`** |

### Other Changes

```diff

-  Symbols:   10680
+  Symbols:   10679
Symbols:
- _objc_retain_x10
Functions:
~ _OUTLINED_FUNCTION_5 -> _OUTLINED_FUNCTION_2 : 12 -> 32
~ _OUTLINED_FUNCTION_1 -> _OUTLINED_FUNCTION_5 : 32 -> 12
~ __ZNSt3__16vectorIPN10ClipperLib8PolyNodeENS_9allocatorIS3_EEE6resizeEm : 284 -> 288
~ __ZN10ClipperLib4AreaERKNSt3__16vectorINS_8IntPointENS0_9allocatorIS2_EEEE : 156 -> 160
~ __ZN10ClipperLib13ClipperOffset8DoOffsetEd : 2732 -> 2736
~ __ZN10ClipperLib9MinkowskiERKNSt3__16vectorINS_8IntPointENS0_9allocatorIS2_EEEES7_RNS1_IS5_NS3_IS5_EEEEbb : 2608 -> 2616
~ __ZNSt3__16vectorI7CGPointNS_9allocatorIS1_EEE18__insert_with_sizeB9fqe220106INS_17_ClassicAlgPolicyEPS1_S7_EENS_11__wrap_iterIS7_EENS8_IPKS1_EET0_T1_l : 492 -> 508
~ sub_1ced0c6b8 -> sub_1cf2d96dc : 3020 -> 3036
~ sub_1ced0df14 -> sub_1cf2daf48 : 256 -> 264
~ +[VKCTextElementProcessor dataDetectorElementFromVNBarcodeObservation:loggingIndex:].cold.1 : 80 -> 84
~ +[VKCTextElementProcessor dataDetectorElementFromVNBarcodeObservation:loggingIndex:].cold.2 : 60 -> 52
~ +[VKCTextElementProcessor dataDetectorElementFromVNBarcodeObservation:loggingIndex:].cold.3 : 60 -> 52
~ ___84+[VKCTextElementProcessor dataDetectorElementFromVNBarcodeObservation:loggingIndex:]_block_invoke.cold.1 : 68 -> 72
```
