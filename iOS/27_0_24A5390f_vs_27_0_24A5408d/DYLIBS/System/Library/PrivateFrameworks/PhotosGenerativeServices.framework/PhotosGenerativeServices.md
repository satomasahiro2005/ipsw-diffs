## PhotosGenerativeServices

> `/System/Library/PrivateFrameworks/PhotosGenerativeServices.framework/PhotosGenerativeServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x70d4` | `0x6714` | **`-0x9c0`** |
| `__TEXT.__text` | `0xafcfc` | `0xafa88` | **`-0x274`** |
| `__AUTH_CONST.__const` | `0x5ba0` | `0x5cb8` | **`+0x118`** |
| `__TEXT.__const` | `0x6a30` | `0x6ad0` | **`+0xa0`** |
| `__AUTH.__data` | `0x88` | `0x120` | **`+0x98`** |
| `__DATA_DIRTY.__objc_data` | `0xad0` | `0xa70` | **`-0x60`** |
| `__DATA.__data` | `0x1850` | `0x1810` | **`-0x40`** |
| `__TEXT.__swift5_capture` | `0x710` | `0x750` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x1f94` | `0x1fd4` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x37b0` | `0x37e8` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0x5e20` | `0x5e58` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x17fd` | `0x17cd` | **`-0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x1038` | `0x1060` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x13a0` | `0x13b8` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x1be0` | `0x1bd0` | **`-0x10`** |
| `__TEXT.__constg_swiftt` | `0x1f4c` | `0x1f5c` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x15ac` | `0x159c` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x2da8` | `0x2db8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x158` | `0x160` | **`+0x8`** |
| `__TEXT.__swift5_fieldmd` | `0x236c` | `0x2374` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x2b4` | `0x2bc` | **`+0x8`** |

### Other Changes

```diff

-910.33.102.0.0
+912.0.111.0.0

