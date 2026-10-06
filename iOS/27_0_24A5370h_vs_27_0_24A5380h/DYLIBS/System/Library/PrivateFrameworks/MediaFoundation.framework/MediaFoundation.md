## MediaFoundation

> `/System/Library/PrivateFrameworks/MediaFoundation.framework/MediaFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x262ac` | `0x28ed0` | **`+0x2c24`** |
| `__TEXT.__oslogstring` | `—` | `0x26a` | **`+0x26a`** |
| `__AUTH_CONST.__const` | `0x2dc8` | `0x2f38` | **`+0x170`** |
| `__TEXT.__eh_frame` | `0x18a8` | `0x1990` | **`+0xe8`** |
| `__AUTH_CONST.__auth_got` | `0x840` | `0x8f8` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0x10c8` | `0x1168` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x1f8` | `0x278` | **`+0x80`** |
| `__DATA.__data` | `0x4b8` | `0x518` | **`+0x60`** |
| `__TEXT.__cstring` | `0x63b` | `0x69a` | **`+0x5f`** |
| `__TEXT.__const` | `0x4b48` | `0x4b78` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0xeac` | `0xedc` | **`+0x30`** |
| `__DATA.__common` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x13d0` | `0x13e8` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x1097` | `0x10a7` | **`+0x10`** |
| `__DATA_CONST.__const` | `0xd8` | `0xe0` | **`+0x8`** |

### Other Changes

```diff

-4026.100.63.0.0
+4026.100.75.0.0

+  - /usr/lib/swift/libswiftOSLog.dylib

-  Functions: 1738
-  Symbols:   738
-  CStrings:  53
+  Functions: 1812
+  Symbols:   757
+  CStrings:  65
Symbols:
+ _OBJC_CLASS_$_NSObject
+ ___swift_allocate_value_buffer
+ ___swift_destroy_boxed_opaque_existential_1Tm
+ ___swift_memcpy26_8
+ ___swift_memcpy58_8
+ ___swift_project_value_buffer
+ __os_log_impl
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftOSLog_$_MediaFoundation
+ __swift_stdlib_bridgeErrorToNSError
+ _objc_release_x23
+ _os_log_type_enabled
+ _parameter-flags
+ _sqlite3_busy_timeout
+ _swift_bridgeObjectRelease_n
+ _swift_errorRetain
+ _swift_getFunctionTypeMetadata
+ _swift_getFunctionTypeMetadata0
+ _swift_getObjectType
+ _swift_release_x28
+ _swift_retain_x26
+ _swift_retain_x27
+ _swift_retain_x28
+ _swift_unknownObjectRetain
+ _symbolic SdSg
+ _symbolic So8NSObjectCIego_
+ _symbolic So8NSObjectCSgIego_
+ _symbolic ______pIego_ s5ErrorP
- ___swift_memcpy34_8
- ___swift_memcpy9_1
- _get_type_metadata 15MediaFoundation11SQLDatabaseV10ConnectionV noncopyable
- _get_type_metadata 15MediaFoundation4_SQLO10ConnectionV noncopyable
- _get_type_metadata 15MediaFoundation4_SQLO7ContextV noncopyable
- _get_type_metadata 15MediaFoundation4_SQLO9IndexInfoV noncopyable
- _get_type_metadata 15MediaFoundation4_SQLO9StatementV noncopyable
- _get_type_metadata Rvz15MediaFoundation11SQLDatabaseV18ValueRepresentableRzlAA4_SQLO8IteratorV noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "Could not commit transaction: %{public}@."
+ "PRAGMA foreign_keys"
+ "PRAGMA foreign_keys = "
+ "Unable to get PRAGMA foreign_key: %{public}@. Defaulting to FALSE."
+ "Unable to get PRAGMA journal_mode: %{public}@. Defaulting to DELETE."
+ "Unable to get PRAGMA locking_mode: %{public}@. Defaulting to NORMAL."
+ "Unable to set PRAGMA foreign_key to %{bool,public}d: %{public}@."
+ "Unable to set PRAGMA journal_mode to %{public}s: %{public}@."
+ "Unable to set PRAGMA locking_mode to %{public}s: %{public}@."
+ "Unable to set busy timeout: %{public}@."
+ "While closing connection, unable to run PRAGMA optimize: %{public}@."
+ "com.apple.MediaFoundation"
```
