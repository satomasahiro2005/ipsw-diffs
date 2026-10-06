## promotedcontentd

> `/usr/libexec/promotedcontentd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d7b64` | `0x3d8ec4` | **`+0x1360`** |
| `__TEXT.__oslogstring` | `0x10adc` | `0x10edc` | **`+0x400`** |
| `__DATA_CONST.__got` | `0x1650` | `0x1850` | **`+0x200`** |
| `__DATA.__objc_data` | `0x9778` | `0x9840` | **`+0xc8`** |
| `__DATA.__objc_const` | `0x2b2f8` | `0x2b388` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0x5b60` | `0x5bc0` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x63a4` | `0x6400` | **`+0x5c`** |
| `__TEXT.__const` | `0x2b18a` | `0x2b1da` | **`+0x50`** |
| `__TEXT.__cstring` | `0x15c95` | `0x15ce5` | **`+0x50`** |
| `__DATA.__data` | `0xe5d8` | `0xe618` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x42ba` | `0x42f4` | **`+0x3a`** |
| `__TEXT.__objc_methlist` | `0x151f0` | `0x15228` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x4938` | `0x4970` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x2dc0` | `0x2df0` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x4c2c` | `0x4c5c` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x4be7` | `0x4c17` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x7120` | `0x7148` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0xf7e0` | `0xf800` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1a1c0` | `0x1a1e0` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x15a8` | `0x15c0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1334` | `0x1348` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x1c6b8` | `0x1c6c8` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x3626` | `0x3636` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x9498` | `0x94a0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xfe0` | `0xfe8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x844` | `0x848` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x11c` | `0x120` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x5bc` | `0x5c0` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xec` | `0xf0` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x118` | `0x11c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-557.1.21.0.0
+557.1.24.0.0

-  Functions: 11778
-  Symbols:   2296
-  CStrings:  11632
+  Functions: 11788
+  Symbols:   2298
+  CStrings:  11649
Symbols:
+ _OBJC_CLASS_$_AMSBag
+ _dispatch_get_specific
+ _dispatch_queue_set_specific
- _OBJC_CLASS_$_AMSCachedBag
CStrings:
+ "Config System Background Task Asked to Expire. onRequestQueue=%d"
+ "Config System Background Task completion block entered. success=%d hasData=%d"
+ "Config System Background Task processing: finished post-update refreshers."
+ "Config System Background Task processing: finished updateConfigurationSystemWithData. result=%d"
+ "Config System Background Task processing: starting APFeatureFlagsProcessRestarter.restartIfNeeded."
+ "Config System Background Task processing: starting EligibilitySnapshotRefresher.refreshUserDefaults."
+ "Config System Background Task processing: starting POIConfigRefresher.refreshUserDefaults."
+ "Config System Background Task processing: starting updateConfigurationSystemWithData."
+ "Database busy timeout saved to UserDefaults: %ld"
+ "Database.BusyTimeout"
+ "[AdRequest] API Response received for placement: %{public}@ in %f seconds"
+ "[AdRequest] Sending API request for placement: %{public}@"
+ "[TT] API response: %{public}lu served (adamIDs: %{private}@), %{public}lu dropped (%{public}@), %{public}lu filled without adamID"
+ "[TT] Expected at most one representation, got %{public}lu"
+ "_TtC16promotedcontentd25DatabaseBusyTimeoutSyncer"
+ "bagForProfile:profileVersion:"
+ "promotedcontentd.DatabaseBusyTimeoutSyncer"
+ "sync"
+ "unfilled:%lu"
- "Config System Background Task Asked to Expire."
- "bagWithProfile:version:processInfo:"
```
