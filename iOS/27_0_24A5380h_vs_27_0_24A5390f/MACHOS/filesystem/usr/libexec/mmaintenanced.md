## mmaintenanced

> `/usr/libexec/mmaintenanced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24480` | `0x24d84` | **`+0x904`** |
| `__TEXT.__gcc_except_tab` | `0x864` | `0x96c` | **`+0x108`** |
| `__DATA.__bss` | `0x2d0` | `0x280` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0x2d76` | `0x2dc6` | **`+0x50`** |
| `__TEXT.__const` | `0x7f8` | `0x7b8` | **`-0x40`** |
| `__TEXT.__cstring` | `0x1bbd` | `0x1bfd` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x9d0` | `0xa00` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1438` | `0x1458` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x13c0` | `0x13e0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x9f0` | `0xa00` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x240` | `0x238` | **`-0x8`** |
| `__TEXT.__init_offsets` | `0x8` | `0x4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-233.0.0.502.1
+233.0.5.0.0

-  Functions: 695
+  Functions: 698

-  CStrings:  478
+  CStrings:  485
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MemoryMaintenance/install/TempContent/Objects/MemoryMaintenance.build/mmaintenanced.build/Objects-normal/arm64e/ecc_api.o
+ _Z21migrate_file_locationRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEES7_16migrate_option_t
+ _Z32setup_environment_for_ecc_daemonv
+ _Z37update_path_ownership_and_permissionsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEjjtb
+ __Z21migrate_file_locationRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEES7_16migrate_option_t
+ __Z29system_supports_ecc_reportingv
+ __Z32setup_environment_for_ecc_daemonv
+ __Z37update_path_ownership_and_permissionsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEjjtb
+ __ZN3ecc9constants5paths13retired_db_v1L9full_pathEv
+ __ZN3ecc9constants5paths13retired_db_v2L9full_pathEv
+ __ZN3ecc9constants5paths16cumulative_db_v2L9full_pathEv
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE17__assign_externalEPKcm
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE21__grow_by_and_replaceEmmmmmmPKc
+ __ZNSt3__14__fs10filesystem4pathC2B9fqe220106INS_17basic_string_viewIcNS_11char_traitsIcEEEEvEERKT_NS2_6formatE
+ _getpwnam
+ ecc_api.cpp
- _GLOBAL__sub_I_ecc_logging.cpp
- _Z23validate_file_ownershipRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEjj
- _Z25validate_file_permissionsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEt
- _Z37update_file_ownership_and_permissionsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEjjt
- _Z46move_file_and_update_permissions_and_ownershipRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEES7_ttt
- __Z16is_ecc_supportedv
- __Z23validate_file_ownershipRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEjj
- __Z25validate_file_permissionsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEt
- __Z37update_file_ownership_and_permissionsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEjjt
- __Z46move_file_and_update_permissions_and_ownershipRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEES7_ttt
- __ZN3ecc9constants5paths13retired_db_v1L4pathE
- __ZN3ecc9constants5paths13retired_db_v2L4pathE
- __ZN3ecc9constants5paths16cumulative_db_v2L4pathE
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEED1Ev
- __ZNSt3__14__fs10filesystem4pathC2B9fqe220106INS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEvEERKT_NS2_6formatE
- __ZNSt3__1plB9fqe220106IcNS_11char_traitsIcEENS_9allocatorIcEEEENS_12basic_stringIT_T0_T1_EERKS9_SB_
CStrings:
+ "/var/db/mmaintenanced/"
+ "Created database directory at '%s'."
+ "Failed to create directory '%s': %d (%s)"
+ "Failed to migrate database from '%s' to '%s'."
+ "Failed to query data for '%s': (%d) %s"
+ "Failed to update ownership/permissions for '%s'"
+ "Failed to update permisions to %04o and/or user/group ownership to %d/%d for '%s'."
+ "dramecc.db"
+ "memory_errors.db"
+ "mobile"
+ "vm.ecc.enabled"
- "Failed to update permissions to %04o and/or user/group ownership to %d/%d for '%s'."
- "Failed to update permissions to %04o for '%s': %d (%s)"
- "Failed to update user/group ownership to %d/%d for '%s': %d (%s)"
- "dram-ecc"
```
