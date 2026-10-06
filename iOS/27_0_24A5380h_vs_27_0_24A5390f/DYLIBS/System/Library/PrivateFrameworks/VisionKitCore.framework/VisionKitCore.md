## VisionKitCore

> `/System/Library/PrivateFrameworks/VisionKitCore.framework/VisionKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x4d38` | `0x43c0` | **`-0x978`** |
| `__DATA_DIRTY.__objc_data` | `0x910` | `0x1288` | **`+0x978`** |
| `__TEXT.__text` | `0xe6bd0` | `0xe70bc` | **`+0x4ec`** |
| `__AUTH_CONST.__objc_const` | `0x31120` | `0x311d0` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x4137` | `0x41a7` | **`+0x70`** |
| `__TEXT.__dlopen_cstrs` | `0x78d` | `0x7f7` | **`+0x6a`** |
| `__TEXT.__objc_methlist` | `0x105bc` | `0x10624` | **`+0x68`** |
| `__DATA.__data` | `0x20d0` | `0x2130` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x9850` | `0x9890` | **`+0x40`** |
| `__DATA_DIRTY.__bss` | `0xd8` | `0x110` | **`+0x38`** |
| `__DATA_DIRTY.__data` | `—` | `0x28` | **`+0x28`** |
| `__DATA.__bss` | `0x14b0` | `0x1490` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x3c58` | `0x3c70` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x26dc` | `0x26e8` | **`+0xc`** |
| `__AUTH.__data` | `0x11d8` | `0x11e0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4378` | `0x4380` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x113c` | `0x1140` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-341.0.0.0.0
+342.0.0.0.0

-  Functions: 6769
-  Symbols:   10667
-  CStrings:  1618
+  Functions: 6776
+  Symbols:   10673
+  CStrings:  1620
Symbols:
+ -[VKAVCaptureFrameProvider videoRotationAngle]
+ -[VKCImageAnalysisBaseView setViConfig:]
+ -[VKCImageAnalysisBaseView viConfig]
+ -[VKCImageAnalysisInteraction setViConfig:]
+ -[VKCImageAnalysisInteraction viConfig]
+ GCC_except_table203
+ GCC_except_table228
+ _OBJC_IVAR_$_VKCImageAnalysisBaseView._viConfig
- GCC_except_table199
- GCC_except_table226
CStrings:
+ "AQ1\xf0A\""
+ "Created VI Coordinator with request type: %lu, environmentBundleID: %@"
+ "Created generic VI Coordinator without config"
- "AQ1\xf01\""
```
