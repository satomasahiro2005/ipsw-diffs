## TrackpadAndMouse

> `/System/Library/PreferenceBundles/TrackpadAndMouse.bundle/TrackpadAndMouse`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb4c8` | `0xbe24` | **`+0x95c`** |
| `__TEXT.__objc_methname` | `0x63f` | `0x4bf` | **`-0x180`** |
| `__TEXT.__objc_stubs` | `0x3a0` | `0x280` | **`-0x120`** |
| `__TEXT.__eh_frame` | `0x2bc` | `0x3a8` | **`+0xec`** |
| `__DATA.__objc_data` | `0x190` | `0xd0` | **`-0xc0`** |
| `__TEXT.__cstring` | `0x4aa` | `0x55e` | **`+0xb4`** |
| `__TEXT.__auth_stubs` | `0xdd0` | `0xd30` | **`-0xa0`** |
| `__DATA.__objc_const` | `0x2e8` | `0x258` | **`-0x90`** |
| `__DATA.__objc_selrefs` | `0x1c8` | `0x158` | **`-0x70`** |
| `__DATA_CONST.__auth_got` | `0x6f0` | `0x6a0` | **`-0x50`** |
| `__TEXT.__objc_methlist` | `0x19c` | `0x14c` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x4d8` | `0x520` | **`+0x48`** |
| `__DATA.__data` | `0x5b0` | `0x570` | **`-0x40`** |
| `__TEXT.__objc_classname` | `0xfd` | `0xbd` | **`-0x40`** |
| `__TEXT.__swift5_reflstr` | `0x1ae` | `0x16e` | **`-0x40`** |
| `__TEXT.__swift5_capture` | `0x84` | `0xbc` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x250` | `0x220` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0x268` | `0x23c` | **`-0x2c`** |
| `__TEXT.__objc_methtype` | `0x11c` | `0xf4` | **`-0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x154` | `0x12c` | **`-0x28`** |
| `__TEXT.__const` | `0x938` | `0x952` | **`+0x1a`** |
| `__TEXT.__swift5_typeref` | `0xe66` | `0xe4e` | **`-0x18`** |
| `__DATA.__bss` | `0x648` | `0x638` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x300` | `0x2f0` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x18` | `0x10` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x4` | `0xc` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x398` | `0x3a0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x20` | `0x1c` | **`-0x4`** |
| `__TEXT.__swift_as_cont` | `0x4` | `0x8` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `—` | `0x4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`

### Other Changes

```diff

-2027.0.2.0.0
+2027.0.1.0.0

-  - /System/Library/PrivateFrameworks/Preferences.framework/Preferences

-  - /usr/lib/swift/libswiftCoreMIDI.dylib

-  Functions: 281
-  Symbols:   148
-  CStrings:  129
+  Functions: 270
+  Symbols:   145
+  CStrings:  112
Symbols:
+ _objc_retain_x21
+ _objc_retain_x24
+ _swift_release_x28
+ _swift_retain_x22
+ _swift_task_create
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
+ _swift_unknownObjectRelease
- _OBJC_CLASS_$_PSViewController
- _OBJC_METACLASS_$_PSViewController
- __swift_FORCE_LOAD_$_swiftCoreMIDI
- _objc_release_x27
- _objc_retain_x19
- _objc_retain_x2
- _objc_retain_x25
- _swift_dynamicCast
- _swift_release_x1
- _swift_retain_x20
- _swift_retain_x8
CStrings:
+ "TrackpadAndMouse/TrackpadAndMouseSettings.swift"
+ "TrackpadAndMouse/TrackpadAndMouseSettingsList.swift"
+ "TrackpadAndMouse/TrackpadAndMouseSettingsListState.swift"
- "$__lazy_storage_$_listState"
- "$__lazy_storage_$_systemState"
- "@24@0:8@16"
- "@32@0:8@16@24"
- "_TtC16TrackpadAndMouse34TrackpadAndMouseSettingsController"
- "addChildViewController:"
- "addSubview:"
- "bounds"
- "didMoveToParentViewController:"
- "handleURL:withCompletion:"
- "initWithCoder:"
- "initWithNibName:bundle:"
- "setAutoresizingMask:"
- "setFrame:"
- "setTitle:"
- "traitCollection"
- "v32@0:8@16@?24"
- "view"
- "viewDidLayoutSubviews"
- "viewDidLoad"
```
