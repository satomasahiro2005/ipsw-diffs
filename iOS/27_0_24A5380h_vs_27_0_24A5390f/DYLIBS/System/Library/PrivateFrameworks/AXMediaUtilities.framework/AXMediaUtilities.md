## AXMediaUtilities

> `/System/Library/PrivateFrameworks/AXMediaUtilities.framework/AXMediaUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd43d8` | `0xd4554` | **`+0x17c`** |
| `__DATA_CONST.__got` | `0xe30` | `0xe78` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0xcc20` | `0xcc60` | **`+0x40`** |
| `__TEXT.__cstring` | `0xa679` | `0xa6aa` | **`+0x31`** |
| `__AUTH_CONST.__objc_const` | `0x14378` | `0x143a8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xb51c` | `0xb534` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x6228` | `0x6238` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xec0` | `0xec4` | **`+0x4`** |

### Other Changes

```diff

-183.0.0.0.0
+184.0.0.0.0

-  Functions: 4743
-  Symbols:   8744
-  CStrings:  2498
+  Functions: 4745
+  Symbols:   8747
+  CStrings:  2500
Symbols:
+ -[AXMBrailleEdgeDetectorOptions luminanceThreshold]
+ -[AXMBrailleEdgeDetectorOptions setLuminanceThreshold:]
+ -[AXMBrailleEdgesDetectorNode _generateResultFromImage:canvasDescription:invert:luminanceThreshold:]
+ -[AXMBrailleEdgesDetectorNode _mapLuminance:toDiscreteNumber:invert:threshold:]
+ GCC_except_table3592
+ GCC_except_table3595
+ GCC_except_table3606
+ GCC_except_table3610
+ GCC_except_table3646
+ GCC_except_table3860
+ GCC_except_table3864
+ GCC_except_table3876
+ GCC_except_table3933
+ GCC_except_table3937
+ GCC_except_table3943
+ GCC_except_table3957
+ GCC_except_table3961
+ GCC_except_table3965
+ GCC_except_table3969
+ GCC_except_table3973
+ GCC_except_table3976
+ GCC_except_table3998
+ GCC_except_table4114
+ GCC_except_table4119
+ GCC_except_table4123
+ GCC_except_table4127
+ GCC_except_table4136
+ GCC_except_table4137
+ _OBJC_IVAR_$_AXMBrailleEdgeDetectorOptions._luminanceThreshold
- -[AXMBrailleEdgesDetectorNode _generateResultFromImage:canvasDescription:invert:]
- -[AXMBrailleEdgesDetectorNode _mapLuminance:toDiscreteNumber:invert:]
- GCC_except_table3590
- GCC_except_table3593
- GCC_except_table3604
- GCC_except_table3608
- GCC_except_table3644
- GCC_except_table3858
- GCC_except_table3862
- GCC_except_table3874
- GCC_except_table3931
- GCC_except_table3935
- GCC_except_table3941
- GCC_except_table3955
- GCC_except_table3959
- GCC_except_table3963
- GCC_except_table3967
- GCC_except_table3971
- GCC_except_table3974
- GCC_except_table3996
- GCC_except_table4112
- GCC_except_table4117
- GCC_except_table4121
- GCC_except_table4125
- GCC_except_table4132
- GCC_except_table4133
CStrings:
+ "    luminanceThreshold: %.2f\n"
+ "luminanceThreshold"
```
