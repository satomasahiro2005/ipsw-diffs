## AppProtection

> `/System/Library/PrivateFrameworks/AppProtection.framework/AppProtection`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb1ddc` | `0xb382c` | **`+0x1a50`** |
| `__TEXT.__cstring` | `0x3212` | `0x33e2` | **`+0x1d0`** |
| `__TEXT.__eh_frame` | `0x2720` | `0x2840` | **`+0x120`** |
| `__AUTH_CONST.__const` | `0x72f8` | `0x73a0` | **`+0xa8`** |
| `__TEXT.__oslogstring` | `0x3e98` | `0x3f28` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0x17d8` | `0x185c` | **`+0x84`** |
| `__TEXT.__objc_methlist` | `0x16ec` | `0x1734` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x2308` | `0x2350` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x6a0` | `0x6c0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xaf0` | `0xb08` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x5b8` | `0x5c8` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x36ac` | `0x36bc` | **`+0x10`** |
| `__AUTH.__objc_data` | `0x2188` | `0x2190` | **`+0x8`** |
| `__AUTH_CONST.__objc_const` | `0x4828` | `0x4830` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x380` | `0x388` | **`+0x8`** |

### Other Changes

```diff

-55.0.0.0.0
+55.1.1.0.0

-  Functions: 3508
+  Functions: 3529

-  CStrings:  624
+  CStrings:  634
Symbols:
+ __OBJC_$_INSTANCE_METHODS_APSettingsManager(SearchAndSiriPrivate|ForAppProtectionUI|AppMigration)
- __OBJC_$_INSTANCE_METHODS_APSettingsManager(SearchAndSiriPrivate|ForAppProtectionUI)
CStrings:
+ "%s has no settings to migrate to %s"
+ "%s is already protected; only clearing the settings of %s"
+ "Cannot migrate the settings of a hidden application"
+ "cannot migrate an application's settings to itself"
+ "cannot migrate settings to an application which is not installed"
+ "errorPreventingMigratingSettings(from:to:)"
+ "migrateSettings(fromBundleIdentifier:toBundleIdentifier:completion:)"
+ "migrateSettings(fromBundleWithIdentifier:toBundleWithIdentifier:)"
+ "migrated settings from %s to %s"
+ "settings can only be migrated between applications"
```
