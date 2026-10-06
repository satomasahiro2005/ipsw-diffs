## libmdns.dylib

> `/usr/lib/libmdns.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x31168` | `0x32948` | **`+0x17e0`** |
| `__AUTH_CONST.__const` | `0x1380` | `0x1480` | **`+0x100`** |
| `__TEXT.__cstring` | `0x21c9` | `0x22c3` | **`+0xfa`** |
| `__TEXT.__oslogstring` | `0x38e8` | `0x39ca` | **`+0xe2`** |
| `__DATA_CONST.__const` | `0x2ab8` | `0x2b48` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x9e0` | `0xa30` | **`+0x50`** |
| `__DATA.__bss` | `0x338` | `0x358` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xf18` | `0xf28` | **`+0x10`** |
| `__TEXT.__const` | `0x1d0` | `0x1e0` | **`+0x10`** |

### Other Changes

```diff

-3111.0.5.0.1
+3111.40.40.0.0

-  Functions: 853
-  Symbols:   2071
-  CStrings:  892
+  Functions: 877
+  Symbols:   2105
+  CStrings:  906
Symbols:
+ GCC_except_table229
+ GCC_except_table423
+ GCC_except_table427
+ GCC_except_table700
+ _CFDictionaryApplyFunction
+ _CFDictionaryRemoveAllValues
+ ____mdns_clock_log_block_invoke
+ ____mdns_domain_name_log_block_invoke
+ ____mdns_domain_name_offset_map_copy_description_block_invoke
+ ___mdns_message_builder_write_message_block_invoke
+ __mdns_clock_log.s_log
+ __mdns_clock_log.s_once
+ __mdns_domain_name_log.s_log
+ __mdns_domain_name_log.s_once
+ __mdns_domain_name_offset_map_applier_function
+ __mdns_domain_name_offset_map_copy_description
+ __mdns_domain_name_offset_map_finalize
+ __mdns_domain_name_offset_map_kind
+ __mdns_message_builder_copy_description
+ __mdns_message_builder_finalize
+ __mdns_message_builder_kind
+ __mdns_message_builder_write_record
+ __mdns_pf_create_thread_conn_tracking_rule_dictionary
+ __mdns_resource_record_copy_description
+ __mdns_resource_record_copy_description_bytes
+ __mdns_resource_record_finalize
+ __mdns_resource_record_kind
+ _mdns_clock_uptime_ns
+ _mdns_domain_name_append_to_copier
+ _mdns_domain_name_offset_map_create.key_callbacks
+ _mdns_message_builder_append_answer_record
+ _mdns_message_builder_create
+ _mdns_message_builder_set_aa_bit
+ _mdns_message_builder_set_qr_bit
+ _mdns_message_builder_write_message
+ _mdns_resource_record_create
+ _mdns_resource_record_get_rdata_bytes_ptr
+ _mdns_resource_record_get_rdata_length
- GCC_except_table227
- GCC_except_table415
- GCC_except_table419
- GCC_except_table682
CStrings:
+ "%s\n\t%s: %u"
+ "<NO RDATA>"
+ "B16@?0r^{mdns_resource_record_s=}8"
+ "B20@?0r^{mdns_domain_name_s={mdns_obj_s=^vii^{mdns_kind_s}}*Q*i{os_unfair_lock_s=I}IBB[2c]}8S16"
+ "Failed to create domain name object: %{mdns:err}ld"
+ "Failed to insert domain name offset map pair: %{mdns:err}ld"
+ "PFUserAddRule() for TCP connection tracking failed"
+ "PFUserAddRule() for UDP connection tracking failed"
+ "clock"
+ "clock_gettime_nsec_np(CLOCK_UPTIME_RAW) error: %{mdns:err}d"
+ "domain_name"
+ "mdns_domain_name_offset_map"
+ "mdns_message_builder"
+ "mdns_resource_record"
+ "«NAME»"
- "PFUserAddRule() for connection tracking failed"
```
