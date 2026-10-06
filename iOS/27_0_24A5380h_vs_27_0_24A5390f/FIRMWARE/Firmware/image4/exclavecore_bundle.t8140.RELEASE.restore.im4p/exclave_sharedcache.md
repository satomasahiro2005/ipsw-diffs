## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_sharedcache`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__const` | `0x3d578` | `0x3d1f0` | **`-0x388`** |
| `__TEXT.__text` | `0x5e7b24` | `0x5e784c` | **`-0x2d8`** |
| `__TEXT.__eh_frame` | `0x34f10` | `0x35038` | **`+0x128`** |
| `__TEXT.__cstring` | `0x4f291` | `0x4f381` | **`+0xf0`** |
| `__TEXT.__const` | `0x122134` | `0x1221a4` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x11ef8` | `0x11f68` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x1bfc8` | `0x1c010` | **`+0x48`** |
| `__DATA.__data` | `0x186b0` | `0x186e8` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x27e48` | `0x27e80` | **`+0x38`** |
| `__TEXT.__swift5_mpenum` | `0x3cc` | `0x39c` | **`-0x30`** |
| `__PDATA.__bss` | `0xc4a8` | `0xc4b8` | **`+0x10`** |
| `__TEXT.__chain_fixups` | `0xb8` | `0xb0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__TIGHTBEAM`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__auth_ptr`
- `__DATA.__got`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__thread_vars`
- `__PDATA.__auth_ptr`
- `__PDATA.__const`
- `__PDATA.__data`
- `__PDATA.__mod_init_func`
- `__PDATA.__shared_cache`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1777.0.16.0.0
-  Functions: 22927
+1777.0.20.0.0
+  Functions: 22941

-  CStrings:  7283
+  CStrings:  7292
CStrings:
+ "1"
+ "OWNERINFO"
+ "Stop prox policy (reset)"
+ "[B] Stop prox policy (reset)"
+ "exbright_mot_enable"
+ "failed to shutdown host with exit code: %d"
+ "freed slot was not most recently allocated"
+ "integer value bound to non-value generic parameter"
+ "integer value where a type is required"
+ "policy-override-chill-pill"
+ "policy-override-chill-pill exceeds MOT, setting back to default to "
+ "yes"
- "[SCHED] Scheduling %s 0x%04hx (%zu/%zu)\n"
- "no fixup data for faultable range [%#lx, %#lx) found"
- "non-zero exit return: %d"
```
