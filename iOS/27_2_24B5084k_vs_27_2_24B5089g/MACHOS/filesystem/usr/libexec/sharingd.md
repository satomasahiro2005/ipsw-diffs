## sharingd

> `/usr/libexec/sharingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6b7098` | `0x6b71fc` | **`+0x164`** |
| `__TEXT.__oslogstring` | `0x3d653` | `0x3d6c3` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x258d4` | `0x258fc` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x149d8` | `0x149e8` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x222c` | `0x2230` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2131.20.65.2.1
+2131.20.71.0.0

-  Functions: 26466
+  Functions: 26468

-  CStrings:  27634
+  CStrings:  27635
CStrings:
+ "Became the console user, re-evaluating AirDrop receive"
+ "No longer the console user, stopping AirDrop receive"
+ "Not the console user session, deferring AirDrop receive start"
+ "updateServerState canRun(appService=%{bool}d, bonjour=%{bool}d, nearField=%{bool}d) inputs(currentConsoleUser=%{bool}d, screenStateSupportsAirDrop=%{bool}d, isAirDropDiscoverable=%{bool}d, isNearbySharingEnabled=%{bool}d, wirelessEnabled=%{bool}d, bluetoothEnabledIncludingRestricted=%{bool}d)"
- "User is logged in, starting app service server if needed"
- "User logged out, stopping servers"
- "updateServerState canRun(appService=%{bool}d, bonjour=%{bool}d, nearField=%{bool}d) inputs(screenStateSupportsAirDrop=%{bool}d, isAirDropDiscoverable=%{bool}d, isNearbySharingEnabled=%{bool}d, wirelessEnabled=%{bool}d, bluetoothEnabledIncludingRestricted=%{bool}d)"
```
