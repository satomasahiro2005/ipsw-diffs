## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8150.RELEASE.restore.im4p/exclave_sharedcache`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5feb44` | `0x5fef9c` | **`+0x458`** |
| `__TEXT.__cstring` | `0x50e61` | `0x50f61` | **`+0x100`** |
| `__TEXT.__constg_swiftt` | `0x28aa8` | `0x28b08` | **`+0x60`** |
| `__DATA.__data` | `0x19150` | `0x191a0` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x13508` | `0x13528` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x1cdf4` | `0x1ce0c` | **`+0x18`** |
| `__DATA.__bss` | `0xe6d0` | `0xe6e0` | **`+0x10`** |
| `__DATA.__const` | `0x3e798` | `0x3e7a8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__TIGHTBEAM`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__auth_ptr`
- `__DATA.__got`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__PDATA.__auth_ptr`
- `__PDATA.__const`
- `__PDATA.__data`
- `__TEXT.__chain_fixups`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
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

-1777.40.34.0.0
+1777.40.37.0.0

-  CStrings:  7436
+  CStrings:  7442
Functions:
~ sub_8290b9c : 992 -> 1024
~ sub_8290f7c -> sub_8290f9c : 104 -> 156
~ sub_8291088 -> sub_82910dc : 272 -> 348
~ sub_8291198 -> sub_8291238 : 2024 -> 2448
~ sub_8292bc4 -> sub_8292e0c : 1204 -> 1472
~ sub_8293078 -> sub_82933cc : 360 -> 456
~ sub_8298e6c -> sub_8299220 : 128 -> 156
~ sub_82a5abc -> sub_82a5e8c : 228 -> 260
~ sub_82a5c54 -> sub_82a6044 : 180 -> 212
~ sub_85b8e94 -> sub_85b92a4 : 808 -> 904
~ sub_85b9850 -> sub_85b9cc0 : 1092 -> 1068
CStrings:
+ "Start not allowed: camera disabled by EDT policy"
+ "Status not allowed: camera disabled by EDT policy"
+ "])\n  deviceStateDisplayWake: allowance="
+ "fpwm-frequency-hz"
+ "policy-sil-disable"
+ "sil-disable-config"
+ "sil-disable-offset"
- "])\n  medinaStateDisplayWake: allowance="
```
