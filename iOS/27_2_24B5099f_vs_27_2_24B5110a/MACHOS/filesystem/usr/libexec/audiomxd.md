## audiomxd

> `/usr/libexec/audiomxd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4498` | `0x4558` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x326` | `0x377` | **`+0x51`** |
| `__DATA_CONST.__cfstring` | `0x40` | `0x60` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x890` | `0x8b0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xc8` | `0xe0` | **`+0x18`** |
| `__TEXT.__cstring` | `0x4ca` | `0x4dc` | **`+0x12`** |
| `__DATA_CONST.__auth_got` | `0x458` | `0x468` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1638.211.0.0.0
+1638.215.0.0.0

-  Symbols:   171
-  CStrings:  93
+  Symbols:   176
+  CStrings:  95
Symbols:
+ _CFPreferencesSynchronize
+ _MGGetSInt32Answer
+ _kCFPreferencesAnyApplication
+ _kCFPreferencesAnyHost
+ _kCFPreferencesAnyUser
Functions:
~ sub_100002a1c : 228 -> 412
~ sub_1000042f8 -> sub_1000043b0 : 1708 -> 1716
CStrings:
+ "%25s:%-5d resynchronizing all preferences to pick up new preferred language list"
+ "DeviceClassNumber"
```
