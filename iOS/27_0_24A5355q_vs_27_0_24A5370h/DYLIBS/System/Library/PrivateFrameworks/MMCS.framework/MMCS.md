## MMCS

> `/System/Library/PrivateFrameworks/MMCS.framework/MMCS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f754` | `0x7f580` | **`-0x1d4`** |
| `__TEXT.__unwind_info` | `0x1570` | `0x1568` | **`-0x8`** |

### Other Changes

```diff

-2700.108.0.0.0
+2700.109.0.0.0
Functions:
~ _MMCSOperationMetricCombineMetrics : 1608 -> 1596
~ _mmcs_operation_metric_add_uint64_dictionary : 332 -> 328
~ _MMCSOperationStateTimeRangeMergedRanges : 668 -> 664
~ __mmcs_read_stream_poolCFFinalize : 1480 -> 1476
~ __mmcs_request_queueCFFinalize : 740 -> 736
~ _mmcs_request_queue_init : 420 -> 440
~ _mmcs_local_chunk_satisfyer_perform : 3472 -> 3468
~ _mmcs_case_insensitive_set_create : 396 -> 408
~ _mmcs_base64_encode_cfdata_to_cstring : 408 -> 404
~ _mmcs_base64_encoded_cstring_to_cfdata : 716 -> 728
~ _mmcs_nshttp_did_open : 804 -> 800
~ _XCFPrintDictionary : 784 -> 768
~ _send_request_downloadChunks : 3352 -> 3356
~ _mmcs_get_req_is_using_itemid : 104 -> 108
~ _file_groups_message_file_count : 424 -> 420
~ _mmcs_get_req_process_another_file_groups_message : 2576 -> 2564
~ _mmcs_get_container_create : 1800 -> 1792
~ _mmcs_get_container_add_ford_instance : 1172 -> 1180
~ _mmcs_get_container_add_chunk_instance : 1580 -> 1588
~ _mmcs_get_container_get_body_size : 176 -> 184
~ _mmcs_get_container_process_data : 7712 -> 7720
~ _mmcs_time_convert_date_header_to_cfabsolutetime : 288 -> 296
~ _mmcs_get_file_compute_remaining_work : 4084 -> 4040
~ _mmcs_get_file_fulfill_locally : 1060 -> 1040
~ _mmcs_get_request_set_progress_and_notify_all_items_not_done : 140 -> 144
~ _mmcs_get_request_notify_all_items_with_pending_progress : 108 -> 112
~ _mmcs_get_req_create : 3436 -> 3296
~ _mmcs_get_request_finalize : 620 -> 624
~ _mmcs_get_request_has_items_not_done : 68 -> 84
~ _mmcs_get_req_call_client_request_completed : 968 -> 972
~ _mmcs_get_req_context_log_timing : 5216 -> 5204
~ _mmcs_get_state_dealloc : 280 -> 272
~ _mmcs_get_file_omit_containers_not_needed : 904 -> 912
~ _mmcs_get_state_process_file_list : 9580 -> 9532
~ _mmcs_get_state_setup_derivative_files_and_containers : 556 -> 548
~ _file_skip_container_and_get_chunks : 296 -> 280
~ _mmcs_cferror_create_with_swiss_army_knife : 416 -> 424
~ _mmcs_http_msg_add_item_token_header : 164 -> 160
~ _mmcs_http_msg_add_items_token_header_simulcast : 140 -> 164
~ __item_by_signature_description : 372 -> 368
~ _mmcs_item_copy_chunk_instances_from_item : 528 -> 524
~ _mmcs_item_get_start_chunk_index_for_inner_item : 152 -> 160
~ _mmcs_item_copy_ford_state_from_item : 228 -> 232
~ _mmcs_item_append_chunk_instance : 528 -> 548
~ _mmcs_item_setup_chunk_references : 536 -> 508
~ _mmcs_item_setup_item_size : 164 -> 160
~ _mmcs_item_setup_item_padded_size : 160 -> 156
~ _mmcs_free_FileChunkList : 216 -> 208
~ _mmcs_free_FileChunkLists : 132 -> 128
~ _mmcs_put_request_create_FileChunkLists : 1944 -> 1892
~ _mmcs_register_request_create_FileChunkLists : 2752 -> 2716
~ _mmcs_update_request_create_AuthorizePutRequestBody : 1836 -> 1832
~ _create_cferror_with_error_response : 624 -> 616
~ _mmcs_create_FileReferenceData : 344 -> 340
~ _schedulePutComplete : 3356 -> 3352
~ _mmcs_put_request_all_put_completes_done : 300 -> 296
~ _mmcs_put_request_process_put_authorization_data : 1720 -> 1716
~ _send_request_uploadChunks : 728 -> 724
~ _mmcs_put_items : 1136 -> 1132
~ _ub_dirname_alloced : 300 -> 296
~ _mmcs_put_req_copy_client_stats : 404 -> 408
~ _mmcs_put_req_context_create : 2700 -> 2736
~ _mmcs_put_req_context_has_items_to_put : 108 -> 112
~ _mmcs_put_req_context_init_items : 1232 -> 1236
~ _mmcs_put_req_context_init_item_with_chunks : 1384 -> 1364
~ _mmcs_put_request_finalize : 448 -> 452
~ _mmcs_put_request_stop_with_error : 1012 -> 1004
~ _mmcs_put_request_append_description : 412 -> 408
~ _mmcs_put_req_is_using_itemid : 104 -> 108
~ _mmcs_put_request_set_progress_and_notify_all_items_not_done : 140 -> 144
~ _mmcs_put_request_has_items_not_done : 68 -> 84
~ _mmcs_put_request_notify_all_items_with_pending_progress : 108 -> 112
~ _mmcs_put_state_invalidate : 80 -> 76
~ _mmcs_put_state_create : 7136 -> 7016
~ _mmcs_put_state_dealloc : 228 -> 216
~ _mmcs_put_state_has_outstanding_async_transactions : 92 -> 104
~ _mmcs_put_state_containers_done_count : 108 -> 104
~ _mmcs_put_state_containers_failed_count : 108 -> 104
~ _mmcs_put_state_get_put_container_for_storage_container_key : 120 -> 116
~ _mmcs_put_state_copy_error_for_failed_containers : 224 -> 220
~ _mmcs_put_state_process_storage_container_error_list : 624 -> 612
~ _mmcs_put_state_process_clone_complete : 140 -> 132
~ _hextostrdup : 156 -> 160
~ _strtohex : 152 -> 148
~ _MMCSGetItemsWithSection : 1536 -> 1528
~ _MMCSRegisterFilesWithOptions : 1488 -> 1512
~ _MMCSRegisterFiles : 412 -> 424
~ _MMCSUnregisterFilesInWorkingDirectory : 876 -> 872
~ -[MMCSOperationMetric rangesCompleted] : 324 -> 320
~ _mmcs_update_items : 1692 -> 1688
~ _handle_response_get_chunk_keys : 4296 -> 4288
~ _mmcs_http_request_create_with_host_info : 4020 -> 4016
~ _mmcs_zcmp : 244 -> 268
~ _mmcs_request_queue_schedule : 2760 -> 2744
~ _mmcs_request_queue_request_did_complete : 1960 -> 1968
~ _mmcs_request_queue_request_cancel_all_queued_and_inflight_requests : 248 -> 244
~ _mmcs_request_queue_copy_description : 204 -> 200
~ _mmcs_network_activity_estimate_bandwidth_network_activity_applier : 412 -> 420
~ _mmcs_request_queue_entry_estimate_bandwidth : 532 -> 536
~ _repeated_field_pack : 1412 -> 1404
~ _protobuf_c_message_unpack : 3048 -> 3044
```
