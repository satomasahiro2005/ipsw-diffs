## ADFollowUpExtension

> `/System/Library/ExtensionKit/Extensions/ADFollowUpExtension.appex/ADFollowUpExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17458` | `0x18290` | **`+0xe38`** |
| `__DATA_CONST.__const` | `0x6c0` | `0x7b0` | **`+0xf0`** |
| `__TEXT.__const` | `0x848` | `0x8c8` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x718` | `0x790` | **`+0x78`** |
| `__TEXT.__swift5_capture` | `0x178` | `0x1ec` | **`+0x74`** |
| `__TEXT.__objc_methname` | `0x1364` | `0x13c4` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x4e8` | `0x530` | **`+0x48`** |
| `__TEXT.__objc_stubs` | `0xcc0` | `0xd00` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x474` | `0x4a6` | **`+0x32`** |
| `__TEXT.__auth_stubs` | `0x15a0` | `0x15c0` | **`+0x20`** |
| `__DATA.__data` | `0x6d8` | `0x6e8` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x4d0` | `0x4e0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xae0` | `0xaf0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x601` | `0x5f1` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0xb7d` | `0xb6d` | **`-0x10`** |
| `__DATA.__bss` | `0x5d8` | `0x5e0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2a8` | `0x2a0` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x1c` | `0x24` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x50` | `0x54` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x2c` | `0x30` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-4.0.39.0.0
+4.0.44.0.0

-  Functions: 348
-  Symbols:   232
-  CStrings:  334
+  Functions: 373
+  Symbols:   231
+  CStrings:  336
Symbols:
+ _swift_release_n
- _swift_release_x24
- _swift_retain_x24
CStrings:
+ "Primary button pressed again, toggling pause/resume of app install progress"
+ "[%s] Can not pause/resume app install progress because app or progress not found"
+ "[%s] Pause/resume requested but no action can be taken"
+ "installProgressKVOTokens"
+ "performWithoutAnimation:"
+ "resumeMetadata:"
- "Primary button pressed again, but can not pause/resume app install progress because app or progress not found"
- "Primary button pressed again, pausing/resuming app install progress"
- "[%s] Progress button pressed but no action can be taken"
- "installProgressKVOToken"
```
