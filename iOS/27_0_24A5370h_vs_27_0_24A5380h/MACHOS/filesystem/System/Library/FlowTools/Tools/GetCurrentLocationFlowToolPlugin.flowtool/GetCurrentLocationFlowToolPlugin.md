## GetCurrentLocationFlowToolPlugin

> `/System/Library/FlowTools/Tools/GetCurrentLocationFlowToolPlugin.flowtool/GetCurrentLocationFlowToolPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x141b4` | `0x14aa4` | **`+0x8f0`** |
| `__TEXT.__eh_frame` | `0x978` | `0xb48` | **`+0x1d0`** |
| `__TEXT.__oslogstring` | `0x5e4` | `0x6e4` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x4f0` | `0x540` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0xda0` | `0xdc0` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x90` | `0xa4` | **`+0x14`** |
| `__DATA_CONST.__auth_got` | `0x6d8` | `0x6e8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1c8` | `0x1d0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x24` | `0x28` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3600.144.5.501.3
+3600.147.12.501.3

-  Functions: 661
+  Functions: 675

-  CStrings:  72
+  CStrings:  75
CStrings:
+ "[Auth] #GetCurrentLocationTool: Device unlock failed, cannot proceed with location TCC request"
+ "[Auth] #GetCurrentLocationTool: Device unlock succeeded, proceeding with location TCC request"
+ "[Auth] #GetCurrentLocationTool: Requesting Device unlock"
```
