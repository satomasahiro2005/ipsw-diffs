## diagnosticscheckupd

> `/usr/libexec/diagnosticscheckupd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x49198` | `0x492bc` | **`+0x124`** |
| `__TEXT.__cstring` | `0x2f29` | `0x2ec9` | **`-0x60`** |
| `__TEXT.__oslogstring` | `0x34da` | `0x353a` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x5b20` | `0x5b40` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `0xa20` | `0xa38` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x2b8` | `0x2c0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1338` | `0x1340` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1374.0.5.0.0
+1374.0.27.0.0
Functions:
~ sub_100038844 : 252 -> 744
~ sub_100038940 -> sub_100038b2c : 40 -> 4
~ sub_100038968 -> sub_100038b30 : 40 -> 4
~ sub_100038990 -> sub_100038b34 : 4 -> 40
~ sub_100038994 -> sub_100038b5c : 4 -> 40
~ sub_10003b150 -> sub_10003b33c : 1168 -> 968
CStrings:
+ "We have been asked to dismiss a view controller that we are not presenting, ignoring."
- "CheckerBoard completion: showing final completion screen without session polling"
```
