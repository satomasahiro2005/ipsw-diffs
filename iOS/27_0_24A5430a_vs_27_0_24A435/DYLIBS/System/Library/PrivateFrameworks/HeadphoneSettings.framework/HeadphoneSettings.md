## HeadphoneSettings

> `/System/Library/PrivateFrameworks/HeadphoneSettings.framework/HeadphoneSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd3b4` | `0xd554` | **`+0x1a0`** |
| `__AUTH_CONST.__cfstring` | `0x1100` | `0x11c0` | **`+0xc0`** |
| `__TEXT.__cstring` | `0xc19` | `0xc79` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x924` | `0x954` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x548` | `0x570` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x1d8` | `0x1f8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xe0c` | `0xe24` | **`+0x18`** |
| `__DATA.__bss` | `0x298` | `0x2a8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x908` | `0x918` | **`+0x10`** |
| `__TEXT.__const` | `0x364` | `0x374` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x4b8` | `0x4c0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x508` | `0x510` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 495
-  Symbols:   688
-  CStrings:  212
+  Functions: 499
+  Symbols:   694
+  CStrings:  221
Symbols:
+ +[HPSProductUtils isShortScreenDevice]
+ +[HPSProductUtils stringForUIInterfaceOrientation:]
+ _MGIsDeviceOfType
+ ___38+[HPSProductUtils isShortScreenDevice]_block_invoke
+ _isShortScreenDevice.onceToken
+ _isShortScreenDevice.sIsShortScreenDevice
CStrings:
+ "False"
+ "HPSProductUtils: isShortScreenDevice -> %s"
+ "LandscapeLeft"
+ "LandscapeRight"
+ "Portrait"
+ "PortraitUpsideDown"
+ "True"
+ "Unknown"
+ "Unrecognized (%ld)"
```
