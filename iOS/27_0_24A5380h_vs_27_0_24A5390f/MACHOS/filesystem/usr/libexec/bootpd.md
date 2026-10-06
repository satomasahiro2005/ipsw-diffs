## bootpd

> `/usr/libexec/bootpd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10f8c` | `0x110f4` | **`+0x168`** |
| `__DATA_CONST.__cfstring` | `0xc40` | `0xcc0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x1ed1` | `0x1f14` | **`+0x43`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-554.0.0.0.0
+555.0.0.0.0

-  Functions: 211
-  Symbols:   197
-  CStrings:  648
+  Functions: 213
+  Symbols:   199
+  CStrings:  651
Symbols:
+ _SubnetAllSubnetsAreLocal
+ _SubnetUseServerConfig
CStrings:
+ "\tAll Subnets Local: yes\n"
+ "\tUse Server Config: %s\n"
+ "use_server_config"
```
