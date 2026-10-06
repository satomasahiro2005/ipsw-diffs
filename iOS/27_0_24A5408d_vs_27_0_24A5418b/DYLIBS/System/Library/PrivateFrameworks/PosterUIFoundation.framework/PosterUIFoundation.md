## PosterUIFoundation

> `/System/Library/PrivateFrameworks/PosterUIFoundation.framework/PosterUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x94d08` | `0x950a8` | **`+0x3a0`** |
| `__AUTH_CONST.__objc_const` | `0x1efb0` | `0x1f038` | **`+0x88`** |
| `__TEXT.__objc_methlist` | `0xab7c` | `0xabdc` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x7fc0` | `0x8000` | **`+0x40`** |
| `__TEXT.__cstring` | `0x6783` | `0x67b3` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x3a21` | `0x3a51` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x5910` | `0x5930` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x17ac` | `0x17bc` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x29e0` | `0x29e8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xbe0` | `0xbe4` | **`+0x4`** |

### Other Changes

```diff

-355.0.5.0.0
+355.0.8.0.0

-  Functions: 4155
-  Symbols:   7425
-  CStrings:  1504
+  Functions: 4161
+  Symbols:   7431
+  CStrings:  1507
Symbols:
+ -[FBSMutableSceneSettings(PosterUIFoundation) pui_setRenderSessionTimeoutInterval:]
+ -[FBSSceneSettings(PosterUIFoundation) pui_renderSessionTimeoutInterval]
+ -[PUIPosterSnapshotHostConfigurationDescriptor captureTimeoutInterval]
+ -[PUIPosterSnapshotHostConfigurationDescriptor copyWithCaptureTimeoutInterval:]
+ -[PUIPosterSnapshotHostConfigurationDescriptor initWithHostWorkQueue:waitUntilReady:inProcessSnapshot:abortsIfBacklightNotFull:captureTimeoutInterval:]
+ _OBJC_IVAR_$_PUIPosterSnapshotHostConfigurationDescriptor._captureTimeoutInterval
+ _PUIPosterSnapshotDefaultCaptureTimeoutInterval
- -[PUIPosterSnapshotHostConfigurationDescriptor initWithHostWorkQueue:waitUntilReady:inProcessSnapshot:abortsIfBacklightNotFull:]
CStrings:
+ "(%p) waiting up to %.1fs for scene readiness"
+ "_captureTimeoutInterval"
+ "captureTimeoutInterval"
```
