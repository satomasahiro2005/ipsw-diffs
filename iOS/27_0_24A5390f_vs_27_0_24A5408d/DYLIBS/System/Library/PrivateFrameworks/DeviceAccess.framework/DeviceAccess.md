## DeviceAccess

> `/System/Library/PrivateFrameworks/DeviceAccess.framework/DeviceAccess`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x549e4` | `0x54bfc` | **`+0x218`** |
| `__TEXT.__cstring` | `0xa143` | `0xa223` | **`+0xe0`** |
| `__AUTH_CONST.__cfstring` | `0x35c0` | `0x3680` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x46c4` | `0x46e4` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x8060` | `0x8070` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f98` | `0x1fa8` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x40` | `0x48` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1408` | `0x1410` | **`+0x8`** |

### Other Changes

```diff

-2700.30.0.0.0
+2700.34.0.0.0

-  Functions: 2300
-  Symbols:   3349
-  CStrings:  1511
+  Functions: 2302
+  Symbols:   3351
+  CStrings:  1519
Symbols:
+ -[DADevice resolvedDisplayImageFileURL]
+ -[DADeviceRegistry requiresCompanionApp]
CStrings:
+ "### resolvedDisplayImageFileURL: container lookup failed (%d)"
+ "%@-Image.%@"
+ "-[DADevice resolvedDisplayImageFileURL]"
+ "DADevices"
+ "bluetoothDualModeAppRequired"
+ "bluetoothLEModeAppRequired"
+ "com.apple.media-device-extension"
+ "dadeviceimagedata"
```
