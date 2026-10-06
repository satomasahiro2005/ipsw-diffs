## profiled

> `/usr/libexec/profiled`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc86e4` | `0xc85b4` | **`-0x130`** |
| `__TEXT.__objc_methname` | `0x16a75` | `0x16b35` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0xfda0` | `0xfe30` | **`+0x90`** |
| `__TEXT.__cstring` | `0xa85a` | `0xa8ba` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x133a0` | `0x13400` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x1238` | `0x11f0` | **`-0x48`** |
| `__DATA.__objc_selrefs` | `0x5488` | `0x54b8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x621c` | `0x624c` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0xeb6` | `0xee6` | **`+0x30`** |
| `__DATA.__objc_const` | `0x7080` | `0x70a8` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x86c0` | `0x86e0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x3010` | `0x3020` | **`+0x10`** |
| `__TEXT.__const` | `0x138e` | `0x137e` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1b60` | `0x1b50` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xb58` | `0xb64` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x20a0` | `0x20a8` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0xe8c` | `0xe94` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-2479.0.0.0.0
+2482.0.0.0.0

-  Functions: 2735
-  Symbols:   1793
-  CStrings:  5747
+  Functions: 2733
+  Symbols:   1794
+  CStrings:  5757
Symbols:
+ _MCFeatureSiriReduceSensitiveContentForced
+ _PCSettingsSetGlobalMCCForceManualWhenRoaming_Failable
- _PCSettingsSetGlobalMCCForceManualWhenRoaming
CStrings:
+ "Applying forceSiriReduceSensitiveContent settings: %{bool,public}d"
+ "Failed to set background-fetch-when-roaming state to %{public}@"
+ "Removing payload with handler “%{public}@”, payload identifier %{public}@..."
+ "com.apple.screentime.regulatory"
+ "effectiveForceSiriReduceSensitiveContent should never be nil"
+ "eraseDeviceWithCompletionHandler:"
+ "forceSiriReduceSensitiveContent"
+ "forceSiriReduceSensitiveContentMetadata"
+ "isORGOEnrolled"
+ "isProvisionallyEnrolled"
+ "siriReduceSensitiveContentForced"
- "Caught exception %{public}@ when setting background-fetch-when-roaming state."
```
