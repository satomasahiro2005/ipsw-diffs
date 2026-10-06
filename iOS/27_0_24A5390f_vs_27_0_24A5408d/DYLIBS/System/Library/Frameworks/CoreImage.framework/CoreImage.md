## CoreImage

> `/System/Library/Frameworks/CoreImage.framework/CoreImage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__runtimeheader` | `0xda3c` | `0x15aa4` | **`+0x8068`** |
| `__TEXT.__text` | `0x34919c` | `0x349728` | **`+0x58c`** |
| `__TEXT.__cstring` | `0x104941` | `0x1049a3` | **`+0x62`** |
| `__DATA_CONST.__const` | `0x64b0` | `0x64d8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x8e18` | `0x8e38` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x15978` | `0x15990` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xaf0` | `0xaf8` | **`+0x8`** |

### Other Changes

```diff

-1663.0.0.0.0
+1667.0.0.0.0

-  Functions: 15161
-  Symbols:   26328
-  CStrings:  8880
+  Functions: 15165
+  Symbols:   26333
+  CStrings:  8881
Symbols:
+ -[CIContext isUberShaderAvailable]
+ -[CIRAWFilter downloadResourcesWithTimeout:completionHandler:]
+ GCC_except_table202
+ GCC_except_table207
+ GCC_except_table217
+ GCC_except_table225
+ GCC_except_table232
+ GCC_except_table258
+ GCC_except_table265
+ GCC_except_table290
+ GCC_except_table301
+ GCC_except_table309
+ GCC_except_table324
+ _OBJC_CLASS_$_NSProgress
+ __ZNK2CI12MetalContext24is_uber_shader_availableEv
+ ___62-[CIRAWFilter downloadResourcesWithTimeout:completionHandler:]_block_invoke
+ ___block_descriptor_48_e8_32o40b_e5_v8?0ls32l8s40l8
- GCC_except_table178
- GCC_except_table200
- GCC_except_table206
- GCC_except_table214
- GCC_except_table224
- GCC_except_table230
- GCC_except_table257
- GCC_except_table264
- GCC_except_table287
- GCC_except_table300
- GCC_except_table308
- GCC_except_table323
CStrings:
+ "1667"
+ "commandBuffer=%p "
+ "float _saturate(float a) {\n  return max(0.0, min(1.0, a));\n}\nfloat _computeSmoothedFWidthCommon(sampler s, vec2 dc, float scale, int channel) {\n  vec2 base_coord = samplerTransform(s, dc);\n  vec2 delta_x = samplerTransform(s, dc + vec2(1.0, 0.0)) - base_coord;\n  vec2 delta_y = samplerTransform(s, dc + vec2(0.0, 1.0)) - base_coord;\n  vec4 left = sample(s, base_coord - delta_x);\n  vec4 right = sample(s, base_coord + delta_x);\n  vec4 down = sample(s, base_coord - delta_y);\n  vec4 up = sample(s, base_coord + delta_y);\n  float dfdx = (0.5 * scale) * (right[channel] - left[channel]);\n  float dfdy = (0.5 * scale) * (up[channel] - down[channel]);\n  float fwidth = abs(dfdx) + abs(dfdy);\n  return (1.0 / 1.200) * clamp(fwidth, 1e-4, 2.0);\n}\nfloat _computeSmoothedFWidthTransformed(sampler s, vec2 dc, float scale) {\n  return _computeSmoothedFWidthCommon(s, dc, scale, 0);\n}\nkernel vec4 _glassHighlight(sampler s, vec4 values0, vec4 values1, float sdfZero, vec4 color) {\n  vec2 dc = destCoord();\n  vec3 sdf = sample(s, samplerCoord(s)).xyz;\n  float height = values0.x;\n  float inset = values0.y;\n  float spread = values0.z;\n  float bias_amount = values0.w;\n  float curvature = values1.x;\n  vec2 light_dir = values1.yz;\n  float sdfScale = values1.w;\n  float distance = ((-(sdf.r - sdfZero)) * sdfScale) - inset;\n  vec2 gradient = -((sdf.gb * 2.0) - 1.0);\n  float d_norm = _saturate(distance / height);\n  float effectiveCurvature = curvature * smoothstep(1.0, 3.0, height);\n  float h = mix(1.0, 1.0 - d_norm, effectiveCurvature);\n  float w = _computeSmoothedFWidthTransformed(s, dc, sdfScale);\n  float mask = _saturate(0.5 + ((height - distance) / w));\n  mask *= _saturate(0.5 + (distance / w));\n  float alpha = h * _saturate((dot(light_dir, gradient) - spread) / max(1.0 - float(spread), 1e-4));\n  alpha = alpha / max((bias_amount * (1.0 - alpha)) + 1.0, 1e-4);\n  color *= mask * alpha;\n  return color;\n}\n"
- "1663"
- "float _saturate(float a) {\n  return max(0.0, min(1.0, a));\n}\nfloat _computeSmoothedFWidthCommon(sampler s, vec2 dc, float scale, int channel) {\n  vec2 base_coord = samplerTransform(s, dc);\n  vec2 delta_x = samplerTransform(s, dc + vec2(1.0, 0.0)) - base_coord;\n  vec2 delta_y = samplerTransform(s, dc + vec2(0.0, 1.0)) - base_coord;\n  vec4 left = sample(s, base_coord - delta_x);\n  vec4 right = sample(s, base_coord + delta_x);\n  vec4 down = sample(s, base_coord - delta_y);\n  vec4 up = sample(s, base_coord + delta_y);\n  float dfdx = (0.5 * scale) * (right[channel] - left[channel]);\n  float dfdy = (0.5 * scale) * (up[channel] - down[channel]);\n  float fwidth = abs(dfdx) + abs(dfdy);\n  return (1.0 / 1.200) * clamp(fwidth, 1e-4, 2.0);\n}\nfloat _computeSmoothedFWidthTransformed(sampler s, vec2 dc, float scale) {\n  return _computeSmoothedFWidthCommon(s, dc, scale, 0);\n}\nkernel vec4 _glassHighlight(sampler s, vec4 values0, vec4 values1, float sdfZero, vec4 color) {\n  vec2 dc = destCoord();\n  vec3 sdf = sample(s, samplerCoord(s)).xyz;\n  float height = values0.x;\n  float inset = values0.y;\n  float spread = values0.z;\n  float bias_amount = values0.w;\n  float curvature = values1.x;\n  vec2 light_dir = values1.yz;\n  float sdfScale = values1.w;\n  float distance = ((-(sdf.r - sdfZero)) * sdfScale) - inset;\n  vec2 gradient = -((sdf.gb * 2.0) - 1.0);\n  float d_norm = _saturate(distance / height);\n  float h = mix(1.0, 1.0 - d_norm, curvature);\n  float w = _computeSmoothedFWidthTransformed(s, dc, sdfScale);\n  float mask = _saturate(0.5 + ((height - distance) / w));\n  mask *= _saturate(0.5 + (distance / w));\n  float alpha = h * _saturate((dot(light_dir, gradient) - spread) / max(1.0 - float(spread), 1e-4));\n  alpha = alpha / max((bias_amount * (1.0 - alpha)) + 1.0, 1e-4);\n  color *= mask * alpha;\n  return color;\n}\n"
```
