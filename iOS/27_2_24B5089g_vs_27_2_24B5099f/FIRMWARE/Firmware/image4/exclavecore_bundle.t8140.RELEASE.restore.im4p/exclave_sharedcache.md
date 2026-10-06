## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_sharedcache`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5fcdc4` | `0x5feb44` | **`+0x1d80`** |
| `__TEXT.__eh_frame` | `0x35d30` | `0x35fe8` | **`+0x2b8`** |
| `__DATA.__const` | `0x3e5e0` | `0x3e798` | **`+0x1b8`** |
| `__TEXT.__const` | `0x123fa4` | `0x124124` | **`+0x180`** |
| `__DATA.__ENDPOINTS` | `0x1a744` | `0x1a84b` | **`+0x107`** |
| `__TEXT.__cstring` | `0x50df1` | `0x50e61` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x28a48` | `0x28aa8` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x1cdb0` | `0x1cdf4` | **`+0x44`** |
| `__DATA.__data` | `0x19110` | `0x19150` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x144ee` | `0x1452c` | **`+0x3e`** |
| `__TEXT.__objc_methtype` | `0xe1` | `0x111` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x1048` | `0x1068` | **`+0x20`** |
| `__DATA.__bss` | `0xe6c0` | `0xe6d0` | **`+0x10`** |
| `__DATA.__auth_ptr` | `0x2490` | `0x2498` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x251c` | `0x2524` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x3e94` | `0x3e98` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__TIGHTBEAM`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__got`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__PDATA.__auth_ptr`
- `__PDATA.__const`
- `__PDATA.__data`
- `__PDATA.__mod_init_func`
- `__PDATA.__shared_cache`
- `__TEXT.__chain_fixups`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1777.40.28.0.2
-  Functions: 23145
+1777.40.34.0.0
+  Functions: 23176

-  CStrings:  7432
+  CStrings:  7436
CStrings:
+ " DisplayManager is not configured!"
+ " but a session is already active!"
+ " but startTimestampUS is nil!"
+ "Builtin.Borrow is not supported in runtime type lookup"
+ "Initialized count must be in 0 ... unsafeUninitializedCapacity."
+ "sharedmem_framemap_getPhysicalAddress"
+ "sharedmem_framemap_setMapped_delta"
+ "v24@?0{sharedmem_pagerange=QQ}8"
- "Initialized count set to greater than specified capacity."
- "localmap_map(%zx): localmap() remap with changed PA (%llx != %llx)\n"
- "sharedmem_framemap_getPhysicalAddresses"
- "sharedmem_framemap_setMapped"
```
