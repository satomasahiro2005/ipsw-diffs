## ManagedSettings

> `/System/Library/Frameworks/ManagedSettings.framework/ManagedSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc19dc` | `0xc0600` | **`-0x13dc`** |
| `__TEXT.__oslogstring` | `0x1f54` | `0x1e54` | **`-0x100`** |
| `__TEXT.__eh_frame` | `0xb88` | `0xb48` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x2b60` | `0x2b50` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0xad0` | `0xac8` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x390` | `0x388` | **`-0x8`** |

### Other Changes

```diff

-304.2.7.0.0
+318.0.0.0.0

-  Functions: 5006
-  Symbols:   1149
-  CStrings:  409
+  Functions: 5003
+  Symbols:   1148
+  CStrings:  405
Symbols:
- _NSFileSize
CStrings:
- "Failed to read effective settings data from %{public}s"
- "Failed to read local settings data from %{public}s"
- "File at path “%{public}s” is too large to read."
- "Settings file %{public}s too large to read: %{public}ld"
```
