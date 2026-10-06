## GetCurrentLocationFlowToolPlugin

> `/System/Library/FlowTools/Tools/GetCurrentLocationFlowToolPlugin.flowtool/GetCurrentLocationFlowToolPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13000` | `0x141b4` | **`+0x11b4`** |
| `__TEXT.__eh_frame` | `0x680` | `0x978` | **`+0x2f8`** |
| `__DATA_CONST.__const` | `0xd28` | `0xad0` | **`-0x258`** |
| `__TEXT.__auth_stubs` | `0xc60` | `0xda0` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x4d7` | `0x5e4` | **`+0x10d`** |
| `__TEXT.__swift5_capture` | `0x2d0` | `0x1e0` | **`-0xf0`** |
| `__DATA_CONST.__auth_got` | `0x638` | `0x6d8` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x468` | `0x4f0` | **`+0x88`** |
| `__TEXT.__cstring` | `0x546` | `0x596` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x1e0` | `0x220` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x190` | `0x1c8` | **`+0x38`** |
| `__TEXT.__swift_as_cont` | `0x60` | `0x90` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x42d` | `0x409` | **`-0x24`** |
| `__TEXT.__objc_methname` | `0x168` | `0x17c` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x3c` | `0x50` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0x78` | `0x88` | **`+0x10`** |
| `__TEXT.__const` | `0xe38` | `0xe48` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x92` | `0x9e` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x18` | `0x24` | **`+0xc`** |
| `__DATA.__data` | `0x2f8` | `0x300` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3600.138.6.501.17
+3600.144.5.501.3

-  Functions: 672
+  Functions: 661

-  CStrings:  66
+  CStrings:  72
Symbols:
+ __os_signpost_emit_with_name_impl
- _objc_retain_x28
CStrings:
+ "From cnPostalAddress - postal code: %{sensitive}s, street: %{sensitive}s, city: %{sensitive}s, state: %{sensitive}s"
+ "GetCurrentLocationTool remote client fix: (%{sensitive}f, %{sensitive}f)"
+ "GetCurrentLocationTool remote client result: %s"
+ "GetCurrentLocationTool remote client: location unavailable — client not authorized or TCC denied"
+ "GetCurrentLocationTool#executeForRemoteClientRequest"
+ "IF.Executor.GetCurrentLocationTool"
+ "[Error] Interval already ended"
+ "coordinate"
+ "location"
- "From cnPostalAddress - postal code: %s, street: %s, city: %s, state: %s "
- "attempting to get address components"
- "locationItem - MKMapsItem - %@"
```
