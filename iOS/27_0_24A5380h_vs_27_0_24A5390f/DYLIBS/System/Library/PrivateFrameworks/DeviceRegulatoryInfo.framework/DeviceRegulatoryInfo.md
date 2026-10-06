## DeviceRegulatoryInfo

> `/System/Library/PrivateFrameworks/DeviceRegulatoryInfo.framework/DeviceRegulatoryInfo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16590` | `0x18224` | **`+0x1c94`** |
| `__AUTH_CONST.__const` | `0x610` | `0x850` | **`+0x240`** |
| `__TEXT.__const` | `0x968` | `0xb14` | **`+0x1ac`** |
| `__TEXT.__oslogstring` | `0x7a7` | `0x907` | **`+0x160`** |
| `__AUTH_CONST.__objc_const` | `0x3a8` | `0x4f0` | **`+0x148`** |
| `__AUTH.__data` | `0x370` | `0x4b0` | **`+0x140`** |
| `__TEXT.__constg_swiftt` | `0x244` | `0x340` | **`+0xfc`** |
| `__TEXT.__cstring` | `0x3c7` | `0x497` | **`+0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0x208` | `0x298` | **`+0x90`** |
| `__AUTH_CONST.__auth_got` | `0x5f8` | `0x680` | **`+0x88`** |
| `__TEXT.__unwind_info` | `0x500` | `0x548` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x310` | `0x34c` | **`+0x3c`** |
| `__DATA.__data` | `0x2f0` | `0x320` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x140` | `0x168` | **`+0x28`** |
| `__DATA.__common` | `0x80` | `0xa0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x2cc` | `0x2ec` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x34` | `0x4c` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x64` | `0x78` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x20` | `0x30` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xa8` | `0xb8` | **`+0x10`** |
| `__DATA_CONST.__const` | `0xb0` | `0xb8` | **`+0x8`** |

### Other Changes

```diff

-2027.0.1.0.0
+2027.0.2.0.0

+  - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics
+  - /System/Library/Frameworks/CoreText.framework/CoreText

+  - /System/Library/PrivateFrameworks/UIFoundation.framework/UIFoundation

+  - /usr/lib/swift/libswiftCoreAudio.dylib

+  - /usr/lib/swift/libswift_DarwinFoundation1.dylib

-  Functions: 334
-  Symbols:   273
-  CStrings:  67
+  Functions: 371
+  Symbols:   307
+  CStrings:  79
Symbols:
+ _CGDataProviderCreateWithURL
+ _CGFontCopyPostScriptName
+ _CGFontCreateWithDataProvider
+ _CTFontCreateWithName
+ _CTFontManagerRegisterGraphicsFont
+ _OBJC_CLASS_$_NSJSONSerialization
+ _OBJC_CLASS_$_UIFont
+ _OBJC_CLASS_$_UIImage
+ __CTFontCreateWithName
+ __DATA__TtC20DeviceRegulatoryInfo26DeviceRegulatoryAttributes
+ __DATA__TtC20DeviceRegulatoryInfoP33_883CB35E0201CD7F6BF03A3CE998632419ResourceBundleClass
+ __IVARS__TtC20DeviceRegulatoryInfo26DeviceRegulatoryAttributes
+ __METACLASS_DATA__TtC20DeviceRegulatoryInfo26DeviceRegulatoryAttributes
+ __METACLASS_DATA__TtC20DeviceRegulatoryInfoP33_883CB35E0201CD7F6BF03A3CE998632419ResourceBundleClass
+ ___swift_closure_destructor.37Tm
+ ___swift_memcpy32_8
+ __swift_FORCE_LOAD_$_swiftCoreAudio
+ __swift_FORCE_LOAD_$_swiftCoreAudio_$_DeviceRegulatoryInfo
+ _chmod
+ _container_system_group_path_for_identifier
+ _free
+ _swift_getObjCClassFromMetadata
+ _swift_release_n
+ _swift_release_x26
+ _symbolic SDySSypG
+ _symbolic _____ 20DeviceRegulatoryInfo0aB10AttributesC
+ _symbolic _____ 20DeviceRegulatoryInfo0aB10AttributesC8MIITDataV
+ _symbolic _____ 20DeviceRegulatoryInfo19ResourceBundleClass33_883CB35E0201CD7F6BF03A3CE9986324LLC
+ _symbolic _____ 20DeviceRegulatoryInfo29ChinaMIITBlueStickerResourcesO
+ _symbolic _____ 20DeviceRegulatoryInfo30ChinaMIITBlueStickerAttributesO
+ _symbolic _____ So17container_error_ta
+ _symbolic _____ s6UInt64V
+ _symbolic _____Sg 20DeviceRegulatoryInfo0aB10AttributesC8MIITDataV
+ _type_layout_string 20DeviceRegulatoryInfo0aB10AttributesC8MIITDataV
+ _type_layout_string So17container_error_ta
- ___swift_closure_destructor.35Tm
CStrings:
+ "ChinaBluesticker"
+ "ChinaGreensticker"
+ "Failed to resolve regulatory system group path, error: %llu"
+ "Failed to set permissions on regulatory system group path, errno: %d"
+ "Invalid MIIT format in regulatory plist: %s"
+ "MIIT e-label: label=%{public}s nal=%{public}s"
+ "No MIIT entry in regulatory plist"
+ "Regulatory plist unavailable or missing RegulatoryInfo"
+ "RegulatoryAttributes"
+ "RegulatoryImages"
+ "regulatory_images.plist"
+ "systemgroup.com.apple.regulatory_images"
```
