## HomeServices

> `/System/Library/PrivateFrameworks/HomeServices.framework/HomeServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8f3ac` | `0x90704` | **`+0x1358`** |
| `__TEXT.__eh_frame` | `0x3d70` | `0x3e68` | **`+0xf8`** |
| `__TEXT.__oslogstring` | `0x25c1` | `0x2671` | **`+0xb0`** |
| `__AUTH_CONST.__objc_const` | `0x1058` | `0x10b8` | **`+0x60`** |
| `__TEXT.__const` | `0x61d0` | `0x6230` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0xde6` | `0xe46` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x4718` | `0x4758` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x16d8` | `0x1714` | **`+0x3c`** |
| `__TEXT.__unwind_info` | `0x1ba0` | `0x1bd8` | **`+0x38`** |
| `__AUTH.__data` | `0x840` | `0x870` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x13d0` | `0x13e8` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x12c3` | `0x12d7` | **`+0x14`** |
| `__TEXT.__cstring` | `0x1b8b` | `0x1b7b` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0xe4` | `0xdc` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x1ec` | `0x1f0` | **`+0x4`** |

### Other Changes

```diff

-490.1.4.0.0
+504.0.0.0.0

-  Functions: 2128
-  Symbols:   849
-  CStrings:  348
+  Functions: 2134
+  Symbols:   852
+  CStrings:  354
Symbols:
+ _get_enum_tag_for_layout_string 12HomeServices21AccessKeyManagerErrorO
+ _kSecAttrAccessible
+ _symbolic SaySDySSypGGAAKcSg
CStrings:
+ "Existing access key available for key %s"
+ "Existing key unavailable for %s. Refetching: %s"
+ "Failed to save new access key: %s"
+ "Re-insert: no existing value"
+ "decoding failure"
+ "https://cabana-server-staging.cdn-apple.com/v1/config?revision=4"
+ "https://cabana-server.cdn-apple.com/v1/config?revision=2"
+ "malformed date string"
- "https://cabana-config-staging.cdn-apple.com/static/v1/bootstrap-qa-5fe335a3-cf42-447e-9eea-81bbd1a0d62e.json"
- "https://cabana-config.cdn-apple.com/static/v1/bootstrap-31e8c871-9a82-4a76-af31-7857bae5b03e.json"
```
