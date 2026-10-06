## Maps

> `/System/Library/Assistant/Plugins/Maps.assistantBundle/Maps`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x17d28` | `0x17e60` | **`+0x138`** |
| `__DATA_CONST.__cfstring` | `0x8300` | `0x8360` | **`+0x60`** |
| `__TEXT.__cstring` | `0x9daf` | `0x9df5` | **`+0x46`** |
| `__TEXT.__text` | `0x144b8` | `0x144dc` | **`+0x24`** |
| `__DATA_CONST.__objc_intobj` | `0x7f8` | `0x810` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2972.30.6.12.16
+2972.30.6.12.32

-  Functions: 1329
-  Symbols:   1286
-  CStrings:  1966
+  Functions: 1332
+  Symbols:   1289
+  CStrings:  1969
Symbols:
+ _MapsConfig_DebugShowSwiftUIDebugFrames
+ _MapsConfig_LinwoodPunchInPrewarmMapView
+ _MapsConfig_NavigationDisableRestore
+ _MapsConfig_ParkedCarDonationFromNavd
- _MapsConfig_NavigationDisableRestoreWhenDebugging
CStrings:
+ "DebugShowSwiftUIDebugFrames"
+ "LinwoodPunchInPrewarmMapView"
+ "NavigationDisableRestore"
+ "ParkedCarDonationFromNavd"
- "NavigationDisableRestoreWhenDebugging"
```
