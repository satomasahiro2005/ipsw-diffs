## libsystem_networkextension.dylib

> `/usr/lib/system/libsystem_networkextension.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15800` | `0x16628` | **`+0xe28`** |
| `__TEXT.__oslogstring` | `0x2d9a` | `0x2e90` | **`+0xf6`** |
| `__DATA.__bss` | `0x618` | `0x668` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x398` | `0x3c0` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x1c0` | `0x1e0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xcf0` | `0xd10` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x158` | `0x140` | **`-0x18`** |
| `__DATA.__data` | `0x2c` | `0x28` | **`-0x4`** |
| `__DATA_DIRTY.__data` | `0xc` | `0x10` | **`+0x4`** |

### Other Changes

```diff

-2315.0.0.0.2
+2322.0.0.0.1

-  Functions: 271
-  Symbols:   491
-  CStrings:  539
+  Functions: 277
+  Symbols:   501
+  CStrings:  545
Symbols:
+ ___ne_copy_cached_bundle_identifier_for_uuid_plist_locked_block_invoke
+ ___ne_copy_cached_bundle_identifier_for_uuid_plist_locked_block_invoke_2
+ ___ne_copy_cached_uuids_for_bundle_identifier_plist_locked_block_invoke
+ ___ne_copy_uuid_cache_plist_locked_block_invoke
+ ___ne_ensure_uuid_cache_mapped_locked_block_invoke
+ _g_uuid_cache_map
+ _ne_copy_uuid_cache_plist_locked
+ _ne_copy_uuid_cache_plist_locked.g_my_boot_session_uuid_plist
+ _ne_copy_uuid_cache_plist_locked.g_my_os_version_plist
+ _ne_copy_uuid_cache_plist_locked.once_token_plist
+ _ne_ensure_uuid_cache_mapped_locked
+ _ne_ensure_uuid_cache_mapped_locked.g_my_boot_session_uuid
+ _ne_ensure_uuid_cache_mapped_locked.g_my_os_version
+ _ne_ensure_uuid_cache_mapped_locked.once_token
+ _ne_uuid_cache_bsearch_fwd
+ _ne_uuid_cache_bsearch_rev
+ _ne_uuid_cache_changed
- ___ne_copy_cached_bundle_identifier_for_uuid_block_invoke
- ___ne_copy_cached_bundle_identifier_for_uuid_block_invoke_2
- ___ne_copy_cached_uuids_for_bundle_identifier_block_invoke
- ___ne_copy_uuid_cache_locked_block_invoke
- _ne_copy_uuid_cache_locked.g_my_boot_session_uuid
- _ne_copy_uuid_cache_locked.g_my_os_version
- _ne_copy_uuid_cache_locked.once_token
CStrings:
+ "%s size invalid: %lu"
+ "Failed to mmap %s: [%d] %s"
+ "Not using UUID cache bin: OS version mismatch (%.*s vs %s)"
+ "Not using UUID cache bin: boot UUID mismatch"
+ "UUID cache bin sandbox check failed"
+ "UUID cache bin: size mismatch (header %u, file %lu)"
+ "UUID cache sandbox plist check failed"
- "UUID cache sandbox check failed"
```
