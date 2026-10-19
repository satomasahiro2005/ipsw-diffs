## VoiceMemos

> `/private/var/staged_system_apps/VoiceMemos.app/VoiceMemos`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fa384` | `0x1fa25c` | **`-0x128`** |
| `__DATA_CONST.__cfstring` | `0x38e0` | `0x3880` | **`-0x60`** |
| `__TEXT.__cstring` | `0xbf59` | `0xbef9` | **`-0x60`** |
| `__TEXT.__gcc_except_tab` | `0x1ee4` | `0x1ec8` | **`-0x1c`** |
| `__TEXT.__unwind_info` | `0x97e0` | `0x97d8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  CStrings:  10366
+  CStrings:  10363
Functions:
~ sub_10006cd00 : 228 -> 16
~ sub_10006d0e0 -> sub_10006d00c : 2724 -> 2640
CStrings:
- "RCWaveformRenderer.mm"
- "[%@] Tried to draw on non-main thread."
- "[%@] Tried to render on non-main thread."
```
