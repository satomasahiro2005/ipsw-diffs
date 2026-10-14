## AXHapticMusicServer

> `/System/Library/AccessibilityBundles/AXHapticMusicServer.axuiservice/AXHapticMusicServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c418` | `0x2cfe0` | **`+0xbc8`** |
| `__DATA_CONST.__const` | `0x1c98` | `0x1db0` | **`+0x118`** |
| `__TEXT.__oslogstring` | `0x13e8` | `0x14f8` | **`+0x110`** |
| `__TEXT.__swift5_capture` | `0x778` | `0x7fc` | **`+0x84`** |
| `__DATA.__objc_const` | `0x9f0` | `0xa50` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x4b2` | `0x512` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x625` | `0x675` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x153d` | `0x157d` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0xb40` | `0xb00` | **`-0x40`** |
| `__TEXT.__cstring` | `0x5eb` | `0x61b` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x358` | `0x37c` | **`+0x24`** |
| `__DATA.__data` | `0x750` | `0x770` | **`+0x20`** |
| `__DATA.__objc_data` | `0x208` | `0x220` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x498` | `0x488` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x10f0` | `0x10e0` | **`-0x10`** |
| `__TEXT.__const` | `0xb30` | `0xb20` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x888` | `0x880` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x2e0` | `0x2d8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x5f8` | `0x600` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x5b5` | `0x5b2` | **`-0x3`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3245.8.4.2.0
+3245.8.9.0.0

-  Functions: 675
-  Symbols:   269
-  CStrings:  427
+  Functions: 689
+  Symbols:   267
+  CStrings:  433
Symbols:
- _AVAudioSessionInterruptionNotification
- _swift_retain_x23
CStrings:
+ "Already fetching haptic track %s, not loading it again"
+ "Backing off engine creation, last failure "
+ "Checking status of server: Enabled: %{bool}d, active: %{bool}d, session valid: %{bool}d, thermal state: %{bool}d, siri active: %{bool}d, camera active: %{bool}d, engine: %{bool}d, engine running: %{bool}d"
+ "Engine stopped handler called for a stale engine. Ignoring"
+ "EngineCreationRetryInterval"
+ "Started a stale haptic engine, ignoring"
+ "Stopped a stale haptic engine, leaving current engine alone"
+ "Stopping and clearing out haptic engine: %s"
+ "fetchingTrackIdentifier"
+ "lastEngineCreationFailureTime"
- "Checking status of server: Enabled: %{bool}d, active: %{bool}d, session valid: %{bool}d, thermal state: %{bool}d, siri active: %{bool}d, camera active: %{bool}d"
- "Stopping and clearing out haptic engine: %@"
- "removeObserver:name:object:"
- "setAutoShutdownTimeout:"
```
