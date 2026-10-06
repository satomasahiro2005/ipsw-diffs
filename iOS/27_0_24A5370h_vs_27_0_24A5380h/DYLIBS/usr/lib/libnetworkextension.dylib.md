## libnetworkextension.dylib

> `/usr/lib/libnetworkextension.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34a88` | `0x3576c` | **`+0xce4`** |
| `__TEXT.__oslogstring` | `0x803e` | `0x8134` | **`+0xf6`** |
| `__DATA.__bss` | `0xce0` | `0xd18` | **`+0x38`** |
| `__TEXT.__cstring` | `0x2ed4` | `0x2f07` | **`+0x33`** |
| `__AUTH_CONST.__const` | `0x3c0` | `0x3e0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1c08` | `0x1c28` | **`+0x20`** |
| `__TEXT.__const` | `0x25c` | `0x26c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x780` | `0x790` | **`+0x10`** |

### Other Changes

```diff

-2315.0.0.0.2
+2322.0.0.0.1

-  Functions: 629
-  Symbols:   1295
-  CStrings:  1024
+  Functions: 635
+  Symbols:   1305
+  CStrings:  1031
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
+ "Invalid call to flow_director_handle_cfil_verdict."
+ "Not using UUID cache bin: OS version mismatch (%.*s vs %s)"
+ "Not using UUID cache bin: boot UUID mismatch"
+ "UUID cache bin sandbox check failed"
+ "UUID cache bin: size mismatch (header %u, file %lu)"
+ "UUID cache sandbox plist check failed"
- "UUID cache sandbox check failed"
```
