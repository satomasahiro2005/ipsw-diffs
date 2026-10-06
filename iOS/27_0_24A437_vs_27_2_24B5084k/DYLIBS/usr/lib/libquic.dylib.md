## libquic.dylib

> `/usr/lib/libquic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd0200` | `0xd0a68` | **`+0x868`** |
| `__TEXT.__oslogstring` | `0x12459` | `0x1260d` | **`+0x1b4`** |
| `__TEXT.__cstring` | `0x8823` | `0x88b5` | **`+0x92`** |
| `__DATA_CONST.__const` | `0x25b0` | `0x25e0` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xd30` | `0xd18` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0xdd8` | `0xdc8` | **`-0x10`** |

### Other Changes

```diff

-6681.2.2.0.0
+6681.40.80.0.0

-  Functions: 1156
-  Symbols:   1660
-  CStrings:  2606
+  Functions: 1157
+  Symbols:   1659
+  CStrings:  2618
Symbols:
+ ___os_log_helper_1_2_16_8_34_4_0_8_34_4_0_4_0_4_0_4_0_4_0_8_34_8_34_4_0_4_0_4_0_4_0_4_0_4_0
+ __quic_timer_remove
+ _quic_migration_is_ignoring_events
+ _quic_migration_record_event
- ___os_log_helper_1_2_14_8_34_4_0_4_0_4_0_4_0_4_0_8_34_8_34_4_0_4_0_4_0_4_0_4_0_4_0
- _nw_protocol_establishment_report_set_quic_stateless_reset_during_path_probe
- _nw_protocol_establishment_report_set_quic_stateless_reset_received
- _quic_migration_report_event
- _quic_timer_remove
CStrings:
+ "%{public}s %{public}s [%{public}s-%{public}s] \n\tConnection attempts: %u, RETRY received: %s, PTOs: %u\n\tEarly data: %s, Migration supported: %s, Keep-alives sent/acknowledged: %u/%u\n\tMigrations: %u succeeded, %u failed, paths validated: %u\n\tStateless reset: received %s, during path probe %s\n\tInbound unidirectional/bidirectional streams: %u/%u\n\tOutbound unidirectional/bidirectional streams: %u/%u\n\tDATA_BLOCKED frames sent/received: %u/%u\n\tSTREAM_DATA_BLOCKED frames sent/received: %u/%u\n"
+ "%{public}s %{public}s [%{public}s-%{public}s] \n\tConnection attempts: %u, RETRY received: %s, PTOs: %u\n\tEarly data: %s, Migration supported: %s, Keep-alives sent/acknowledged: %u/%u, ECN state: %s, L4S: %s\n\tRTT: base %llu ms, network %llu ms, latest %llu ms, minimum %llu ms, smoothed %llu ms (variance %llu ms)\n\tPath MTU: %hu, minimum MSS: %hu\n\tMigrations: %u succeeded, %u failed, paths validated: %u\n\tStateless reset: received %s, during path probe %s\n\tInbound unidirectional/bidirectional streams: %u/%u\n\tOutbound unidirectional/bidirectional streams: %u/%u\n\tDATA_BLOCKED frames sent/received: %u/%u\n\tSTREAM_DATA_BLOCKED frames sent/received: %u/%u\n"
+ "%{public}s %{public}s [%{public}s-%{public}s] [S%llu] early data verdict pending, holding application data"
+ "%{public}s %{public}s [%{public}s-%{public}s] no longer in fallback mode over %{public}s"
+ "%{public}s acked packet <%{public}s %llu> (length %u bytes, sent %llu)"
+ "%{public}s connection closing; deferring destroy of unprocessed acked packet <%{public}s %llu>"
+ "%{public}s handshake not confirmed, not retransmitting application data"
+ "%{public}s initialized loss recovery timer"
+ "%{public}s inner_state is null or 0"
+ "%{public}s loss_recovery->recovery_timer is null or 0"
+ "%{public}s migration event %u: result '%{public}s' (repeat %u), time %u ms, migration time %u ms, RTT %u ms -> %u ms, type '%{public}s' -> '%{public}s', LQM %d -> %d, fallback? %d primary? %d priority? %d loss? %d"
+ "%{public}s reset loss recovery timer to %llu"
+ "%{public}s timer entry is not on this timer"
+ "_quic_timer_remove"
+ "invalid path state"
+ "no connection ID"
+ "no viable path"
+ "path lost"
+ "path validation failed"
+ "quic_migration_is_ignoring_events"
+ "quic_migration_record_event"
+ "success"
+ "v24@?0^{quic_timer=}8^{quic_timer_entry=}16"
- "%{public}s %{public}s [%{public}s-%{public}s] \n\tConnection attempts: %u, RETRY received: %s, PTOs: %u\n\tEarly data: %s, Migration supported: %s, Keep-alives sent/acknowledged: %u/%u\n\tMigration events: %u, paths validated: %u\n\tStateless reset: received %s, during path probe %s\n\tInbound unidirectional/bidirectional streams: %u/%u\n\tOutbound unidirectional/bidirectional streams: %u/%u\n\tDATA_BLOCKED frames sent/received: %u/%u\n\tSTREAM_DATA_BLOCKED frames sent/received: %u/%u\n"
- "%{public}s %{public}s [%{public}s-%{public}s] \n\tConnection attempts: %u, RETRY received: %s, PTOs: %u\n\tEarly data: %s, Migration supported: %s, Keep-alives sent/acknowledged: %u/%u, ECN state: %s, L4S: %s\n\tRTT: base %llu ms, network %llu ms, latest %llu ms, minimum %llu ms, smoothed %llu ms (variance %llu ms)\n\tPath MTU: %hu, minimum MSS: %hu\n\tMigration events: %u, paths validated: %u\n\tStateless reset: received %s, during path probe %s\n\tInbound unidirectional/bidirectional streams: %u/%u\n\tOutbound unidirectional/bidirectional streams: %u/%u\n\tDATA_BLOCKED frames sent/received: %u/%u\n\tSTREAM_DATA_BLOCKED frames sent/received: %u/%u\n"
- "%{public}s initialized loss recovery timer (id %u)"
- "%{public}s loss_recovery->timer_id is null or 0"
- "%{public}s migration event %u: time %u ms, migration time %u ms, RTT %u ms -> %u ms, type '%{public}s' -> '%{public}s', LQM %d -> %d, fallback? %d primary? %d priority? %d loss? %d"
- "%{public}s new_path is null or 0"
- "%{public}s removed packet <%{public}s %llu> (length %u bytes, sent %llu) from outstanding packets"
- "%{public}s reset loss recovery timer (id %u) to %llu"
- "quic_migration_report_event"
- "quic_timer_remove"
- "v20@?0^{quic_timer=}8C16"
```
