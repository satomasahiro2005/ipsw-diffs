## AXAggregateStatisticsServer

> `/System/Library/AccessibilityBundles/AXAggregateStatisticsServer.axuiservice/AXAggregateStatisticsServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfb18` | `0xfed0` | **`+0x3b8`** |
| `__TEXT.__cstring` | `0x3428` | `0x3532` | **`+0x10a`** |
| `__DATA_CONST.__cfstring` | `0x3080` | `0x3140` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x17af` | `0x183b` | **`+0x8c`** |
| `__TEXT.__objc_stubs` | `0x1980` | `0x1a00` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x15d` | `0x1a6` | **`+0x49`** |
| `__DATA.__objc_selrefs` | `0x780` | `0x7a0` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x2fe` | `0x30f` | **`+0x11`** |
| `__TEXT.__objc_methlist` | `0x364` | `0x374` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0

-  Functions: 239
+  Functions: 242

-  CStrings:  697
+  CStrings:  709
CStrings:
+ "Resetting Ask VQA daily invocation count for key %{public}@ after rollup"
+ "_logVqaInvocationsForKey:eventName:magnifierDefaults:"
+ "accessibility.switchcontrol.facegestures.enable"
+ "com.apple.accessibility.liverecognition.vqa.dailyinvocations"
+ "com.apple.accessibility.magnifier.vqa.dailyinvocations"
+ "configuredEyeTrackingFaceGestures"
+ "invocationCount"
+ "isEyeTrackingFaceGesturesEnabled"
+ "liveRecognitionVqaInvocationCountForAnalytics"
+ "magnifierVqaInvocationCountForAnalytics"
+ "setInteger:forKey:"
+ "v40@0:8@16@24@32"
```
