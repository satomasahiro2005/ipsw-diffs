## ValidUpdater

> `/usr/libexec/ValidUpdater`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6984` | `0x69d8` | **`+0x54`** |
| `__TEXT.__auth_stubs` | `0x900` | `0x920` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x200` | `0x218` | **`+0x18`** |
| `__DATA.__common` | `0x8` | `0x18` | **`+0x10`** |
| `__DATA.__data` | `0x1f0` | `0x1e0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x488` | `0x498` | **`+0x10`** |
| `__DATA.__bss` | `0x20` | `0x28` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x278` | `0x280` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-134.0.21.0.0
+134.40.15.0.0

-  Functions: 132
-  Symbols:   195
+  Functions: 133
+  Symbols:   197
Symbols:
+ _$s11SwiftCRLite22ValidInitialRetryDelaySivg
+ _$s11SwiftCRLite25ValidInitialRetryAttemptsSivg
CStrings:
+ "daemon startup failed with: %{public}@"
+ "validDownload scheduled update: %{public}@"
+ "validDownloadTask completed: %{public}@"
- "daemon startup failed with: %@"
- "validDownload scheduled update: %@"
- "validDownloadTask completed: %@"
```
