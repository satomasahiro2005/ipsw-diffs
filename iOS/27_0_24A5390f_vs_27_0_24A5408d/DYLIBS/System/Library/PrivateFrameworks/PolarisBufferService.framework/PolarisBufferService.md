## PolarisBufferService

> `/System/Library/PrivateFrameworks/PolarisBufferService.framework/PolarisBufferService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5d3f4` | `0x5d25c` | **`-0x198`** |
| `__TEXT.__cstring` | `0x7a49` | `0x7ab9` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0xa99e` | `0xa961` | **`-0x3d`** |
| `__DATA_CONST.__const` | `0x740` | `0x770` | **`+0x30`** |
| `__AUTH.__thread_bss` | `0x8` | `0x28` | **`+0x20`** |
| `__AUTH.__thread_vars` | `0x18` | `0x30` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x690` | `0x6a8` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x2d70` | `0x2d80` | **`+0x10`** |

### Other Changes

```diff

-256.0.3.0.0
+256.0.5.0.0

-  Functions: 1993
-  Symbols:   2263
-  CStrings:  1543
+  Functions: 1992
+  Symbols:   2269
+  CStrings:  1547
Symbols:
+ __ZL16targetModuleNamei
+ __ZN13PSCommsServer12add_cli_infoEPcS0_b15target_module_tP18callback_context_t
+ __ZN20comms_message_recv_t16deallocate_portsEv
+ __ZN20comms_message_recv_t6rejectEv
+ __ZZL16targetModuleNameiE3buf
+ __ZZL16targetModuleNameiE3buf$tlv$init
+ _mach_msg_destroy
+ _objc_release_x26
+ _objc_retain_x26
- __ZN13PSCommsServer12add_cli_infoEPcS0_b
- __ZN13PSCommsServer23invokeRegisteryCallbackE15target_module_tP14comms_cb_arg_t
- _ps_comms_invoke_registry_callback
CStrings:
+ "(unknown:%#x)"
+ "08:48:48"
+ "Aug  4 2026"
+ "PLS_MOD_COMMS_SERVER"
+ "PLS_MOD_MANIFEST_AGENT_SERVICE"
+ "PLS_MOD_RESOURCE_FACTORY"
+ "PLS_MOD_STREAM_SERVER"
+ "PLS_MOD_SYSTEM_TRANSITION_SERVICE"
+ "PLS_MOD_SYS_GRAPH"
+ "PSCommsServer: %s\n"
+ "PSCommsServer: %s not registered for port \"%s\", rejecting"
+ "PSCommsServer: %s on port \"%s\", rejecting"
+ "PSCommsServer: Unknown message received on port \"%s\", msgh_id=%#x, rejecting"
+ "PSCommsServer: cannot register server \"%s\", MAX_CLI_INFO (%d) reached"
+ "reply port %#x\n"
- "%s:%d PSCommsServer: Unknow message recevied! msgh_id=%#x\n"
- "00:47:11"
- "Jul 11 2026"
- "PSCommsServer: PLS_MOD_MANIFEST_AGENT_SERVICE\n"
- "PSCommsServer: PLS_MOD_RESOURCE_FACTORY\n"
- "PSCommsServer: PLS_MOD_STREAM_SERVER\n"
- "PSCommsServer: PLS_MOD_SYSTEM_TRANSITION_SERVICE\n"
- "PSCommsServer: PLS_MOD_SYS_GRAPH\n"
- "PSCommsServer: Unknow message recevied! msgh_id=%#x\n"
- "Resource factory overwriting callback for target module:%u"
- "reply port %d\n"
```
