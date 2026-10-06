## Categories

> `/System/Library/PrivateFrameworks/Categories.framework/Categories`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb798` | `0xb364` | **`-0x434`** |
| `__TEXT.__cstring` | `0x2e04` | `0x2f25` | **`+0x121`** |
| `__AUTH_CONST.__objc_intobj` | `—` | `0xa8` | **`+0xa8`** |
| `__AUTH_CONST.__cfstring` | `0x3780` | `0x3800` | **`+0x80`** |
| `__DATA_CONST.__objc_arraydata` | `0xab8` | `0xb30` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0x676` | `0x6db` | **`+0x65`** |
| `__TEXT.__gcc_except_tab` | `0x41c` | `0x3e4` | **`-0x38`** |
| `__DATA_CONST.__const` | `0x6e8` | `0x6c0` | **`-0x28`** |
| `__AUTH_CONST.__const` | `0x140` | `0x160` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x82c` | `0x84c` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x990` | `0x9a8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x720` | `0x738` | **`+0x18`** |
| `__DATA.__bss` | `0x60` | `0x70` | **`+0x10`** |
| `__TEXT.__const` | `0xb0` | `0xb8` | **`+0x8`** |

### Other Changes

```diff

-58.0.1.0.0
+58.1.3.0.0

-  Functions: 221
+  Functions: 222

-  CStrings:  508
+  CStrings:  515
Symbols:
+ +[CTCategory _equivalentBundleIDForDestinationScheme:fromBundleID:sourceScheme:]
+ +[CTCategory bundleIDForDeviceFamily:fromBundleID:fromDeviceFamily:]
+ +[CTCategory currentDeviceFamily]
+ +[CTCategory deviceFamilyForPlatform:]
+ +[CTCategory schemeStringForDeviceFamily:]
+ -[CTCategories bundleIDForDeviceFamily:fromBundleID:fromDeviceFamily:]
+ GCC_except_table22
+ GCC_except_table26
+ GCC_except_table35
+ GCC_except_table41
+ GCC_except_table43
+ GCC_except_table69
+ GCC_except_table94
+ _OBJC_CLASS_$_NSConstantIntegerNumber
+ ___33+[CTCategory currentDeviceFamily]_block_invoke
+ ___80+[CTCategory _equivalentBundleIDForDestinationScheme:fromBundleID:sourceScheme:]_block_invoke
+ _currentDeviceFamily.deviceFamily
+ _currentDeviceFamily.onceToken
+ _objc_retain_x4
- +[CTCategories currentIOSDevice]
- +[CTCategory itemWith:platform:array:]
- +[CTCategory schemeStringForPlatform:]
- GCC_except_table21
- GCC_except_table24
- GCC_except_table32
- GCC_except_table36
- GCC_except_table40
- GCC_except_table42
- GCC_except_table66
- GCC_except_table78
- GCC_except_table95
- ___38+[CTCategory itemWith:platform:array:]_block_invoke
- ___38+[CTCategory itemWith:platform:array:]_block_invoke_2
- ___38+[CTCategory itemWith:platform:array:]_block_invoke_3
- ___38+[CTCategory itemWith:platform:array:]_block_invoke_4
- ___38+[CTCategory itemWith:platform:array:]_block_invoke_5
- ___56+[CTCategory bundleIDForPlatform:fromBundleID:platform:]_block_invoke
- ___block_descriptor_40_e8_32r_e25_v32?0"NSString"8Q16^B24lr32l8
CStrings:
+ "%s: no scheme for device family (source %ld, destination %ld); one of them is outside CTDeviceFamily"
+ "+[CTCategory bundleIDForDeviceFamily:fromBundleID:fromDeviceFamily:]"
+ "com.apple.EmojiPoster"
+ "com.apple.GradientPoster"
+ "com.apple.PridePoster"
+ "q"
+ "tvos://com.apple.Fitness"
+ "tvos://com.apple.TVAppStore"
+ "tvos://com.apple.TVMusic"
+ "tvos://com.apple.TVPhotos"
+ "tvos://com.apple.TVSettings"
+ "tvos://com.apple.TVWatchList"
+ "tvos://com.apple.facetime"
+ "tvos://com.apple.podcasts"
- "iPhone"
- "ios://"
- "iosmac://"
- "macos://"
- "tvos://"
- "visionos://"
- "watchos://"
```
