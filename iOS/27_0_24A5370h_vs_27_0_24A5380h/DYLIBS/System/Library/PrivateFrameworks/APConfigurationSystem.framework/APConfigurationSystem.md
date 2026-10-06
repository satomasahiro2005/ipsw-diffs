## APConfigurationSystem

> `/System/Library/PrivateFrameworks/APConfigurationSystem.framework/APConfigurationSystem`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b9f0` | `0x1d07c` | **`+0x168c`** |
| `__DATA_DIRTY.__bss` | `0xc10` | `0x1910` | **`+0xd00`** |
| `__DATA.__bss` | `0x4000` | `0x3800` | **`-0x800`** |
| `__TEXT.__oslogstring` | `0xcc9` | `0x1069` | **`+0x3a0`** |
| `__TEXT.__const` | `0x2cd8` | `0x2f58` | **`+0x280`** |
| `__DATA_DIRTY.__data` | `0x578` | `0x7c0` | **`+0x248`** |
| `__AUTH.__objc_data` | `0x1b8` | `—` | **`-0x1b8`** |
| `__DATA_DIRTY.__objc_data` | `0xbd0` | `0xd88` | **`+0x1b8`** |
| `__AUTH_CONST.__const` | `0x1728` | `0x1880` | **`+0x158`** |
| `__TEXT.__gcc_except_tab` | `0x18` | `0x140` | **`+0x128`** |
| `__DATA.__data` | `0x8f8` | `0x7e8` | **`-0x110`** |
| `__AUTH.__data` | `0xd8` | `—` | **`-0xd8`** |
| `__TEXT.__eh_frame` | `0x6c0` | `0x778` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0x938` | `0x9b8` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x9be` | `0xa30` | **`+0x72`** |
| `__TEXT.__constg_swiftt` | `0x924` | `0x988` | **`+0x64`** |
| `__TEXT.__swift5_fieldmd` | `0x9f8` | `0xa58` | **`+0x60`** |
| `__TEXT.__swift5_proto` | `0x274` | `0x29c` | **`+0x28`** |
| `__TEXT.__cstring` | `0x1610` | `0x1630` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0xb8` | `0xd8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x718` | `0x728` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x788` | `0x798` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x61f` | `0x62f` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xd8` | `0xe4` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x2e8` | `0x2f0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xc5c` | `0xc64` | **`+0x8`** |

### Other Changes

```diff

-557.1.21.0.0
+557.1.24.0.0

-  Functions: 927
-  Symbols:   298
-  CStrings:  223
+  Functions: 961
+  Symbols:   301
+  CStrings:  238
Symbols:
+ _OBJC_EHTYPE_$_NSException
+ _objc_begin_catch
+ _objc_end_catch
CStrings:
+ "Database/APDatabase"
+ "Error: Exception during tar extraction at %{private}@: %{public}@."
+ "Error: Exception writing tar entry to %{private}@: %{public}@."
+ "Error: Failed to close destination file at %{private}@, error: %{public}@."
+ "Error: Failed to read tar source, error: %{public}@."
+ "Error: Failed to seek tar source to offset %llu, error: %{public}@."
+ "Error: Failed to write tar entry to %{private}@, error: %{public}@."
+ "Error: Premature EOF reading tar source; %llu bytes still expected for %{private}@."
+ "Error: Unable to create destination file at %{private}@, error: %{public}@."
+ "Error: Unable to open destination file for writing at %{private}@."
+ "Response handler: _processData entered. tempDirExists=%d"
+ "Response handler: _processData exited. status=%ld"
+ "Response handler: pre-existing temp dir cleanup finished."
+ "Response handler: pre-existing temp dir found, starting cleanup at %{public}@."
+ "Warning: Failed to close tar source at %{private}@, error: %{public}@."
```