-  Functions: 4992
-  Symbols:   1628
-  CStrings:  565
+  Functions: 4981
+  Symbols:   1638
+  CStrings:  558
Symbols:
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_NUOpaqueDescriptor
+ __DATA__TtC24PhotosGenerativeServices21PGSSafetyDebugCapture
+ __METACLASS_DATA__TtC24PhotosGenerativeServices21PGSSafetyDebugCapture
+ _symbolic _____ 24PhotosGenerativeServices20PGSBlockedGenerationV
+ _symbolic _____ 24PhotosGenerativeServices21PGSSafetyDebugCaptureC
+ _symbolic _____Ieghn_ 24PhotosGenerativeServices20PGSBlockedGenerationV
+ _symbolic _____ytIeghnr_ 24PhotosGenerativeServices20PGSBlockedGenerationV
+ _symbolic _____yy_____YbcSg_____G s13ManagedBufferCsRi__rlE 24PhotosGenerativeServices20PGSBlockedGenerationV So16os_unfair_lock_sV
+ _type_layout_string 24PhotosGenerativeServices20PGSBlockedGenerationV
CStrings:
+ "_flexRangeProperties"
+ "dividePipeline:<flexRangeProperties"
+ "flexRangeProperties"
+ "kernel vec4 gainMapMultiply(__sample im, __sample gm, float f)\n{\n  float3 color = log2(1.0 + im.rgb);\n  float3 gain = log2(1.0 + gm.rgb);\n  float3 light = mix(gain, color, f);\n  light = exp2(light) - 1.0;\n  return vec4(light, 1.0);\n}"
+ "kernel vec4 lightMapDivide(__sample im, __sample lm, float2 a)\n{\n  float3 color = log2(1.0 + im.rgb);\n  float3 light = log2(1.0 + lm.rgb);\n  float3 glog2 = a.x * light + a.y * color;\n  float3 gain = exp2(glog2) - 1.0;\n  return vec4(gain, 1.0);\n}"
- "dividePipeline:<mixFactor"
- "dividePipeline:<preserveColor"
- "kernel vec4 gainMapMultiply(__sample im, __sample gm)\n{\n  const float3 weq = float3(1.0/3.0, 1.0/3.0, 1.0/3.0);\n  float luma = dot(im.rgb, weq);\n  float maxRGB = max(max(im.r, im.g), im.b);\n  luma = 0.5 * (luma + maxRGB);\n  float gain = gm.r;\n  const float e = 0.01;\n  luma = (1 - e) * luma + e;\n  gain = (1 - e) * gain + e;\n  float light = gain * luma;\n  return vec4(light, light, light, 1.0);\n}"
- "kernel vec4 gainMapMultiply(__sample im, __sample gm, float f)\n{\n  const float3 weq = float3(1.0/3.0, 1.0/3.0, 1.0/3.0);\n  float luma = dot(im.rgb, weq);\n  float maxRGB = max(max(im.r, im.g), im.b);\n  luma = 0.5 * (luma + maxRGB);\n  luma = log2(1.0 + luma);\n  float gain = log2(1.0 + gm.r);\n  float light = mix(gain, luma, f);\n  light = exp2(light) - 1.0;\n  return vec4(light, light, light, 1.0);\n}"
- "kernel vec4 gainMapMultiplyRGB(__sample im, __sample gm)\n{\n  const float e = 0.01;\n  float3 color = (1 - e) * im.rgb + e;\n  float3 gain = (1 - e) * gm.rgb + e;\n  float3 light = gain * color;\n  return vec4(light, 1.0);\n}"
- "kernel vec4 gainMapMultiplyRGB(__sample im, __sample gm, float f)\n{\n  float3 color = log2(1.0 + im.rgb);\n  float3 gain = log2(1.0 + gm.rgb);\n  float3 light = mix(gain, color, f);\n  light = exp2(light) - 1.0;\n  return vec4(light, 1.0);\n}"
- "kernel vec4 lightMapDivide(__sample im, __sample lm)\n{\n  const float3 weq = float3(1.0/3.0, 1.0/3.0, 1.0/3.0);\n  float luma = dot(im.rgb, weq);\n  float maxRGB = max(max(im.r, im.g), im.b);\n  luma = 0.5 * (luma + maxRGB);\n  float light = lm.r;\n  light = min(light, luma);\n  const float e = 0.01;\n  luma = (1.0 - e) * luma + e;\n  float gain = light/luma;\n  gain = (gain - e)/(1.0 - e);\n  return vec4(gain, gain, gain, 1.0);\n}"
- "kernel vec4 lightMapDivide(__sample im, __sample lm, float2 a)\n{\n  const float3 weq = float3(1.0/3.0, 1.0/3.0, 1.0/3.0);\n  float luma = dot(im.rgb, weq);\n  float maxRGB = max(max(im.r, im.g), im.b);\n  luma = 0.5 * (luma + maxRGB);\n  luma = log2(1.0 + luma);\n  float light = dot(lm.rgb, weq);\n  light = log2(1.0 +light);\n  float glog2 = a.x * light + a.y * luma;\n  float g = exp2(glog2) - 1.0;\n  return vec4(g, g, g, 1.0);\n}"
- "kernel vec4 lightMapDivideRGB(__sample im, __sample lm)\n{\n  const float3 weq = float3(1.0/3.0, 1.0/3.0, 1.0/3.0);\n  float iml = dot(im.rgb, weq);\n  float imx = max(max(im.r, im.g), im.b);\n  float luma = 0.5 * (iml + imx);\n  float lml = dot(lm.rgb, weq);\n  float lmx = max(max(lm.r, lm.g), lm.b);\n  float light = 0.5 * (lml + lmx);\n  light = min(light, luma);\n  const float e = 0.01;\n  luma = (1 - e) * luma + e;\n  float gain = light/luma;\n  gain = (gain - e)/(1 - e);\n  return vec4(gain, gain, gain, 1.0);\n}"
- "kernel vec4 lightMapDivideRGB(__sample im, __sample lm, float2 a)\n{\n  float3 color = log2(1.0 + im.rgb);\n  float3 light = log2(1.0 + lm.rgb);\n  float3 glog2 = a.x * light + a.y * color;\n  float3 gain = exp2(glog2) - 1.0;\n  const float3 weq = float3(1.0/3.0, 1.0/3.0, 1.0/3.0);\n  float g = dot(gain, weq);\n  return vec4(g, g, g, 1.0);\n}"
- "multiplyPipeline:<mixFactor"
- "multiplyPipeline:<preserveColor"
```
