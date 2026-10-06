## CameraStoragePlugin

> `/System/Library/PreferenceBundles/StoragePlugins/CameraStoragePlugin.bundle/CameraStoragePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x2e7` | `0x2f8` | **`+0x11`** |
| `__TEXT.__oslogstring` | `0x226` | `0x236` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-4162.0.0.0.3
+4167.0.0.0.2
CStrings:
+ "[CameraStoragePlugin] Creating VCC tip with %lld bytes remaining capacity"
+ "[CameraStoragePlugin] Virtual Capture Card has no remaining capacity (%lld bytes), skipping tip"
+ "_createVCCTipWithRemainingCapacity:"
+ "remainingCapacity"
- "[CameraStoragePlugin] Creating VCC tip with %lld bytes free space"
- "[CameraStoragePlugin] Virtual Capture Card has no free space (%lld bytes), skipping tip"
- "_createVCCTipWithFreeSpace:"
- "freeSize"
```
