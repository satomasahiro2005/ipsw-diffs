## misd

> `/usr/libexec/misd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21d24` | `0x21e14` | **`+0xf0`** |
| `__DATA_CONST.__cfstring` | `0xb40` | `0xba0` | **`+0x60`** |
| `__TEXT.__cstring` | `0xb6ba` | `0xb718` | **`+0x5e`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-398.0.0.0.0
+399.0.0.0.0

-  CStrings:  1754
+  CStrings:  1758
Functions:
~ sub_100008d58 : 852 -> 972
~ sub_1000191c0 -> sub_100019238 : 2324 -> 2444
CStrings:
+ "DisableHostModeAllSubnetsLocal %s"
+ "HostModeAllSubnetsLocal"
+ "all_subnets_local"
+ "use_server_config"
```
