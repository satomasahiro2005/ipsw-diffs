## CarPlaySettings

> `/Applications/CarPlaySettings.app/CarPlaySettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd7884` | `0xd94d8` | **`+0x1c54`** |
| `__TEXT.__oslogstring` | `0x3471` | `0x3841` | **`+0x3d0`** |
| `__TEXT.__cstring` | `0x4244` | `0x4124` | **`-0x120`** |
| `__DATA.__bss` | `0x4848` | `0x4948` | **`+0x100`** |
| `__TEXT.__const` | `0x6f94` | `0x7034` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x3710` | `0x3760` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x5cb0` | `0x5cf8` | **`+0x48`** |
| `__TEXT.__objc_methname` | `0x13035` | `0x13075` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x1b98` | `0x1bc0` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x292c` | `0x2954` | **`+0x28`** |
| `__DATA.__objc_const` | `0x14d20` | `0x14d40` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x61bc` | `0x61d4` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x778` | `0x790` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0xb4` | `0xc8` | **`+0x14`** |
| `__DATA.__data` | `0x5088` | `0x5078` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x3f28` | `0x3f38` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xf80` | `0xf90` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x15d0` | `0x15e0` | **`+0x10`** |
| `__DATA.__objc_data` | `0x3950` | `0x3958` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xd68` | `0xd70` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1f0` | `0x1f8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1fc` | `0x204` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3620` | `0x3628` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-577.2.0.0.0
+580.0.0.0.0

-  Functions: 4892
-  Symbols:   1685
-  CStrings:  4212
+  Functions: 4896
+  Symbols:   1691
+  CStrings:  4217
Symbols:
+ _$s13CarAssetUtils22CAUAssetLibraryManagerC5CAFUIE011fetchCustomA5Image5named13isTransparentSo7UIImageCSgSS_SbtF
+ _$s5CAFUI22CAFUIImageArchiveAssetV05imageC10IdentifierSSSgvg
+ _$s5CAFUI22CAFUIImageArchiveAssetV8rawValueACSS_tcfC
+ _$s5CAFUI22CAFUIImageArchiveAssetVMa
+ _$sSSs23CustomStringConvertiblesWP
+ _$sSq14CarPlayAssetUIs23CustomStringConvertibleRzlE11descriptionSSvg
CStrings:
+ "Failed to find center console: display present (id: %{public}s) but no themeData entry - themeData keys: %{public}s"
+ "Failed to find center console: no display with displayType == .centerConsole - displays: %{public}s, themeData keys: %{public}s"
+ "Failed to find cluster data: cluster display present (id: %{public}s) but no themeData entry - themeData keys: %{public}s"
+ "Failed to find cluster data: no display with displayType == .cluster - displays: %{public}s, themeData keys: %{public}s"
+ "Failed to find matching wallpaper for display %{public}s: %{public}s"
+ "Failed to find theme data for required displays - required: [%{public}s, %{public}s], themeData keys: %{public}s"
+ "Failed to load current wallpaper for display %{public}s - currentLayoutID: %{public}s, currentWallpaperID: %{public}s"
+ "[AmbientLight] CARThemeManagerData.update: display=%{public}s palette=%{public}s ambientSync=%{public}s"
+ "clusterThemeManagerDidFinishLoading - displays: %{public}s, themeData keys: %{public}s"
+ "createLayoutSelector called - displays: %{public}s, themeData keys: %{public}s"
+ "setSystemPrefersReducedResourceUsage:"
+ "systemPrefersReducedResourceUsage"
- "Failed to find center console"
- "Failed to find cluster data"
- "Failed to find matching wallpaper for display %s: %s"
- "Failed to find theme data for required displays."
- "Failed to load current wallpaper"
- "[AmbientLight] CARThemeManagerData.update: display=%{public}@ palette=%{public}@ ambientSync=%{public}@"
- "clusterThemeManagerDidFinishLoading - displays count: %{public}ld, themeData keys: %{public}s"
```
