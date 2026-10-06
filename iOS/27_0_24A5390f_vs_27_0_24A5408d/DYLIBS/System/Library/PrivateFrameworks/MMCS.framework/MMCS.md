## MMCS

> `/System/Library/PrivateFrameworks/MMCS.framework/MMCS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__gcc_except_tab` | `0x63c` | `0x384` | **`-0x2b8`** |
| `__TEXT.__text` | `0x7f620` | `0x7f478` | **`-0x1a8`** |
| `__TEXT.__cstring` | `0x177ed` | `0x178c2` | **`+0xd5`** |
| `__AUTH_CONST.__const` | `0x2d10` | `0x2d88` | **`+0x78`** |
| `__AUTH_CONST.__cfstring` | `0xcee0` | `0xce80` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x53d0` | `0x5410` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0xe68` | `0xe88` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1598` | `0x15a8` | **`+0x10`** |

### Other Changes

```diff

-2700.109.0.0.0
+2700.112.0.0.0

-  Functions: 2401
-  Symbols:   3295
-  CStrings:  2988
+  Functions: 2418
+  Symbols:   3310
+  CStrings:  2990
Symbols:
+ GCC_except_table20
+ GCC_except_table27
+ GCC_except_table32
+ GCC_except_table36
+ _MMCSHTTPContextAssertCurrent
+ _MMCSHTTPContextPerformBlockAsync
+ _MMCSHTTPContextPerformBlockSync
+ ___MMCSHTTPContextPerformBlockAsync_block_invoke
+ ___MMCSHTTPContextPerformBlockSync_block_invoke
+ ___block_descriptor_64_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
+ ___block_descriptor_64_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___mmcs_perform_run_loop_target_sync_block_invoke
+ ___mmcs_report_close_block_invoke
+ __os_crash
+ _dispatch_assert_queue$V2
+ _dispatch_assert_queue_not$V2
+ _dispatch_sync
+ _mmcs_container_recorded_completion_info_count
+ _mmcs_get_complete_create_request_body
+ _mmcs_http_context_copy_perform_target
+ _mmcs_perform_dispatch_target_assert_current
+ _mmcs_perform_dispatch_target_assert_current_debug
+ _mmcs_perform_dispatch_target_assert_not_current
+ _mmcs_perform_dispatch_target_assert_not_current_debug
+ _mmcs_perform_dispatch_target_sync
+ _mmcs_perform_run_loop_target_assert_current
+ _mmcs_perform_run_loop_target_assert_current_debug
+ _mmcs_perform_run_loop_target_assert_not_current
+ _mmcs_perform_run_loop_target_assert_not_current_debug
+ _mmcs_perform_run_loop_target_sync
+ _mmcs_perform_target_assert_not_current
+ _mmcs_perform_target_sync
+ _mmcs_request_queue_set_max_requests_inflight
+ _mmcs_request_queue_set_requests_inflight
+ _objc_retain_x24
- GCC_except_table1
- GCC_except_table11
- GCC_except_table21
- GCC_except_table28
- GCC_except_table34
- GCC_except_table4
- GCC_except_table9
- _HttpContextPerformBlockAsync
- _HttpContextPerformBlockSync
- ___39-[MMCSHTTPContext invalidateStreamPair]_block_invoke
- ___Block_byref_object_copy_
- ___Block_byref_object_dispose_
- ___HttpContextPerformBlockAsync_block_invoke
- ___HttpContextPerformBlockSync_block_invoke
- ___block_descriptor_48_e8_32r40r_e5_v8?0lr32l8r40l8
- ___block_descriptor_56_e8_32s40bs_e5_v8?0ls32l8s40l8
- ___block_descriptor_64_e8_32s_e5_v8?0ls32l8
- _kMMCSEnginePropertyTestMaxInflightContainerRequests
- _mmcs_request_queue_set_test_max_requests_inflight
- _mmcs_request_queue_set_test_requests_inflight
- _objc_release_x9
CStrings:
+ "MMCSHTTPContextAssertCurrent"
+ "MMCSHTTPContextPerformBlockAsync"
+ "MMCSHTTPContextPerformBlockSync"
+ "mmcs runloop: %@ invalid: calling completionHandler with NSURLSessionResponseCancel"
+ "mmcs runloop: %@ invalid: calling completionHandler with nil"
+ "mmcs runloop: %@ invalid: calling completionHandler with nil request"
+ "mmcs runloop: %@ unknown task %@. Expected %@: ignoring delegate callback"
+ "mmcs_container_recorded_completion_info_count"
+ "mmcs_get_complete_create_request_body"
+ "mmcs_perform_target: current thread is not executing on the expected run loop"
+ "mmcs_perform_target: current thread is unexpectedly executing on the run loop it must not be confined to"
+ "mmcs_perform_target_sync"
- "%@ invalid: calling completionHandler with NSURLSessionResponseCancel"
- "%@ invalid: calling completionHandler with nil"
- "%@ invalid: calling completionHandler with nil request"
- "%@ invalid: ignoring delegate callback"
- "%@ unknown task %@. Expected %@: ignoring delegate callback"
- "HttpContextPerformBlockAsync"
- "HttpContextPerformBlockSync"
- "getCompleteRequestBodyCreate"
- "kMMCSEnginePropertyTestMaxInflightContainerRequests"
- "mmcs runloop: %@ invalid. Returning nil body stream"
```
