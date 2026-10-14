## Safety

> `/System/Library/Health/FeedItemPlugins/Safety.healthplugin/Safety`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb3168` | `0xb9b5c` | **`+0x69f4`** |
| `__DATA.__bss` | `0x6e80` | `0x7600` | **`+0x780`** |
| `__TEXT.__const` | `0x7054` | `0x75c4` | **`+0x570`** |
| `__AUTH_CONST.__objc_const` | `0x47e0` | `0x4b90` | **`+0x3b0`** |
| `__TEXT.__cstring` | `0x37b8` | `0x3aa8` | **`+0x2f0`** |
| `__AUTH.__data` | `0x650` | `0x8e0` | **`+0x290`** |
| `__AUTH.__objc_data` | `0x1550` | `0x1748` | **`+0x1f8`** |
| `__TEXT.__eh_frame` | `0x1ff0` | `0x21c0` | **`+0x1d0`** |
| `__DATA.__data` | `0x13a8` | `0x1568` | **`+0x1c0`** |
| `__TEXT.__unwind_info` | `0x2660` | `0x27f0` | **`+0x190`** |
| `__TEXT.__constg_swiftt` | `0x3130` | `0x3288` | **`+0x158`** |
| `__TEXT.__oslogstring` | `0x253f` | `0x266f` | **`+0x130`** |
| `__TEXT.__swift5_fieldmd` | `0x1cdc` | `0x1dc8` | **`+0xec`** |
| `__TEXT.__swift5_reflstr` | `0x1cd9` | `0x1db9` | **`+0xe0`** |
| `__AUTH_CONST.__const` | `0x3428` | `0x34f0` | **`+0xc8`** |
| `__TEXT.__swift5_typeref` | `0x1d96` | `0x1e56` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x96c` | `0x9ec` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x1a10` | `0x1a80` | **`+0x70`** |
| `__TEXT.__swift5_assocty` | `0x540` | `0x5b0` | **`+0x70`** |
| `__DATA.__common` | `0xb8` | `0x118` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0xb74` | `0xbc0` | **`+0x4c`** |
| `__TEXT.__swift5_proto` | `0x5ec` | `0x628` | **`+0x3c`** |
| `__DATA_CONST.__objc_selrefs` | `0xb18` | `0xb40` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x220` | `0x240` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0xec` | `0x104` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x270` | `0x284` | **`+0x14`** |
| `__DATA_CONST.__objc_protolist` | `0xa0` | `0xb0` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x98` | `0xa4` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x6c` | `0x78` | **`+0xc`** |
| `__DATA.__objc_stublist` | `0x80` | `0x88` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x50` | `0x58` | **`+0x8`** |

### Other Changes

```diff

-7027.1.54.2.3
+7027.1.56.2.9

-  Functions: 3164
-  Symbols:   330
-  CStrings:  479
+  Functions: 3289
+  Symbols:   333
+  CStrings:  499
Symbols:
+ _OBJC_CLASS_$_NSError
+ _kHKHAKeyCompletedBuddyOniPadVersionAI
+ _kHKHAKeyCompletedBuddyVersionAI
CStrings:
+ "%{public}s Could not save dismissal: %{public}s"
+ "%{public}s viewDidLoad"
+ "IntelligentHealthAppUpdateState"
+ "IntelligentHealthAppUpdateTile"
+ "Safety.IntelligentHealthAppUpdateTileView"
+ "Safety/IntelligentHealthAppUpdateTileView.swift"
+ "Safety/IntelligentHealthAppUpdateViewController.swift"
+ "[%{public}s] Couldn't read the dismissal state: %{public}@"
+ "[%{public}s] Database locked, retrying when unlocked"
+ "[%{public}s] Run, isEligible: %{bool,public}d, isOmakaseEnabled: %{bool,public}d"
+ "_createCheckedThrowingContinuation(_:)"
+ "com.apple.health.safety.intelligent.health.app.update"
+ "com.apple.health.safety.intelligentHealthAppOnboardingVersion"
+ "com.apple.health.safety.intelligentHealthAppUpdateDismissal"
+ "intelligentHealthAppUpdateDismissal"
+ "intelligent_health_app_update_description"
+ "intelligent_health_app_update_header_title"
+ "intelligent_health_app_update_icon"
+ "intelligent_health_app_update_title"
+ "safety.intelligent.health.app.update"
```
