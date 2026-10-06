## OnDeviceDaemon

> `/System/Library/PrivateFrameworks/OnDeviceDaemon.framework/OnDeviceDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `—` | `0x196` | **`+0x196`** |
| `__TEXT.__cstring` | `0x24f` | `0xef` | **`-0x160`** |
| `__TEXT.__text` | `0x4f1c` | `0x4ff0` | **`+0xd4`** |
| `__TEXT.__eh_frame` | `0x308` | `0x388` | **`+0x80`** |
| `__DATA_DIRTY.__data` | `0x1c0` | `0x158` | **`-0x68`** |
| `__AUTH_CONST.__const` | `0x318` | `0x368` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x488` | `0x440` | **`-0x48`** |
| `__TEXT.__unwind_info` | `0x1c8` | `0x208` | **`+0x40`** |
| `__DATA.__data` | `0x1f0` | `0x228` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x44` | `0x54` | **`+0x10`** |
| `__TEXT.__const` | `0x3a0` | `0x398` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x1b6` | `0x1b7` | **`+0x1`** |

### Other Changes

```diff

-3.0.59.0.0
+3.1.10.0.0

-  Functions: 115
-  Symbols:   189
-  CStrings:  16
+  Functions: 126
+  Symbols:   197
+  CStrings:  17
Symbols:
+ ___swift__destructor
+ ___swift_destroy_boxed_opaque_existential_0
+ ___swift_destroy_boxed_opaque_existential_1Tm
+ __os_log_impl
+ __swiftImmortalRefCount
+ _memcpy
+ _objc_release_x20
+ _os_log_type_enabled
+ _swift_beginAccess
+ _swift_release_n
+ _swift_release_x20
+ _swift_release_x25
+ _swift_retain_n
+ _swift_retain_x24
+ _swift_unknownObjectRetain
+ _symbolic _____ 2os6LoggerV
+ _symbolic ______p s5ErrorP
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
- ___swift_destroy_boxed_opaque_existential_1
- _objc_release_x25
- _swift_release_x19
- _swift_release_x22
- _swift_release_x23
- _swift_release_x26
- _swift_release_x27
- _symbolic _____ 18OnDeviceFoundation8OSLoggerV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 18OnDeviceFoundation10LogMessageV
- _symbolic ypSg
CStrings:
+ "%{public}s"
+ "Failed to obtain process audit token: %{public}d. Entitlement checks will deny all."
+ "⚙️ Initializing sandbox for %{public}s"
+ "✅ Activated: %{public}s"
+ "💥 Daemon run loop exited, result=%{public}d"
+ "🟢 Starting daemon with %{public}ld services"
- ". Entitlement checks will deny all."
- "Failed to obtain process audit token: "
- "⚙️ Initializing sandbox for "
- "💥 Daemon run loop exited, result="
- "🟢 Starting daemon with "
```
