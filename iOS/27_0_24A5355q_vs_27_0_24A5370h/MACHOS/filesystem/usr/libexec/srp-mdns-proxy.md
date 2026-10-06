## srp-mdns-proxy

> `/usr/libexec/srp-mdns-proxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x85ea8` | `0x89034` | **`+0x318c`** |
| `__TEXT.__oslogstring` | `0x13408` | `0x13763` | **`+0x35b`** |
| `__TEXT.__cstring` | `0x8646` | `0x8914` | **`+0x2ce`** |
| `__TEXT.__unwind_info` | `0x600` | `0x630` | **`+0x30`** |
| `__DATA.__bss` | `0xa48` | `0xa70` | **`+0x28`** |
| `__TEXT.__const` | `0x2dd` | `0x2d5` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3066.0.0.502.1
+3085.0.0.0.1

-  Functions: 474
-  Symbols:   1159
-  CStrings:  2612
+  Functions: 487
+  Symbols:   1181
+  CStrings:  2647
Symbols:
+ _cti_netdata_created
+ _cti_netdata_finalize
+ _cti_netdata_finalized
+ _cti_netdata_release_
+ _netdata_tracker_context_release
+ _netdata_tracker_created
+ _netdata_tracker_deliver_first_events
+ _netdata_tracker_finalize
+ _netdata_tracker_finalized
+ _netdata_tracker_initial_netdata_timeout
+ _netdata_tracker_maybe_stop
+ _netdata_tracker_network_data_callback
+ _netdata_tracker_serial_number
+ _netdata_tracker_set_omr_watcher
+ _netdata_tracker_set_service_tracker
+ _netdata_tracker_start
+ _netdata_tracker_start_network_data_events
+ _old_cti_netdata_created
+ _old_cti_netdata_finalized
+ _old_netdata_tracker_created
+ _old_netdata_tracker_finalized
+ _omr_watcher_lost_prefix_reclaim
+ _omr_watcher_release_
+ _service_tracker_network_data_callback
+ _service_tracker_release_
- _cti_track_network_data_
- _network_data_tracker_callback
- _service_tracker_stop
CStrings:
+ "%{public}s: [NT%lld] callback with no data error--ignoring"
+ "%{public}s: [NT%lld] canceling initial event retry wakeup"
+ "%{public}s: [NT%lld] could not start network data tracker: %d"
+ "%{public}s: [NT%lld] created"
+ "%{public}s: [NT%lld] netdata already running"
+ "%{public}s: [NT%lld] netdata tracker started"
+ "%{public}s: [NT%lld] server_state netdata tracker not NULL when it should be."
+ "%{public}s: [NT%lld] starting"
+ "%{public}s: [ST%lld] couldn't start the request to get Thread services, status: %d"
+ "%{public}s: invalid netdata API mode %d"
+ "%{public}s: lost prefix {%{public}s%{private, mask.hash, srp:in6_addr_segment}.6P:%{public, mask.hash, srp:in6_addr_segment}.2P:%{private, mask.hash, srp:in6_addr_segment}.8P}/%d has come back"
+ "%{public}s: lost prefix {%{public}s%{private, mask.hash, srp:in6_addr_segment}.6P:%{public, mask.hash, srp:in6_addr_segment}.2P:%{private, mask.hash, srp:in6_addr_segment}.8P}/%d has expired"
+ "%{public}s: no service data in network data!"
+ "%{public}s: timeout"
+ "*lost_prefix_pointer"
+ "*ppref"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/mDNSResponderExtras/ServiceRegistration/netdata-tracker.c"
+ "22:13:39"
+ "Jun  9 2026"
+ "cti_netdata %d %d %d %d|"
+ "cti_netdata_create"
+ "cti_netdata_finalize"
+ "cti_netdata_release_"
+ "cti_netdata_retain_"
+ "lost_prefix"
+ "netdata"
+ "netdata->offmesh_routes"
+ "netdata->prefixes"
+ "netdata->services"
+ "netdata_tracker %d %d %d %d|"
+ "netdata_tracker_context_release"
+ "netdata_tracker_create"
+ "netdata_tracker_initial_netdata_timeout"
+ "netdata_tracker_maybe_stop"
+ "netdata_tracker_network_data_callback"
+ "netdata_tracker_start"
+ "netdata_tracker_start_network_data_events"
+ "omr_watcher_lost_prefix_reclaim"
+ "omr_watcher_retain_"
+ "probe_result %d %d %d %d|"
+ "server_state->netdata_tracker"
+ "service_tracker_network_data_callback"
+ "service_tracker_retain_"
- "%{public}s: [ST%lld] netdata get started"
- "%{public}s: cannot start service_tracker without knowing the netdata API mode"
- "20:49:27"
- "Jun  3 2026"
- "netdata.offmesh_routes"
- "netdata.prefixes"
- "netdata.services"
- "service_tracker_stop"
```
