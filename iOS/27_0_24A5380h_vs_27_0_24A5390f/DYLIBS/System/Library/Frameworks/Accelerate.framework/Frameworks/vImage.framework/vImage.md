## vImage

> `/System/Library/Frameworks/Accelerate.framework/Frameworks/vImage.framework/vImage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28a850` | `0x292ee4` | **`+0x8694`** |
| `__TEXT.__eh_frame` | `0x1a50` | `0x1ed8` | **`+0x488`** |
| `__AUTH_CONST.__const` | `0xbd88` | `0xbf88` | **`+0x200`** |
| `__TEXT.__unwind_info` | `0x22f0` | `0x2430` | **`+0x140`** |
| `__TEXT.__cstring` | `0x6ac7` | `0x6acb` | **`+0x4`** |

### Other Changes

```diff

-650.0.0.0.0
+650.0.1.0.0

-  Functions: 3334
-  Symbols:   4266
+  Functions: 3409
+  Symbols:   4342
Symbols:
+ _rpad_axis_fill
+ _rpad_axis_max_taps
+ _rpad_axis_zones
+ _rpad_compute_interior_row
+ _rpad_core
+ _rpad_fused_1_1_0
+ _rpad_fused_1_1_1
+ _rpad_fused_1_2_0
+ _rpad_fused_1_2_1
+ _rpad_fused_1_3_0
+ _rpad_fused_1_3_1
+ _rpad_fused_1_4_0
+ _rpad_fused_1_4_1
+ _rpad_fused_1_5_0
+ _rpad_fused_1_5_1
+ _rpad_fused_1_6_0
+ _rpad_fused_1_6_1
+ _rpad_fused_1_7_0
+ _rpad_fused_1_7_1
+ _rpad_fused_1_8_0
+ _rpad_fused_1_8_1
+ _rpad_fused_2_1_0
+ _rpad_fused_2_1_1
+ _rpad_fused_2_2_0
+ _rpad_fused_2_2_1
+ _rpad_fused_2_3_0
+ _rpad_fused_2_3_1
+ _rpad_fused_2_4_0
+ _rpad_fused_2_4_1
+ _rpad_fused_2_5_0
+ _rpad_fused_2_5_1
+ _rpad_fused_2_6_0
+ _rpad_fused_2_6_1
+ _rpad_fused_2_7_0
+ _rpad_fused_2_7_1
+ _rpad_fused_2_8_0
+ _rpad_fused_2_8_1
+ _rpad_fused_3_1_0
+ _rpad_fused_3_1_1
+ _rpad_fused_3_2_0
+ _rpad_fused_3_2_1
+ _rpad_fused_3_3_0
+ _rpad_fused_3_3_1
+ _rpad_fused_3_4_0
+ _rpad_fused_3_4_1
+ _rpad_fused_3_5_0
+ _rpad_fused_3_5_1
+ _rpad_fused_3_6_0
+ _rpad_fused_3_6_1
+ _rpad_fused_3_7_0
+ _rpad_fused_3_7_1
+ _rpad_fused_3_8_0
+ _rpad_fused_3_8_1
+ _rpad_fused_4_1_0
+ _rpad_fused_4_1_1
+ _rpad_fused_4_2_0
+ _rpad_fused_4_2_1
+ _rpad_fused_4_3_0
+ _rpad_fused_4_3_1
+ _rpad_fused_4_4_0
+ _rpad_fused_4_4_1
+ _rpad_fused_4_5_0
+ _rpad_fused_4_5_1
+ _rpad_fused_4_6_0
+ _rpad_fused_4_6_1
+ _rpad_fused_4_7_0
+ _rpad_fused_4_7_1
+ _rpad_fused_4_8_0
+ _rpad_fused_4_8_1
+ _rpad_fused_table
+ _rpad_scalar_pixel
+ _rpad_xgather_build
+ _vImageResizeFaceID_Planar16U
+ _vImageResizeFaceID_Planar8toPlanar16U
+ _vImageResizeWithPaddingFaceID_Planar16U
+ _vImageResizeWithPaddingFaceID_Planar8toPlanar16U
CStrings:
+ "650.0.1"
- "650"
```
