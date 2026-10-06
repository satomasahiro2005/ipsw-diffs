## libFontParser.dylib

> `/System/Library/PrivateFrameworks/FontServices.framework/libFontParser.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c966c` | `0x1c985c` | **`+0x1f0`** |
| `__AUTH.__objc_data` | `0x930` | `0x8e0` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x50` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0xc4` | `0x8b` | **`-0x39`** |
| `__TEXT.__eh_frame` | `0x9dd8` | `0x9e08` | **`+0x30`** |
| `__TEXT.__const` | `0x7c680` | `0x7c670` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x15d0` | `0x15d8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x7d04` | `0x7d0c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x7558` | `0x7560` | **`+0x8`** |

### Other Changes

```diff

-462.0.0.0.0
+463.0.0.1.0

-  Symbols:   6610
-  CStrings:  5506
+  Symbols:   6612
+  CStrings:  5505
Symbols:
+ GCC_except_table174
+ GCC_except_table178
+ GCC_except_table183
+ __ZN14TFragmentCache18DeleteUnlessCachedEPK22TFileFragmentReference
+ _os_unfair_lock_assert_not_owner
- GCC_except_table184
- __ZN14TFragmentCache11RemoveValueEPK22TFileFragmentReference
- __ZN18TFileFragmentCache11RemoveIndexEl
CStrings:
- "FontParser could not open filePath %{public}s: %{errno}d"
```
