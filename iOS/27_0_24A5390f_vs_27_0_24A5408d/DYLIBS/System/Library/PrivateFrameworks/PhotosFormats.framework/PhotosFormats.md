## PhotosFormats

> `/System/Library/PrivateFrameworks/PhotosFormats.framework/PhotosFormats`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd6824` | `0xd6810` | **`-0x14`** |

### Other Changes

```diff

-910.33.102.0.0
+912.0.111.0.0

+  - /System/Library/PrivateFrameworks/Portrait.framework/Portrait
Functions:
~ -[PFPosterDynamicDeviceConfiguration initWithCoder:] : 624 -> 660
~ +[PFParallaxLayoutConfiguration configurationForScreenSize:screenScale:determinedConfiguration:orientation:] : 640 -> 600
~ -[PFPosterOrientedLayout layoutByUpdatingImageSize:] : 1724 -> 1708
```
