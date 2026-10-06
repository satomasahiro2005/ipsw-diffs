## TVRemoteIntents

> `/private/var/staged_system_apps/TVRemote.app/PlugIns/TVRemoteIntents.appex/TVRemoteIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7498` | `0x76dc` | **`+0x244`** |
| `__TEXT.__oslogstring` | `0x654` | `0x6c8` | **`+0x74`** |
| `__TEXT.__gcc_except_tab` | `0x160` | `0x104` | **`-0x5c`** |
| `__DATA_CONST.__const` | `0x2d0` | `0x2f0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1d8` | `0x1e8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x300` | `0x310` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x190` | `0x198` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1b8` | `0x1c0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-627.0.19.0.0
+627.0.28.0.0

-  Functions: 129
-  Symbols:   126
-  CStrings:  448
+  Functions: 131
+  Symbols:   129
+  CStrings:  450
Symbols:
+ _TVRCCaptionsEnabled
+ _TVRCToggleCaptions
+ _objc_retain_x21
+ _objc_retain_x23
- _objc_retain_x24
CStrings:
+ "Failed to receive response for event: %{public}@ error: %{public}@"
+ "Sending TVRCToggleCaptions with value=%{public}@"
```
