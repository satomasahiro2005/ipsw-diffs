## cksharingmanagementd

> `/System/Library/PrivateFrameworks/CKSharingManagementDaemon.framework/Support/cksharingmanagementd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c0` | `0x720` | **`+0x260`** |
| `__TEXT.__auth_stubs` | `0x1e0` | `0x2a0` | **`+0xc0`** |
| `__DATA_CONST.__auth_got` | `0xf8` | `0x158` | **`+0x60`** |
| `__TEXT.__const` | `0x46` | `0x56` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x70` | `0x78` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `—` | `0x4` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `—` | `0x4` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `—` | `0x4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-23.0.0.0.0
+26.0.0.0.0

-  Functions: 4
-  Symbols:   52
+  Functions: 8
+  Symbols:   65
Symbols:
+ _$s25CKSharingManagementDaemon21CKShareManagerServiceC6sharedACvgZ
+ _$s25CKSharingManagementDaemon21CKShareManagerServiceC9bootstrapyyYaF
+ _$s25CKSharingManagementDaemon21CKShareManagerServiceC9bootstrapyyYaFTu
+ _$s25CKSharingManagementDaemon22BootstrapEventListenerC5start19systemTaskScheduler16setStreamHandler7handleryAA06SystemiJ8Protocol_p_ySPys4Int8VG_So17OS_dispatch_queueCSgySo0R11_xpc_object_pYbctXEyyYaYbctF
+ _$s25CKSharingManagementDaemon22BootstrapEventListenerC5start19systemTaskScheduler16setStreamHandler7handleryAA06SystemiJ8Protocol_p_ySPys4Int8VG_So17OS_dispatch_queueCSgySo0R11_xpc_object_pYbctXEyyYaYbctFfA0_
+ _$s25CKSharingManagementDaemon22BootstrapEventListenerC5start19systemTaskScheduler16setStreamHandler7handleryAA06SystemiJ8Protocol_p_ySPys4Int8VG_So17OS_dispatch_queueCSgySo0R11_xpc_object_pYbctXEyyYaYbctFfA_
+ _$s25CKSharingManagementDaemon22BootstrapEventListenerC6sharedACvgZ
+ _$s25CKSharingManagementDaemon22BootstrapEventListenerCMa
+ _swift_release
+ _swift_release_x24
+ _swift_task_alloc
+ _swift_task_dealloc
+ _swift_task_switch
```
