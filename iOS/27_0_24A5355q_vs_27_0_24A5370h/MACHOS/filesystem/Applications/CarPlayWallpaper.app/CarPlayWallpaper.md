## CarPlayWallpaper

> `/Applications/CarPlayWallpaper.app/CarPlayWallpaper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8cd8` | `0x8f34` | **`+0x25c`** |
| `__TEXT.__objc_stubs` | `0x10e0` | `0x1180` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x39c` | `0x42c` | **`+0x90`** |
| `__TEXT.__objc_methname` | `0x1e66` | `0x1ed2` | **`+0x6c`** |
| `__DATA_CONST.__const` | `0x4a0` | `0x508` | **`+0x68`** |
| `__TEXT.__cstring` | `0x1e8` | `0x218` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x780` | `0x7a8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x9f4` | `0xa04` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x300` | `0x308` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-571.3.0.0.0
+574.2.0.0.0

-  Functions: 244
+  Functions: 249

-  CStrings:  468
+  CStrings:  477
CStrings:
+ "No FBSScene available to signal wallpaper readiness"
+ "No scene available to signal wallpaper readiness"
+ "Signaling wallpaper ready: %{public}@"
+ "setCompletionBlock:"
+ "setIsReady:"
+ "signalWallpaperReady"
+ "updateClientSettingsWithBlock:"
+ "v16@?0@\"FBSMutableSceneClientSettings\"8"
+ "windowScene"
```
