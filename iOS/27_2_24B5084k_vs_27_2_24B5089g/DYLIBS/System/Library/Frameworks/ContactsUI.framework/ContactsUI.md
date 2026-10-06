## ContactsUI

> `/System/Library/Frameworks/ContactsUI.framework/ContactsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0xb29d` | `0xb2e1` | **`+0x44`** |
| `__TEXT.__const` | `0xc550` | `0xc520` | **`-0x30`** |
| `__DATA.__bss` | `0xa588` | `0xa5a8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xdda8` | `0xdd90` | **`-0x18`** |
| `__AUTH.__data` | `0x35f0` | `0x35e0` | **`-0x10`** |
| `__DATA.__data` | `0xadc8` | `0xadb8` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x3a11` | `0x3a21` | **`+0x10`** |
| `__TEXT.__text` | `0x387e14` | `0x387e1c` | **`+0x8`** |

### Other Changes

```diff

-1463.200.41.0.0
+1463.200.51.0.0

-  CStrings:  3249
+  CStrings:  3250
CStrings:
+ "No contact at index %lu of %lu after foreground fetch of %{public}@"
```
