## MobileStoreSettings

> `/System/Library/PreferenceBundles/MobileStoreSettings.bundle/MobileStoreSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3db0c` | `0x3d020` | **`-0xaec`** |
| `__TEXT.__swift5_typeref` | `0x3f5e` | `0x3c76` | **`-0x2e8`** |
| `__TEXT.__const` | `0x2110` | `0x1fb0` | **`-0x160`** |
| `__DATA.__bss` | `0xef8` | `0xdf8` | **`-0x100`** |
| `__DATA.__objc_data` | `0xae0` | `0xa00` | **`-0xe0`** |
| `__TEXT.__auth_stubs` | `0x1a00` | `0x1940` | **`-0xc0`** |
| `__TEXT.__oslogstring` | `0x840` | `0x8f0` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0xfa0` | `0xf00` | **`-0xa0`** |
| `__DATA_CONST.__const` | `0x1318` | `0x1288` | **`-0x90`** |
| `__DATA.__data` | `0x14f0` | `0x1470` | **`-0x80`** |
| `__DATA_CONST.__auth_ptr` | `0x608` | `0x588` | **`-0x80`** |
| `__TEXT.__constg_swiftt` | `0xaa8` | `0xa30` | **`-0x78`** |
| `__DATA.__objc_const` | `0xb98` | `0xb28` | **`-0x70`** |
| `__DATA_CONST.__auth_got` | `0xd08` | `0xca8` | **`-0x60`** |
| `__TEXT.__objc_methname` | `0x1611` | `0x15b1` | **`-0x60`** |
| `__TEXT.__swift5_reflstr` | `0x78a` | `0x72a` | **`-0x60`** |
| `__TEXT.__objc_classname` | `0x321` | `0x2d1` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0xc18` | `0xbc8` | **`-0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x4cc` | `0x488` | **`-0x44`** |
| `__TEXT.__swift5_assocty` | `0x1b8` | `0x180` | **`-0x38`** |
| `__DATA.__objc_selrefs` | `0x5f8` | `0x5c8` | **`-0x30`** |
| `__TEXT.__cstring` | `0x1104` | `0x10d4` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x48c` | `0x45c` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x530` | `0x508` | **`-0x28`** |
| `__TEXT.__swift5_capture` | `0x50c` | `0x4ec` | **`-0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x40` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x60` | `0x58` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x58` | `0x50` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-13.0.33.0.0
+13.0.36.0.0

-  Functions: 1075
-  Symbols:   244
-  CStrings:  441
+  Functions: 1044
+  Symbols:   240
+  CStrings:  434
Symbols:
+ _OBJC_CLASS_$_OBPrivacyPresenter
- _OBJC_CLASS_$_OBBundle
- _OBJC_CLASS_$_OBPrivacyCombinedController
- _OBJC_CLASS_$_UIBarButtonItem
- _OBJC_CLASS_$_UINavigationController
- _swift_retain_x1
CStrings:
+ "Can’t present the data privacy sheet because no view controller is available"
+ "Could not create OBPrivacyPresenter for the App Store and Apple Arcade privacy flow"
+ "presenterForPrivacyUnifiedAboutWithIdentifiers:"
- "MobileStoreSettings.Coordinator"
- "_TtCV19MobileStoreSettings28OnboardingPrivacyViewWrapper11Coordinator"
- "bundleWithIdentifier:"
- "dismissViewController"
- "initWithBundles:"
- "initWithRootViewController:"
- "initWithTitle:style:target:action:"
- "navigationItem"
- "onDismiss"
- "setRightBarButtonItem:"
```
