## libsystem_kernel.dylib

> `/usr/lib/system/libsystem_kernel.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34ec0` | `0x34ee0` | **`+0x20`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-13361.0.0.502.1
+13432.0.5.502.4
Functions:
~ _os_channel_get_next_slot : 1012 -> 1004
~ _os_channel_packet_free : 396 -> 400
~ _os_channel_packet_pool_purge : 752 -> 744
~ _os_channel_purge_packet_alloc_ring_common : 664 -> 652
~ ___libkernel_init : 396 -> 392
~ _posix_spawnattr_set_importancewatch_port_np : 148 -> 156
~ _posix_spawnattr_set_persona_groups_np : 104 -> 112
~ _mach_error_string_int : 348 -> 360
~ _thread_get_exception_ports : 708 -> 716
~ _posix_spawnattr_set_groups_np : 260 -> 268
~ _os_cpu_in_cksum : 256 -> 240
~ _task_get_exception_ports : 708 -> 716
~ _posix_spawnattr_setmacpolicyinfo_np : 448 -> 468
~ _task_swap_exception_ports : 808 -> 812
~ __libkernel_memmove : 280 -> 272
~ __posix_spawn_with_filter : 1888 -> 1876
~ _port_for_id_internal : 184 -> 180
~ _mach_error_type : 200 -> 208
~ __mach_vsnprintf : 396 -> 392
~ _posix_spawnattr_getarchpref_np : 116 -> 120
~ _posix_spawnattr_setbinpref_np : 168 -> 184
~ _posix_spawnattr_setarchpref_np : 172 -> 188
~ _posix_spawnattr_set_registered_ports_np : 148 -> 156
~ _posix_spawnattr_getmacpolicyinfo_np : 192 -> 212
~ _posix_spawnattr_set_jetsam_ttr_np : 184 -> 188
~ _os_channel_get_next_event_handle : 912 -> 908
~ _os_channel_buflet_alloc : 560 -> 552
~ _os_channel_buflet_free : 400 -> 404
~ _debug_syscall_reject_config : 276 -> 280
~ _proc_listpidspath : 2912 -> 2864
~ _exc_server_routine : 52 -> 56
~ _exc_server : 140 -> 144
~ _host_get_boot_info : 528 -> 536
~ _host_get_exception_ports : 708 -> 716
~ _host_swap_exception_ports : 808 -> 812
~ _host_kernel_version : 512 -> 520
~ __kernelrpc_mach_port_kobject_description : 568 -> 576
~ _netname_check_in : 428 -> 416
~ _netname_look_up : 596 -> 588
~ _netname_check_out : 424 -> 404
~ _netname_version : 416 -> 420
~ _thread_swap_exception_ports : 808 -> 812
~ __simple_getenv : 148 -> 144
~ __simple_getenv.19 : 152 -> 148
CStrings:
+ "Neural Engine"
- "VM_MEMORY_109"
```
