## VisionCompanion

> `/System/Library/PrivateFrameworks/VisionCompanion.framework/VisionCompanion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72fec` | `0x74230` | **`+0x1244`** |
| `__TEXT.__eh_frame` | `0x5f48` | `0x6028` | **`+0xe0`** |
| `__AUTH_CONST.__const` | `0x3788` | `0x3850` | **`+0xc8`** |
| `__TEXT.__oslogstring` | `0x1d04` | `0x1dc4` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0xb70` | `0xc28` | **`+0xb8`** |
| `__AUTH.__data` | `0x2b8` | `0x358` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x170f` | `0x17af` | **`+0xa0`** |
| `__TEXT.__const` | `0x3c6c` | `0x3cbc` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1d80` | `0x1dc0` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0xfc8` | `0x1004` | **`+0x3c`** |
| `__TEXT.__swift5_capture` | `0x9d0` | `0xa04` | **`+0x34`** |
| `__TEXT.__swift5_typeref` | `0x156c` | `0x1592` | **`+0x26`** |
| `__DATA_CONST.__objc_selrefs` | `0x640` | `0x660` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0xa54` | `0xa70` | **`+0x1c`** |
| `__DATA.__data` | `0xa68` | `0xa78` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x730` | `0x740` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x644` | `0x650` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x10c` | `0x110` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x330` | `0x334` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x3f8` | `0x3fc` | **`+0x4`** |

### Other Changes

```diff

-33.0.0.0.1
+35.0.2.0.0

-  Functions: 1938
-  Symbols:   793
-  CStrings:  287
+  Functions: 1961
+  Symbols:   798
+  CStrings:  295
Symbols:
+ _OBJC_CLASS_$_NSUbiquitousKeyValueStore
+ __DATA__TtC15VisionCompanion30CompanionSessionKVSCoordinator
+ __IVARS__TtC15VisionCompanion30CompanionSessionKVSCoordinator
+ __METACLASS_DATA__TtC15VisionCompanion30CompanionSessionKVSCoordinator
+ ___swift_closure_destructor.41Tm
+ ___swift_closure_destructor.86Tm
+ _symbolic So25NSUbiquitousKeyValueStoreC
+ _symbolic _____ 15VisionCompanion0B21SessionKVSCoordinatorC
- ___swift_closure_destructor.35Tm
- ___swift_closure_destructor.80Tm
- _swift_release_x28
CStrings:
+ "%s incremented session: writing sessionCount=%lld"
+ "%s received cross device analytics task %s"
+ "%s sync failed: %@"
+ "%s sync succeeded: sessionCount=%lld"
+ "com.apple.visioncompaniond.scheduledtasks.crossdeviceanalytics"
+ "com.apple.visionproapp.kvs"
+ "debug.mydevice.mockNameEnabled"
+ "debug.mydevice.mockNameLength"
```
