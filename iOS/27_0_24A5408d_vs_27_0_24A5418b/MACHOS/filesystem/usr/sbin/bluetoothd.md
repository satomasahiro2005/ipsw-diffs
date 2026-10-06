## bluetoothd

> `/usr/sbin/bluetoothd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x903084` | `0x902ef8` | **`-0x18c`** |
| `__TEXT.__oslogstring` | `0xc0bca` | `0xc0b4f` | **`-0x7b`** |
| `__TEXT.__gcc_except_tab` | `0x70994` | `0x70968` | **`-0x2c`** |
| `__TEXT.__unwind_info` | `0x26228` | `0x26218` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2700.51.1.1.0
+2700.51.1.3.0

-  Functions: 37354
+  Functions: 37351

-  CStrings:  43027
+  CStrings:  43024
CStrings:
+ "23:16:23"
+ "Aug 13 2026"
- "22:14:55"
- "Aug  5 2026"
- "Identification - Device ID unknown, not generating"
- "Trying to be central for A2DP"
- "makeActiveModeAndCentral - invalid device"
```
