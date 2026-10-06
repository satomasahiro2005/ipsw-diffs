## MedicationsHealthAppPluginBundle

> `/System/Library/Health/FeedItemPlugins/MedicationsHealthAppPluginBundle.healthplugin/MedicationsHealthAppPluginBundle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25f8` | `0xa58` | **`-0x1ba0`** |
| `__DATA.__bss` | `0x300` | `—` | **`-0x300`** |
| `__TEXT.__auth_stubs` | `0x430` | `0x1d0` | **`-0x260`** |
| `__TEXT.__const` | `0x330` | `0xf0` | **`-0x240`** |
| `__TEXT.__eh_frame` | `0x138` | `—` | **`-0x138`** |
| `__DATA_CONST.__auth_got` | `0x220` | `0xf0` | **`-0x130`** |
| `__DATA_CONST.__const` | `0x1c0` | `0xd0` | **`-0xf0`** |
| `__DATA_CONST.__auth_ptr` | `0x120` | `0x50` | **`-0xd0`** |
| `__TEXT.__unwind_info` | `0x150` | `0xa0` | **`-0xb0`** |
| `__DATA.__objc_data` | `0x1e0` | `0x148` | **`-0x98`** |
| `__DATA.__data` | `0x180` | `0xf0` | **`-0x90`** |
| `__TEXT.__constg_swiftt` | `0x19c` | `0x114` | **`-0x88`** |
| `__TEXT.__swift5_typeref` | `0x9a` | `0x24` | **`-0x76`** |
| `__TEXT.__swift5_capture` | `0x58` | `—` | **`-0x58`** |
| `__TEXT.__objc_classname` | `0x13d` | `0xed` | **`-0x50`** |
| `__DATA.__objc_const` | `0x120` | `0xd8` | **`-0x48`** |
| `__TEXT.__swift5_assocty` | `0x30` | `—` | **`-0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x5c` | `0x30` | **`-0x2c`** |
| `__DATA_CONST.__got` | `0x38` | `0x10` | **`-0x28`** |
| `__TEXT.__swift5_reflstr` | `0x23` | `—` | **`-0x23`** |
| `__TEXT.__objc_stubs` | `0x80` | `0x60` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x18` | `—` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `—` | **`-0x14`** |
| `__TEXT.__objc_methname` | `0x54` | `0x43` | **`-0x11`** |
| `__DATA.__common` | `0x40` | `0x30` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x28` | `0x18` | **`-0x10`** |
| `__DATA.__objc_stublist` | `0x8` | `—` | **`-0x8`** |
| `__TEXT.__objc_methtype` | `0x1e` | `0x16` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x14` | `0xc` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x8` | `—` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x4` | `—` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x4` | `—` | **`-0x4`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7
+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

-  - /System/Library/PrivateFrameworks/HealthExperienceUI.framework/HealthExperienceUI
+  - /System/Library/PrivateFrameworks/HealthAppServices.framework/HealthAppServices

-  Functions: 72
-  Symbols:   74
-  CStrings:  15
+  Functions: 21
+  Symbols:   48
+  CStrings:  12
Symbols:
+ _OBJC_CLASS_$_LSApplicationWorkspace
+ _objc_release_x21
+ _objc_release_x26
+ _swift_release_x19
+ _swift_release_x23
+ _swift_retain_x19
- _OBJC_CLASS_$_UIApplication
- _OBJC_CLASS_$__TtC32MedicationsHealthAppPluginBundle35_MedicationsHealthAppPluginDelegate
- _OBJC_METACLASS_$_NSObject
- _OBJC_METACLASS_$__TtC26MedicationsHealthAppPlugin34MedicationsHealthAppPluginDelegate
- _OBJC_METACLASS_$__TtC32MedicationsHealthAppPluginBundle35_MedicationsHealthAppPluginDelegate
- __swiftEmptyArrayStorage
- __swiftEmptyDictionarySingleton
- _objc_allocWithZone
- _objc_msgSendSuper2
- _objc_release_x27
- _objc_release_x8
- _objc_retain
- _objc_retain_x20
- _objc_retain_x21
- _swift_bridgeObjectRelease
- _swift_deallocObject
- _swift_getForeignTypeMetadata
- _swift_getObjectType
- _swift_getWitnessTable
- _swift_release_x20
- _swift_release_x22
- _swift_release_x24
- _swift_release_x25
- _swift_release_x8
- _swift_retain_x20
- _swift_retain_x22
- _swift_task_alloc
- _swift_task_create
- _swift_task_dealloc
- _swift_task_switch
- _swift_unknownObjectRelease
- _swift_unknownObjectRetain
CStrings:
+ "defaultWorkspace"
+ "hk_asyncOpenURL:"
+ "hk_canOpenURL:"
- "@16@0:8"
- "_TtC32MedicationsHealthAppPluginBundle35_MedicationsHealthAppPluginDelegate"
- "dealloc"
- "init"
- "openURL:options:completionHandler:"
- "sharedApplication"
```
