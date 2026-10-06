## CarPlaySettings

> `/Applications/CarPlaySettings.app/CarPlaySettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd2754` | `0xd7884` | **`+0x5130`** |
| `__TEXT.__eh_frame` | `0x21a0` | `0x27c8` | **`+0x628`** |
| `__DATA_CONST.__const` | `0x5980` | `0x5cb0` | **`+0x330`** |
| `__TEXT.__swift5_typeref` | `0xf808` | `0xfa98` | **`+0x290`** |
| `__DATA.__objc_const` | `0x14aa0` | `0x14d20` | **`+0x280`** |
| `__TEXT.__const` | `0x6d24` | `0x6f94` | **`+0x270`** |
| `__TEXT.__unwind_info` | `0x3460` | `0x3620` | **`+0x1c0`** |
| `__DATA.__data` | `0x4ed8` | `0x5088` | **`+0x1b0`** |
| `__TEXT.__constg_swiftt` | `0x27a4` | `0x292c` | **`+0x188`** |
| `__DATA.__objc_data` | `0x37e0` | `0x3950` | **`+0x170`** |
| `__DATA.__bss` | `0x4738` | `0x4848` | **`+0x110`** |
| `__TEXT.__swift5_capture` | `0x14c8` | `0x15d0` | **`+0x108`** |
| `__TEXT.__objc_classname` | `0x145f` | `0x155f` | **`+0x100`** |
| `__TEXT.__cstring` | `0x4154` | `0x4244` | **`+0xf0`** |
| `__TEXT.__objc_methname` | `0x12f65` | `0x13035` | **`+0xd0`** |
| `__DATA_CONST.__got` | `0xec0` | `0xf80` | **`+0xc0`** |
| `__TEXT.__auth_stubs` | `0x3650` | `0x3710` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x193c` | `0x19f0` | **`+0xb4`** |
| `__TEXT.__objc_methlist` | `0x6154` | `0x61bc` | **`+0x68`** |
| `__DATA_CONST.__auth_got` | `0x1b38` | `0x1b98` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x9b20` | `0x9b60` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x1c83` | `0x1cc3` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x114` | `0x14c` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0x5fe2` | `0x6012` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0xe8` | `0x118` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0xbc` | `0xe8` | **`+0x2c`** |
| `__DATA_CONST.__objc_classlist` | `0x3c0` | `0x3e0` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x3491` | `0x3471` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x3f10` | `0x3f28` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x1e4` | `0x1fc` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0xd60` | `0xd68` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-574.2.0.0.0
+577.2.0.0.0

-  - /usr/lib/swift/libswiftCarPlay.dylib

-  Functions: 4797
-  Symbols:   1670
-  CStrings:  4196
+  Functions: 4892
+  Symbols:   1685
+  CStrings:  4212
Symbols:
+ _$s5CAFUI31CAFUIDevicePickerViewControllerC35resetSpinningCellAndUserInteractionyyFTj
+ _$s7SwiftUI4FontV11subheadlineACvgZ
+ _$sScT6cancelyyF
+ _$sScTMa
+ _$sScTss5NeverORs_rlE5valuexvg
+ _$sScTss5NeverORs_rlE5valuexvgTu
+ _$sScTss5NeverORszABRs_rlE11isCancelledSbvgZ
+ _$ss11AnyHashableVyABxcSHRzlufC
+ _AFIsChinaSKU
+ _kCAPackageOptionPrepareContents
+ _swift_allocateGenericClassMetadata
+ _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
+ _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_multiPayloadEnumGeneric_getEnumTag
+ _swift_initClassMetadata2
+ _swift_initStackObject
+ _swift_setDeallocating
+ _swift_task_isCancelledWithFlags
- _$s5CAFUI31CAFUIDevicePickerViewControllerC35resetSpinningCellAndUserInteractionyyF
- _$s7SwiftUI26UIViewRepresentableContextV11environmentAA17EnvironmentValuesVvg
- __swift_FORCE_LOAD_$_swiftCarPlay
CStrings:
+ "@\"NSSet\"24@0:8@\"SBHIconManager\"16"
+ "CUSTOMIZE_STYLE_FOR_DRIVE_MODE"
+ "RESET_THEME_DESCRIPTION"
+ "This will reset the gauge style, color, and wallpaper to the defaults for this drive mode."
+ "View.task @ CarPlaySettings/CARThemeLayoutPreview.swift:"
+ "_TtC15CarPlaySettings17CAPackageHostView"
+ "_TtC15CarPlaySettings25CARThemeWallpaperHostView"
+ "_TtCV15CarPlaySettings17CARThemeWallpaper20WallpaperCoordinator"
+ "_TtCV15CarPlaySettings23CARCAPackageOverlayView18PackageCoordinator"
+ "iconImagePrecacheInfosForIconManager:"
+ "id  "
+ "id value "
+ "initWithTitle:style:target:action:"
+ "loader"
+ "packageView"
+ "resolveWallpaper:options:"
+ "resolvedView"
- "Failed to load CA package: %s"
```
