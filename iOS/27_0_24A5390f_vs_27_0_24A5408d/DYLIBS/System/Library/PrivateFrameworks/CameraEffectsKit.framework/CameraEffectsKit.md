## CameraEffectsKit

> `/System/Library/PrivateFrameworks/CameraEffectsKit.framework/CameraEffectsKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x100868` | `0x1008fc` | **`+0x94`** |
| `__TEXT.__oslogstring` | `0x81e0` | `0x81fd` | **`+0x1d`** |

### Other Changes

```diff

-6312.0.5.0.0
+6312.0.6.0.0

-  Functions: 7130
-  Symbols:   12092
-  CStrings:  1755
+  Functions: 7131
+  Symbols:   12090
+  CStrings:  1756
Symbols:
- ___109-[JFXVideoCameraController JFX_configureCaptureSesstionForPosition:applyFFCZoom:configureLockedCamera:error:]_block_invoke_3
- ___109-[JFXVideoCameraController JFX_configureCaptureSesstionForPosition:applyFFCZoom:configureLockedCamera:error:]_block_invoke_4
Functions:
~ ___109-[JFXVideoCameraController JFX_configureCaptureSesstionForPosition:applyFFCZoom:configureLockedCamera:error:]_block_invoke_2 : 612 -> 652
~ -[UIDevice(JFX) jfx_hasDepthCapableCamera] : 144 -> 156
~ -[UIDevice(JFX) jfx_hasTrueDepthFrontCamera] : 144 -> 156
~ ___109-[JFXVideoCameraController JFX_configureCaptureSesstionForPosition:applyFFCZoom:configureLockedCamera:error:]_block_invoke_2.cold.1 : 96 -> 84
+ ___109-[JFXVideoCameraController JFX_configureCaptureSesstionForPosition:applyFFCZoom:configureLockedCamera:error:]_block_invoke_2.cold.2
CStrings:
+ "Cannot setup depth camera %@"
```
