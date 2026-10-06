## LocalAuthenticationPrivateUI

> `/System/Library/PrivateFrameworks/LocalAuthenticationPrivateUI.framework/LocalAuthenticationPrivateUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x780` | `0x4b0` | **`-0x2d0`** |
| `__DATA_DIRTY.__objc_data` | `0x50` | `0x320` | **`+0x2d0`** |
| `__TEXT.__text` | `0x315fc` | `0x316d8` | **`+0xdc`** |
| `__TEXT.__gcc_except_tab` | `0x37c4` | `0x3808` | **`+0x44`** |
| `__DATA.__bss` | `0x118` | `0xf0` | **`-0x28`** |
| `__DATA_DIRTY.__bss` | `—` | `0x28` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x3d8` | `0x3e0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x16b0` | `0x16b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x14a8` | `0x14b0` | **`+0x8`** |

### Other Changes

```diff

-2319.0.16.502.1
+2319.0.33.0.1

-  Symbols:   1949
+  Symbols:   1950
Symbols:
+ _MGGetLogicalDeviceDisplayCount
Functions:
~ -[LAUIPhysicalButtonView didMoveToWindow] : 320 -> 348
~ -[LAUIPhysicalButtonView interfaceOrientationDidChange:] : 516 -> 552
~ -[LAUIPhysicalButtonView updateFrame] : 1788 -> 1908
~ -[LAUIPhysicalButtonView _physicalButtonNormalizedFrame] : 4 -> 252
~ __ZN36LAUI_uniform_cubic_b_spline_renderer10renderer_t14shared_state_t6createEPU19objcproto9MTLDevice11objc_object : 2432 -> 2424
~ __ZN36LAUI_uniform_cubic_b_spline_renderer10renderer_t15remap_instancesEv : 328 -> 312
~ __ZZN12_GLOBAL__N_118face_id_animator_tC1ERN36LAUI_uniform_cubic_b_spline_renderer10renderer_tE23LAUIPearlGlyphPathStylefRKNS_15face_id_state_tEENKUlNS_10quadrant_tEE_clES8_ : 3276 -> 3204
~ __ZNSt3__16vectorIN12_GLOBAL__N_118face_id_animator_t14ring_context_tENS_9allocatorIS3_EEE26__swap_out_circular_bufferERNS_14__split_bufferIS3_RS5_EE : 376 -> 316
~ __ZNSt3__16vectorIN12_GLOBAL__N_118face_id_animator_t18quadrant_context_tENS_9allocatorIS3_EEE26__swap_out_circular_bufferERNS_14__split_bufferIS3_RS5_EE : 376 -> 336
~ __ZNSt3__134__uninitialized_allocator_relocateB9fqe220106INS_9allocatorIN36LAUI_uniform_cubic_b_spline_renderer10animator_tIDv3_fLNS2_27animator_interpolation_typeE0EEEEEPS6_EEvRT_T0_SB_SB_ : 152 -> 136
```
