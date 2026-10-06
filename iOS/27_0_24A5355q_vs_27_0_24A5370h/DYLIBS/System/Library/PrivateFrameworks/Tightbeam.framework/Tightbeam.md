## Tightbeam

> `/System/Library/PrivateFrameworks/Tightbeam.framework/Tightbeam`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e70c` | `0x3f5c0` | **`+0xeb4`** |
| `__DATA_CONST.__const` | `0x438` | `0x568` | **`+0x130`** |
| `__AUTH_CONST.__const` | `0x38a0` | `0x3998` | **`+0xf8`** |
| `__TEXT.__swift5_reflstr` | `0xa79` | `0xb49` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x53fb` | `0x54ab` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0x1090` | `0x1120` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x13ac` | `0x1438` | **`+0x8c`** |
| `__TEXT.__const` | `0x23d8` | `0x2438` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0xc98` | `0xce8` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0xe24` | `0xe6e` | **`+0x4a`** |
| `__TEXT.__constg_swiftt` | `0x18a8` | `0x18e8` | **`+0x40`** |
| `__TEXT.__swift5_builtin` | `0x1f4` | `0x21c` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0xae8` | `0xaf8` | **`+0x10`** |
| `__DATA.__data` | `0x408` | `0x418` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x18c` | `0x194` | **`+0x8`** |

### Other Changes

```diff

-627.0.0.0.0
+631.0.0.0.2

-  Functions: 2043
-  Symbols:   1247
-  CStrings:  404
+  Functions: 2072
+  Symbols:   1281
+  CStrings:  411
Symbols:
+ ____ZL40_tb_afk_interface_transport_send_messageP14tb_transport_sP12tb_message_sPS2_21tb_connection_flags_t_block_invoke
+ ____accumulator_destructor_block_invoke
+ ____find_or_create_accumulator_scoped_block_invoke
+ ____find_or_create_accumulator_scoped_block_invoke_2
+ ____tb_service_connection_create_with_blocks_block_invoke
+ ___swift_memcpy56_8
+ ___tb_client_connection_create_with_invalidation_handler_block_invoke
+ ___tb_list_find_or_create_scoped_block_invoke
+ ___tb_mach_client_transport_create_block_invoke
+ ___tb_message_accumulator_accumulate_block_invoke
+ __alloc_tracked_service_connection
+ __dispatch_source_type_mach_send
+ __find_or_create_accumulator_scoped
+ __invoke_arrival_block
+ __invoke_departure_block
+ __invoke_message_handler_block
+ __iterate_list_locked
+ __tracking_message_handler_f
+ _dispatch_resume
+ _dispatch_source_cancel_and_wait
+ _dispatch_source_get_handle
+ _symbolic Spy_____G So31tb_tracked_service_connection_sV
+ _symbolic SvSgSv_S2vtXCSg
+ _symbolic _____ So31tb_tracked_service_connection_sV
+ _symbolic _____ So35tb_connection_message_handler_ctx_sV
+ _symbolic ___________SvSgtXC So35tb_connection_message_handler_ctx_sV s6UInt64V
+ _symbolic y______SvSgtXC s6UInt64V
+ _tb_client_connection_create_with_endpoint_invalidation_handler
+ _tb_client_connection_create_with_endpoint_invalidation_handler_f
+ _tb_client_connection_create_with_endpoint_static_invalidation_handler_f
+ _tb_client_connection_create_with_invalidation_handler
+ _tb_client_connection_create_with_invalidation_handler_f
+ _tb_list_find_or_create_scoped
+ _tb_null_transport_retain
+ _tb_tracked_service_connection_create_f
+ _tb_tracked_service_connection_create_with_endpoint_f
+ _type_layout_string So31tb_tracked_service_connection_sV
+ _type_layout_string So35tb_connection_message_handler_ctx_sV
- ____add_accumulator_block_invoke
- __add_accumulator
- __iterate_list
- _objc_retain_x22
CStrings:
+ "B16@?0^v8"
+ "B16@?0^{tb_message_accumulator_s=QQQ*}8"
+ "TB_ASSERT: added"
+ "^v8@?0"
+ "com.apple.tightbeam.mach_transport.channel_q"
+ "com.apple.tightbeam.mach_transport.source_q"
+ "tb_list.c"
+ "v20@?0^{tb_connection_s=(?=[97c]^v)}8I16"
+ "v28@?0i8*12Q20"
- "TB_ASSERT: success"
- "com.apple.tightbeam.mach_transport.q"
```
