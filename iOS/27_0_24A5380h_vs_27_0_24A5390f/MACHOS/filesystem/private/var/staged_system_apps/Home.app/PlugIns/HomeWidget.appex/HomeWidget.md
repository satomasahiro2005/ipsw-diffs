## HomeWidget

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeWidget.appex/HomeWidget`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9de60` | `0x9ccdc` | **`-0x1184`** |
| `__TEXT.__eh_frame` | `0x31d4` | `0x317c` | **`-0x58`** |
| `__TEXT.__auth_stubs` | `0x2ff0` | `0x3040` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x753c` | `0x74ee` | **`-0x4e`** |
| `__TEXT.__swift5_reflstr` | `0xe1e` | `0xdee` | **`-0x30`** |
| `__DATA_CONST.__auth_got` | `0x1800` | `0x1828` | **`+0x28`** |
| `__TEXT.__const` | `0x47c8` | `0x47a8` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0xb00` | `0xb20` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x929` | `0x93b` | **`+0x12`** |
| `__TEXT.__cstring` | `0x204d` | `0x203d` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xe0c` | `0xe00` | **`-0xc`** |
| `__DATA.__data` | `0x2be0` | `0x2bd8` | **`-0x8`** |
| `__DATA.__objc_selrefs` | `0x360` | `0x368` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xec0` | `0xec8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xb90` | `0xb98` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x114` | `0x11c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1830` | `0x1828` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x2a4` | `0x2a0` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x1a4` | `0x1a0` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1232.3.0.0.0
+1238.0.0.0.0

-  Functions: 1829
-  Symbols:   235
+  Functions: 1826
+  Symbols:   242
Symbols:
+ _OBJC_CLASS_$_HFHomeKitDispatcher
+ _OBJC_CLASS_$_HMHomeManagerConfiguration
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
CStrings:
+ "HomeWidgetCore/HMHomePredictions.swift"
+ "setConfiguration:"
- "SignificantChangesDescription"
- "SignificantChangesTitle"
```
