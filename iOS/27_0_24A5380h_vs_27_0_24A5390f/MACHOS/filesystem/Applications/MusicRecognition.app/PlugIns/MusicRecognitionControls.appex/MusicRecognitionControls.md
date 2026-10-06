## MusicRecognitionControls

> `/Applications/MusicRecognition.app/PlugIns/MusicRecognitionControls.appex/MusicRecognitionControls`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f98` | `0x38a4` | **`+0x90c`** |
| `__TEXT.__eh_frame` | `0xe0` | `0x1c0` | **`+0xe0`** |
| `__TEXT.__auth_stubs` | `0x610` | `0x6c0` | **`+0xb0`** |
| `__DATA_CONST.__auth_got` | `0x310` | `0x368` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x110` | `0x160` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x160` | `0x198` | **`+0x38`** |
| `__TEXT.__const` | `0x3c4` | `0x3e4` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x80` | `0xa0` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x540` | `0x558` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x4a` | `0x5a` | **`+0x10`** |
| `__DATA.__data` | `0x368` | `0x370` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x20` | `0x28` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x230` | `0x238` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x128` | `0x130` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x8` | `0xc` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x8` | `0xc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-427.0.40.0.0
+427.0.44.0.0

-  Functions: 83
-  Symbols:   69
-  CStrings:  22
+  Functions: 95
+  Symbols:   75
+  CStrings:  23
Symbols:
+ _objc_release_x19
+ _swift_deallocObject
+ _swift_getObjectType
+ _swift_task_create
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
CStrings:
+ "setBool:forKey:"
```
