## SmartNameSuggestionsService

> `/System/Library/PrivateFrameworks/SmartNameSuggestions.framework/XPCServices/SmartNameSuggestionsService.xpc/SmartNameSuggestionsService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x171f0` | `0x1a3c0` | **`+0x31d0`** |
| `__TEXT.__auth_stubs` | `0x1490` | `0x1620` | **`+0x190`** |
| `__DATA_CONST.__auth_got` | `0xa50` | `0xb18` | **`+0xc8`** |
| `__TEXT.__oslogstring` | `0x8ab` | `0x96b` | **`+0xc0`** |
| `__DATA_CONST.__got` | `0x208` | `0x278` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x468` | `0x4d2` | **`+0x6a`** |
| `__TEXT.__cstring` | `0x4bf` | `0x511` | **`+0x52`** |
| `__DATA.__data` | `0xa48` | `0xa98` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x540` | `0x4f0` | **`-0x50`** |
| `__TEXT.__const` | `0xd18` | `0xd68` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x1db` | `0x20b` | **`+0x30`** |
| `__DATA.__objc_const` | `0x860` | `0x888` | **`+0x28`** |
| `__DATA_CONST.__auth_ptr` | `0x2b0` | `0x2d0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x4db` | `0x4fb` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1d3` | `0x1f0` | **`+0x1d`** |
| `__TEXT.__objc_methlist` | `0x198` | `0x1b4` | **`+0x1c`** |
| `__TEXT.__eh_frame` | `0xab8` | `0xad0` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x2b4` | `0x2cc` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0xc0` | `0xac` | **`-0x14`** |
| `__DATA.__objc_data` | `0x258` | `0x268` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x48c` | `0x494` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x90` | `0x98` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4d8` | `0x4e0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x24` | `0x28` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-21.0.0.0.0
+24.0.0.0.0

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 335
-  Symbols:   203
-  CStrings:  185
+  Functions: 344
+  Symbols:   209
+  CStrings:  196
Symbols:
+ __objc_autoreleasePoolPop
+ __objc_autoreleasePoolPush
+ _kFDSImportOptionSandboxExtension
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _sandbox_extension_issue_file
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_release_x1
+ _swift_retain_x23
+ _swift_retain_x27
- _objc_retain_x24
- _objc_retain_x28
- _swift_deallocUninitializedObject
- _swift_release_n
- _swift_retain_n
CStrings:
+ "Cancelling request %s"
+ "Issued sandbox extension token for %{private}s: len:%ld"
+ "Request cancelled"
+ "activeTasks"
+ "cancelRequest:"
+ "com.apple.iwork."
+ "com.apple.spotlight-indexable"
+ "sandbox_extension_issue_file(%s) failed for %{private}s"
+ "simulateSlowRequest: cancelled at tick %ld"
+ "simulateSlowRequest: entering cooperative sleep loop"
+ "v24@0:8@\"NSUUID\"16"
+ "v24@0:8@16"
- "Stripped %{public}ld iWork media/font noise items, length now %ld"
```
