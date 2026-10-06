## AudioDSPManager

> `/System/Library/PrivateFrameworks/AudioDSPManager.framework/AudioDSPManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x8070` | `0x7ee0` | **`-0x190`** |
| `__DATA_DIRTY.__bss` | `0x22a0` | `0x2420` | **`+0x180`** |
| `__AUTH.__objc_data` | `0x618` | `0x4b0` | **`-0x168`** |
| `__DATA_DIRTY.__objc_data` | `0x778` | `0x8e0` | **`+0x168`** |
| `__DATA_DIRTY.__data` | `0x10e0` | `0x1220` | **`+0x140`** |
| `__DATA.__data` | `0x15d0` | `0x14b8` | **`-0x118`** |
| `__TEXT.__cstring` | `0x674e` | `0x67ae` | **`+0x60`** |
| `__TEXT.__text` | `0xc1124` | `0xc1168` | **`+0x44`** |
| `__AUTH.__data` | `0x600` | `0x5d8` | **`-0x28`** |
| `__AUTH_CONST.__const` | `0x8168` | `0x8148` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x608` | `0x5f8` | **`-0x10`** |
| `__TEXT.__const` | `0xf468` | `0xf478` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x8f0` | `0x8e0` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x7364` | `0x7370` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x15a0` | `0x1598` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x5d8` | `0x5e0` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x37f8` | `0x37f0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x3d10` | `0x3d18` | **`+0x8`** |

### Other Changes

```diff

-241.205.0.0.0
+241.206.0.0.0

-  Symbols:   4471
-  CStrings:  1251
+  Symbols:   4465
+  CStrings:  1253
Symbols:
+ -[CMDeviceStateManagerShim initWithName:]
- +[CMDeviceStateManagerShim shared]
- -[CMDeviceStateManagerShim init]
- GCC_except_table45
- __ZZ34+[CMDeviceStateManagerShim shared]E8instance
- __ZZ34+[CMDeviceStateManagerShim shared]E9onceToken
- ___34+[CMDeviceStateManagerShim shared]_block_invoke
- _objc_release_x1
CStrings:
+ "Couldn't create a device state manager client"
+ "com.apple.audio.AudioDSPManager.devicePose"
```
