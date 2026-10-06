## AudioAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/AudioAppIntentsExtension.appex/AudioAppIntentsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x367c8` | `0x36b44` | **`+0x37c`** |
| `__TEXT.__oslogstring` | `0x5d3` | `0x6d3` | **`+0x100`** |
| `__TEXT.__auth_stubs` | `0xd10` | `0xd20` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x2aa4` | `0x2a94` | **`-0x10`** |
| `__DATA.__data` | `0x25a8` | `0x25a0` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x690` | `0x698` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1b50` | `0x1b48` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.33.17.0.0
+3605.20.1.0.0

-  Functions: 2258
-  Symbols:   113
-  CStrings:  101
+  Functions: 2256
+  Symbols:   112
+  CStrings:  103
Symbols:
- _objc_release_x25
Functions:
~ sub_10002b08c : 1312 -> 2340
- sub_10002b5ac
- sub_10002c384
CStrings:
+ "App bundle identifier is AirPlay receiver, substituting represented bundle identifier: %{public}s"
+ "App bundle identifier is remote player service with Classical represented bundle identifier, substituting Classical"
+ "App bundle identifier: %{public}s"
- "App bundle identifier: %@"
```
