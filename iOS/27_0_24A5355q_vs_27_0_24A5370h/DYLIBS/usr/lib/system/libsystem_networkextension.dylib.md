## libsystem_networkextension.dylib

> `/usr/lib/system/libsystem_networkextension.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15838` | `0x15800` | **`-0x38`** |

### Other Changes

```diff

-2303.0.0.0.2
+2315.0.0.0.2
Functions:
~ _ne_session_set_socket_attributes : 416 -> 412
~ _ne_session_agent_get_advisory : 320 -> 316
~ _necp_drop_dest_copy_dest_entry_list : 1492 -> 1504
~ _ne_session_create_xpc_string_from_necp_level : 104 -> 112
~ _ne_session_get_necp_level_from_xpc_value : 132 -> 148
~ _ne_session_agent_get_advisory_interface_index : 180 -> 176
~ _ne_copy_signing_identifier_for_pid_with_audit_token : 648 -> 644
~ _ne_session_set_socket_tracker_attributes : 588 -> 580
~ _ne_tracker_domain_is_known_tracker : 1008 -> 1004
~ _ne_tracker_validate_domain : 1596 -> 1592
~ _ne_trie_has_high_ascii : 44 -> 52
~ _ne_trie_insert : 2532 -> 2492
~ _ne_trie_search : 960 -> 932
```
