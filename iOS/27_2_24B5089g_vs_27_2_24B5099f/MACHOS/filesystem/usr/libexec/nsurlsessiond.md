## nsurlsessiond

> `/usr/libexec/nsurlsessiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8427c` | `0x84688` | **`+0x40c`** |
| `__TEXT.__oslogstring` | `0xf8cf` | `0xf9a2` | **`+0xd3`** |
| `__TEXT.__gcc_except_tab` | `0xe820` | `0xe8e4` | **`+0xc4`** |
| `__TEXT.__auth_stubs` | `0x11d0` | `0x11e0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x900` | `0x908` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x6334` | `0x633c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2e80` | `0x2e88` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`

### Other Changes

```diff

-3896.200.41.0.0
+3896.200.52.0.0

-  Functions: 2102
-  Symbols:   518
-  CStrings:  3899
+  Functions: 2103
+  Symbols:   519
+  CStrings:  3902
Symbols:
+ __CFN_isForegroundOnlyAVAssetDownloadIdentifier
CStrings:
+ "%{public}@ cancelling foreground-only AVAssetDownload: client disconnected"
+ "%{public}@ no Live Activity: foreground-only session"
+ "Cleaning up foreground-only session <%{public}@>.<%{public}@>: last task completed"
```
