## inputanalyticsd

> `/usr/libexec/inputanalyticsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3dc` | `0x494` | **`+0xb8`** |
| `__TEXT.__cstring` | `0x7d` | `0xc4` | **`+0x47`** |
| `__DATA_CONST.__const` | `0x40` | `0x80` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x1a0` | `0x1e0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x101` | `0x138` | **`+0x37`** |
| `__DATA_CONST.__auth_got` | `0xd8` | `0xf8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__const` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x70` | `0x78` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`

### Other Changes

```diff

-153.0.0.0.0
+154.1.4.0.0

-  Functions: 10
-  Symbols:   38
-  CStrings:  13
+  Functions: 11
+  Symbols:   43
+  CStrings:  17
Symbols:
+ __os_log_impl
+ __xpc_event_key_name
+ _objc_release_x19
+ _xpc_dictionary_get_string
+ _xpc_set_event_stream_handler
Functions:
~ sub_1000009d8 : 204 -> 236
+ sub_100000c5c
CStrings:
+ "(unknown)"
+ "com.apple.notifyd.matching"
+ "inputanalyticsd received notification from: %{public}s"
+ "v16@?0@\"NSObject<OS_xpc_object>\"8"
```
