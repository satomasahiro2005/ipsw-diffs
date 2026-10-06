## Setup

> `/Applications/Setup.app/Setup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24b3d0` | `0x24cefc` | **`+0x1b2c`** |
| `__TEXT.__oslogstring` | `0x14e3c` | `0x14eec` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0x29380` | `0x29420` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x409ae` | `0x40a3e` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x8708` | `0x8758` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x4308` | `0x4348` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x9e28` | `0x9e58` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0xcaec` | `0xcb1a` | **`+0x2e`** |
| `__DATA.__objc_selrefs` | `0xcd00` | `0xcd18` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1dd10` | `0x1dd28` | **`+0x18`** |
| `__DATA.__data` | `0x7a00` | `0x7a10` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x28e0` | `0x28f0` | **`+0x10`** |
| `__TEXT.__const` | `0x3630` | `0x3640` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x11bc` | `0x11cc` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x2788` | `0x2792` | **`+0xa`** |
| `__DATA_CONST.__auth_got` | `0x1488` | `0x1490` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x510` | `0x518` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5411.0.0.0.0
+5411.101.0.0.0

-  Functions: 12341
-  Symbols:   1534
-  CStrings:  14876
+  Functions: 12357
+  Symbols:   1535
+  CStrings:  14883
Symbols:
+ _swift_release_x3
CStrings:
+ "AppState changed (%{private}s): %{public}s"
+ "AppState changed (%{public}s): %{public}s"
+ "Aug 13 2026"
+ "Failed to determine bundleID: %{public}s"
+ "Updating app state."
+ "appStatesFrom:"
+ "bundleIdentifierForIdentityString:error:"
+ "containsSuspiciousChangesWithOriginalAppStates:currentAppStates:bundleIdentifierResolver:"
- "Aug  4 2026"
```
