## libxpc.dylib

> `/usr/lib/system/libxpc.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x530c8` | `0x53010` | **`-0xb8`** |
| `__DATA_CONST.__const` | `0x1e20` | `0x1e30` | **`+0x10`** |

### Other Changes

```diff

-3295.0.0.502.1
+3298.0.4.502.1
Functions:
~ __xpc_graph_deserializer_skip_value : 180 -> 184
~ __xpc_interface_routine : 1596 -> 1584
~ __XPC_MISUSE_FAULT : 628 -> 632
~ _launch_activate_socket : 800 -> 796
~ __launch_enable_or_disable_directory : 1124 -> 1120
~ _launch_bootout_user_service_4coresim_with_flags : 1240 -> 1236
~ __print_disable_error : 268 -> 264
~ __print_enable_error : 268 -> 264
~ ____launch_domain_routine_async_block_invoke_2 : 512 -> 508
~ __xpc_deserialize_from_wire_id : 160 -> 164
~ _xpc_copy : 300 -> 296
~ _xpc_copy_debug_description : 1000 -> 996
~ __xpc_array_copy : 128 -> 124
~ __xpc_array_equal : 148 -> 140
~ __xpc_array_hash : 104 -> 100
~ __xpc_array_desc : 868 -> 864
~ __xpc_array_debug_desc : 1568 -> 1560
~ __xpc_array_serialize : 700 -> 696
~ __xpc_array_dispose : 96 -> 92
~ _xpc_array_apply_f : 140 -> 136
~ _xpc_array_create : 272 -> 268
~ _xpc_array_apply : 232 -> 228
~ _xpc_array_set_int64 : 452 -> 448
~ _xpc_array_get_int64 : 276 -> 272
~ _xpc_array_get_uint64 : 276 -> 272
~ __xpc_traverse_array : 440 -> 432
~ __xpc_traverse_simple : 540 -> 544
~ _launch_data_alloc : 484 -> 480
~ _launch_data_new_integer : 188 -> 184
~ _launch_data_get_integer : 196 -> 192
~ _launch_data_get_errno : 196 -> 192
~ _xpc_get_service_uid_for_token : 892 -> 888
~ _xpc_event_publisher_get_subscriber_asid : 748 -> 744
~ _xpc_event_publisher_set_event : 1052 -> 1048
~ __xpc_event_publisher_set_subscriptions : 2028 -> 2076
~ _xpc_event_publisher_create_subscription : 1032 -> 1028
~ ____xpc_event_publisher_setup_poll_block_invoke_2 : 636 -> 632
~ ____xpc_event_publisher_fire_impl_block_invoke : 600 -> 612
~ ____xpc_event_publisher_create_connection_block_invoke : 344 -> 356
~ ____xpc_event_publisher_check_and_update_inflight_count_block_invoke : 292 -> 304
~ __xpc_connection_copy_listener_port : 612 -> 608
~ __xpc_connection_pack_message : 300 -> 296
~ __xpc_data_print_bytes_string : 380 -> 388
~ __xpc_user_sessions_info_routine : 1248 -> 1240
~ __xpc_dictionary_copy : 324 -> 320
~ __xpc_dictionary_equal : 340 -> 336
~ __xpc_dictionary_hash : 300 -> 296
~ __xpc_dictionary_desc : 884 -> 880
~ __xpc_dictionary_debug_desc : 728 -> 724
~ __xpc_dictionary_serialize : 420 -> 416
~ __xpc_dictionary_dispose : 500 -> 496
~ __xpc_dictionary_extract_reply_port : 60 -> 64
~ _xpc_dictionary_apply_f : 304 -> 300
~ __xpc_dictionary_apply_node_f : 288 -> 284
~ _xpc_dictionary_expects_reply : 64 -> 60
~ _xpc_dictionary_create : 128 -> 144
~ __xpc_dictionary_insert : 2004 -> 2012
~ _xpc_dictionary_apply : 408 -> 404
~ _xpc_dictionary_get_remote_connection : 104 -> 96
~ _xpc_dictionary_set_int64 : 544 -> 540
~ _xpc_dictionary_set_uint64 : 532 -> 528
~ __xpc_dictionary_look_up_fast : 508 -> 504
~ _xpc_dictionary_get_int64 : 288 -> 284
~ _xpc_dictionary_get_uint64 : 284 -> 280
~ __xpc_dictionary_desc_apply : 1388 -> 1396
~ __xpc_dictionary_serialize_apply : 540 -> 536
~ __xpc_dictionary_look_up_wire_apply : 496 -> 500
~ _vproc_swap_integer : 712 -> 708
~ __xpc_int64_equal : 364 -> 356
~ __xpc_int64_hash : 252 -> 248
~ __xpc_int64_desc : 328 -> 324
~ __xpc_int64_debug_desc : 340 -> 336
~ __xpc_int64_debug : 248 -> 244
~ __xpc_int64_serialize : 260 -> 256
~ __xpc_int64_deserialize : 220 -> 216
~ _xpc_int64_create : 188 -> 184
~ _xpc_int64_get_value : 196 -> 192
~ __xpc_uint64_equal : 364 -> 356
~ __xpc_uint64_hash : 252 -> 248
~ __xpc_uint64_desc : 328 -> 324
~ __xpc_uint64_debug_desc : 340 -> 336
~ __xpc_uint64_debug : 248 -> 244
~ __xpc_uint64_serialize : 260 -> 256
~ __xpc_uint64_deserialize : 212 -> 208
~ _xpc_uint64_create : 176 -> 172
~ _xpc_uint64_get_value : 196 -> 192
~ __xpc_string_cache_desc : 340 -> 348
~ __xpc_string_cache_free_entries : 100 -> 104
~ ____xpc_init_pid_domain_process_initial_images_block_invoke : 248 -> 244
~ __xpc_collect_environment : 216 -> 224
~ __xpc_dyld_image_callback : 564 -> 576
~ ____xpc_start_listeners_block_invoke : 168 -> 164
~ __xpc_serializer_cleanup : 248 -> 244
~ __xpc_serializer_apply : 432 -> 424
~ _launch_trial_factors_active_reload : 456 -> 452
~ ____create_with_format_and_arguments_block_invoke_2.40 : 1612 -> 1608
~ __removal_reply_event : 416 -> 412
~ __translate_attrs : 1392 -> 1384
~ _launch_copy_busy_extension_instances : 560 -> 564
~ _ce_element_array_free : 104 -> 108
~ _xpc_create_lwcr_query_for_validation_category : 180 -> 188
~ _serialize_xpc_dict : 768 -> 760
~ _serialize_xpc_object : 944 -> 940
~ __transaction_snapshot_new_locked : 348 -> 364
~ __os_transaction_log_snapshot : 832 -> 820
~ __xpc_bundle_resolve_path_variant : 264 -> 280
~ _xpc_add_bundle_with_lwcr : 584 -> 580
~ _xpc_add_bundles_for_domain : 536 -> 532
~ __xpc_spawnattr_unpack_strings : 160 -> 164
~ __xpc_spawnattr_binprefs_pack : 380 -> 392
~ _xpc_create_from_plist_with_string_cache : 7892 -> 7932
~ __xpc_plist_swap_int : 172 -> 180
~ __xpc_plist_parse_data : 288 -> 296
~ __xpc_plist_offset_of_object : 264 -> 276
~ __xpc_xml_lex : 1032 -> 1036
~ __xpc_xml_replace_entities : 828 -> 848
~ __xpc_bundle_desc : 2360 -> 2352
~ _xpc_bundle_copy_normalized_cryptex_path : 368 -> 348
~ __xpc_bundle_normalize_cryptex_path : 388 -> 384
~ __xpc_realpath_cryptex : 420 -> 416
~ __xpc_file_transfer_serialize : 1196 -> 1192
~ _xpc_file_transfer_get_size : 368 -> 364
~ __launch_service_stats_copy_impl : 1436 -> 1428
~ __xpc_service_attach_event : 1320 -> 1308
~ ___xpc_activity_set_criteria_block_invoke : 1160 -> 1156
~ __xpc_activity_set_criteria : 1500 -> 1492
~ __xpc_activity_dispatch : 1840 -> 1836
~ ___xpc_activity_run_block_invoke_2 : 364 -> 360
~ ___xpc_activity_debug_block_invoke_2 : 364 -> 360
~ __xpc_activity_normalize_integer : 544 -> 536
~ __xpc_activity_set_state_from_cts : 744 -> 740
~ __objectForActiveContext : 676 -> 672
~ _xpc_format_specifiers_lookup : 176 -> 172
~ _CESerializeWithOptions : 584 -> 604
~ _der_vm_execute_nocopy : 3004 -> 2988
~ _der_vm_execute_match_string : 256 -> 252
~ _der_vm_execute_match_string_prefix : 276 -> 272
~ _string_value_allowed_iterate : 316 -> 312
~ _string_prefix_allowed_iterate : 244 -> 240
~ __objc_getTaggedPointerTag.980 : 100 -> 96
```
