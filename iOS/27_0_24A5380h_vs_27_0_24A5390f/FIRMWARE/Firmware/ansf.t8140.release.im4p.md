## ansf.t8140.release.im4p

> `Firmware/ansf.t8140.release.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e65fc` | `0x1e53fc` | **`-0x1200`** |
| `__TEXT.read` | `0x720c` | `0x6f9c` | **`-0x270`** |
| `__TEXT.__cstring` | `0x2508b` | `0x25172` | **`+0xe7`** |
| `__TEXT.shared` | `0xdef0` | `0xdfd4` | **`+0xe4`** |
| `__TEXT.__const` | `0x5b28` | `0x5b68` | **`+0x40`** |
| `__DATA.__const` | `0x23e8` | `0x2420` | **`+0x38`** |
| `__DATA.__zerofill` | `0x20fa78` | `0x20faa8` | **`+0x30`** |
| `__DATA.__data` | `0x5bf0` | `0x5bf8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA._rtk_mtab`
- `__DATA._rtk_patchbay`

### Other Changes

```diff

-  Functions: 1965
+  Functions: 1970

-  CStrings:  3959
+  CStrings:  3961
CStrings:
+ "!MIDR: 0x%x"
+ "241.0.6"
+ "241.0.6~137"
+ "AppleStorageFirmwareASP3-241.0.6~137"
+ "{ 'trace_id': 'CMD_DRAIN', 'tp_func': %d, 'timestamp': %llu, 'thresh': %u, 'inUseCnt': %u, 'elapsed_us': %u }\n"
+ "{ 'trace_id': 'CMD_IMMEDIATE', 'tp_func': %d, 'timestamp': %llu, 'opType': %u, 'tag': %u, 'elapsed_us': %u }\n"
- "!MIDR: 0x%llx"
- "236"
- "236~174"
- "AppleStorageFirmwareASP3-236~174"
```
