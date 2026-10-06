## libquic.dylib

> `/usr/lib/libquic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcbf68` | `0xcd378` | **`+0x1410`** |
| `__TEXT.__oslogstring` | `0x11a0b` | `0x11c3e` | **`+0x233`** |
| `__DATA_CONST.__got` | `0x0` | `0x90` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x2508` | `0x2558` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0xcd0` | `0xc90` | **`-0x40`** |
| `__DATA_DIRTY.__bss` | `0x680` | `0x660` | **`-0x20`** |
| `__TEXT.__cstring` | `0x86e0` | `0x8700` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xda8` | `0xdc0` | **`+0x18`** |
| `__DATA.__bss` | `0x528` | `0x520` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xd08` | `0xd10` | **`+0x8`** |

### Other Changes

```diff

-6681.0.436.0.8
+6681.0.498.502.1

-  Functions: 1143
-  Symbols:   1642
-  CStrings:  2579
+  Functions: 1146
+  Symbols:   1648
+  CStrings:  2584
Symbols:
+ ___quic_conn_async_if_needed_block_invoke
+ ___quic_conn_async_if_needed_block_invoke_2
+ _nw_protocol_establishment_report_set_quic_stateless_reset_during_path_probe
+ _nw_protocol_establishment_report_set_quic_stateless_reset_received
+ _nw_protocol_instance_is_flushing
+ _quic_path_mark_migration_intent
CStrings:
+ "%{public}s %{public}s [%{public}s-%{public}s] \n\tConnection attempts: %u, RETRY received: %s, PTOs: %u\n\tEarly data: %s, Migration supported: %s, Keep-alives sent/acknowledged: %u/%u\n\tMigration events: %u, paths validated: %u\n\tStateless reset: received %s, during path probe %s\n\tInbound unidirectional/bidirectional streams: %u/%u\n\tOutbound unidirectional/bidirectional streams: %u/%u\n\tDATA_BLOCKED frames sent/received: %u/%u\n\tSTREAM_DATA_BLOCKED frames sent/received: %u/%u\n"
+ "%{public}s %{public}s [%{public}s-%{public}s] \n\tConnection attempts: %u, RETRY received: %s, PTOs: %u\n\tEarly data: %s, Migration supported: %s, Keep-alives sent/acknowledged: %u/%u, ECN state: %s, L4S: %s\n\tRTT: base %llu ms, network %llu ms, latest %llu ms, minimum %llu ms, smoothed %llu ms (variance %llu ms)\n\tPath MTU: %hu, minimum MSS: %hu\n\tMigration events: %u, paths validated: %u\n\tStateless reset: received %s, during path probe %s\n\tInbound unidirectional/bidirectional streams: %u/%u\n\tOutbound unidirectional/bidirectional streams: %u/%u\n\tDATA_BLOCKED frames sent/received: %u/%u\n\tSTREAM_DATA_BLOCKED frames sent/received: %u/%u\n"
+ "%{public}s %{public}s [%{public}s-%{public}s] cancelling pulse timer; current path is still usable"
+ "%{public}s %{public}s [%{public}s-%{public}s] cannot find alternate path for pmtud; disarming timer"
+ "%{public}s %{public}s [%{public}s-%{public}s] connection in PTO recovery for >= %u ms, closing connection"
+ "%{public}s %{public}s [%{public}s-%{public}s] no better path, but current path is still usable; not declaring it lost"
+ "%{public}s %{public}s [%{public}s-%{public}s] not arming pulse timer on companion path; expecting connectivity to resume"
+ "%{public}s %{public}s [%{public}s-%{public}s] suspending pulse timer while probing path over %{public}s"
+ "quic_path_mark_migration_intent"
- "%{public}s %{public}s [%{public}s-%{public}s] \n\tConnection attempts: %u, RETRY received: %s, PTOs: %u\n\tEarly data: %s, Migration supported: %s, Keep-alives sent/acknowledged: %u/%u\n\tMigration events: %u, paths validated: %u\n\tInbound unidirectional/bidirectional streams: %u/%u\n\tOutbound unidirectional/bidirectional streams: %u/%u\n\tDATA_BLOCKED frames sent/received: %u/%u\n\tSTREAM_DATA_BLOCKED frames sent/received: %u/%u\n"
- "%{public}s %{public}s [%{public}s-%{public}s] \n\tConnection attempts: %u, RETRY received: %s, PTOs: %u\n\tEarly data: %s, Migration supported: %s, Keep-alives sent/acknowledged: %u/%u, ECN state: %s, L4S: %s\n\tRTT: base %llu ms, network %llu ms, latest %llu ms, minimum %llu ms, smoothed %llu ms (variance %llu ms)\n\tPath MTU: %hu, minimum MSS: %hu\n\tMigration events: %u, paths validated: %u\n\tInbound unidirectional/bidirectional streams: %u/%u\n\tOutbound unidirectional/bidirectional streams: %u/%u\n\tDATA_BLOCKED frames sent/received: %u/%u\n\tSTREAM_DATA_BLOCKED frames sent/received: %u/%u\n"
- "%{public}s %{public}s [%{public}s-%{public}s] Connection in PTO recovery for >= %u ms, closing connection"
- "%{public}s %{public}s [%{public}s-%{public}s] cannot find alternate path for pmtud"
```
