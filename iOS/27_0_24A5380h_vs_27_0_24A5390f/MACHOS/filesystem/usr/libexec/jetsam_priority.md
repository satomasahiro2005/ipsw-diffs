## jetsam_priority

> `/usr/libexec/jetsam_priority`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xafbc` | `0xb404` | **`+0x448`** |
| `__TEXT.__gcc_except_tab` | `0xcc4` | `0xd20` | **`+0x5c`** |
| `__TEXT.__auth_stubs` | `0x5d0` | `0x610` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1320` | `0x135f` | **`+0x3f`** |
| `__DATA_CONST.__auth_got` | `0x2f8` | `0x318` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xe0` | `0xf8` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-10848.0.9.0.0
+10848.0.13.0.0

-  Symbols:   128
-  CStrings:  190
+  Symbols:   135
+  CStrings:  196
Symbols:
+ _XPC_COALITION_INFO_KEY_BUNDLE_IDENTIFIER
+ _XPC_COALITION_INFO_KEY_NAME
+ __xpc_type_dictionary
+ _strdup
+ _strncmp
+ _xpc_coalition_copy_info
+ _xpc_dictionary_get_string
+ _xpc_get_type
- _objc_release_x24
Functions:
~ sub_100000b7c : 27196 -> 28244
~ sub_100007e30 -> sub_100008248 : 532 -> 580
CStrings:
+ "   \n   Internal Only\n"
+ "   -g: Print process coalitions.\n"
+ ":kd:n:hcelifgs:w:rxp:z::"
+ "Unknown"
+ "coalition_id"
+ "coalition_name"
+ "com.apple."
+ "self"
+ "to launchd"
- ":kd:n:hcelifs:w:rxp:z::"
- "Warning: Could not get coalitions for pid %d.\n"
- "coalition"
```
